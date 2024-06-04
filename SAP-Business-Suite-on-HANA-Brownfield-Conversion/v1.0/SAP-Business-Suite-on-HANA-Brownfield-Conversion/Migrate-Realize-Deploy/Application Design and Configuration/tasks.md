
# Module: Application Design and Configuration
## Task 1: Cutover Preparation
#### Description
Prepare a detailed cutover plan that includes all the required activities. Document the strategy, scope, and timelines for moving from the as-is solution to the to-be solution and the post-go-live support period immediately the following go-live. Ensure that a number of trial cutover exercises are included before the live cutover. Ensure that timings are validated and adjusted where necessary.

## Task 2: Output Management
#### Description
Deliver output management processes, including the connection of devices, customization of forms, and the determination logic.

#### Tools
AWS Cloud Migration Factory
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
•  Automate and implement the migration process in multiple iterations (waves) until all the applications are migrated
## Task 2: Subtask 1: Set Up Printers
#### Description
The purpose of this task is to define the technical setup for printing business documents. This is executed by defining print queues in the system and installing the print manager on local network.

Procedure:

Execute procedure listed in accelerator **[Output Management Set-up Instructions (1LQ)](https://support.sap.com/content/dam/SAAP/Sol_Pack/Library/Setup/1LQ_Set-Up_EN_XX.pdf)**.
## Task 2: Subtask 2: Set Up Email
#### Description
The purpose of this task is to define the technical setup for sending emails. This includes defining the sender domains, sender email addresses and email addresses for testing.

Procedure:

Execute procedure listed in accelerator **[Output Management Set-up Instructions (1LQ).](https://support.sap.com/content/dam/SAAP/Sol_Pack/Library/Setup/1LQ_Set-Up_EN_XX.pdf)**
## Task 2: Subtask 3: Customize Form Templates
#### Description
The purpose of this task is to create customer specific form templates based on the SAP provided templates using Adobe LiveCycle Designer. Activities include downloading the form templates, modifying and testing them locally, and uploading them back to the system for further testing.

SAP delivers standard form templates for many business applications as well as for different layout definitions.

Procedure:

Execute procedure listed in accelerator **[Output Management Set-up Instructions (1LQ)](https://support.sap.com/content/dam/SAAP/Sol_Pack/Library/Setup/1LQ_Set-Up_EN_XX.pdf)**.
## Task 2: Subtask 4: Customize Email Templates
#### Description
The purpose of this task is to create customer specific email templates based on the SAP provided templates. Activities include copying an SAP email template, modifying its content, and defining business rules for its usage. SAP delivers standard email templates for many business applications.

Procedure:

Execute procedure listed in accelerator **[Output Management Set-up Instructions (1LQ)](https://support.sap.com/content/dam/SAAP/Sol_Pack/Library/Setup/1LQ_Set-Up_EN_XX.pdf)**.
## Task 2: Subtask 5: Transport Custom Objects from Quality to Production System
#### Description
The purpose of this task is to migrate the custom objects and configuration to the P-System.

Procedure:

Execute procedure listed in accelerator **[Output Management Set-up Instructions (1LQ)](https://support.sap.com/content/dam/SAAP/Sol_Pack/Library/Setup/1LQ_Set-Up_EN_XX.pdf)**.
## Task 3: User Access and Security Implementation
#### Description
Ensure the solution meets the Customers security requirements.Steps to perform are:1) Realise the security services.2) Document the results of the security activities (e.g. S/4HANA Authorization Concept).
#### Tools
AWS Cloud Migration Factory
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Clean up and decommission the resources used during the migration process.
#### Acceptance Criteria
• Optimize the performance of the server instances 
## Task 4: Solution Walkthrough
#### Description
Provide a walkthrough of the new solution capability to the corresponding project team members for early knowledge transfer. Run a session per Line of Business/ end-to-end solution and present the new functionality from an application perspective. Explain the required configuration from an IT perspective. An agile approach is recommended; develop the solution and show the iterations.

## Task 5: Solution Configuration
#### Description
Configure solution to meet requirements. Configure the mandatory settings, according to the delta design defined and agreed during the fit-to-standard process. An agile approach is recommended; develop the solution and show iterations.

## Task 6: Analytics Configuration
#### Description
Configure embedded analytics in the Development, Quality, and Production environment, as signed off in the Explore phase. Follow the setup guide of Scope Item BDH, published in the SAP Signavio Process Navigator.

## Task 7: UX Deployment
#### Description
Application Design and Configuration

## Task 8: Analytics Configuration in the Quality System
#### Description
Analytics Configuration in the Quality System
## Task 8: Subtask 1: Setup and Enable Embedded Analytics
#### Description
The purpose of this task is to enable embedded analytics in the solution.

Procedure:
Follow and review the configuration, technical setup, and enablement published in the SAP Signavio Process Navigator via the following path: **[Embedded Analytics with SAP S/4HANA](https://me.sap.com/processnavigator/SolP/BGH)** accelerator > navigate to the “Accelerators” section > choose the Technical Setup and Enablement for SAP S/4HANA Embedded Analytics file.
## Task 8: Subtask 2: Configure Analytics in the Quality System
#### Description
The purpose of this task is to configure Analytics according to the previously developed setup guides.

Procedure:
* Configure reports to the specifications determined in the Explore phase.
* Execute pre-delivered test scripts where available.
* Test and evaluate the analytics report(s) with the available data.
* Capture and release the custom objects in the transport request (TR).

## Task 9: Analytics Configuration in the Production System
#### Description
The purpose of this deliverable is the configuration of Analytics in the Production System.
## Task 9: Subtask 1: Verify Analytics in the Production System
#### Description
The purpose of this task is to verify the analytics in the Production system according to the previously developed setup guides for a successful run.

Prerequisites:
* Successful import of the transport request in the Production system
* Successful testing of reports in the Quality landscape

Procedure:
* Execute pre-delivered test scripts where available.
* Execute custom reports to the specifications which were run through in the previous system.
## Task 10: ISV Partner Spotlight: Redwood
#### Description
* RunMyJobs is a native cloud platform with a guaranteed 99.95% SaaS uptime and zero-effort maintenance, so you can be confident to run millions of transactions daily and deliver the expected performance. 
* RunMyJobs is the only enterprise job scheduler that can directly integrate S/4HANA, SAP BTP and other SAP solutions in the workload automation space without requiring any custom code or special infrastructure.
* RunMyJobs consolidates job scheduling requirements in a powerful platform, enables companies to build automation faster with drag-and-drop visual process editor and prebuilt templates, and job orchestration across both current and future SAP ecosystem. 
