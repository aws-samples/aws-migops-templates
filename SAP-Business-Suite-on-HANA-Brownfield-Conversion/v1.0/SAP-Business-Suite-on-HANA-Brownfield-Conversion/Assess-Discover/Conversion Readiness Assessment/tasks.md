
# Module: Conversion Readiness Assessment
## Task 1: Perform SAP Readiness Check for SAP S/4HANA
#### Description
The purpose of this task is to run a self-service report from the SAP Support Portal to check conversion readiness. To support customer conversion projects, SAP offers SAP Readiness Check for SAP S/4HANA to help customers during the planning and preparation activities for the system conversion to SAP S/4HANA.

Review and familiarize yourself with the SAP S/4HANA Conversion scenario using the following accelerators: [SAP Readiness Check SAP Help Portal](https://help.sap.com/viewer/p/SAP_READINESS_CHECK) and the [SAP Readiness Check Community](https://community.sap.com/topics/readiness-check). The SAP Readiness Check for SAP S/4HANA focuses on high-level findings, for example:
Simplification Item Relevance
Custom Code
Recommended Fiori Apps​
SAP S/4HANA Sizing​
Add-on Compatibility​
Business Functions​
Use the SAP Note 2913617 - SAP Readiness Check 2.0 accelerator to have a guided step by step procedure to
Implement or de-implement per mandatory prerequisites
Run SAP Readiness Check in current ERP production system
Access the result through SAP For Me

Note: There are multiple SAP Readiness Check scenarios available. Make sure to select the SAP Readiness Check for SAP S/4HANA Conversion scenario.

## Task 2: Conduct Functional Review Workshop
#### Description
The purpose of this task is to conduct working sessions to review the Simplification Items, Financial Data Quality, and Customer Vendor Integration Analysis from the SAP Readiness Check result to understand the functional steps required before, during, and after the system conversion to S/4HANA

1. Review and familiarize yourself with the Functional Review Workshop Guide for System Conversion accelerator.
2. Distribute the Simplification Items to business process experts for review in their respective line of business to understand the compatibility scope status and associated business impact. ​
3. Conduct Simplification Item Workshops by business process areas (i.e. Finance, Procurement, Sales, etc.) to go through all the Simplification Items and classify them into three groups: requires remediations before conversion, need implementation efforts (i.e. Fit-to-standard workshop), not relevant.
*  Finance process experts can use Financial Data Quality results to check quality of financial data, analyze possible inconsistencies, and decide how to resolve them.
*  Master data experts can leverage Customer Vendor Integration analysis for a status on the current state of customer vendor integration and data quality issue.
4. Define the pre-projects to be executed during the Prepare phase. Some examples are the reconciliation of Financial Data and the synchronization of Customers/Vendors into Business partners (CVI) in a Sandbox environment.

Notes:
Reference the [Simplification Item Catalog](https://me.sap.com/sic) for a full list of items.
Not all Simplification Items are mandatory.
A typical system conversion project prioritizes those mandatory mediation items first. However, SAP Recommends including the items listed in the Compatibility Scope Analysis.
During the workshop, customers should also decide if optional Simplification Items will be addressed as part of the initial phase of the project or in a secondary phase.



## Task 3: Conduct Technical Review Workshop
#### Description
The purpose of the task is to conduct the working sessions to deep dive into Add-on Compatibility, Active Business Functions, SAP S/4HANA Sizing, and Custom Code Analysis from the SAP Readiness Check result for planning and preparing system conversion to SAP S/4HANA.


1. Review the [Technical Review Workshop Guide for System Conversion](https://support.sap.com/content/dam/SAAP/SAP_Activate/S4H_1032%20Technical%20Review%20Workshop%20Guide%20for%20System%20Conversion.pptx) accelerator. Familiarize yourself with examples provided and schedule workshop(s).
2. Schedule the sessions by each relevant topic. Make sure to invite the main stakeholders.
3. Conduct technical Workshops for Add-on Compatibility, Active Business Functions, SAP S/4HANA Sizing, and Custom Code Analysis.
4. Define the pre-projects to be executed during the Prepare phase. Some examples are Perform Data Volume Management, Add-On Compatibility, and Cleanup of unused custom code.