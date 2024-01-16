
# Module: Migration Preparation
## Task 1: Review learnings from Mobilize phase and kickoff Migrate phase
#### Description
Review and validate the decisions and outcomes from the Mobilize phase with project stakeholders. The following outcomes need to be validated before the start of the Migrate phase:
1. Migration project plan is in place and signed off by customer, partners, AWS.
2. AWS landing zone is in place
3. Source system preparation completed (compatibility, patch levels, system/data cleanup, etc
4. Key issues and risks are reviewed and priorities aligned across the project team.
#### Acceptance Criteria
• Validated outcomes of the Mobilize phase prior to start of the Migrate phase
• Migration phase kickoff meeting held
## Task 2: Knowledge transfer and training
#### Description
Prepare a plan for executing the training plan (from Learning Needs Assessment, etc), and/or knowledge transfer for the SAP migration to AWS. The plan must include the following: 

*  AWS Operations training
*  AWS Security training
*  SAP on AWS training
*  AWS DevOps training
#### Acceptance Criteria
• Defined plan for knowledge transfer and training for SAP support team 
## Task 3: Finalize Migration Types & tools
#### Description
Based on business & migration objectives, application versions, capacities, and costs of migration identified in the Assess and Mobilize phases, confirm decision on the type of migration(s) to be performed for each SAP workload, and identify the tools and processes that are appropriate for implementing each migration strategy (Mig Hub Orchestrator, DMO, etc)
#### Tools
AWS Cloud Migration Factory
#### Tools
AWS Application Migration Service
#### Tools
SAP on AWS migration methodology
#### Tools
AWS/SAP Hana Migration Tools
#### Tools
AWS Prescriptive Guidance Migration Strategies
#### Tools
 Migrating SAP HANA from Other Platforms to AWS
#### Acceptance Criteria
• Confirm migration type to implement based on the data available from the Assess and Mobilize phases. 
• Identify the tools required to migrate workloads to AWS using a specific migration strategy
## Task 3: Subtask 1: Classify each SAP System (SID) with Specific Workload migration type
#### Description
Ensure you define the appropriate tools for migration type involved.
1. In the case of homogenous migrations for HANA, HANA system replication would be leveraged. For Oracle databases, it is preferred to use oracle data guard assuming customer already has the enterprise license.
2. In the case of SAP Bolt-Ons, AWS Migration Service (MGN) can be leveraged for migrating the data.
3. For heterogenous migrations, typically SAP native tools like Software Provisioning Manager (SWPM) are used for migration of the data from on-premise to AWS.
#### Tools
SAP Migration Scenarios
#### Acceptance Criteria
• Ensure the correct migration strategy is chosen to align the business allocated downtime.
## Task 4: Finalize application wave planning / prioritization
#### Description
Application prioritization is the process of determining the order and grouping that SAP applications/workloads should be migrated to the cloud (waves). Initial prioritization/wave planning should have been conducted in mobilize phase, confirm if any assumptions changed and finalize the application waves & priority. Final prioritization should be based on the complexity of migrating the SAP applications to the cloud and and criteria/rules defined to help classify the workloads.

In general, for each SAP production system, multiple environments should be in place to ensure effective change management processes and maintain integrity of the production application codeset. Recommended environments should include at a minimum; Development, QA/Test, Production, and additional sandboxes may be needed for testing and prototyping purposes. 

For each Wave, considerations should be made to include all tightly coupled systems in the same wave.
1. ERP App Server & DB environments
2. Supporting environments (BI, PI/PO, BOBJ, etc)
3. Shared environments (SolMan, SAP Router, WebDisp, etc)

Wave planning strategies can be based on the type of environments (i.e. Dev / Test / Production waves), or if applications have de-coupled production environments, they can be mixed in with non-production systems from the de-coupled applications.
#### Tools
 Large Migration Portfolio playbook prioritization
#### Acceptance Criteria
• A list of application components prioritized based on the business and technical rules
## Task 4: Subtask 1: Identify dependencies between systems to define migration priority and order
#### Description
Ensure the dependencies between different SAP systems and bolt-ons are identified to ensure they are migrated together. This is to ensure the post migration testing and validation would not have issues with data validation.
#### Acceptance Criteria
• Ensure the system dependency is correctly identified for smoother migration of SAP landscapes. 
## Task 4: Subtask 2: Define the application prioritization process
#### Description
There are three process options for prioritizing applications:
1. Manual complexity scoring: Use complexity scoring criteria to assess the difficulty of migrating each application
2. Application nomination: Application owners nominate applications for migration
3. Discovery tool: Define criteria within the parameters of the discovery tool, and then the tool analyzes the applications and provides a final complexity score.
#### Tools
Defining the application prioritization process
#### Acceptance Criteria
• Prioritization process based on discovery tools
## Task 4: Subtask 3: Define the application prioritization rules
#### Description
Define application prioritization rules, to determine the migration order of the applications. Create rules to assess the priority of each application so you can schedule the application in the appropriate wave. Common business and technology rules include the following:
- Specifying the order and schedule for migrating data centers
- Prioritizing business units
- Capturing deadlines for critical business applications
#### Tools
Defining prioritization rules
#### Acceptance Criteria
• Defined prioritization rules
## Task 4: Subtask 4: Finalize the application prioritization process
#### Description
Define how the portfolio workstream uses the rules and processes to prioritize applications. This is the process that the portfolio workstream references in the implementation stage of the migration.
#### Acceptance Criteria
• Finalized process for prioritization
## Task 5: Update project plan based on migration wave priorities, finalize timing, assign ownership, facilitate access requests
#### Description
Once all SAP applications are identified for migration waves, update the project plan/timeline accordingly (along with identified outcomes), allocate the appropriate project resources and assign ownership.

Ideally Project Planning  sessions should include representatives from these areas:

1. Cloud Ops Teams ( Network , Security, etc..)
2. SAP Technical Teams
3. SAP Testing Teams
4. SAP Functional Teams
5. Business Process owners 
6. Leadership team/PMO

#### Acceptance Criteria
• Finalize detailed project plan with migration waves clearly defined
• Project resources assigned and on-boarded
• Project Tooling provisioned (SharePoint,Jira etc..)
## Task 6: Define Test & Validation strategy
#### Description
Identify and define the test & validation strategy & scenarios for the migration. This is critical to ensuring the success of the migration to ensure it meets business and technical requirements prior to execution.  The test cycles should cover  at a minimum, the following:

1. Integration and system testing
2. Performance testing
3. User acceptance testing
4. Pre & Post-migration verification testing
5. HA/DR Test Scenarios.
#### Acceptance Criteria
• Identified test scenarios for migration to AWS
• Identified test tooling and resources.
## Task 6: Subtask 1: Create and/or update test cases
#### Description
Review the customer's existing SAP upgrade test cases (if applicable), remove any test cases that may not apply to a cloud migration, and add any additional test cases that may be needed for the new cloud operating model.
#### Acceptance Criteria
• Approved inventory of test cases
## Task 7: Readiness checkpoint planning (Go/No-go planning workshop)
#### Description
Establish readiness checkpoint process & criteria during a Go / No-go planning workshop in order to identify the specific areas which should be verified prior to go-live . Readiness checks  can be evaluated across various domains like -
Platform readiness, Business readiness, People readiness and Cutover readiness.



#### Acceptance Criteria
• Readiness checklist / scorecard