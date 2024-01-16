
# Module: Rehost SQL Server to Amazon EC2
## Task 1: Rehost SQL Server to Amazon EC2 Window SQL Server using native tools
#### Description
You can migrate SQL Server to Amazon EC2 SQL Server (Self managed) using native backup/restore method.  Full, Differential and Transaction log are the most common type of SQL Server Backups. Depending on the RTO (Recovery Time Objective) and RPO (Recovery Point Objective) of the organization you have to setup the backup/restore strategy for the minimal downtime.
#### Tools
SQL Server Database Backup Command
#### Tools
Create Master Key SQL Server 
#### Tools
SQL Server Database Restore Command
#### Tools
Backup Certificate
#### Acceptance Criteria
Application is working as expected by connecting to the EC2 SQL Server
#### Acceptance Criteria
There isn't any error reported for the SQL Server DB in the error log
#### Acceptance Criteria
Database dependent objects migrated to SQL Server as well. Object include Users, Logins, Agent Jobs, SSIS Packages, SSRS reports, SSAS and more.
#### Acceptance Criteria
Migrated database is online on EC2 SQL Server
## Task 1: Subtask 1: Verify the Source and Target SQL Server
#### Description
Make sure target Amazon EC2 meets the required OS Version, SQL Server Version, Organization best practices, CPU, Memory and available storage as per your requirement.
#### Acceptance Criteria
Meets the required Amazon EC2, Windows and SQL Server standards as per the organization requirement.
## Task 1: Subtask 2: Script out SQL Server objects
#### Description
You can skip the script out step if you are planning to restore system databases (Master and MSDB). Master and MSDB system database has all the SQL Server level objects. You have to just work on copying the windows server level required file (i.e. Batch file)

Script out the server level objects part of the migration.
1. SQL Server Logins
2. Agent Jobs
3. Linked Servers
4. Server level triggers
5. Windows Server level batch jobs and the files you want to on the target Amazon EC2
#### Tools
Script out objects
#### Acceptance Criteria
All the required objects script out successfully
#### Acceptance Criteria
Script files copied to target Amazon EC2 
## Task 1: Subtask 3: Backup the Security Certificates (Only for TDE databases)
#### Description
SQL Syntax :

BACKUP CERTIFICATE certname TO FILE ='path_to_file'  
      WITH PRIVATE KEY   
      (   
        FILE ='path_to_private_key_file',  
        ENCRYPTION BY PASSWORD ='encryption_password'   
      )   
#### Tools
Backup Certificate
#### Acceptance Criteria
Certificated Backup Successful.
## Task 1: Subtask 4: Backup Database
#### Description
Perform the Full, Differential and Transaction log based your organization RPO/RTO requirement.
#### Tools
Backup Commands
#### Acceptance Criteria
DB backed up successfully.
#### Acceptance Criteria
Backup files are copied to AWS
## Task 1: Subtask 5: Create Master Key and Certificate (For TDE Database Only)
#### Description

#### Tools
Create Master Key on Target SQL Server
#### Tools
Create Certificate on Target SQL Server from source backup
#### Acceptance Criteria
Master Key and Certificate created successfully
## Task 1: Subtask 6: Restore Database
#### Description
1. Restore database form the copied source database backups.
2. To Setup HA (Log Shipping, Always On, DB Mirroring) you have to also restore the databases on the standby Amazon EC2 SQL Server as well in restoring state. 
#### Tools
Restore Database
#### Acceptance Criteria
Database Restore Successful
## Task 1: Subtask 7: Restore Scripted Objects
#### Description
You can skip this step if have restored system databases (Master and MSDB). Master and MSDB system database has all the SQL Server level objects. You have to just work on copying the windows server level required file (i.e. Batch file)

Restore all the scripted SQL Server objects, copied files and create the scheduled task if any.
SQL Server Logins
Agent Jobs
Linked Servers
Server level triggers
Windows Server level batch jobs and the files you want to on the target Amazon EC2

#### Acceptance Criteria
Successfully restored and created the required object on target Amazon EC2 SQL Server. Note you have to restore on the stand by instance as well if any.
## Task 2: Migrate SQL Server DBs to Amazon EC2 SQL Server using Log shipping
#### Description
Microsoft SQL Server log shipping is a method of replicating databases using transaction logs that can enable the physical replication of a warm standby database such that it is an exact binary replica of the primary database. Often this method is referred to as physical replication.
#### Acceptance Criteria
All the required databases successfully restored to Amazon EC2
## Task 2: Subtask 1: Setup Log Shipping between On-Premise and Amazon EC2
#### Description
Log Shipping is a basic level SQL Server high-availability technology that is part of SQL Server. It is an automated backup and restore process that allows you to create another copy of your database for failover.

Log shipping involves copying a database backup and subsequent transaction log backups from the primary (source) server and restoring the database and transaction log backups on one or more secondary (Stand By / Destination) servers.
#### Tools
Step by Step Log Shipping 
## Task 3: Migrate SQL Server DBs to Amazon RDS using Database Mirroring
#### Description
Database mirroring is a solution for increasing the availability of a SQL Server database. Mirroring is implemented on a per-database basis and works only with databases that use the full recovery model.
## Task 3: Subtask 1: Configure Database Mirroring
#### Description
Check Microsoft [Documentation](https://learn.microsoft.com/en-us/sql/database-engine/database-mirroring/database-mirroring-sql-server?view=sql-server-ver16) for the database mirroring setup
#### Tools
Database Mirroring
#### Acceptance Criteria
Successfully Setup the mirroring between on-premise SQL Server and Amazon EC2 SQL Server.
## Task 4: Migrate SQL Server DBs to Amazon EC2 SQL Server using Always On Availability Group
#### Description

## Task 4: Subtask 1: Configure SQL Server Always on between on-premise and Amazon EC2 SQL Server
#### Description
1. Extend the on-premise domain to AWS
2. Launch the Amazon EC2 SQL Server with same version, edition and collation
3. Create fail over cluster and add on-premise and Amazon EC2
4. Restore Full and transaction log backup on Amazon EC2 SQL Server
5. Create a availability group and add the on-premise database and EC2 database to availability group
6. Synchronize the changes
7. Monitor the lag and when lag is zero perform the failover
#### Tools
Always On APG 
#### Tools
SQL Server Always on
#### Acceptance Criteria
Successfully setup the always on
## Task 4: Subtask 2: Failover Availability Group to Amazon EC2 SQL Server
#### Description
Perform the failover once synchronization lag is zero
#### Tools
Monitor always on 
#### Tools
Failover Always On
#### Acceptance Criteria
Perform the successful failover to Amazon EC2 SQL Server.
## Task 5: Migrate SQL Server DBs to Amazon EC2 using DMS
#### Description
Migrate data from one or many Microsoft SQL Server databases using AWS DMS. With a SQL Server database as a source, you can migrate data to another SQL Server database, or to one of the other AWS DMS supported databases.

1. Configure source SQL Server for continuous replication
2. Configure target SQL Server for DMS
3. Create replication instance
4. Create source and target endpoints
5. Create tasks for the replication
6. Monitor the cloud watch metrics for the replication lags
#### Tools
APG DMS
#### Tools
DMS - SQL Server as Target
#### Tools
DMS - SQL Server as Source
#### Acceptance Criteria
SQL Server Database/Tables migrated successfully.
## Task 5: Subtask 1: Prepare the source and target SQL Server for the DMS CDC
#### Description

## Task 5: Subtask 2: Generate the SQL Script of the source
#### Description
DMS only migrates the data. You have to generate the script of the database to migrate the TSQL objects (Procedures, functions, triggers etc.) 
## Task 5: Subtask 3: Launch Replication Instance
#### Description
Launch Replication instance and make sure it is able to connect both source and target SQL Server.
#### Acceptance Criteria
Launched Successfully
## Task 5: Subtask 4: Create Source and Target endpoints
#### Description
Endpoint will allow replication instance to connect the source and target.
#### Acceptance Criteria
Endpoint connection successful
## Task 5: Subtask 5: Create DMS Tasks
#### Description
Create DMS tasks to replicate tables from source to target SQL Server
#### Acceptance Criteria
task is replicating data successfully.
## Task 5: Subtask 6: Monitor the DMS CW metrics and cutover
#### Description
Monitor the DMS cloud watch metrics for the replication lag and when replication lag is zero, you can cut over application to target.
#### Acceptance Criteria
Data replication successfully and application is working fine with the target SQL Server.
## Task 6: Migrate SQL Server DBs to Amazon EC2 SQL Server using basic availability group
#### Description
Always On Basic Availability Groups provide a high availability solution for SQL Server from version 2016 and above on Standard Edition. A basic availability group supports a failover environment for a single database. It is created and managed much like traditional (advanced) Always On Availability Groups (SQL Server) with Enterprise Edition
#### Tools
BAG SQL Server
#### Acceptance Criteria
Successful configuration of BAG and successful replication to target SQL Server database.
## Task 6: Subtask 1: Configure the Basica Availability Group
#### Description

## Task 6: Subtask 2: Failover On-premise BAG database
#### Description

## Task 7: Migrate SQL Server DBs to Amazon EC2 SQL Server using Distributed availability groups
#### Description
A distributed availability group spans two separate availability groups. You can think of it as an availability group of availability groups. The underlying availability groups are configured on two different WSFC clusters. The availability groups that participate in a distributed availability group do not need to share the same location. They can be physical or virtual, on premises or in the public cloud. The availability groups in a distributed availability group don’t have to run the same version of SQL Server. The target DB instance can run a later version of SQL Server than the source DB instance.

A distributed availability group architecture gives you a flexible way to rehost a mission-critical SQL Server instance or database on AWS. It provides a hybrid solution for lifting and shifting (or lifting and transforming) your critical SQL Server databases on AWS. 
#### Tools
Configure DAG
#### Tools
DAG
#### Acceptance Criteria
Successful database replication and failover
## Task 7: Subtask 1: Configure DAG between source and target
#### Description

#### Tools
Configure DAG
#### Acceptance Criteria
Successful DAG configuration
## Task 7: Subtask 2: Perform failover
#### Description

#### Tools
Manual failover
#### Acceptance Criteria
Successful failover
## Task 8: Migrate SQL Server DBs to Amazon EC2 SQL Server using Transactional replication
#### Description
Transactional replication is a SQL Server technology that is used to replicate changes between two databases. These changes can include database objects like tables (primary key is required), stored procedures, views, and so on, as well as data. The replication process involves a publisher (the primary database that publishes data), a subscriber (a secondary database that receives replicated data), and a distributor (a server that stores metadata and transactions for transactional replication). You can use transactional replication for SQL Server on Amazon EC2 and Amazon RDS for SQL Server DB instances.
#### Tools
Replication
#### Tools
Transactional Replication
#### Tools
Setting up Transactional Replication
#### Acceptance Criteria
Replicated the source SQL Server database to target SQL Server successfully
## Task 8: Subtask 1: Configure the replication between source and target
#### Description
Configure the replication.
1. Create Publisher
2. Create Distributor
3. Create Subscriber
4. Monitor the replication
#### Acceptance Criteria
Data replicated successfully
## Task 8: Subtask 2: Cutover
#### Description
Switch over application to connect to target SQL Server.
#### Acceptance Criteria
Application able to connect and perform the transaction successfully on the target SQL Server.
## Task 9: Migrate SQL Server DBs to Amazon EC2 SQL Server using Detach and attach
#### Description
The data and transaction log files of a database can be detached and then reattached to the same or another instance of SQL Server. Detaching and attaching a database is useful if you want to change the database to a different instance of SQL Server on the same computer or to move the database.
#### Tools
Detach/Attach
#### Acceptance Criteria
Database migrated successfully to target and database is in online state allowing  application connections.
## Task 9: Subtask 1: Stop the application
#### Description
Stop the application so the incoming connection and transaction won't fail.
## Task 9: Subtask 2: Detach the Source Database
#### Description
Detach the source database and copy the .MDF, .NDF and .LDF which are data and log files to AWS EC2 SQL Server.
## Task 9: Subtask 3: Attach the database
#### Description
Attach data and log files to target SQL Server instance
## Task 9: Subtask 4: Start the application
#### Description
Configure application connection to use the target SQL Server endpoint and check the connectivity.
## Task 10: Migrate SQL Server DBs to Amazon EC2 SQL Server using AWS Migration Hub Orchestrator
#### Description
Two new migration templates for SQL database migration is available in Miguration Hub Orchestrator. Templates are designed to help our customers reduce SQL Server migration time and effort. You can get started with predefined workflow templates, which are based on the proven Microsoft SQL Server migration best practices. Additionally, you can customize the migration workflows by adding, reordering, and removing steps according to your specific requirements.
## Task 10: Subtask 1: Create applications in Migration Hub
#### Description
You need to create the applications first before using Migration Hub Orchestrator. You can import your server information using [AWS Migration Hub Import](https://docs.aws.amazon.com/application-discovery/latest/userguide/discovery-import.html) or [AWS Application Discovery Service](https://docs.aws.amazon.com/application-discovery/latest/userguide/what-is-appdiscovery.html). After that,  you can logically define and group discovered servers into applications. See details in this [document](https://docs.aws.amazon.com/application-discovery/latest/userguide/discovered_servers.html#applications).
#### Tools
AWS Applicaation Discovery Service
#### Tools
Migration Hub Report
## Task 10: Subtask 2: Configure the Migration Hub Orchestrator plugin
#### Description
The Migration Hub Orchestrator plugin is a virtual appliance that is installed in your VMware environment and automate the migration steps on premises. To deploy the plugin as a virtual machine (VM) in your VMware environment, download the plugin Open Virtualization Archive (OVA) file. See details in this [document](https://docs.aws.amazon.com/migrationhub-orchestrator/latest/userguide/orchestrate-migrations.html#download-plugin).

#### Tools
AWS Migration Hub Orchestrator
## Task 10: Subtask 3: Rehost Microsoft SQL Server to Amazon EC2
#### Description
With Rehost SQL server on Amazon EC2 template, you can rehost your SQL Servers on-premises to Amazon EC2 using native backup and restore. See details in this [document](https://docs.aws.amazon.com/migrationhub-orchestrator/latest/userguide/rehost-sql-ec2.html).
#### Tools
AWS Migration Hub Orchestrator
## Task 11: Migrate SQL Server DBs to Amazon EC2 SQL Server using AWS Application Migration Service
#### Description
AWS Application Migration Service simplifies and expedites your migration to AWS by automatically converting your source servers from physical, virtual, or cloud infrastructure to run natively on AWS. It further simplifies your migration and reduces costs by allowing you to use the same automated process for a wide range of applications, without changes to applications, their architecture, or the migrated server.
#### Tools
QuickStart Guide
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
EC2 SQL Server launched with the data successfully.
## Task 11: Subtask 1: Pre-requisites
#### Description
1. Initialize AWS MGN using the AWS Console
2. Create the replication template 
3. Alternatively, Initialize AWS MGN using the API
4. Optionally configure remote access to worker machine if running the tool remotely and not on the application server
#### Tools
Application Migration Service
## Task 11: Subtask 2: First Time Setup
#### Description
Follow the steps on this page for the first time setup https://docs.aws.amazon.com/mgn/latest/ug/first-time-setup-gs.html
#### Tools
First Time Setup
## Task 11: Subtask 3: Add Source Servers
#### Description
Follow the steps on this page to add source servers https://docs.aws.amazon.com/mgn/latest/ug/adding-servers-gs.html
#### Tools
Add Source Servers
## Task 11: Subtask 4: Configure launch settings
#### Description
Follow the steps on this page to configure launch settings https://docs.aws.amazon.com/mgn/latest/ug/configuring-target-gs.html
#### Tools
Configure Launch Settings
## Task 11: Subtask 5: Launch test instance
#### Description
	Follow the steps on this page to launch test instance https://docs.aws.amazon.com/mgn/latest/ug/launching-test-gs.html
#### Tools
Launch Test Instance
## Task 11: Subtask 6: Launch a cutover instance
#### Description
Follow the steps on this page to launch a cutover instance https://docs.aws.amazon.com/mgn/latest/ug/launch-cutover-gs.html
#### Tools
Lauch cutover instance