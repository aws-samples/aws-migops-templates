
# Module: Plan Operations
## Task 1: Ensure that the right operations strategy is in place
#### Description
Once the database is in AWS, make sure that best practices are in place for the following:

1) Monitoring
2) Alerting and backups
3) High availability

Tools like Amazon CloudWatch help collect key metrics for CPU and memory usage, I/O, etc. Tools like AWS CloudTrail are integrated with AWS Database Migration Service (AWS DMS). 
#### Tools
Amazon CloudWatch
#### Tools
AWS CloudTrail
#### Acceptance Criteria
• Set up monitoring in AWS
## Task 2: Check on operational roles and responsibilities
#### Description
Ensure that the operational roles and responsibilities defined in the Mobilize phase are correct and current. Use defined procedures to run operations effectively. 
#### Tools
RACI Matrix
#### Acceptance Criteria
• Check and update the operational roles and responsibilities RACI matrix as needed. 
## Task 3: Create playbooks and troubleshooting documents
#### Description
Once the database migration is complete in AWS, ensure that the team creates playbooks and troubleshooting documents. These playbooks and documents will help operation teams ensure that the environment is stable and available at all times. 

You can use the following playbooks for reference:
 
1) [Oracle to Aurora PostgreSQL migration playbook](https://docs.aws.amazon.com/dms/latest/oracle-to-aurora-postgresql-migration-playbook/chap-oracle-aurora-pg.html)
2) [SQL Server to Aurora PostgreSQL migration playbook](https://docs.aws.amazon.com/dms/latest/sql-server-to-aurora-postgresql-migration-playbook/chap-sql-server-aurora-pg.html)
3) [SQL Server to Aurora MySQL migration playbook](https://docs.aws.amazon.com/dms/latest/sql-server-to-aurora-mysql-migration-playbook/chap-sql-server-aurora-mysql.html)
4) [Oracle to Aurora MySQL migration playbook](https://docs.aws.amazon.com/dms/latest/oracle-to-aurora-mysql-migration-playbook/chap-oracle-aurora-mysql.html)
#### Tools
AWS Schema Conversion Tool (SCT) 
#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• Created troubleshooting documents
#### Acceptance Criteria
• Created operational runbooks