
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

## Task 2: AWS: Landing zone review
#### Description
Review landing zone for Non-SAP customer applications in customer's AWS account. Review connectivity options for integration with the RISE with SAP environment including options for [Transit Gateway](https://aws.amazon.com/transit-gateway/) and [VPC peering](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html). 
Further review options for backup, recovery, high-availability, and disaster recovery for customer's adjacent workloads. 

## Task 3: AWS: Adjacent workload review
#### Description
Review integration with 3rd party non-SAP applications 

## Task 4: Initial Sizing
#### Description
The initial sizing approach is based on current environment size and users. RISE with SAP is sized based on [FUE](https://community.sap.com/t5/enterprise-resource-planning-blogs-by-sap/did-you-say-fue-a-definition/ba-p/13556847) 

The SAP CAA (direct engagement) or Partner CAA (indirect engagement) to perform an initial sizing check using sizing reports.

## Task 4: Subtask 1: Advanced Sizing
#### Description
Review the useful link to verify if the Customer should go through Advanced Sizing activities.

## Task 4: Subtask 2: AWS: Right sizing adjacent workloads
#### Description
AWS: Right sizing adjacent workloads
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

## Task 9: ISV Spotlight: Onapsis
#### Description
Onapsis can help in RISE with SAP deployments with: 
* Ensure clear understanding of best practices for SAP application security
* Before migration, identify legacy systems and custom code issues
* Fully understand security obligations for systems integrators and RFPs
* Maximize efficiency for testing throughout the project
* Prepare your team and understand the shared security model you have with RISE for SAP
* Always keep the lights on: Keep your legacy systems protected and productive in the meantime