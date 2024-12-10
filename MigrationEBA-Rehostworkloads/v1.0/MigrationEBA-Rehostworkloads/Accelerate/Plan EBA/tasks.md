
# Module: Plan EBA
## Task 1: Define And Activate Cadence
#### Description
EBA Planning is a shared responsibility of customer, partner and AWS; success of the EBA depends on it.

**Suggested Candence:**
* **Sponsor** - 2-3 times during the EBA cycle - 1/ At the start for alignment and goal setting, 2/ End of planning phase to prepare for EBA kick off, 3/ During EBA for daily standups and demo, and 4/ Post EBA readout and next steps
* **EBA leads** - Daily standups or at least 2-3 times per week to monitor progress
* **WS Leads** - 3x/week or as needed to complete pre-work
* **Other** - SMEs and workstream leads should hold working sessions as needed to make progress leading up to the EBA

*(Owner: EBA lead drives key cadence)*

#### Acceptance Criteria
Planning calls scheduled on everyone's calendar.
## Task 2: Finalize Scope And Select Applications
#### Description
1. Identify 5-10 candidate applications for the EBA with the goal of shortlisting 3-5 medium complexity application eventually. If the customer already has a migration plan in place, this step becomes a review of the selected applications to ensure alignment amongst stakeholders.

2. Application Selection Guidance - Selected applications should:
*  Represent the application landscape that is in the migration program or scope
*  Be of “Medium-level” complexity
*  Have a defined business value that can be validated post-migration (ie. cost/agility/UX)
*  Have established or documented acceptance testing criteria
*  Have the application owner on board and application SMEs available to participate in the EBA

3. If required, conduct portfolio assessment/application discovery to identify and prioritize the applications for the EBA. Reach out to AWS account team for more information on portfolio assessment.discovery or visit the [eba home page](https://aws.amazon.com/experience-based-acceleration/).

*(Owner: EBA and Tech Lead with customer alignment)*
## Task 3: Determine EBA Workstreams
#### Description
Target minimum workstreams to accomplish the EBA goals, typically 3-4 is sufficient. Workstream choices will depend on the EBA type and objectives. For detailed workstream guidance, click on the links below:
1. [Command Center](https://amazon.awsapps.com/workdocs/index.html#/document/b25087109fbc0115dab1a4a8e57b59e681b360f3a9ca4b153e28d938f0dd18f6)
2. [Operations](https://amazon.awsapps.com/workdocs/index.html#/document/fdf098487ac69a8199ad7e62ae54b765e884a1e508cd8992e472bc7f37d07d69)
3. [Security](https://amazon.awsapps.com/workdocs/index.html#/document/898a40b27f43438c88d0be386bbf4e9904f6d4514ade8797fe94473fd2ded292)
4. [Foundations](https://amazon.awsapps.com/workdocs/index.html#/document/e0fd736bb2a282e8d4900e0c6a203fae0cfa475e1a064cfc13269c74912a4940)
5. [Platform](https://amazon.awsapps.com/workdocs/index.html#/document/66f226fb3cb7487a955ed14fb80748db62ccbaa1622f0c4fc49cab6fa2e13254)
6. [Windows](https://amazon.awsapps.com/workdocs/index.html#/document/252633d92e3253c00f4a5786d029d8e3bc45cde86f0fc3bf2418eb3464e2e64d)
7. [Migration](https://amazon.awsapps.com/workdocs/index.html#/document/89e990e29f09b9e04e663195ef57849f1fdc157b4c2daace9b5c5218441d90aa)
8. [Modernization](https://amazon.awsapps.com/workdocs/index.html#/document/0b1d175fdbe755b785798b2f61c7b99ff8a5041f4cf4542f58bcb5584c5e36f9)
9. [Automation](https://amazon.awsapps.com/workdocs/index.html#/document/be3156a9f2431477f3dd6d50aa713f73de0eaaebe8296182ce2724964a6d7089)
10. [App Acceleration](https://amazon.awsapps.com/workdocs/index.html#/document/038e42f13f3f16659accf1e31902f11b3c9ab2adc25fd29cbb13245a136d1e5f)

*(Owner: EBA and Tech leads)*
#### Tools
Workstream Template
#### Acceptance Criteria
Attach completed slides in the attach file section.
## Task 4: Identify Workstream Participants & Their Roles
#### Description
* Complete the template with Customer and AWS names and roles for each workstream. Attach completed slide in the attach files section below.
* Review the Role definitions for an EBA and the RACI Guidance before filling out the template.

*(Owner: EBA Lead)*
#### Tools
Workstream Participants Template with Roles & Resp. Guidance
## Task 5: Assess and Schedule Required Trainings
#### Description
Identify training/workshops/immersion days required for the customer team to: 1/ successfully execute the EBA and 2/ setup a fly wheel effect for continued momentum beyond the EBA. 

*(Owner: EBA and Tech Lead)*
#### Tools
AWS Workshops (Public)
## Task 6: Workstream Application - Deep Dive Application Layer
#### Description
Deep dive to understand the application layer current state, dependencies, documentation available, gaps, etc. (*Owner: Tech Lead)*
## Task 7: Workstream Application - Deep Dive Messaging Layer
#### Description
Understand the current state and the desired "To be" state for the messaging layer. *(Owner: Tech Lead)*
## Task 8: Workstream Application - Deep Dive Integration Layer On-Prem
#### Description
Uncover and understand all on-prem integrations and which will continue to be needed and how it will be accomplished. *(Owner: Tech Lead)*
## Task 9: Workstream Application - Deep Dive Integration Layer External
#### Description
Understand the existing external integrations and what would it look like in the future state. *(Owner: Tech Lead)*
## Task 10: Workstream Application - Deep Dive Licensing implications related to OS, Apps, and Infrastructure Tools
#### Description
Understand the existing licenses for OS, Applications (COTS) and Infrastructure tools and what would it look like in the future state. (Owner: Tech Lead)
#### Tools
Optimization and Licensing Assessment
## Task 11: Workstream Application - Deep Dive Deployment and Testing Models (Manual vs Automated)
#### Description
Identify existing processes for deploying the application and translate that to AWS. *(Owner: Tech Lead)*
## Task 12: Landing Zone
#### Description
Make sure to have a full understanding of Landing Zone requirements
#### Tools
Landing Zone
## Task 12: Subtask 1: Workstream Foundations - AWS accounts discussion
#### Description
Engage the customer in discussion about AWS Accounts, and what are the requirements for EBA 
## Task 12: Subtask 2: Workstream Foundations - Create AWS Accounts
#### Description
create the identified AWS Accounts
## Task 12: Subtask 3: Workstream Foundations - Enable AWS Organizations
#### Description
Enable AWS Organization, and move created account in the correct OU
## Task 12: Subtask 4: Workstream Foundations - Determine AWS Region
#### Description
Determine in which region/s the EBA target architecture operates
## Task 12: Subtask 5: Workstream Networking - Define IP ranges and setting  up VPCs
#### Description
Define the required IP ranges and set up required VPCs
## Task 12: Subtask 6: Workstream Networking - Network connectivity discussion (VPN/DX/TGW/Peering/EndPoints)
#### Description
Engage the customer in discussion about Network connectivity (on-prem -> AWS, and AWS -> AWS)
## Task 12: Subtask 7: Workstream Networking - Networking Setup
#### Description
Setup the network for the EBA (Public & Private Subnets, VPC Peerings, Transit Gateway, etc.) and how Corporate Network will connect to AWS
## Task 12: Subtask 8: Workstream Networking - Identify/Configure Any Firewall, Port, Protocol
#### Description
Identify & configure Firewall/Port/Protocol required for EBA
## Task 12: Subtask 9: Workstream Networking - DNS / Route53 Integration
#### Description
Configure Route53 and integration with existing DNS (if any)
## Task 12: Subtask 10: Workstream Networking - VPC security design(NACL/SG)
#### Description
configure VPC level security (Network ACLs, Security Groups, Route Tables)
## Task 12: Subtask 11: Workstream Networking - VPC Endpoints
#### Description
Create the identified VPC Endpoints needed for the EBA
## Task 13: Run the Cloud Foundation Assessment Tool (CFAT)
#### Description
**Running CFAT is MANDATORY for migrations where cloud foundations is in scope.**
CFAT is a read-only script which can be run in the customer's management account via a single line command. The tool runs in less than 2 mins and generates a detail report and a maturity score. The maturity score reflects the status of the foundational elements in the account - what is enabled and what is not? Where are the critical gaps, required vs. recommended elements. The output is a detaled report which also identifies the required elements that must be completed before migration at scale can begin. Links to prescriptive guidance and level of effort needed to complete each task is detailed in the report.
#### Tools
Cloud Foundations Assessment Tool (CFAT)
#### Tools
Enablement and Training to use CFAT
#### Acceptance Criteria
Go/No-Go decision on Cloud foundations focused EBA. Based on CFAT report, a task plan of the required activities to be completed as part of the EBA to build a solid foundations for migration at scale. 
## Task 14: Workstream Application - Generate Target State Architecture
#### Description
Build out the on-prem to AWS Services mapping and generate the target state architecture. *(Owner: Tech Lead)*
## Task 15: Assess operating Model for the application
#### Description
* Does the app team have full control of infra, apps and configuration (example: 2 pizza team)
* If the operating model is split between different team, What are the internal processes for engagement.
## Task 16: Prepare Participants For EBA And Execute Pre-work
#### Description
* Meet with participants to review scope and specific assignments.
* Hold a EBA watch party for the EBA Foundations training and ensure all participants have taken the training.
* Identify all pre-work for each workstream.
* Tech lead identifies pre-requisites and ensures completion. 
* Complete pre-work through strong collaboration between customer and AWS participants. 
**NOTE: Customer owns the activity, AWS provides guidance.**
* Attach pre-work list for each workstream in the attach file section below.
* **AWS Services that can be leveraged in the pre-work step:**
* [AWS Application Migration Service (AWS MGN)](https://w.amazon.com/bin/view/Application-Migration-Service)
* [AWS Application Discovery Services](https://aws.amazon.com/application-discovery/)
* [AWS Control Tower](https://aws.amazon.com/controltower/)

*(Owner: EBA and Tech Lead)*
#### Tools
EBA Foundations Training
#### Tools
EBA Technical Pre-work Example List
## Task 16: Subtask 1: Deliver Identified Trainings
#### Description

## Task 16: Subtask 2: Identify & Execute Pre-Work
#### Description

## Task 17: EBA Logistics
#### Description
* Plan EBA logistics (use attached checklist under subtasks).
* Develop and finalize EBA agenda (use attached template under subtasks).
* Attach the finalized agenda in the attach file section below.

*(Owner: EBA Lead)*
## Task 17: Subtask 1: Plan EBA Logistics
#### Description
if the EBA is virtual make sure to have all the required "virtual room" the workstream needs and a centralized kanban board to track progresses.
If the EBA is in person make sure to have rooms booked for the entire duration, whiteboard available for drafting, sticky notes for kanban (and a cowbell to celebrate achievements)
If the EBA is hybrid you'll need both
## Task 17: Subtask 2: Develop and Finalize EBA Agenda
#### Description
finalize the agenda with:
- voice of the customer
- stand-ups
- retro
- demo sessions
- EBA closure

and make sure to circulate it ahead of time
## Task 18: Pre-Requisites
#### Description
This task tracks the status of all the identified pre-requisites & pre-works.
Additional ones can be added if required.

## Task 18: Subtask 1: Complete Foundations Workstream
#### Description

## Task 18: Subtask 2: Complete Security Workstream
#### Description

## Task 18: Subtask 3: Complete Networking Workstream
#### Description

## Task 18: Subtask 4: Complete Operations Workstream
#### Description

## Task 19: Network Planning
#### Description
Plan your network target state
## Task 19: Subtask 1: Network Bandwidth
#### Description
Make sure to have enough bandwidth for EBA objectives
## Task 19: Subtask 2: Non Blocking IP Addresses
#### Description
Determine if your application requires the existing IP address moved to AWS. If you need the existing IP address, ensure the VPC CIDR created in AWS is non-overlapping to avoid any routing issues.

Here are some strategies to handle overlapping IP spaces - [Connecting Networks with Overlapping IP ranges](https://aws.amazon.com/blogs/networking-and-content-delivery/connecting-networks-with-overlapping-ip-ranges/)
#### Tools
Connecting Networks with Overlapping IP ranges
## Task 20: AWS Lift & Shift Services - MGN
#### Description
Provide overview & support setup and configuration of AWS MGN
## Task 20: Subtask 1: AWS MGN Overview
#### Description
Introduce Business and Technical audience to AWS MGN
#### Tools
AWS MGN Documentation
## Task 20: Subtask 2: Identify AWS Accounts for MGN
#### Description
Make sure to identify which account to use for AWS MGN. Choose the account that suits best in the region you want to migrate resources to
## Task 20: Subtask 3: Setup MGN
#### Description
Make sure to correctly setup MGN
#### Tools
MGN First time setup
## Task 21: AWS Lift & Shift Services - Cloud Migration Factory
#### Description
Provide overview & support setup and configuration of AWS Cloud Migration Factory
## Task 21: Subtask 1: AWS Cloud Migration Factory Overview
#### Description
Introduce Business and Technical audience to AWS Cloud Migration Factory
#### Tools
AWS Cloud Migration Factory Documentation
## Task 21: Subtask 2: Setup Cloud Migration Factory
#### Description
Make sure to correctly setup Cloud Migration Factory
#### Tools
How to get started with Cloud Migratioon Factory
## Task 22: AWS Lift & Shift Services - DMS
#### Description
Provide overview & support setup and configuration of AWS DMS
## Task 22: Subtask 1: AWS DMS Overview
#### Description
Introduce Business and Technical audience to AWS DMS
#### Tools
AWS DMS Documentation
## Task 22: Subtask 2: Setup DMS
#### Description
Make sure to correctly setup DMS
#### Tools
Setting up for AWS DMS
## Task 23: AWS Lift & Shift Services - DataSync
#### Description
Provide overview & support setup and configuration of AWS DataSync
## Task 23: Subtask 1: AWS DataSync Overview
#### Description
Introduce Business and Technical audience to AWS DataSync
#### Tools
AWS DataSync Documentation
## Task 23: Subtask 2: Setup DataSync
#### Description
Make sure to correctly setup DataSync
#### Tools
Getting started with AWS DataSync
## Task 24: AWS Lift & Shift Services - Storage Gateway
#### Description
Provide overview & support setup and configuration of AWS Storage Fateway
## Task 24: Subtask 1: AWS Storage Gateway Overview
#### Description
Introduce Business and Technical audience to AWS Storage Gateway
#### Tools
AWS Storage Gateway Documentation
## Task 24: Subtask 2: Setup Storage Gateway
#### Description
Make sure to correctly setup Storage Gateway
#### Tools
Getting started with Storage Gateway
## Task 25: Finalize Architecture Deep Dive
#### Description
Deep dive in the target architecture and how it maps to the existent architecture. Make sure to do so from all the perspectives
## Task 25: Subtask 1: Server layer requirements deepdive
#### Description

## Task 25: Subtask 2: Storage layer requirements deepdive
#### Description

## Task 25: Subtask 3: Network layer requirements deepdive
#### Description

## Task 25: Subtask 4: Databases layer requirements deepdive
#### Description

## Task 25: Subtask 5: API integrations layer deepdive
#### Description

## Task 25: Subtask 6: Messaging layer deepdive
#### Description
