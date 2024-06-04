
# Module: Data Management
## Task 1: Data Migration
#### Description
Legacy data migration. Develop, test, and execute the data migration programs and processes defined in the Explore phase. Perform iterative data migration and testing cycles focused on the analysis of data, refinement of business rules, and processes designed to move, cleanse, transform, and enrich legacy data required to support the various test cycles and ultimately the production cutover.Take advantage of data migration templates, perform the upload of data into the staging area of the migration tool, data validation, load simulation, data migration execution, and conduct a final data quality assessment.The Customer should validate and sign-off the migration.

## Task 1: Subtask 1: Execute Data Migration Using Staging Tables in SAP S/4HANA - Dev
#### Description
Execute Data Migration Using Staging Tables in SAP S/4HANA
This task is relevant for implementations using the staging tables migration approach.

The purpose of this task is to execute data migration using the staging tables approach.

Procedure:

1. Follow the procedure in the [Data Migration to SAP S/4HANA from Staging (2Q2)](https://me.sap.com/processnavigator/SolS/EARL_SolS-055/2023/SolP/2Q2?region=US) accelerator to migrate the various migration objects. Below is a summary of the steps.
* Create the migration project.
* Select the migration objects.
* Populate the staging tables with the files or alternatively via 3rd party tools.
* Validate data and perform value mapping.
* Simulate data migration.
* Execute data migration.

2. Verify migrated data for accuracy and completeness.

3. Document the process and sequence for each object in the cutover plan.
## Task 1: Subtask 2: Execute Migrate Data Directly from an Existing SAP System - Dev
#### Description
This task is relevant for implementations using the migration scenario Migrate Data Directly from SAP system.

The purpose of this task is to execute data migration using the Migrate Data Directly from SAP system approach.

Procedure:

1. Follow the procedure in the [Help - Migrate Data Directly from SAP System accelerator](https://help.sap.com/viewer/29193bf0ebdd4583930b2176cb993268/latest/en-US/7a62b59726ce42e7a10770b06940f934.html). Below is a summary of the steps.
* Create/update RFC Connection and Select data
* Validate Data and Perform Value Mapping
* Simulate Data Migration
* Execute Data Migration
2. Update or verify that the processes and sequences for each object are documented in the cutover plan.

## Task 1: Subtask 3: Transport Data Migration Project to the Test Tenant
#### Description
The purpose of this task is to transport the data migration project to the target tenant.

Prerequisites:

Data migration project is assigned to a transportable development package during the project creation.
Procedure:

1.Add the objects to the transport request via SAP S/4HANA migration object modeler (transaction LTMON). Detailed documentation for the SAP S/4HANA migration object modeler can be accessed online from the app.

2. Move the transport request to the target system using the transport management system.
* For additional information on the transport process when using staging tables, see the [Transport Concept – Migrate Data Using Staging Tables accelerator.](https://www.sap.com/documents/2021/10/6af5929d-007e-0010-bca6-c68f7e60039b.html)
* For additional information on the transport process when using direct transfer, see the Note 3043614 - SAP S/4HANA Migration Cockpit: Transfer data directly from SAP system - transport & system modifiability.
* Procedure Notes:

The Export/Import functionality will be deactivated in future release. For more information on the Export/Import functionality, see accelerator SAP Note 3081981 - Migration Object Modeler (LTMOM): How to transfer or export / import a project from one system to another, Migration Cockpit - Migrate Data Using Staging Tables.
## Task 1: Subtask 4: Execute Data Migration Using Staging Tables in SAP S/4HANA - Test
#### Description
This task is relevant for implementations using the staging tables migration approach.

The purpose of this task is to execute data migration using the staging tables approach.

Procedure:

1. Follow the procedure in the [Data Migration to SAP S/4HANA from Staging (2Q2) ](https://me.sap.com/processnavigator/SolS/EARL_SolS-055/2023/SolP/2Q2?region=US)accelerator to migrate the various migration objects. Below is a summary of the steps.
* Create the migration project.
* Select the migration objects.
* Populate the staging tables with the files or alternatively via 3rd party tools.
* Validate data and perform value mapping.
* Simulate data migration.
* Execute data migration.
* Verify migrated data for accuracy and completeness.
2. Document the process and sequence for each object in the cutover plan.
## Task 1: Subtask 5: Execute Migrate Data Directly from an Existing SAP System - Test
#### Description
This task is relevant for implementations using the migration scenario Migrate Data Directly from SAP system.

The purpose of this task is to execute data migration using the Migrate Data Directly from SAP system approach.

Procedure:

Follow the procedure in the [Help - Migrate Data Directly from SAP System](https://help.sap.com/viewer/29193bf0ebdd4583930b2176cb993268/latest/en-US/7a62b59726ce42e7a10770b06940f934.html) accelerator. Below is a summary of the steps.
Create/update RFC Connection and Select data
Validate Data and Perform Value Mapping
Simulate Data Migration
Execute Data Migration
Update or verify that the processes and sequences for each object are documented in the cutover plan.
## Task 1: Subtask 6: Conduct Final Data Quality Assessment
#### Description
The purpose of this task is to verify the quality of the data sets once all objects have been migrated into all integrated systems. The stakeholders are notified that data migration is completes and business scenario testing can begin.

Procedure:

1. Conduct a final quality assessment with the data owners documenting the findings and action items.
2. Report the final findings to key stakeholders.
3. Finalize documentation of data migration processes.
4. Finalize the data cutover sequence and plan.
## Task 1: Subtask 7: Transport Data Migration Project to Production
#### Description
The purpose of this task is to transport the data migration project to the target tenant.

Prerequisites:

Data migration project was previously transported from development.
Procedure:

1. Move the transport request to the target system using the transport management system.
* For additional information on the transport process when using staging tables, see the [Transport Concept – Migrate Data Using Staging Tables](https://www.sap.com/documents/2021/10/6af5929d-007e-0010-bca6-c68f7e60039b.html) accelerator.
* For additional information on the transport process when using direct transfer, see the Note 3043614 - SAP S/4HANA Migration Cockpit: Transfer data directly from SAP system - transport & system modifiability.

## Task 2: AWS: Data migration tools and accelerators
#### Description
Evaluate AWS tools for data migration acceleration from SAP and non-SAP sources. The target maybe SAP Datasphere. 

## Task 3: Cutover Plan
#### Description
Cutover planning covers the cutover tasks required to achieve the Production Cutover with the desired quality, outcomes and timelines. Cutover Planning includes all aspects to execute a cutover. Including logistics, communications, key decision points, continuity and contingency planning and a detailed Cutover Project Plan.

## Task 3: Subtask 1: Create Cutover Plan and Documentation for System Conversion
#### Description
This task is relevant for the System Conversion scenario

The purpose of this task is to create and document the cutover plan. The plan is based on the learnings from the load & verification runs that have been performed so far. The conversion of the production system requires a clearly defined cutover plan and will typically be controlled by a cutover manager. This task will help you get a validated cutover plan, which documents all the steps leading up to and through a successful Go-Live.

The cutover plan does not detail the technical conversion to the level that is captured in the cookbook. It is common to highlight specific tasks from the cookbook within the cutover plan to ensure the process is on schedule.

Procedure:

Review the [How to Approach Remote Cutover ](https://support.sap.com/content/dam/SAAP/SAP_Activate/S4H_747%20How%20to%20Approach%20Remote%20Cutover.pptx)accelerator.
Create a draft cutover plan that documents the end-to-end activities of the cutover. The following are commonly found in a cutover plan.
Prerequisite steps for the production conversion
Ramp-down activities (e.g. batch jobs, interfaces, etc.)
Pre-conversion validation reports
End-user lockout
Technical migration and business data conversion
Post conversion changes (e.g. transports, parameter changes, etc.)
Technical post-conversion validation reports (e.g. checking for business data consistency)
Business-driven system validation and comparison of the pre and post-conversion reports
Go/No-Go decision
Ramp-Up activities (e.g. batch jobs, interfaces, etc.)
User unlock
Review roles and responsibilities. Every task within the cutover plan should have an assigned owner, estimated duration, and identified dependencies. Whenever possible, assign a name to the owner of the task, and not a team or group of resources. The owner of each task should validate and approve the task to ensure they understand their responsibilities. If there are any tasks required to specifically enable the conversion activities, the cutover plan should include related tasks to reset the values to the intended productive state.
Include contingency plans. The cutover plan should also include a contingency plan to revert the changes in the event there is a No-Go decision. If the contingency plan does not exist within the actual cutover plan, the cutover plan should have reference to the location of the fallback plan.
Perform the following activities based on the additional conversion runs:
Document key steps of the migration and conversion activities.
Assign owners to all tasks.
Review the tasks with the owners to confirm ownership and document the estimated duration.
Conduct at least one full walk-through of the plan as an entire team.
Document the fallback or contingency plan to safely return production operations in the event of a No-Go.
Work with the business process owners and the batch schedule owners to document the steps required to safely and quickly ramp down and ramp-up production operations.
Long-running batch jobs should be identified so they can be rescheduled ahead of time. In the event a batch job needs to be manually terminated at the time of the cutover, it is important to have the termination procedures or the owners, documented and readily available.
Procedure Note(s):
## Task 4: Production Cutover
#### Description
The purpose of this deliverable is to execute the cutover plan and ready the business and system for productive use. The cutover plan contains both business process tasks as well as system tasks. It is executed in the days prior to the go-live date.

Examples of potential tasks in the cutover list are as follows. Based on the solution, not all may be applicable.

* Setting up and initializing the production system
* Setting up and verifying interface connections
* Migration or creation of master data
* Migration of order objects (i.e. purchase orders, sales orders, etc)
* User creation/access
* Go/no go decision points
* Closing the legacy systems
* Notification of impacted 3rd parties
* Completing all required documentation for regulatory purposes
## Task 4: Subtask 1: Execute Cutover Tasks per the Cutover Plan
#### Description
The purpose of this task is to cutover to the productive system, obtain the customer approval (sign-off), validate that the go-live acceptance criteria have been met, and confirm the successful go-live.

Procedure:

Execute the cutover to Production following the task defined in the cutover plan.
Document the actual duration of each step to support future projects.
Capture any variances to the plan along with the decision maker who approved the change.
The cutover manager(s) should proactively notify task owners of upcoming tasks, to ensure their availability.
Regularly communicate status to stakeholders.
Test and validate the systems after the cutover has finished.
Obtain the production approval sign-off, which documents the agreement with the stakeholders that cutover tasks have been successfully executed.
#### Tools
How to Approach Remote Cutover (Public)
## Task 5: ISV Partner Spotlight - DMI - Data Migration Implementation by JiVS IMP - Realize
#### Description
Definition of historical and operational data, structure and value mapping, providing data to migration cockpit, load data. Prepare historization. Supported by JiVS IMP SAP S/4

## Task 6: ISV Partner Spotlight - DMI - Production Data Load by JiVS IMP
#### Description
Production Data Load supported by JiVS IMP Migration 
