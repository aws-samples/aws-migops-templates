
# Module: Database migration schema conversion
## Task 1: Identify sources and Create mapping rules
#### Description
There are multiple source and target database combinations that you can use to carry out a database migration. Choose the source and target databases and start the database migration process. 

After you choose the source and target databases in AWS, choose a schema conversion tool and start converting the schema. For example, you can use the AWS Schema Conversion Tool (AWS SCT). After you choose and set up the tool, create mapping rules. A mapping rule describes a source-target pair that includes a source database schema or a source database and a target database platform.

For more information, see [AWS Schema Conversion Tool (SCT)](https://docs.aws.amazon.com/SchemaConversionTool/latest/userguide/CHAP_Welcome.html).

#### Tools
AWS Schema Conversion Tool (SCT) 
#### Acceptance Criteria
• Choose a schema conversion tool
#### Acceptance Criteria
• Created mapping rules
## Task 2: Create a database migration assessment report
#### Description
When planning a database conversion, it is helpful to create a database assessment report. The report gives a summary of schema conversion tasks and the details of those items that can't be automatically converted to your target database. Use this report to evaluate how much of the project you can use the schema conversion tool for and the number of manual tasks to be done. 

The migration assessment report includes the following:

1) Executive summary
2) License evaluation
3) Cloud support, indicating any features in the source database not available on the target
4) Recommendations, including conversion of server objects, backup suggestions, and linked server changes

For more information, see [AWS Schema Conversion Tool (SCT)](https://docs.aws.amazon.com/SchemaConversionTool/latest/userguide/CHAP_Welcome.html).
#### Tools
Migration assessment reports with AWS SCT
#### Tools
AWS Schema Conversion Tool (SCT) 
#### Acceptance Criteria
• Completed the database-migration assessment report 
#### Acceptance Criteria
• Completed database-migration assessment report 
## Task 3: Complete schema conversion
#### Description
After you complete the database-migration assessment report, start converting the schema from the source databases to target databases. You can use tools like AWS SCT to complete this schema conversion task. 

Create tasks or subtasks as needed for source to target schema conversion. Refer to the following playbooks for guidance. 

1) [Oracle to Aurora PostgreSQL migration playbook](https://docs.aws.amazon.com/dms/latest/oracle-to-aurora-postgresql-migration-playbook/chap-oracle-aurora-pg.html)
2) [SQL Server to Aurora PostgreSQL migration playbook](https://docs.aws.amazon.com/dms/latest/sql-server-to-aurora-postgresql-migration-playbook/chap-sql-server-aurora-pg.html)
3) [SQL Server to Aurora MySQL migration playbook](https://docs.aws.amazon.com/dms/latest/sql-server-to-aurora-mysql-migration-playbook/chap-sql-server-aurora-mysql.html)
4) [Oracle to Aurora MySQL migration playbook](https://docs.aws.amazon.com/dms/latest/oracle-to-aurora-mysql-migration-playbook/chap-oracle-aurora-mysql.html)


#### Tools
AWS Schema Conversion Tool (SCT) 
#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• Completed schema conversion between source and target databases.
#### Acceptance Criteria
• Completed schema conversion between source and target databases