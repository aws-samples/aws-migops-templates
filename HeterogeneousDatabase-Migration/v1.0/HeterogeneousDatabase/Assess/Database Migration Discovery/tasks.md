
# Module: Database Migration Discovery
## Task 1: Perform a deep dive into the database that you want to migrate
#### Description
The database migration discovery is an important phase where the team does a deep dive into the database that needs to be migrated. During the discovery phase key aspects of the database such as database configuration, HA/DR implementation, schema objects, usage of proprietary features, dependencies with other databases and applications, associated ETLs or data pipelines, replication, and topography, are identified and documented.

A deep dive is conducted where the customer team who owns that database walks through the database structure, schema, and all its associated dependencies. During this time, the AWS team also walks through DB Discovery Questionnaire with the customer team to get more information on the database. The AWS team or the customer database SME must run the AWS Schema Conversion Tool for a deep-dive database assessment for migration.

For more information, see [DB Migration Questionnaire](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/Database%20Migration%20Questionnaire.xlsx).

#### Tools
DB Migration Questionnaire
#### Tools
AWS Schema Conversion tool
#### Acceptance Criteria
• Completed the DB Migration Questionnaire document
#### Acceptance Criteria
• Output of the assessment report from the AWS Schema Conversion Tool
## Task 2: Plan on how to migrate the database
#### Description
After you gather data from the deep dive, perform the following next steps: 

1) Analyze  database schema objects by running the AWS Schema Conversion Tool (SCT)
2) Based on SCT reports, review object counts and estimate the size of the data store to be migrated and the effort required for code conversion and unit testing
3) Identify schema objects or proprietary database features that cannot be automatically converted
4) Create a plan for migrating the database, including workarounds for any incompatibilities between the source database and the target database engines 
5) Understand the technological complexities 
6) Map database-to-application dependencies (which apps access the database)
7) Map database-to-ETL-job dependencies (which ETL jobs intput/output data from the database)
8) Map database-to-database dependencies (usage of database links, linked servers, etc.)

Consolidate this data into an estimation template.

For more information, see [DB Migration Scope Template](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/DBMigration_Scope_Template.docx).

#### Tools
DB Migration Scope Template
#### Acceptance Criteria
• Completed Database Migration Scope document
## Task 3: Prepare Migration estimates
#### Description
This task helps in preparing an estimate for the migration to its target.  Use this task to identify the following details: 

1) Number and types of major schema objects (including stored procedures) and their complexity
2) Database hardware specifications 
3) Database HA/DR configuration (RAC, DataGuard, AlwaysON, etc.)
4) Classification of objects that can and cannot be automatically converted 
5) Size of the database  
6) Creating a resource plan based on the estimate.

For more information, see [DB Effort Estimation Template](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/Efforts_Estimates_Staff_Plans_RACI_Matrix.xlsx).


#### Tools
DB Effort Estimation Template
#### Acceptance Criteria
• Completed database-migration estimation document