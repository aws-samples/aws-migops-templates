
# Module: Technical architecture
## Task 1: System Design Validation
#### Description
Prior to the contract signature, SAP (direct) or Partner (indirect) should discuss with the customer the target technical architecture scope and explain the PCE Roles & Responsibilities, also collecting information on the SAP and Customer network integration. 

The to-be landscape information should be reviewed for future state determination, including but not limited to:
* Solutions
* Sizing
* Security
* Connectivity
* Disaster Recovery

#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• A document (PDF or spreadsheet) with current inventory data and performance data
## Task 2: AWS: Landing zone review
#### Description
Review landing zone for Non-SAP customer applications in AWS
Review Connectivity options - TGW/VPC peering
Review Backup recovery, HA/DR

## Task 3: AWS: Adjacent workload review
#### Description
Review integration with 3rd party non-SAP applications 

## Task 4: Blue Field Sizing
#### Description
In complex cases, like Selective Data transitions, with high data volumes to migrate, an additional service to calculate the target size may be required. SAP CAA (direct engagement) or Partner CAA (indirect engagement) to perform an initial sizing check using sizing reports and use the results for Blue Field scenarios. 
## Task 5: Introduction to the Pre-Provisioning Form
#### Description
The CAA should introduce the customer to the Pre-Provisioning Form (also known as the technical assessment form. The customer is required to complete and sign-off the Pre-Provisioning Form (PPF) and return it to SAP. This must be completed and returned within 5 days after the contract signature. For indirect customers, refer to the Partner Playbook in the useful link section.

## Task 6: AWS: Right sizing review for adjacent workloads
#### Description
Review right sizing approach for adjacent workloads 
Review AWS Well Architected Framework principles for SAP adjacent workloads.
Reference: https://aws.amazon.com/architecture/well-architected/
## Task 7: Target Enterprise Architecture
#### Description
Assess the technical options and determine the recommended Customer Enterprise Architecture. Prepare a draft technical deployment roadmap. The output of the Application Value & Scoping will then determine the target solutions that the CAA can then use to define the Technical architecture.

## Task 8: Platform Security Validation
#### Description
Customer to validate with the SAP Account team that their security requirements are met on the platform. Eg: Ensure PCI DSS compliant to meet credit card requirements.Customer to engage and align with their security team. SAP Account team to engage with the relevant SAP security pre-sales team. Note(s): All security contacts can be found in the useful links section.

## Task 9: Conversion Readiness Assessment
#### Description
The purpose of the task is to conduct the working sessions to deep dive into Add-on Compatibility, Active Business Functions, SAP S/4HANA Sizing, and Custom Code Analysis from the SAP Readiness Check result for planning and preparing system conversion to SAP S/4HANA.
## Task 10: Temporary Hardware for Shell Creation
#### Description
Temporary hardware is required to create Shell systems from the source system (via system copy)
#### Acceptance Criteria
Shell system created via system copy from production successfully.
## Task 11: ISV Spotlight: Enhanced sizing with inputs from KTern
#### Description
ISV Spotlight: Enhanced sizing with inputs from KTern