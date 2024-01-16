
# Module: Replatform SQL Server to Amazon RDS
## Task 1: Migrate SQL Server to Amazon RDS using native backup/restore
#### Description
Amazon RDS supports native backup and restore for Microsoft SQL Server databases using full backup, differential backup and transaction log files. When you use RDS, you access files stored in Amazon S3 rather than using the local file system on the database server.
#### Tools
RDS SQL Server Native Backup/Restore
## Task 1: Subtask 1: Create S3 Bucket
#### Description
Create S3 bucket to upload source SQL Server Backup files
## Task 1: Subtask 2: Create Custom options group and attach to RDS SQL Server
#### Description
1. Add the SQLSERVER_BACKUP_RESTORE option to option group
2. Create the IAM role for S3 access
3. Attach the option group to RDS SQL Server
## Task 1: Subtask 3: Upload the source backup files to S3 and restore it on RDS
#### Description
Upload the backup files to Amazon S3 and restore it on Amazon RDS SQL Server
#### Tools
Native Backup/Restore
## Task 2: Migrate SQL Server DBs to Amazon RDS SQL Server using DMS
#### Description

#### Tools
Configuring Source SQL Server
#### Tools
Migrate Amazon RDS SQL Server using DMS
#### Tools
Enable native backup/restore RDS SQL Server 
#### Acceptance Criteria
Successful migration of SQL Server to RDS SQL Server database
## Task 2: Subtask 1: Backup the source database
#### Description
Back up the SQL Server database from the on-premises source.
#### Acceptance Criteria
Successful database backup
## Task 2: Subtask 2: Restore databsae on RDS SQL Server
#### Description
Restore the database backup file to the target Amazon RDS for SQL Server.
#### Tools
RDS SQL Server Backup/Restore
#### Acceptance Criteria
Successful database restore
## Task 2: Subtask 3: Configure the DMS
#### Description
1. Create the AWS DMS replication instance
2. Create the source and target endpoints
3. Create the AWS DMS task for continuous replication
#### Tools
Setting up DMS
#### Acceptance Criteria
Successful data migration
## Task 2: Subtask 4: Monitor the task for ongoing DMS replication
#### Description
AWS DMS provides statistics for the following:
Host Metrics – Performance and utilization statistics for the replication host, provided by Amazon CloudWatch. For a complete list of the available metrics, see Replication instance metrics.

Replication Task Metrics – Statistics for replication tasks including incoming and committed changes, and latency between the replication host and both the source and target databases. For a complete list of the available metrics, see Replication task metrics.

Table Metrics – Statistics for tables that are in the process of being migrated, including the number of insert, update, delete, and DDL statements completed.
#### Tools
Migration Service Metrics
#### Acceptance Criteria
Monitor the DMS metrics and cutover the application to use RDS SQL Server
## Task 3: Migrate SQL Server DBs to Amazon RDS SQL Server using Log shipping
#### Description
Microsoft SQL Server log shipping is a method of replicating databases using transaction logs that can enable the physical replication of a warm standby database such that it is an exact binary replica of the primary database. Often this method is referred to as physical replication.
#### Acceptance Criteria
1. Successful Configuration of Log shipping
2. Successful DB migration
## Task 3: Subtask 1: Setup and Configure Logshipping
#### Description
Setup Log shipping
#### Tools
Configure LogShipping
#### Acceptance Criteria
Successful migration SQL Server database
## Task 4: Migrate SQL Server DBs to Amazon RDS SQL Server using Transaction Replication
#### Description
Transactional replication is a SQL Server technology that is used to replicate changes between two databases. These changes can include database objects like tables (primary key is required), stored procedures, views, and so on, as well as data. The replication process involves a publisher (the primary database that publishes data), a subscriber (a secondary database that receives replicated data), and a distributor (a server that stores metadata and transactions for transactional replication). You can use transactional replication for SQL Server on Amazon EC2 and Amazon RDS for SQL Server DB instances.
#### Tools
Migrate to RDS SQL Server using transactional replication part I
#### Tools
Transactional replication
#### Tools
Migrate to RDS SQL Server using transaction replication part II
## Task 4: Subtask 1: Enable Distribution on Source database
#### Description

#### Tools
Enable Distribution
#### Acceptance Criteria
Successful creation of distribution on source SQL Server
## Task 4: Subtask 2: Create RDS database and objects
#### Description
Script out the source database and create the DB and objects on RDS SQL Server
#### Tools
Replication
#### Acceptance Criteria
Successful creation of RDS SQL Server database
## Task 4: Subtask 3: Create Publication on Source SQL Server
#### Description
source SQL Server system, your next step is to create a publication for each table with the data that you want to migrate to the RDS environment. To do so, open the context (right-click) menu for Local Publications under the Replication node on your source server, and then choose New Publication.
#### Tools
Transfer data
#### Acceptance Criteria
Successful publication and data transfer
## Task 4: Subtask 4: Transfer Data using replication
#### Description

#### Tools
Setting up Replication Part 2
#### Tools
Setting up Replication Part 1
#### Acceptance Criteria
Successfully transfer data
## Task 5: Migrate SQL Server DBs to Amazon RDS SQL Server using AWS Migration Hub Orchestrator
#### Description
Two new migration templates for SQL database migration is available in Miguration Hub Orchestrator. Templates are designed to help our customers reduce SQL Server migration time and effort. You can get started with predefined workflow templates, which are based on the proven Microsoft SQL Server migration best practices. Additionally, you can customize the migration workflows by adding, reordering, and removing steps according to your specific requirements.
#### Tools
MHO Blog
#### Tools
MHO RDS template
#### Acceptance Criteria
Database migrated successfully