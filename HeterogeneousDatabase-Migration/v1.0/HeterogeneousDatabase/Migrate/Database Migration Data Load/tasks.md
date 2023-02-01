
# Module: Database Migration Data Load
## Task 1: Complete the database migration data load
#### Description
In this task you use AWS Database Migration Service (AWS DMS). AWS DMS supports migration between 20-plus database and analytics engines, such as 

1) Oracle to Amazon Aurora MySQL
2) MySQL to Amazon Relational Database (RDS) MySQL
3) Microsoft SQL Server to Amazon Aurora PostgreSQL
4) MongoDB to Amazon DocumentDB
5) Oracle to Amazon Redshift 
6) To and from Amazon Simple Storage Service (S3)

Ensure that the replication instance is set up and that endpoints for both source and target are available before you run AWS DMS. Conduct a test to ensure connectivity between these endpoints and the replication instance. Then, perform a migration of existing data (full load). Capture statistics for the table data that gets loaded. These statistics are helpful in determining the required production downtime.
#### Tools
AWS Database Migration Service (AWS DMS)
#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• A target database with loaded data
#### Acceptance Criteria
• Target database with loaded data
## Task 2: Sanity testing
#### Description
After the data load is complete, compare the data in the source and the target databases and identify all anomalies. Create and check in scripts to handle these anomalies. 

#### Acceptance Criteria
• Ensure that the source and target database are identical.
#### Acceptance Criteria
• Ensured that the source and target database are identical