
# Module: Proof of Concept
## Task 1: Complete the database migration schema conversion for POC
#### Description
This goal of this task is to complete the database-migration schema conversion as a proof of concept. This task can be performed on a few databases instead of the entire database infrastructure. 

#### Tools
AWS Schema Conversion Tool (SCT) 
#### Acceptance Criteria
• Used the AWS Schema Conversion Tool (SCT) to convert to the target schema
## Task 1: Subtask 1: Identify sources and create mapping rules
#### Description
There are multiple source and target database combinations that you can use to carry out a databsase migration. Finalize the source and target databases and start the database migration process. 

After you finalize the source and target databases in AWS, use the schema-converstion tool to start converting the schemas. 

After you select and set up the tool, create mapping rules. A mapping rule describes a source-target pair that includes a source database schema or a source database and a target database platform.

For more information, see [AWS Schema Conversion Tool (SCT)](https://docs.aws.amazon.com/SchemaConversionTool/latest/userguide/CHAP_Welcome.html)
#### Tools
AWS Schema Conversion Tool (SCT) 
#### Acceptance Criteria
• Selected a schema conversion tool
#### Acceptance Criteria
• Created mapping rules
## Task 1: Subtask 2: Create a database migration assessment report
#### Description
When planning a database conversion, it is helpful to create a database-assessment report. The report gives a summary of schema conversion tasks and the details for items that can't be automatically converted to your target database. Use this report to evaluate how much of the project can be completed with the schema conversion tools and the number of manual tasks to be done. 

The migration assessment report includes the following:

1) An executive summary
2) A license evaluation
3) The extent of cloud support and which features in the source database aren't available on the target
4) Recommendations, including conversion of server objects, backup suggestions, and linked server changes

For more information, see [Migration assessment reports with AWS SCT](https://docs.aws.amazon.com/SchemaConversionTool/latest/userguide/CHAP_AssessmentReport.html).
#### Tools
Migration assessment reports with AWS SCT
#### Tools
AWS Schema Conversion Tool (SCT) 
#### Acceptance Criteria
• Completed the database-migration assessment report 
#### Acceptance Criteria
• Completed database-migration assessment report 
## Task 1: Subtask 3: Complete schema conversion
#### Description
After you complete the database-migration assessment report, start converting the schema from the source databases to the target databases. Use tools like AWS SCT  to complete this schema-conversion task. 
#### Tools
AWS Schema Conversion Tool (SCT) 
#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• Completed schema conversion between source and target databases.
#### Acceptance Criteria
• Completed schema conversion between source and target databases
## Task 2: Database migration code transformation for POC
#### Description
The goal of this task is to complete the database-migration code transformation as part of a proof of concept. You can perform this task on some databases and not on the entire database infrastructure. 

#### Tools
AWS Schema Conversion Tool (SCT) 
#### Acceptance Criteria
• Code conversion standards
#### Acceptance Criteria
• A learnings manual
#### Acceptance Criteria
• Converted code
## Task 3: Database migration data load
#### Description
AWS DMS is a tool for loading data from source databases to target databases. It supports most heterogenous migrations, like Oracle or SQL Server to Amazon Aurora. Ensure that the replication instance is set up and that endpoints for both source and target are available before you run the DMS.

#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• Target database with loaded data
## Task 3: Subtask 1: Complete the database migration data load
#### Description
AWS DMS is a common tool used to load data from source databases to target databases. It supports most heterogenous migrations, like Oracle or SQL Server to Amazon Aurora. Ensure that the replication instance is set up and that endpoints for both source and target are available before you run the DMS. Conduct a test to ensure connectivity between these endpoints and the replication instance. 

Create a task for performing a full load of the database. Start the task and capture statistics for the table data being loaded. These statistics help determine the required production downtime. 
#### Tools
AWS Database Migration Service (AWS DMS)
#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• A target database with loaded data
#### Acceptance Criteria
• Target database with loaded data
## Task 3: Subtask 2: Sanity testing
#### Description
After you complete the data load, compare the data between the source and the target databases and identify any anomalies. Handle anomalies separately and create and check in scripts for handling anomalies. 
#### Acceptance Criteria
• Ensure that the source and target database are identical.
#### Acceptance Criteria
• Ensured that the source and target database are identical