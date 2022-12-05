
# Module: Engagement Pre-Kickoff
## Task 1: Overall scope success metrics and business outcomes
#### Description
This purpose of this task is to get the overall scope and timelines of the database-migration project, as well as a high-level overview of the current state of source databases and their associated applications. The AWS team and customer team(s) work together during this phase to determine the success metrics and desired business outcomes that can be used to track the project as it progresses. The success metrics and business outcomes are then reviewed and approved by the executive sponsor(s) and steering  committee responsible for the project.

#### Acceptance Criteria
• Clarified a high-level understanding of the current source database environment
#### Acceptance Criteria
• Clarified the scope and overall project timeline  
#### Acceptance Criteria
• Defined success metrics, drivers for migration, and the desired business and functional outcomes 
## Task 2: Program governance model
#### Description
Define the overall program-governance model by defining the following layers:

1) Strategic governance
2) Project governance
3) Project tracking

#### Tools
Program governance template
#### Acceptance Criteria
• Completed the program-governance template and uploaded it as an attachment
## Task 3: Understand all decision makers 
#### Description
In this task, you create a list of all primary stakeholders (technical and non-technical) who will either participate in the migration or make decisions regarding the migration. Record all names and keep the list up to date.

#### Acceptance Criteria
• Uploaded a record of all business leaders and primary technical stakeholders from each subtask.
## Task 3: Subtask 1: Specify the business leaders that are responsible for the migration
#### Description
Common business-focused roles we engage with that influence the contact-center technology decisions: 

1)	Delivery Practice Managers (DPMs)
2)	Engagement Managers (EMs)
3)	AWS Lead Consultants
4)	Account Manager
5)	Customer Practice Manager 
6)	Executive Leadership Team
7)	Executive Sponsor


#### Acceptance Criteria
• Finalized the list of business leaders that are responsible for the migration. 
## Task 3: Subtask 2: Specify the technical stakeholders that are responsible for the migration
#### Description
Common technical roles we engage with that influence the contact center technology decisions:

1) Solution Architects
2) Application owners 
3) Lead/Senior Database Engineers or Consultants
4) Customer SMEs in system, storage, networking, cloud, and other domains 

#### Acceptance Criteria
• Finalized the list of technical stakeholders that are responsible for the migration. 
## Task 4: Define the database-migration RACI
#### Description
This task outlines who is Responsible (R), Accountable (A), Consulted (C), or Informed (I) in each task and phase of the database migration.

Responsible (R): Performs the activities
Accountable (A): Delegates the work and checks for completion
Consulted (C): Provides inputs and supports the activity
Inform (I): Informed about the activity

For more information, see [RACI Matrix](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/DatabaseMigrationRACI.docx).
#### Tools
RACI Matrix
#### Acceptance Criteria
• Defined and finalized a RACI matrix
## Task 5: Tools and communication channels
#### Description
Define the tools and communication channels to use for managing the migration project. 

1) You can use tools for overall migration project management and collaboration.
2) You can use communication tools like Amazon Chime for team communications on a periodic cadence. 

#### Acceptance Criteria
• Identified a list of collaboration tools
#### Acceptance Criteria
• Identified communication channels for the migration teams
## Task 6: Risks assumption issues and dependencies
#### Description
This task helps in assessing the following: 

1)	Key risks
2)	Assumptions
3)	Issues
4)	Dependencies of the migration project

For more information, see [RAID Log](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/RisksandIssues.docx).

#### Tools
RAID Log
#### Acceptance Criteria
• Defined a RAID log template
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