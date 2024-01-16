
# Module: Replatform SQL Server to Amazon RDS Custom
## Task 1: Migrate SQL Server DBs to Amazon RDS Custom SQL Server using backup/restore
#### Description
Amazon RDS custom supports native backup and restore operations for Microsoft SQL Server databases using full and differential backup (.bak) files. It also supports differential restore and log restore options to minimize downtime for your application.

    Take a full backup of the database on the on-premises DB instance.
    Upload the backup file to Amazon S3.
    Download the backup file from S3 to your RDS Custom for SQL Server DB instance.
    Restore a database using the downloaded backup file on the RDS Custom for SQL Server DB instance.


#### Tools
Backup/Restore
## Task 1: Subtask 1: Backup the on-premises database
#### Description

#### Acceptance Criteria
Successful Backup
## Task 1: Subtask 2: Upload the backup file to Amazon S3
#### Description
Upload the backup files to S3
#### Acceptance Criteria
Successful Upload.
## Task 1: Subtask 3: Download the backup file from Amazon S3
#### Description
To download the backup file from S3
1.Using RDP, connect to your RDS Custom for SQL Server DB instance.
2.Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/
3.In the Buckets list, choose the name of the bucket that contains your backup file.
4.Choose the backup file mydb-full-compressed.bak.
5.For Actions, choose Download as.
6.Open the context (right-click) menu for the link provided, then choose Save As.
7.Save mydb-full-compressed.bak to the D:\rdsdbdata\BACKUP directory.
#### Tools
Download
#### Acceptance Criteria
Successful download
## Task 1: Subtask 4: Restor the backup file to the RDS Custom for SQL Server DB instance
#### Description
You have to write the native SQL Server restore command to restore the database.
Example :
restore database mydatabase from disk='D:\rdsdbdata\BACKUP\mydb-full-compressed.bak'
with move 'mydatabase' to 'D:\rdsdbdata\DATA\mydatabase.mdf',
move 'mydatabase_log' to 'D:\rdsdbdata\DATA\mydatabase_log.ldf';

#### Tools
Backup/Restore
#### Acceptance Criteria
Successful restore
## Task 2: Migrate SQL Server DBs Amazon RDS custom SQL Server using Log shipping
#### Description
SQL Server Log shipping allows you to automatically send transaction log backups from a primary database on a primary server instance to one or more secondary databases on separate secondary server instances. The transaction log backups are applied to each of the secondary databases individually. 
## Task 2: Subtask 1: Configure the Logshipping
#### Description
1. Perform the on-premise database full backup
2. Restore the backup on with **NO RECOVERY** on RDS Custom SQL Server
3. Schedule a job to perform the transaction log backup and upload it to S3 on-premise sever
4. Schedule a job on RDS Custom to download the transaction log backup and restore it on RDS with No Recovery
5. Plan the cut off time and recover the database
#### Tools
Backup/Restore
#### Acceptance Criteria
Successful log-shipping configuration
## Task 2: Subtask 2: Cutover
#### Description
Bring the RDS Custom database online and point the application to connect to RDS custom SQL Server database
#### Acceptance Criteria
Successful application connectivity.
## Task 3: Migrate SQL Server DBs to Amazon RDS custom using Always On availability groups
#### Description
Microsoft SQL Server Always On is a high-availability feature for Microsoft SQL Server databases. With the synchronous-commit secondary replica, your application remains transparent to a failover. If the primary node in the Always On Availability Group (AAG) fails due to unforeseen circumstances or due to maintenance, your applications remain unaware of the failure, and automatically redirect to a functional node.
## Task 3: Subtask 1: Configure SQL Server Always on
#### Description
1. Verify the SQL Server edition, version and collation. It should match as on-premise.
2. Add WSFC to each node. In SQL Server 2017 we can configure clusterless Availability Group in SQL Server without failover cluster configuration on participating replicas. 
3. Configure SQL Server to enable the Always On
4. Create availability group and add the RDS Custom SQL Server as replica. You can either perform the backup/restore or seed the database from availability group.
#### Tools
Backup/Restore
#### Acceptance Criteria
Successful availability group configuration and failover
## Task 3: Subtask 2: Cutover
#### Description
Change the application to connect to RDS custom and test the application.
## Task 4: Migrate SQL Server DBs to Amazon RDS custom using Basic Availability Groups
#### Description
Always On Basic Availability Groups replaces the deprecated Database Mirroring feature and provides a similar level of feature support. Basic availability groups enable a primary database to maintain a single replica. This replica can use either synchronous-commit mode or asynchronous-commit mode. We can use the BAG for the migration to RDS custom as well.
## Task 4: Subtask 1: Configure the BAG
#### Description
1. Verify the SQL Server edition, version and collation. It should match as on-premise.
2. Add WSFC to each node. In SQL Server 2017 we can configure clusterless Availability Group in SQL Server without failover cluster configuration on participating replicas. 
3. Configure SQL Server to enable the Always On
4. Create availability group and add the RDS Custom SQL Server as replica. You can either perform the backup/restore or seed the database from availability group.
#### Tools
Backup/Restore
#### Acceptance Criteria
Successful BAG configuration and database replication.
## Task 4: Subtask 2: Cutover
#### Description
Change the application connection to RDS custom and make sure the application is working fine.
#### Acceptance Criteria
Application successful
## Task 5: Migrate SQL Server DBs to Amazon RDS custom SQL Server using Distributed availability groupsSQL
#### Description
Microsoft SQL Server Always On availability groups provide a high availability (HA) and disaster recovery (DR) solution for SQL Server. An availability group consists of a primary replica that accepts read/write traffic, and up to eight secondary replicas that accept read traffic. An availability group is configured on a Windows Server Failover Cluster (WSFC) with two or more nodes.

Microsoft SQL Server Always On distributed availability groups provide a solution to configure two separate availability groups between two independent WFSCs. The availability groups that are part of the distributed availability group don’t have to be in the same data center. One availability group can be on premises, and the other availability group can be on the Amazon Web Services (AWS) Cloud on Amazon Elastic Compute Cloud (Amazon EC2) or RDS Custom SQL Server instances in a different domain. We can use it for SQL Server database migration.
#### Tools
DAG
#### Tools
Multi-AZ RDS Custom SQL Server
#### Acceptance Criteria
Database Migrated Successfully
## Task 5: Subtask 1: Configure the Always On for on-premise SQL Server
#### Description

## Task 5: Subtask 2: Create multi-az RDS Custom for SQL Server
#### Description

#### Tools
Multi-AZ SQL Server
## Task 5: Subtask 3: Create the distributed availability group on the primary cluster
#### Description

## Task 5: Subtask 4: Join the distributed availability group from the secondary cluster
#### Description

## Task 5: Subtask 5: Cutover
#### Description
Point the application to use the RDS Custom SQL Server
#### Acceptance Criteria
Successful connectivity and application testing
## Task 6: Migrate SQL Server DBs to Amazon RDS custom SQL Server using transactional replication
#### Description
Transactional replication is a SQL Server technology that is used to replicate changes between two databases. These changes can include database objects like tables (primary key is required), stored procedures, views, and so on, as well as data. The replication process involves a publisher (the primary database that publishes data), a subscriber (a secondary database that receives replicated data), and a distributor (a server that stores metadata and transactions for transactional replication). You can use transactional replication for SQL Server on Amazon EC2 and Amazon RDS for SQL Server DB instances.

Transactional replication creates a snapshot of the objects and data in your on-premises (publication) database and sends it to the subscriber database. After the snapshot is applied to the subscriber, all subsequent data changes and schema modifications made at the publisher are sent over to the subscriber as they occur. The data changes are then continuously applied to the subscriber in the same order as they occurred at the publisher.

After synchronization is complete, you perform validation on the target SQL Server DB instance. When the two databases are in sync, you stop stop the activity on the on-premises database, ensure that replication has completed, and then perform the cutover to the target SQL Server DB instance. You can then stop the push subscription, delete it, and start using Amazon RDS custom for SQL Server.
#### Tools
APG Transaction Replication
#### Tools
Transaction Replication
## Task 6: Subtask 1: Configure transaction replication
#### Description
1. Configure Publisher
2. Configure Distributed
3. Configure Subscriber RDS Custom SQL Server 
4. Replicate the transactions from publisher to subscriber
5. Monitor the Replication for the synchronization

#### Tools
Configure Transactional Replication
#### Acceptance Criteria
Successful synchronization
## Task 6: Subtask 2: Cutover
#### Description
Once the publisher and subscriber synchronized map the application to use the RDS custom endpoints.
#### Acceptance Criteria
Successful application connectivity and functionality testing
## Task 7: Migrate SQL Server DBs to Amazon RDS custom SQL Server using Detach/Attach
#### Description
The data and transaction log files of a database can be detached and then reattached to the same or another instance of SQL Server. Detaching and attaching a database is useful if you want to change the database to a different instance of SQL Server on the same computer or to move the database.
#### Tools
Detach/Attach
#### Acceptance Criteria
Database successfully migrated to RDS custom.
## Task 7: Subtask 1: Detach the source database
#### Description
1. Detach the source database
2. Upload it to S3
3. Download on the RDS Custom
4. Attach the database RDS Custom SQL Server
#### Tools
Backup/ Restore
#### Tools
Detach/Attach
#### Acceptance Criteria
Successfully attach the database on RDS custom SQL Server
## Task 7: Subtask 2: Cutover
#### Description
Change the application to connect to RDS SQL Server and test the connectivity.
#### Acceptance Criteria
Successful application testing