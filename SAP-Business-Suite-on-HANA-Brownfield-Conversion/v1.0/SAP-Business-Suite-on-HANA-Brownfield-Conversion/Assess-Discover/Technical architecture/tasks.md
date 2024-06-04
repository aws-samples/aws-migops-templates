
# Module: Technical architecture
## Task 1: System Design Validation
#### Description
Prior to the contract signature, SAP (direct) or Partner (indirect) should discuss with the customer the target technical architecture scope and explain the PCE Roles & Responsibilities, also collecting information on the SAP and Customer network integration. The to-be landscape information should be reviewed for future state determination, including but not limited to:SolutionsSizingSecurityConnectivityDisaster Recovery

#### Tools
Migration Evaluator collector tool
## Task 1: Subtask 1: Introduction to the Pre-Provisioning Form
#### Description
The CAA should introduce the customer to the Pre-Provisioning Form (also known as the technical assessment form. The customer is required to complete and sign-off the Pre-Provisioning Form (PPF) and return it to SAP. This must be completed and returned within 5 days after the contract signature. For indirect customers, refer to the Partner Playbook in the useful link section.

## Task 1: Subtask 2: Migration server Hardware for Partner led migration services
#### Description
Partner-led migrations require additional hardware (Shell), due to governance restrictions of the cloud providers
Note: This is only relevant for Brownfield and Selective Data Transition (SDT) scenarios.

## Task 2: AWS: Landing zone review
#### Description
Review landing zone for Non-SAP customer applications in AWS
Review Connectivity options - TGW/VPC peering
Review Backup recovery, HA/DR

## Task 3: AWS: Adjacent workload review
#### Description
Review integration with 3rd party non-SAP applications 

## Task 4: Initial Sizing
#### Description
The initial sizing approach is based on the specific customer journey. It may be that for system conversions, the sizing report is executed to produce the target sizing estimates. In more complex cases, like Selective Data transitions, with high data volumes to migrate, an additional service to calculate the target size may be required.SAP CAA (direct engagement) or Partner CAA (indirect engagement) to perform an initial sizing check using sizing reports and use the results for system conversion scenarios.The AE may need to engage services to perform quick sizer functions for Greenfield net new journeys.

## Task 4: Subtask 1: Advanced Sizing
#### Description
Review the useful link to verify if the Customer should go through Advanced Sizing activities.

## Task 4: Subtask 2: AWS: Right sizing adjacent workloads
#### Description
AWS: Right sizing adjacent workloads
## Task 5: Advanced Sizing
#### Description
Review the tools listed below to go through Advanced Sizing activities if needed.

#### Tools
SAP Sizing
#### Tools
HANA Quick Sizer
## Task 6: AWS: Right sizing review for adjacent workloads
#### Description
Review right sizing approach for adjacent workloads 
Review **[AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)** principles for SAP adjacent workloads.

## Task 7: Target Enterprise Architecture
#### Description
Assess the technical options and determine the recommended Customer Enterprise Architecture. Prepare a draft technical deployment roadmap. The output of the Application Value & Scoping will then determine the target solutions that the CAA can then use to define the Technical architecture.

## Task 8: Platform Security Validation
#### Description
Customer to validate with the SAP Account team that their security requirements are met on the platform. Eg: Ensure PCI DSS compliant to meet credit card requirements.Customer to engage and align with their security team. SAP Account team to engage with the relevant SAP security pre-sales team. 
## Task 9: Conversion Readiness Assessment
#### Description
Conversion Readiness Assessment
## Task 9: Subtask 1: Conduct Technical Review Workshop
#### Description
The purpose of the task is to conduct the working sessions to deep dive into Add-on Compatibility, Active Business Functions, SAP S/4HANA Sizing, and Custom Code Analysis from the SAP Readiness Check result for planning and preparing system conversion to SAP S/4HANA.
## Task 10: ISV Partner Spotlight: Onapsis
#### Description
Onapsis can help in RISE with SAP deployments with
* Ensure clear understanding of best practices for SAP application security
* Before migration, identify legacy systems and custom code issues
* Fully understand security obligations for systems integrators and RFPs
* Maximize efficiency for testing throughout the project
* Prepare your team and understand the shared security model you have with RISE for SAP
* Always keep the lights on: Keep your legacy systems protected and productive in the meantime
