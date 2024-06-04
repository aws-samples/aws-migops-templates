
# Module: Extensibility
## Task 1: Prepare Custom Code
#### Description
Relevant for a system conversion scenario.Prepare and analyse the custom code from the On-Premise system and adapt it to the newest SAP S/4HANA. The custom code migration process for the system conversion to SAP S/4HANA describes how to analyse legacy code, the tools and necessary procedures to migrate custom code. The process consists of the preparatory analysis and the adaptation of the custom code after the technical system conversion. The Partner needs to execute code analysis and migration.

## Task 1: Subtask 1: Cleanup Custom code
#### Description
erform a custom code clean up to reduce the custom code footprint prior to the start of the system conversion and new implementation. Two steps to take, decommission unused custom code &/or improve custom code quality. Procedure to decommission:

Set up the decommissioning cockpit in SAP Solution Manager.
Compare the list of used code (identified via the usage and procedure logging or business process documentation), with the custom code inventory list. This helps to identify code that is not in use.
Identify and define the custom code objects subject to decommissioning.
Perform backups and decommission the custom code.
Procedure to improve custom code quality:
Set up an efficient custom code quality management process and project.
Implement the corresponding Software Quality check tools, like SAP ABAP Test cockpit or SAP Code Inspector.
Test your newly implemented quality measures by running a code quality improvement project.
## Task 2: Extension Planning & Design
#### Description
Bimodal architecture design. Plan, design and sign-off on business process extensions. The final decision regarding the extension sits with the customer, after taking into account workload, used technology, licenses and skill set of resources.

## Task 3: Artificial Intelligence Planning & Design
#### Description
Start planning for the Artificial Intelligence (AI) implementation. This includes completion of the questionnaire and installation of various applications before running SAP Intelligent RPA Bots.As part of the planning, review the processes for Robotics Process Automation to establish the business processes that can be automated.
## Task 4: Perform Data Volume Planning
#### Description
This task is relevant for the System Conversion scenario.

The purpose of this task is to plan and prepare the Data Volume Management (DVM). This task should be considered prior to a system conversion to reduce the amount of data to be converted. It can impact the duration and downtime of the cutover.

Prerequisites:

Data Volume Management Planning should be considered specifically in the following cases:

Sizing results indicate the need for an SAP HANA server larger than the expected
DVM Alerts from the SAP Early Watch Alert report indicates a need for DVM
Data archiving is already actively used. This indicates the need to adjust the archiving strategy according to the new data models and technology (i.e. data aging)
The system is older than 5 years and no significant data archiving has been scheduled and there is a high probability that data is on the system that is no longer relevant for daily business processes.
Precondition is a first estimate on the expected database size of SAP HANA sees task Define Technical Architecture.

Procedure

Review SAP Note 2818267 - Data Volume Management during migration to SAP S/4HANA.
Review **[Help - Data Aging](https://help.sap.com/docs/SAP_NETWEAVER_750/669e1da71e744a34af9b86deec50a57c/5306a0995655488785175d57bef083da.html)** and SAP Note 2315141 - Collective note for Data Aging Framework.
Analyze the current database and determine how much data can be archived or deleted upfront of an SAP S/4HANA implementation.
Use Data Volume Management app available in SAP for Me. However, in case you have not archived before, it could be challenging to identify the key archiving objects and their saving potential.
Create and document the Data Volume Management plan and strategy prior to transitioning to the new S/4HANA solution. The plan should have the following:
Go or No-Go decision for future DVM activities in the scope of the S/4HANA conversion project.
In the case of Go, the result will be a road map that defines the exact scope of the data volume management activities including timelines, estimated effort, required teams, and resources for the individual data archiving and deletion activities.
Based on this road map, the next step of defining a Data Volume Management strategy will be performed.
## Task 5: ISV Partner Spotlight - DMI - Installation of JiVS IMP SAP S/4 migration edition
#### Description
Installation of migration tooling supported by JiVS IMP SAP S/4
## Task 6: ISV Partner Spotlight - KTern - Prepare Custom Code
#### Description
Prepare and analyse the custom code from the On-Premise system and adapt it to the newest SAP S/4HANA. The custom code migration process for the system conversion to SAP S/4HANA describes how to analyze legacy code, the tools and necessary procedures to migrate custom code. The process consists of the preparatory analysis and the adaptation of the custom code after the technical system conversion. The Partner needs to execute code analysis and migration.

Run KTern.AI analysis to capture as-is and to-be code impact with usage insights.

Leverage KTern.AI data-driven scan of SAP ERP systems to understand the clean core driven analysis of as-is custom codes with usage and determine the comprehensive to-be impact with prioritization of fixes based on level of impact and materiality.
## Task 7: ISV Partner Spotlight: SNP
#### Description
During Mobilize/Prepare/Explore phase, SNP can help build your target landscape. 
[SNP CrystalBridge Shell Creator](https://www.snpgroup.com/en/platform/software-and-components/crystalbridge-shell-creator/) ensure the fastest possible system build with only customization data & without any master and transactional data. [CrystalBridge Shell Creator](https://www.snpgroup.com/en/platform/software-and-components/crystalbridge-shell-creator/) can make an empty copy of any SAP system, complete with customizations.