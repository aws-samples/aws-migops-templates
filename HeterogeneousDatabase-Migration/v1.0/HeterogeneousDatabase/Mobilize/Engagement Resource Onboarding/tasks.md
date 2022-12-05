
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
# Module: Database Migration Training and Workshops
## Task 1: Understand the database services that are available in AWS
#### Description
Database migration workshops are designed to introduce users to the available cloud-native database services and capabilities that AWS offers. In addition, the workshop provides a deeper dive on Amazon Aurora PostgreSQL. The workshop also draws a parallel between the source and target databases in terms of features and architecture, which is important from a heterogenous-database-migration standpoint.  

For a complete list of source and target databases that the AWS Database Migration service supports, see the following resources: 

1) [Sources for data migration](https://docs.aws.amazon.com/dms/latest/userguide/CHAP_Source.html)
2) [Targets for data migration](https://docs.aws.amazon.com/dms/latest/userguide/CHAP_Target.html)
#### Acceptance Criteria
• Understood the different types of cloud-native databases offered by AWS
## Task 1: Subtask 1: Introduction to Amazon Aurora
#### Description
Amazon Aurora is a fully managed relational database engine that's compatible with both MySQL and PostgreSQL. 

[Immersion day � Introduction to Amazon Aurora](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/Introduction_to_Amazon_Aurora.pdf)

[Amazon Aurora User Guide](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)

#### Acceptance Criteria
• Understood the features, capabilities< and architecture of Amazon Aurora
#### Acceptance Criteria
• Understood the primary use cases for Amazon Aurora 
## Task 1: Subtask 2: Understand Amazon Aurora monitoring and Performance Insights.
#### Description
Amazon Aurora monitoring and Performance Insights provide additional and more granular information about the database load and performance characteristics. 

For more information, see [here](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/Monitoring%20and%20Performance%20Insights_final.pdf).
#### Acceptance Criteria
• Understood the features and capabilities offered with Amazon Aurora monitoring and Performance Insights
## Task 1: Subtask 3: Explore the similarities and differences between Oracle PL SQL and PostgreSQL PL pgSQL.
#### Description
Most users migrating from Oracle prefer a PostgreSQL-based target like AWS Aurora for PostgreSQL because of the similarities between the Oracle PL/SQL and PostgreSQL PL/pgSQL procedural languages. Migrating from Oracle to PostgreSQL is often easier when compared to other target database engines. This task helps users learn about the similarities and differences in SQL syntax between PostgreSQL and Oracle.

For more information, see [Training PostgreSQL for Oracle Users](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/PostgreSQL%20for%20Oracle%20Users.pdf).
#### Acceptance Criteria
• Understood the similarities and differences between Oracle and PostgreSQL SQL syntax
## Task 1: Subtask 4: Learn about Oracle PostgreSQL PL pgSQL
#### Description
Most users migrating from Oracle prefer a PostgreSQL-based target like AWS Aurora for PostgreSQL because of the similarities between the Oracle PL/SQL and PostgreSQL PL/pgSQL procedural languages. Migrating from Oracle to PostgreSQL is often easier when compared to other target database engines. This task helps users learn about PL/pgSQL and the similarities and differences with Oracle�s PL/SQL. 

For more information, see [Training-PLpgSQL](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/PLpgSQL.pdf).

#### Acceptance Criteria
• Understood the similarities and differences between the syntaxes of Oracle and PostgreSQL PL/pgSQL
## Task 1: Subtask 5: Learn about PostgreSQL performance
#### Description
Performance tuning is an important task for any database migration project, especially in heterogenous migrations when switching between database engines. In this task, you learn about the performance capabilities of PostgreSQL and study examples of PostgreSQL database tuning.

For more information, see [Immersion Day - PostgreSQL Performance](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/performanceaupgid.pdf).
#### Acceptance Criteria
• Understood PostgreSQL Query Planner statistics
#### Acceptance Criteria
• Understood PostgreSQL indexes
#### Acceptance Criteria
• Understood the PostgreSQL Query Optimizer
## Task 1: Subtask 6: Learn about partitioning in PostgreSQL
#### Description
Table partitioning is a key feature of the PostgreSQL database that allows enhanced performance and availability advantages when dealing with very large volumes of data. In this task, you learn about table partitioning in PostgreSQL, its benefits, features, and capabilities.

[Immersion Day � Partitioning in PostgreSQL](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/partitioning_postgress.pdf).
#### Acceptance Criteria
• Understanding the benefits of table partitioning
#### Acceptance Criteria
• Understanding how partitioning works in a PostgreSQL database
#### Acceptance Criteria
• Understanding the various PostgreSQL-specific table partitioning features and capabilities 
## Task 2: Learn about AWS migration tools
#### Description
AWS offers several tools to accelerate the migration of databases into cloud-native database technologies. Amazon Database Migration Service (DMS) and Amazon Schema Conversion Tool (SCT) both offer automation around heterogenous real-time data replication and conversion of database schema and artifacts between different database engines. In this task you learn how to get started with Amazon DMS and SCT and learn about the different features and capabilities of each.

#### Acceptance Criteria
• Understood the role of Amazon Schema Tool (SCT) in a database migration project 
#### Acceptance Criteria
• Understood the features and capabilities of SCT
#### Acceptance Criteria
• Understood how to use SCT to convert a source database schema to the target database dialect
#### Acceptance Criteria
• Understood the role of Amazon Database Migration Service (DMS) in a database migration project 
#### Acceptance Criteria
• Understood the features and capabilities of Amazon DMS
#### Acceptance Criteria
• Understood how to use DMS to replicate data in a heterogenous database environment 
# Module: Mobilize Phase readiness
## Task 1: Determine the next steps in the Mobilize phase
#### Description
Identify a complete list of objectives and tasks to kick-start the Mobilize phase. 
#### Acceptance Criteria
• Objectives and tasks for the Mobilize phase
## Task 2: Document an execution plan for the Mobilize phase
#### Description
The Mobilize phase is performed by both AWS personnel and customer stakeholders. It is important to determine who performs which tasks in the Mobilize phase. Engage AWS and customer stakeholders and create a plan ahead of time to determine who will be performing the tasks. 
#### Acceptance Criteria
• Determine the AWS personnel and customer stakeholder who will perform the Mobilize phase tasks. 
## Task 3: Ensure that all appropriate artifacts and decisions are recorded
#### Description
To sign-off on the Assess phase, complete the following artifacts 

1) AWS migration first call deck
2) Migrating environment infrastructure discovery data
3) Signed Statement of Work (SOW) if needed
# Module: Engagement Kickoff
## Task 1: Plan for the Launch Ready Planning LRP
#### Description
This kickoff is used to review and come to agreement on all the items discussed as a part of the pre-kickoff. All the key stakeholders of the project gather for a kick-off meeting where they walk through all the key items of the project.
Use the LRP to achieve the following outcomes

� Proof of concept
� Overall project timeline
� Wave plan
� Dependencies
� Deliverables
� Risks and issues

#### Acceptance Criteria
• Proof of concept
#### Acceptance Criteria
• Overall project timeline
#### Acceptance Criteria
• Wave plan
#### Acceptance Criteria
• Dependencies
#### Acceptance Criteria
• Deliverables
#### Acceptance Criteria
• Risks and issues
## Task 2: Finalize DB migration artifacts
#### Description
After you complete the LRP, the next action is to finalize all the database migration artifacts required to kick off the migration activities. The artifacts to be finalized include: 

� Finalized scope and timelines 
� Signed SOW
� Reviewed business outcomes
� Database migration RACI matrix
� Database migration program governance. 
� Database migration RAID log
#### Acceptance Criteria
• Finalized scope and timelines 
#### Acceptance Criteria
• Signed SOW
#### Acceptance Criteria
• Reviewed business outcomes
#### Acceptance Criteria
• Database-migration RACI matrix
#### Acceptance Criteria
• Database-migration program governance. 
#### Acceptance Criteria
• Database-migration RAID log
# Module: Ways of Working Agile Delivery
## Task 1: Create an engagement and execution plan
#### Description
Use the PowerPoint template in GitHub to prepare a presentation. Meet with workstream leads and spend time reviewing next steps, and assign appropriate owners. 
#### Acceptance Criteria
• Ensure that workstream leads acknowledge the plan and that they start putting together backlogs for their areas in the next set of tasks. Create new MigOps tasks from the relevant backlog. 
## Task 2: Create a task roadmap
#### Description
Use the task roadmap template in GitHub to create tasks for workstream owners to create their respective backlogs. The template in GitHub spans multiple work streams. Add additional workstreams as needed. Create new MigOps tasks from the relevant backlog. 
#### Acceptance Criteria
• Ensured that tasks per work stream were created in this phase. Ensured that all tasks have owners assigned by the workstream lead. 
## Task 3: Create subtasks roadmap
#### Description
Use the subtasks roadmap template in GitHub to create subtasks for workstream owners to create their respective backlogs. The template in GitHub spans multiple work streams. Add additional work streams as needed. Create new MigOps tasks from the relevant backlog. 
#### Acceptance Criteria
• Ensured that subtasks were created in this phase. Ensured that all tasks have owners assigned by the workstream lead. 
## Task 4: Plan sprints and execute
#### Description
Ensure that each task and subtask are scheduled to be carried out in a future sprint. All task assignees must update the start date and end date for each task based on planning. As tasks are carried out, workstream owners can choose to double-check the acceptance criteria for each task and confirm completion. 
#### Acceptance Criteria
• Ensured that the timelines for performing tasks and subtasks are recorded. Ensure that all workstream leads keep up with timelines and discuss any risks. 
#### Acceptance Criteria
• Assign due dates to all tasks and subtasks according to the sprint plan.
# Module: Engagement Resource Onboarding
## Task 1: Complete resource onboarding
#### Description
Plan resource onboarding according to the following:

1) Overall project timeline
2) Wave plan and pipeline

To identify and onboard resources, perform the following activities:

1) Raise resource requests
2) Identify availability of resources based on the required timeline
3) After you identify the resources, onboard them to the migration environment 
#### Acceptance Criteria
• Completed resource onboarding for the migration project