
# Module: Refactor SQL Server to Amazon RDS
## Task 1: Refactor SQL Server to Babelfish for Aurora PostgreSQL
#### Description

#### Tools
DMS Babelfish as a target
#### Tools
Babelfish Compass Tool Instructions
#### Tools
Babelfish Compass Tool
#### Tools
DMS SQL Server as Source
## Task 1: Subtask 1: Run Compass tool to analyze database.SQL files
#### Description
With Babelfish Compass, you can quickly analyze T-SQL SQL/DDL scripts for compatibility with Babelfish. Babelfish Compass identifies the SQL features that aren’t supported by the current version of Babelfish and creates an assessment report on the SQL/DDL. The purpose of such analysis is to inform a go/no-go decision about whether it makes sense to consider starting a migration project from SQL Server to Babelfish and to estimate the efforts required for the migration
#### Tools
Babelfish Compass
#### Acceptance Criteria
Analyze the babelfish compass report. Remediate the suggested changes at source and rerun the report to verify.
## Task 1: Subtask 2: Create target schema on Aurora PostgreSQL Babelfish
#### Description
Create schema on the target Aurora PostgreSQL Babelfish.
#### Acceptance Criteria
Schema created successfully
## Task 1: Subtask 3: Setup DMS and Replicate the Database to Aurora PostgreSQL Babelfish
#### Description

#### Tools
Babelfish as a target
#### Tools
SQL Server as source
#### Acceptance Criteria
Data is replicating from source SQL Server to Aurora PostgreSQL Babelfish successfully.
## Task 1: Subtask 4: Perform DB and Application testing
#### Description
1. Successful validation of target database
2. Successful validation of the application test cases
## Task 2: Refactor SQL Server to RDS MySQL
#### Description

#### Tools
AWS SCT Guide
#### Tools
AWS SCT
#### Tools
Step by Step Migration guide
## Task 2: Subtask 1: Run SCT on Source Database
#### Description
1. Download and Install  AWS SCT
2. Connect to source SQL Server database
3. Run the SCT
4. Download the SCT Output and remediate the unsupported features/SQL
#### Tools
AWS SCT
#### Acceptance Criteria
Completed the analysis of the SCT output.
Remediated the reported issues,
## Task 2: Subtask 2: Deploy the SCT conveted schema on RDS MySQL
#### Description
Migrate the SCT converted and data engineer remediated schema to RDS MySQL
#### Acceptance Criteria
Schema Migrated to RDS MySQL successfully.
## Task 2: Subtask 3: Migrate the SQL Server Database using DMS
#### Description

#### Tools
Instruction to Setup DMS
#### Acceptance Criteria
Migrate the SQL Server database to RDS MySQL successfully
## Task 2: Subtask 4: Perform the Database and Application validation
#### Description

#### Acceptance Criteria
Successfully competed the validation of the converted database, data and application.
## Task 3: Refactor SQL Server to Amazon RDS PostgreSQL
#### Description

#### Tools
Install and Configure AWS SCT
#### Tools
Configure RDS PostgreSQL for DMS Target
#### Tools
AWS SCT (Schema Conversion Tool)
#### Tools
Configure SQL Server for DMS source
#### Tools
SCT Playbook
#### Acceptance Criteria
1. Migrate SQL Server DB to RDS PostgreSQL
2. Perform the database and application validation
## Task 3: Subtask 1: Run AWS SCT on Source SQL Database
#### Description

1.	Download and Install AWS SCT
2.	Connect to source SQL Server database
3.	Run the SCT
4.	Download the SCT Output and remediate the unsupported features/SQL

#### Tools
AWS SCT
#### Acceptance Criteria
1. Complete the analysis of the AWS SCT output
2. Remediated the reported issues.
## Task 3: Subtask 2: Create the AWS SCT converted database objects on RDS MySQL
#### Description
1. Create the AWS SCT converted objects on RDS PostgreSQL
2. Remediate the suggested changes or rewrite the logic for the unsupported features and create database objects on RDS PostgreSQL
#### Tools
PgAdmin Client tool
#### Acceptance Criteria
All database objects are deployed on RDS PostgreSQL
## Task 3: Subtask 3: Migrate SQL Server DB to RDS PostgreSQL using DMS
#### Description
1. Setup AWS Database Migration Service
2. Configure SQL Server as source
3. Configure PostgreSQL as target
4. Create the DMS tasks to migrate the data
#### Tools
AWS DMS
#### Acceptance Criteria
SQL Server data is migrated to RDS PostgreSQL successfully.
## Task 4: Refactor SQL Server to Amazon RDS MariaDB
#### Description
Migrate SQL Server Database to RDS MariaDB
#### Tools
AWS DMS
#### Tools
Configure SQL Server as source in DMS
#### Tools
MariaDB as DMS target
#### Tools
AWS SCT
#### Tools
Setup DMS
## Task 4: Subtask 1: Run AWS SCT on Source SQL Database
#### Description
1.	Download and Install AWS SCT
2.	Connect to source SQL Server database
3.	Run the SCT
4.	Download the SCT Output and remediate the unsupported features/SQL

#### Tools
Configure and Install AWS SCT
#### Acceptance Criteria
1. Complete the AWS SCT output analysis
2. Remediate the reported issues
## Task 4: Subtask 2: Create the DB Objects on RDS MariaDB
#### Description
1. Create the SCT converted objects on RDS MariaDB
2. Remediate the AWS SCT reported issues and create DB objects on target
#### Acceptance Criteria
All Source database objects created on target RDS MariaDB
## Task 4: Subtask 3: Migrate the SQL Server DB to RDS MariaDB using DMS
#### Description
Setup AWS Database Migration Service
2. Configure SQL Server as source
3. Configure PostgreSQL as target
4. Create the DMS tasks to migrate the data

#### Tools
Configure DMS
#### Acceptance Criteria
Migrate the SQL Server database to RDS MariaDB successfully.
## Task 4: Subtask 4: Perform the database and application validation
#### Description
Perform the validation of migrate database and test the application.
#### Acceptance Criteria
Successful validation of the database and application.
## Task 5: Refactor SQL Server to Amazon Aurora PostgreSQL
#### Description
Migrate SQL Server database to Aurora PostgreSQL
#### Tools
Playbook
#### Tools
Install and Configure SCT
#### Tools
AWS SCT
#### Tools
Setup DMS
#### Tools
AWS DMS
#### Tools
PostgreSQL as DMS Target
#### Tools
SQL Server as DMS Source
#### Acceptance Criteria
SQL Server DB migrated to Aurora PostgreSQL completed successfully
## Task 5: Subtask 1: Run AWS SCT on source SQL Database
#### Description
1.	Download and Install AWS SCT
2.	Connect to source SQL Server database
3.	Run the SCT
4.	Download the SCT Output and remediate the unsupported features/SQL

#### Tools
Install AWS SCT
#### Tools
AWS SCT Guide
#### Acceptance Criteria
Complete the AWS SCT output analysis and remediate the unsupported features.
## Task 5: Subtask 2: Create the DB Objects on Aurora PostgreSQL
#### Description
Create the converted and remediate DB Objects on the Aurora PostgreSQL
#### Acceptance Criteria
Create all the DB Objects on Aurora PostgreSQL
## Task 5: Subtask 3: Migrate the SQL Server Database to Aurora PostgreSQL
#### Description
1. Setup AWS Database Migration Service
2. Configure SQL Server as source
3. Configure PostgreSQL as target
4. Create the DMS tasks to migrate the data

#### Tools
Setup and Configure DMS
#### Acceptance Criteria
Migrate the SQL Server to Aurora PostgreSQL successfully
## Task 5: Subtask 4: Perform the database and application validation
#### Description
Validate the database and application
#### Acceptance Criteria
Successful validation of the database and application.
## Task 6: Refactor SQL Server to Amazon Aurora MySQL
#### Description
Migrate SQL Server database to Aurora MySQL
#### Tools
Setting up DMS
#### Tools
Install and Configure AWS SCT
#### Tools
DMS SQL Server as source
#### Tools
SQL Server to Aurora MySQL migration playbook
#### Tools
AWS SCT Guide
## Task 6: Subtask 1: Run AWS SCT on source SQL Server database
#### Description
1.	Download and Install AWS SCT
2.	Connect to source SQL Server database
3.	Run the SCT
4.	Download the SCT Output and remediate the unsupported features/SQL

#### Tools
Install and Configure AWS SCT
#### Tools
SQL Server to Amazon Aurora MySQL Playbook
#### Tools
AWS SCT Guide
#### Acceptance Criteria
1. Complete the AWS SCT output analysis
2. Remediate the AWS SCT reported issues
## Task 6: Subtask 2: Create the DB Objects on Aurora MySQL
#### Description
Migrate the SCT converted and remediated DB Objects to Aurora MySQL
#### Acceptance Criteria
Successful DB Object creation on Aurora MySQL
## Task 6: Subtask 3: Migrate SQL Server Database to Aurora MySQL using DMS
#### Description
1. Setup AWS Database Migration Service
2. Configure SQL Server as source
3. Configure PostgreSQL as target
4. Create the DMS tasks to migrate the data

#### Tools
Setup DMS
#### Acceptance Criteria
Successful migration of SQL Server DB to Aurora MySQL
## Task 6: Subtask 4: Perform the Database and Application validation
#### Description
1. Validate the Database
2. Validate the Application

#### Acceptance Criteria
Successful validation of database and application.