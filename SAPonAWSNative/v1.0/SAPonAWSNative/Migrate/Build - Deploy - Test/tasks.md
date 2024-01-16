
# Module: Build - Deploy - Test
## Task 1: Download and stage necessary software components (SAP, third party tools, etc)
#### Description
Ensure the agreed upon software releases of SAP and required third party components are in staging directories in preparation for installation activities (SAP software from SAP Marketplace, customer's preferred IaC components, etc).  Ensure to confirm latest versions per the SAP Product Availability Matrix.
#### Tools
SAP Software Downloads
#### Tools
SAP Launchpad
#### Tools
AWS Marketplace
#### Tools
SAP Product Availability Matrix (requires SAP Universal ID)
#### Acceptance Criteria
• Required software releases available in appropriate staging directories (NFS/EFS accessible to appropriate EC2 systems)
## Task 2: Pre-migration activities for non-production SAP Systems (DEV, QA, Pre-Prod)
#### Description
In the pre-migration task, the migration team is responsible for preparing the non-production environments. This includes provisioning and configuring the base infrastructure (using IaC tools like Cloud Migration Factory as appropriate),  identifying the data transfer tooling to be used for migrating data from on-premise to AWS.
#### Tools
AWS Cloud Migration Factory
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Provisioned non-production environments
• Data transfer tooling identified and configured
## Task 2: Subtask 1: Validate base Infrastructure provisioned for SAP migration 
#### Description
Ensure the infrastructure for all SAP application servers and databases are provisioned and configured using the chosen automation tools (identified during Mobilize phase). This could be Launch Wizard for SAP ,Cloud formation templates, or other automation tools.Acceptance Criteria: All the provisioned infrastructure will need to be validated to ensure it is setup similar to the customer source environment.
#### Tools
AWS Launch Wizard for SAP
#### Tools
AWS Migration Hub Orchestrator
#### Acceptance Criteria
• All the provisioned infrastructure will need to be validated to ensure it is setup similar to the customer source environment.
## Task 2: Subtask 2: Identify data transfer tooling from on-premisis to AWS
#### Description
The data transfer tool should be identified, configured and tested well in advance of initial migration workloads.   
#### Tools
AWS Migration Hub
#### Tools
Network-to-Amazon VPC connectivity
#### Tools
AWS DataSync
## Task 3: Non-Prod SAP data migration activities (DEV, QA, Pre-Prod)
#### Description
During this task, the migration team will execute the migration for the non-production environments. Migration tasks are scheduled in waves, with each wave consisting of a group of applications and servers that have the same cutover date. These tasks can include the following:
- Confirm SAP system builds were completed
- Execute data migration using the chosen migration method (Cloud Migration Factory, etc)
- Validate data and SAP systems are working as expected
#### Tools
AWS Cloud Migration Factory
#### Tools
AWS Prescriptive Guidance - Migration strategies
#### Tools
SAP on AWS migration methodology
#### Tools
Migrating SAP HANA from other platforms to AWS
#### Tools
AWS Application Migration Service
#### Tools
AWS / SAP HANA Migration Tools 
#### Tools
AWS Prescriptive Guidance - Migration terms
#### Acceptance Criteria
• Automate and execute the migration process in multiple iterations (waves) until all the applications are migrated
## Task 3: Subtask 1: Confirm SAP System build
#### Description
Build SAP Systems that are part of the non-prod landscape.
#### Acceptance Criteria
• Installed SAP systems
## Task 3: Subtask 2: Import project related transports
#### Description
Ensure any SAP migration project-related transports are imported into the relevant SAP system in proper sequence, and that the CI/CD pipeline for all related migrated non-SAP applications are up-to-date.  
#### Acceptance Criteria
• Successful import of all transports & CI/CD changes (with any errors/alerts addressed)
## Task 3: Subtask 3: Data migration
#### Description
Migrate data for the SAP Systems that are part of the non-prod landscape based on the migration scenario .


#### Tools
Backup/Restore Tools
#### Tools
SAP Software SUM DMO
#### Tools
Migration Tools and Methodologies
## Task 3: Subtask 4: Technical Validations
#### Description
Validate/verify/test the SAP systems after the migration.

Typical Validation activities include :
1. Connection Tests between SAP systems.
2. Confirm Transport Paths.
3. RFC Checks
4. PI/Interface Checks
5. Transaction Checks.
6. Job executions.
7. Login Tests from front end ( SAP Gui, FIORI etc..)
#### Acceptance Criteria
• Confirm all identified Technical Checks are passed.
## Task 4: Post migration Testing /functional Validations for Migrated Wave
#### Description
Now that the SAP non-production environments are migrated, validate the environments and applications based on the test & validation strategy. Perform the following steps to ensure that validation is complete.
* integration and system testing
* Performance testing
* User acceptance testing
#### Acceptance Criteria
• Verify all necessary functional/UAT testing completion
## Task 4: Subtask 1: Execute integration system testing
#### Description
Execute end to end system integration testing according to testing strategy
#### Acceptance Criteria
• Completed test scenarios with all critical defects resolved.
## Task 4: Subtask 2: Execute system performance testing according to testing strategy
#### Description
Execute apporopriate performance testing scenarios on similarly sized system to production
#### Acceptance Criteria
• Completed test scenarios with system performance meeting or exceeding stated KPIs/metrics
## Task 4: Subtask 3: Execute user acceptance testing according to testing strategy
#### Description
Execute appropriate UAT scenarios as defined in the testing strategies, executed by identified business/super users
#### Acceptance Criteria
• Completed UAT scenarios with all critical defects resolved
## Task 5: HA/DR testing
#### Description
HA/DR Testing in an integral component of a well-architected SAP on AWS solutions. Plan for a HA/DR testing in your migration journey.

1. Identify HA and DR Test cases covering various failure scenarios. ( HANA Scale-Up, Scale-out, Application)
2. Validate test cases with AWS, Implementation partner and SAP.
3. Run applicable HA/DR testing for each wave
4. Explore automated tools like AWS FIS to introduce controlled chaos in resiliency testing
#### Tools
AWS Fault Injection Simulator 
#### Tools
Use Controlled Experiments to Boost Resilience
#### Acceptance Criteria
• Verify completion of HA/DR testing within expected RTO and RPO objectives.