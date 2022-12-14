
# Module: Initial Engagement with AWS
## Task 1: Get an overview of the AWS migration methodology
#### Description
To migrate applications to AWS, we recommend that you use an approach that consists of four phases: assessment, mobilization, migration, and operation. Before you start a migration, get an overview of these phases and of the AWS tools to consider in each phase. These details help simplify and automate the entire migration experience. 

For an overview of the phases and tools that we recommend you use for migrations, see [AWS Migration Hub.](https://docs.aws.amazon.com/migrationhub/latest/ug/whatishub.html.)

For an overview of the migration process, see [AWS Cloud Migration.](https://aws.amazon.com/cloud-migration/.)
#### Tools
Overview of AWS Migration Services
#### Acceptance Criteria
• Understood the phases of a migration.
#### Acceptance Criteria
• Discovered the list of AWS tools to use in each phase.
## Task 2: Document migration goals
#### Description
Document the type of applications that you want to migrate. Determine the main concerns that you need to address and the outcomes that you want to achieve by migrating to AWS. Example outcomes are cost savings and increased IT productivity. 

The questions and solutions that you document during the discussion help determine the overall direction for the migration.  

For more details, see [AWS Cloud Migration](https://aws.amazon.com/cloud-migration/) and [AWS Prescriptive Guidance](https://aws.amazon.com/prescriptive-guidance/.)
#### Acceptance Criteria
• Documented a comprehensive list of workloads to migrate
#### Acceptance Criteria
• Documented the list of concerns and suggested solutions for AWS  migration.  
#### Acceptance Criteria
• Documented the list of outcomes to be achieved with migration. 
## Task 2: Subtask 1: Application workloads to migrate
#### Description
Create  an initial list of applications that need to be migrated to AWS. Workloads may include  applications, websites, databases, storage, physical or virtual servers and  data centers from an on-premises environment, hosting facility, or other  cloud infrastructures to AWS.
#### Acceptance Criteria
•  Document a comprehensive list of workloads to migrate 
## Task 2: Subtask 2: Address migration concerns
#### Description
There  may be various concerns regarding migrating to cloud such as Application  migration strategies, Software licensing, Cost savings, performance  disruption during migration, migration project resources, developing a  foundation for operating in the cloud, Security and compliance etc. Engaging  with AWS experts will address those prioritized concerns.  

AWS Cloud Migration provides answers to above mentioned concerns:  [AWS Migrations](https://aws.amazon.com/cloud-migration/) 

Also AWS Prescriptive Guidance provides various strategies for AWS  Migrations: [AWS Prescriptive Guidance](https://aws.amazon.com/prescriptive-guidance/)
#### Acceptance Criteria
•  Document list of concerns and suggested solutions for AWS migration.
## Task 3: Perform first planning checkpoint
#### Description
After you complete a deep dive and address the major concerns, prepare a central deck or document where you outline the best solutions and services that AWS provides for migrations.  

Include the following in the deck:  
1) A migration plan for your application portfolio
2) A potential operating model and service management framework
3) A plan to use an experienced AWS partner
4) A plan to use AWS programs such as MAP for the migration
#### Acceptance Criteria
•  A presentation deck with the best solutions and services AWS provides for migrations to AWS
# Module: Migration Readiness Assessment
## Task 1: MRA -  Review objectives and best practices
#### Description
Migration Readiness Assessment (MRA) is a critical step early in the migration journey. Its goal is to assess the readiness of your applications for migrating to AWS. You gain critical  insights regarding readiness and build a plan to close the identified gaps. 

The MRA also provides AWS and AWS partners with an opportunity to build trust and to be positioned as the preferred provider as customers expand their adoption into the AWS Cloud.

As part of the MRA workflow, the primary task is to review the targeted objectives of the migration journey. Targeted objectives might include building an overall vision, creating a reliable implementation roadmap, identifying gaps, and providing corrective actions.

In this module, you review the current architecture, security, and governance. You also create concrete deliverables to prepare for cloud adoption. By validating migration readiness against the available best practices, you can identify the strengths and weaknesses of the current architecture and avoid possible roadblocks while migrating.

For more information about MRA, see [Migration Readiness](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-readiness/welcome.html.)
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Reviewed the current architecture and identify strengths and weaknesses
#### Acceptance Criteria
• Created an implementation roadmap for migration based on best practices
## Task 2: Perform MRA pre-workshop activities
#### Description
Perform  pre-workshop activities as a first step in the MRA.  The pre-workshop activities include the following:  

1) Identifying attendees
2) Pre-workshop questionnaire 
3) Planning the delivery (teneral and technical scope)
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Created a list of attendees who support the MRA delivery
#### Acceptance Criteria
• Created a pre-workshop questionnaire
## Task 2: Subtask 1: Identifying  stakeholders
#### Description
Create a list of attendees who will be part of a unified team that supports the delivery of the MRA. The attendees include a migration expert who facilitates the assessment activities and a customer expert who drives the customer relationship.

For more information about the attendees, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-readiness/assessment-meeting.html#attendees)
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Create a list of attendees who support the MRA delivery
## Task 2: Subtask 2: Pre-workshop Questionnaire
#### Description
A facilitator, a sponsor, and participants of the MRA carry out this task. The facilitator owns the assessment with support from the sponsor and the participants. The facilitator follows the  pre-workshop questionnaire workflow and assigns, follows up, and reviews the questionnaire.


#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Complete pre-workshop  questionnaire.
## Task 2: Subtask 3: Planning the delivery
#### Description
After completing the pre-workshop questionnaire, the facilitator reviews the responses and understands the targeted outcomes. In addition to scheduling the workshop events as part of the MRA, the facilitator also  reviews the technical scope of the MRA. 
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Identify detailed plan of deliverables
## Task 3: Perform MRA workshop activities
#### Description
The facilitator organizes the workshop activities as a second step in the MRA. The workshop agenda includes the following:

1) Executive perspective
2) Trends, success patterns, and alignment
3) Discovery
4) Financial enablement
5) Workshop results and closure
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Prepared a detailed MRA report
#### Acceptance Criteria
• Created a document describing the next phase proposal 
## Task 4: Perform MRA post-workshop activities
#### Description
After you complete the workshop, start preparing for the Mobilize phase. The preparation must cover the following:

1) Customers identify the leader for the migration within the organization
2) Customers have commitment to move forward with the migration phases
3) Customers to decide on governance, security, and operating processes  
4) Creation of a final SOW for the Mobilize phase
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Created a detailed SOW for the Mobilize phase
# Module: Data collection setup
## Task 1: Collect data using appropriate data collection tool
#### Description
To evaluate the current migrating environment to AWS, you need to collect the inventory and performance data of the  environment that needs to be migrated. To collect this data, you set up and run the Migration Evaluator collector tool. The collector tool accumulates data with a high level of accuracy, which helps to analyze and suggest the appropriate approach for migration.

For information about the tool, see [Agentless collector overview](https://d1.awsstatic.com/migration-evaluator-resources/agentless_collector_overview.pdf.)




#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• A document (PDF or spreadsheet) with current inventory data and performance data
## Task 1: Subtask 1: Migration Evaluator collector tool overview
#### Description
Migration  Evaluator collector tool document outlines the flow of data while using the  tool, in which the customer chooses to acquire provisioning and utilization  patterns via the on-premises agentless Migration Evaluator Collector.   

More details regarding the tool can be found here:  [Agentless collector overview](https://d1.awsstatic.com/migration-evaluator-resources/agentless_collector_overview.pdf)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• Overview of Migration Evaluator tool.  
#### Acceptance Criteria
• Clear understanding how data is collected and retained using the collector tool.
## Task 1: Subtask 2: Run pre installation checklist
#### Description
After you gain a clear understanding of the Migration Evaluator collector tool, run through a checklist of items before you install the  tool. 

The following document highlights the [checklist](https://d1.awsstatic.com/migration-evaluator-resources/collector_install-guide.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  Run through the checklist and ensure that all prerequisites are satisfied. 
## Task 1: Subtask 3: Install the Migration Evaluator collector tool
#### Description
After you ensure that the items in the pre-installation checklist are satisfied, install the tool. See [here](https://d1.awsstatic.com/migration-evaluator-resources/collector_install-guide.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• Installed the Migration Evaluator Bootstrapper 
#### Acceptance Criteria
• Installed the Migration Evaluator collector
## Task 1: Subtask 4: Configure the Migration Evaluator collector  tool
#### Description
After  successfully installing the Migration Evaluator collector tool, it needs to  be configured to collect the desired inventory data. This depends on the type  of resources that needs to be migrated to AWS. There could be different types  of resources in a migrating environment such as VMWare, SQL Servers, Bare  metal servers, Hyper V servers etc. 

#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  Configured the tool for the desired resources in the environment
## Task 1: Subtask 5: Add notes about collected data
#### Description
After you successfully configure the Migration Evaluator collector tool, validate the collected data and document any missing details and dependencies.
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  Added notes and upload the data back to the tool.
## Task 2: Upload existing collector tool data 
#### Description
If a complete list of servers with their provisioning, software, and utilization is already available, the Migration Evaluator tool supports uploading the existing environment data.

Use the data-import template to upload the data. See [Data Import template](https://d1.awsstatic.com/migration-evaluator-resources/ME_DataImport_Simple.68724f31e3dd1469c1095a13597d74c79dd734b9.xlsx.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• Gathered provisioning, software, and utilization data for the existing environment
#### Acceptance Criteria
• Used the data-import template to upload the collected data
# Module: Directional Business Case creation
## Task 1: Generate  quick insights report 
#### Description
Provides a summary of discovered infrastructure, highlighting the savings that can be achieved by rightsizing workloads to match actual utilization. 

Business stakeholders can download a one-page summary highlighting the estimated savings to rehost on AWS based on usage patterns with costs broken down by infrastructure and software licenses.

For a more technical audience, detailed per-server and per-SQL-server data is also available.

For a Quick Insights report sample, see [Quick Insights Sample Report](https://d1.awsstatic.com/asset-repository/Migration_Evaluator_Quick_Insights_Sample_Report.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• A detailed Quick Insights report that provides a summary of the discovered migrating environment
## Task 2: Generate directional business case
#### Description
A  business case report is provided at the end of the migration assessment. The report includes the following: 

1)  Scope overview
2)  On-premises estimate using industry benchmarks and cost modelling scenarios
3)  Microsoft SQL core insights  
4)  Utilization patterns.For the directional business case, see [Business Case Sample](https://d1.awsstatic.com/asset-repository/tso-logic/MigrationEvaluator_TSOLogic_AWS_BusinessCaseSample.pdf.)

#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  A detailed directional-business-case document 
# Module: Specialized assessment Optimization and Licensing Assessment OLA
## Task 1: OLA  Secure customer agreement
#### Description
As part of the  OLA process, secure a customer agreement that includes the following: 

1) Migration project scope
2) Business objective 
3) Project contacts
4) Security and privacy
5) Project-timeline review


#### Acceptance Criteria
• Customer confirms readiness to kick-start the OLA project. 
## Task 2: OLA  Kick off project
#### Description
After the customer confirms readiness to kickstart the OLA project, do the following:

1) Kick off the OLA project
2) Install the data collector tool (Migration Evaluator collector tool) on the desired migrating environment infrastructure
3) Use the tool to collect utilization data
#### Acceptance Criteria
• Provisioned the data collector tool with the desired migrating environment infrastructure
#### Acceptance Criteria
• Used the Migration Evaluator collector tool to collect utilization data for the migrating environment
## Task 3: OLA  Document results
#### Description
After you use the Migration Evaluator collector tool to collect the data, do the following:

1) Prepare the final output presentation based on the collected data
2) Move to the next steps to integrate with partners and Proserve teams
#### Acceptance Criteria
•  Generated the OLA report using the collected data
# Module: Specialized assessment Storage Discovery Analysis SDA
## Task 1: SDA  First planning checkpoint
#### Description
Prepare a central document that outlines the following:

1) Current storage-infrastructure performance and capacity data in the migrating environment
2) Mappings to AWS storage services for each storage infrastructure discovered in the migrating environment
3) Directional cost estimation
4) High-level engagement plan
#### Acceptance Criteria
• Prepare a  presentation where you highlight the discovered storage infrastructure and directional business case
## Task 2: SDA  project kickoff
#### Description
After you create the document, do the following:  

1) Kick off the SDA project
2) Get customer agreement to register for the NetApp Cloud Insights tool 
3) Install the NetApp Cloud Insights tool
4) Use the tool to collect capacity, performance, space savings, storage type, access type, workload type, and architecture details


#### Acceptance Criteria
• NetApp Cloud Insights tool provisioned with the desired migrating environment infrastructure
#### Acceptance Criteria
• Migrating environment utilization data collected using the tool
## Task 3: SDA  Document results
#### Description
After you use the Migration Evaluator collector tool to collect the data, prepare the following: 

1) The final output presentation based on the collected data
2) The next steps to integrate with p artners and Proserve teams


#### Acceptance Criteria
• Documented business case for an on-premises storage migration to AWS  including a one-year directional cost analysis. 
#### Acceptance Criteria
• Documented on-premises storage footprint insights, analysis, and mapping to  AWS storage services  
#### Acceptance Criteria
• Documented roadmap proposal for one (1) pilot storage workload migration (in partnership with ProServe)
# Module: Mobilize Phase readiness
## Task 1: Document  Mobilize phase execution plan
#### Description
Mobilize phase  is performed by both AWS personnel, AWS partners or customer stakeholders. It is  important to determine who performs which Tasks in the mobilize phase. Plan ahead of time by engaging the AWS and customer stakeholders determines who will be performing the tasks. 


#### Acceptance Criteria
• Determine  the AWS Personnel and Customer stakeholder to perform the Mobilize phase  tasks. 
## Task 2: Record  appropriate artifacts and decisions
#### Description
In  order to sign off on the Assess phase as part the AWS Migration the following artifacts must be completed. Some artifacts may not be relevant depending on the type of migration:  

1) Central repository of all migration decisions  
2) Migration Readiness Assessment (MRA) report  
3) Migrating environment infrastructure discovery data   
4) Directional Business Case   
5) Optimization and Licencing Assessment (OLA)  
6) Storage Discovery & Analysis (If needed)  
7) Signed Statement of Work (SOW) if AWS Professional Services or partner is executing the migration


#### Acceptance Criteria
• Present central repository of all migration decisions taken till now
#### Acceptance Criteria
• Ensure upload of Migration Readiness Assessment (MRA) is complete  
#### Acceptance Criteria
• Ensure migrating environment infrastructure discovery data is available
#### Acceptance Criteria
• Ensure Directinal Business Case is approved by senior management  
#### Acceptance Criteria
• Complete Optimization and Licencing Assessment (OLA)
#### Acceptance Criteria
• Complete Storage Discovery & Analysis (If needed)
#### Acceptance Criteria
• Decide who will perform the migration and upload statements of work as needed
# Module: Overall Governance
## Task 1: Engagement Initiation
#### Description
This task helps in the initiation of the Mobilize phase. It assumes that the Assess phase was successfully completed. The goal of this task is to start creating a plan, collect all artifacts, and kick off engagement.
#### Acceptance Criteria
• Obtain completed SOW document (if applicable)
#### Acceptance Criteria
• Conduct engagement kickoff with Mobilize team  
#### Acceptance Criteria
• Customer onboarding
## Task 1: Subtask 1: Obtain fully executed SOW from Practice Manager if applicable
#### Description
Finalize the SOW as part of the completion of the Assess phase. To kick-start the Mobilize phase, engage with the practice manager to get the finalized SOW and analyze the scope, cost, and planning details. 
#### Acceptance Criteria
• Completed an SOW after the Assess phase
## Task 1: Subtask 2: Establish the Engagement/Mobilize Delivery Team
#### Description
To ensure timely planning and execution, resource the team with qualified team members with the appropriate skill sets. Add them as contributors to the journey.
#### Acceptance Criteria
•  Finalized the team to own the Mobilize phase deliverables
## Task 1: Subtask 3: Conduct internal engagement kickoff with  Account Team/Mobilize Team
#### Description
Plan and conduct an internal team kickoff that includes all AWS and vendor and partner resources. This inclusive kick-off ensures that all stakeholders have an opportunity to establish and agree to a common operating model before engaging the full customer team.
#### Acceptance Criteria
• Completed an engagement kickoff with the associated teams 
#### Acceptance Criteria
• Clear knowledge on the plan and deliverables
## Task 1: Subtask 4: Review SOW and Deliverables with Account  Team/Mobilize team
#### Description
Review the SOW with the account team so that there is a common understanding of  scope, cost, and planning. Also review the list of planned deliverables for the Mobilize phase. 
#### Acceptance Criteria
•  Reviewed a plan for the Mobilize phase
#### Acceptance Criteria
• Reviewed the list of deliverables for the Mobilize phase
## Task 1: Subtask 5: Request customer docs, data and org  charts, etc from Account Team
#### Description
To validate your understanding of the organization and communication, request  organizational charts from the customer and your organization. Upload the charts as attachments. 
#### Acceptance Criteria
•  Defined an organizational hierarchy for effective communication
## Task 1: Subtask 6: Manage Background Check and Site/Tools  Access for consultants
#### Description
Understand and document the customer's background and tools-access process in order to communicate the process and complete the on-boarding in a timely manner. Upload the final artifact as an attachment. 
## Task 1: Subtask 7: Assign Workstream Leads to review and refine each module in the Mobilize phase
#### Description
Each AWS workstream owner must refine tasks and subtasks in each of their modules.
#### Acceptance Criteria
•  Defined backlog items for execution 
## Task 1: Subtask 8: Setup Customer Onboarding instructions
#### Description
Identify and document onboarding instructions such as onboarding forms and access processes.

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Customer-Offboarding-Checklist.md).
#### Acceptance Criteria
•  Documented onboarding instructions
## Task 2: Resource Management
#### Description
This task ensures that migration engagement is set up in CRM tools (for example, Salesforce). 
#### Acceptance Criteria
• Engagement onboarding in CRM tool
## Task 2: Subtask 1: Ensure  Engagement is setup in SFDC
#### Description
Complete the  engagement setup in SFDC so that resourcing and financial management can be  completed.


#### Acceptance Criteria
• Completed  engagement setup in the CRM tool
## Task 2: Subtask 2: Submit Resource Requests to Resource Management
#### Description
Submit  resource requests to ensure that the engagement is staffed appropriately.
#### Acceptance Criteria
•  Successful resource requests submitted in the CRM tool
## Task 2: Subtask 3: Complete staffing resource forecasts in SFDC
#### Description
Complete  resource requests to ensure that the engagement is staffed appropriately.
#### Acceptance Criteria
•  Approved and confirmed resource requests in the CRM tool
## Task 2: Subtask 4: Review and Monitor resource forecasts in SFDC
#### Description
Review  and update the staffing resource forecast in SFDC so that they are aligned  with the most recent requirements.
#### Acceptance Criteria
•  Completed staffing resource forecast in the CRM tool
## Task 3: Partner Collaboration
#### Description
Ensures partner onboarding is complete. Defines the distribution of roles and responsibilities.
#### Tools
Mobilize responsibility distribution template
#### Acceptance Criteria
• Partner onboarding complete
#### Acceptance Criteria
• Defined responsibility distribution
## Task 3: Subtask 1: Complete  Partner and PO Financial Management
#### Description
Complete the partner engagement setup in SFDC so that resourcing and financial management  can be completed.
#### Acceptance Criteria
• Completed partner-engagement setup in the CRM tool
## Task 3: Subtask 2: Define Roles & Resources
#### Description
Work  with the project partners and validate roles, resources, and responsibilities to ensure that the team has a clear understanding of each.

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Mobilize-Responsibility-Distribution.md).
#### Tools
Mobilize responsibility distribution template
#### Acceptance Criteria
•  Documented the role and responsibilities for each team member
## Task 3: Subtask 3: Complete onboarding with partner
#### Description
Ensure that the partner onboarding process has been established and that time and schedule are aligned with work.
#### Acceptance Criteria
•  Documented a list of onboarding processes for partners
## Task 3: Subtask 4: Provide Mobilize-Specific Training 
#### Description
Train the team in the Mobilize phase so that they can work effectively.
#### Acceptance Criteria
•  Trained team members to carry out the Mobilze phase using management tools
## Task 4: Engagement Tooling
#### Description
Review Customer?s current state project  management methods and capabilities.

#### Acceptance Criteria
• Identified and Approved list of tools for Mobilize  phase
#### Acceptance Criteria
• Project management for Mobilize phase
## Task 4: Subtask 1: Customer  Purchases Engagement Tooling 
#### Description
Review and  validate engagement tooling so that templates and backlogs can be loaded as  quickly and effectively as possible.
#### Tools
GitHub repos
#### Tools
Communication tools
#### Acceptance Criteria
• Identified list of tools to support the mobilize phase implementation.
## Task 4: Subtask 2: Obtain approval to install tools or  applications in the customer environment
#### Description
Obtain  approval and access to install the framework tools in the enviromnent so that  the team can begin to rely on the framework at the outset of the project.
#### Tools
GitHub repos
#### Tools
Communication tools
#### Acceptance Criteria
•  Approved list of engagement tools
## Task 4: Subtask 3: Implement Engagement Tooling 
#### Description
Implement  engagement tooling so that the Mobilize phase can be established as soon as  the engagement kickstarts.
#### Tools
GitHub repos
#### Tools
Communication tools
#### Acceptance Criteria
• Installation of approved engagement tools.
#### Acceptance Criteria
• Kickstart using the tools. 
## Task 4: Subtask 4: Workstream Lead to review and refine DKs and  backlogs
#### Description
Review  the epics and stories in the backlog template so that we can be sure that the  backlog aligns with the SOW requirements.
#### Acceptance Criteria
•  Reviewed list of tasks and subtasks as per the approved SOW  deliverables. 
## Task 4: Subtask 5: Workstream Leads to create epics or stories to  fill any backlog gaps 
#### Description
Create  epics, stories, and subtasks in the backlog so that the starting backlog  aligns with the unique characteristics of the SOW. 
#### Acceptance Criteria
• Identified list of Epics/Stories/Tasks as part of backlog items.
## Task 4: Subtask 6: Collate Workstream backlogs for import
#### Description
Collate  workstream refined backlogs for ease of review and upload to the approved  tool 
 
#### Acceptance Criteria
• Identified list of Epics/Stories/Tasks as part of backlog items.
## Task 4: Subtask 7: Import backlog to approved tool
#### Description
Import  workstream refined backlogs for use during the Mobilize engagement
#### Acceptance Criteria
 1) Identified list of Epics/Stories/Tasks as part of backlog items.
## Task 4: Subtask 8: Stand up the IT Governance Decision  Catalog 
#### Description
Throughout  the large migration, leads make decisions to resolve any issues that arise.  Because of the size and scope of a large migration project, the project  manager cannot be present when every decision is made. Workstream leads are  responsible for recording the decisions that affect their workstream. The  project manager is responsible for reviewing the decisions and presenting  recent decisions at the project status review meetings.  

More information is available [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-governance-playbook/task-project-management.html#step-decision-log)
#### Acceptance Criteria
•  Defined decision catalog
## Task 4: Subtask 9: Stand up the RAID log
#### Description
Similar  to the decision log, you should track risks and issues in a project  management tool known as a risks, actions, issues, and dependencies (RAID)  log. No matter how thoroughly you plan your large migration, issues will  occur, and you will identify some risks to your project. By identifying and  recording risks and issues, you provide transparency to the project, and you  establish a process to control and monitor potential issues, minimizing their  impact to the project.  

More information is available [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-governance-playbook/task-project-management.html#step-raid-log)
#### Acceptance Criteria
•  Defined RAID log
## Task 5: Engagement Logistics
#### Description
Review engagement sponsorship and logistics such as location, working hours, and single point of contact.

#### Acceptance Criteria
• Identified Leadership team
#### Acceptance Criteria
• Defined engagement logistics
## Task 5: Subtask 1: Identify and Engage Executive Sponsorhip (CIO/Deputy CIO)
#### Description
Ensure that you have a clear understanding of the executive leadership team and of project sponsorship and ownership.
#### Acceptance Criteria
• Identified the executive leadership team
## Task 5: Subtask 2: Establish Meeting Cadence with Executive Sponsorship
#### Description
To establish preplanning elements, set up a regular cadence with the executive sponsorship, then meet weekly to maintain communication and governance during the sprint cycles.
#### Acceptance Criteria
• Scheduled periodic meetings with the executive leadership team
## Task 5: Subtask 3: Get Customer Commitment for work schedule for team.
#### Description
Identify the core team of customer staff and ensure that they will be available full-time at least three days per week, so that the appropriate velocity and cadence can be maintained.
#### Acceptance Criteria
• Identified work schedule for the team
## Task 5: Subtask 4: Confirm office location and typical office hours
#### Description
Confirm working locations and typical hours so that the team has appropriate access.
#### Acceptance Criteria
• Identified work location and hours
## Task 5: Subtask 5: Identify a customer onsite contact and/or helpdesk to assist with issues
#### Description
Identify an onsite contact so that the team knows who to reach out to for facilities or process issues.
#### Acceptance Criteria
• Identified Single Point of Contact (SPOC)
## Task 6: Customer Onboarding
#### Description
This task helps in the customer onboarding with access requests and hardware possession. 
#### Acceptance Criteria
• Completed Access requests
## Task 6: Subtask 1: Submit access  requests for AWS resources
#### Description
Submit the appropriate resource access requests such as for project management tools and communication tools.

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Customer-Onboarding-Checklist.md).
#### Acceptance Criteria
• Created  access requests to AWS resources
## Task 6: Subtask 2: Determine the customer network-access model (VPN or laptop) 
#### Description
Determine how the team can access the tools required for the engagement.  For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Customer-Onboarding-Checklist.md)
#### Acceptance Criteria
•  Created and approved access requests using proprietary access tools
## Task 6: Subtask 3: Submit requests for badges, laptops, and other  resources
#### Description
Submit the apprioriate requests for physical resources for each team member  so that they can operate within the work space.
#### Acceptance Criteria
•  Created and approved access requests using proprietary access tools
## Task 7: Engagement Controls
#### Description
This task helps with working on the delivery kits for the Mobilize phase, with establishing communication mechanisms, and with project governance.
#### Tools
RACI templates
#### Acceptance Criteria
• Delivery kits for the Mobilize phase impor
#### Acceptance Criteria
• Defined RACI document
#### Acceptance Criteria
• Defined escalation matrix
## Task 7: Subtask 1: Import the Mobilize  Delivery Kits (DKs) to the approved tool
#### Description
Import  workstream delivery kits for use during the engagement.
## Task 7: Subtask 2: Establish a distribution list for the project team internally or externally accessible
#### Description
Establish  a Distribution List for ease of communication during the engagement. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Stakeholder-Register.md).
#### Tools
Communication tools
#### Acceptance Criteria
•  Created distribution list for effective communication
## Task 7: Subtask 3: Establish a stakeholder register Mobilize team page
#### Description
Establish  a stakeholder register for the engagement. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Stakeholder-Register.md).
#### Tools
Stakeholder register template
#### Acceptance Criteria
•  Documented list of stakeholders
## Task 7: Subtask 4: Establish a communication plan
#### Description
Establish a communication plan for the engagement.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Governance-%26-Norms.md)

#### Acceptance Criteria
•  Defined and approved communication plan
## Task 7: Subtask 5: Establish a deliverables log
#### Description
Establish a deliverables log for the engagement.
#### Acceptance Criteria
•  Defined and approved deliverables catalog
## Task 7: Subtask 6: Confirm the governance process with the customer 
#### Description
Confirm the dovernance processes for the engagement.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Governance-%26-Norms.md)

#### Acceptance Criteria
•  Defined and approved governance criteria. 
## Task 7: Subtask 7: Identify and document key dates, milestones and  success criteria for project
#### Description
Document  key dates, milestones, and success criteria for the engagement.
#### Acceptance Criteria
•  Created project plan with milestones, timelines, and success criteria
## Task 7: Subtask 8: Develop High Level Project plan
#### Description
Create a high-level project plan for the engagement.

#### Acceptance Criteria
•  Created high-level project plan
## Task 7: Subtask 9: Review and refine Project RACI document
#### Description
RACI template helps gain a common understanding for who makes decisions or performs activities in an initiative or in the future state of an organization. It helps set expectations upfront and minimizes issues that may arise later.
#### Tools
RACI templates
#### Acceptance Criteria
•  Create RACI document clearly defining responsible stakeholders
## Task 7: Subtask 10: Establish escalation matrix project and internal
#### Description
Define the escalation matrix for the engagement. An escalation matrix is a document or system that defines when escalation must happen and who must handle incidents at each escalation level.
#### Acceptance Criteria
•  Defined escalation matrix with appropriate hierarchy of escalation
## Task 7: Subtask 11: Establish sprint schedule and meeting cadence  (standups, retrospectives, status)
#### Description
Establish a sprint schedule and standard cadence with the customer for the Mobilize engagement. Daily team stand-ups and daily recurring workstream working sessions for initial sprints are recommended to maximize team  productivity.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Sprint-Schedule.md)
#### Acceptance Criteria
•  Defined sprint plans with appropriate schedules
## Task 7: Subtask 12: Establish agree on Weekly Status  Reporting Steering Committee meetings
#### Description
Establish weekly status reporting with the customer for the Mobilize engagement. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/MobilizeAccelerator/MobilizeAccelerator/Mobilize-Artifacts/Sprint-Status-%26-Demo.md)


#### Acceptance Criteria
•  Defined weekly status report templates
## Task 8: Customer Kick-off
#### Description
Customer Kick-off
## Task 8: Subtask 1: Distribute agenda and session invitations for customer kickoff and LRP sessions
#### Description
Distribute invitations and materials in preparation for the customer kickoff and LRP sessions
## Task 8: Subtask 2: Conduct customer-working-backwards workshop if  required
#### Description
Conduct working-backwards workshops if needed to support the engagement
## Task 8: Subtask 3: Conduct customer kickoff abd workstream Long-Range Planning LRP sessions
#### Description
Conduct kickoff and  LRP sessions to etablish the workstream goals and objectives for the  engagement
# Module: Portfolio Assessment
## Task 1: Portfolio Prerequisites
#### Description
This task helps in assessing data for the migrating environment, procuring discovery tools, and identifying key stakeholders for the portfolio discovery.
#### Tools
Data Source Discovery Assessment
#### Acceptance Criteria
• Finalize the discovery tool for the migrating environment
#### Acceptance Criteria
• Procure the discovery tool 
#### Acceptance Criteria
• Get approval to deploy the discovery tool in the migrating environment 
#### Acceptance Criteria
• Identify the stakeholders who will be involved as part of the migrating environment discovery
## Task 1: Subtask 1: Assess Discovery Data Sources & Tooling
#### Description
For migrating an environment to AWS, identifying and documenting existing sources of data and appropriate tooling is critical. Answering the following questions gives more details regarding the migrating environment?s current data. 

1) How accurate and up to date are the current infrastructure and application inventory?  
2) Does the inventory contain dependency data?
3) Does the inventory contain a catalog of licenses and licensing agreements for each product? 

Based on the level of trust assigned to these data points, choose the best discovery tool. 

For the full guidance, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/understanding-initial-assessment-data-requirements.html.)
#### Tools
Data Source Discovery Assessment
#### Acceptance Criteria
•  Get clear data points on the current infrastructure and its dependencies  
#### Acceptance Criteria
• Choose a discovery tool based on the collected data points
## Task 1: Subtask 2: Procure Discovery Tooling and/or Obtain  Approval for Deployment
#### Description
After you choose the discovery tool, procure the licenses and NDAs for usage and the cost to purchase for deployment in the current infrastructure.  Next, submit these details to organization leadership and stakeholders for approval for deployment in the existing environment.
#### Acceptance Criteria
• Procure the discovery tool by analyzing the cost, license agreements 
#### Acceptance Criteria
• Get approval from organization leadership and stakeholders to deploy in the current environment.
## Task 1: Subtask 3: Identify Stakeholders for Portfolio Discovery
#### Description
Migration of an environment is performed by both AWS personnel and customer stakeholders. It is important to determine who performs which tasks in this phase.  

Determining the answers for the following questions gives more clarity on the stakeholders

1) Who is impacted by the migration?  
2) Who are the decision makers?  
3) Who benefits from this migration?  
4) Who is responsible for performing the migration? 

For more guidance, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/understanding-initial-assessment-data-requirements.html)


#### Acceptance Criteria
• Create a list of stakeholders who will be affected by the migration or benefit from it. 
#### Acceptance Criteria
• Determine the decision makers those and responsible to perform the migration tasks.
## Task 2: Portfolio Discovery
#### Description
This first stage of  assessment focuses on the initial steps of obtaining and analyzing data at  the Portfolio Level. The main objective is to identify business drivers and  collect general data from applications and infrastructure in order to obtain  an initial view of the portfolio, including high-level technical and business  attributes such as application names, environment, product versions,  criticality, performance values, and others. This is key in order to  understand the scope of the project, identify initial migration candidates,  and inform the business case.
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Document a detailed plan to perform migrating environment discovery including the scope, prioritization, configuration and data collection.
#### Acceptance Criteria
• Document migrating environment Business drivers such as Accelerate innovation, Reduce operational and infrastructure costs, Increase operational resiliency etc.
#### Acceptance Criteria
• Capture complete application and infrastructure metadata.
#### Acceptance Criteria
• Document complete list of systems which will be part of the data collection.
#### Acceptance Criteria
• Create a prioritized list of applications with a stack rank in order of priority to migrate.
#### Acceptance Criteria
• Create a plan to iteratively collect data requirements of migrating applications.
#### Acceptance Criteria
• Detailed knowledge of the migrating environment
#### Acceptance Criteria
• Interdependencies of the portfolio
#### Acceptance Criteria
• Migration plan with appropriate workloads and timelines
## Task 2: Subtask 1: Plan Portfolio  Discovery Party
#### Description
The primary goals of the discovery party are to level up on the discovery process, identify the addressable scope, introduce an initial application prioritization criteria, and install, configure, and test the discovery tooling (if applicable), including rolling out data collection. To do so, it is necessary that the sources of data be clearly identified. Also, it is key that the requirements for tooling deployment, as well as the technical particularities of the environment where the tool will be deployed, be considered in advance. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning)
#### Acceptance Criteria
• Document a detailed plan to perform migrating environment discovery including the scope, prioritization, configuration, and data collection
## Task 2: Subtask 2: Document Portfolio Business Drivers
#### Description
To validate whether the outcomes have been achieved, link business drivers to a metric that can be measured throughout the migration journey. The company?s strategic goals and annual reports can act as a starting point. Focus the conversation on where the company wants to be, based on existent and projected metrics, as a result of moving to the cloud. Consider goals and business outcomes. Also, consider what success looks like as cloud adoption increases.  Next, establish the importance level of each driver. What are the priorities? What are the expected benefits? How do the benefits support the business goals and outcomes? In the context of application portfolio assessment, this will help to assist workload prioritization for migration and to establish technical guiding principles. However, business drivers will define and impact the migration program as a whole.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Business-Drivers-and-Technical-Guiding-Principles.md)

#### Acceptance Criteria
• Document migrating environment business drivers such as Accelerate innovation, Reduce operational and infrastructure costs, and Increase operational resiliency
## Task 2: Subtask 3: Review Application Infrastructure Attributes  and Data Requirements
#### Description
Capturing application and infrastructure metadata (regardless of the source) is an iterative approach. It can take several weeks to obtain the desired level of detail. The recommendation is to focus on the data that can be obtained now and to keep enriching the data set as more data become available. A full inventory list includes tooling, assessment process, prioritization, migration strategy, and wave planning. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
•  Capture complete application and infrastructure metadata
## Task 2: Subtask 4: Identify Addressable Application/Infrastructure  Scope
#### Description
To perform the preliminary analysis, it is essential to understand which systems are in scope for discovery. Likewise, when discovery tooling is being used, it is essential to understand which systems will be targeted for data collection.
#### Acceptance Criteria
•  Document complete list of systems which will be part of the data  collection
## Task 2: Subtask 5: Establish Default Application Prioritization  Criteria
#### Description
The objective of application prioritization is to select the application attributes (typically 2 to 10) that will be used to establish the order in which the applications will be moved to AWS, and to then assign a corresponding score or weighting to the possible values of those attributes. Next, you define the importance level of each attribute for prioritization. For example, if two attributes are being considered, the first step is to define the score for each possible value for those attributes. The next step will be to establish one of the attributes to have more importance or relevance for the prioritization of applications. The result of prioritization will be a ranking of applications. If the scoring is correct, the top 20 applications will be good candidates to select from for the initial migration and will be aligned to the desired criteria. If the outcome is not agreed upon, adjust the criteria and recreate the list. It takes several iterations to obtain baselined criteria. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Application-Prioritization-Criteria.md)
#### Acceptance Criteria
•  Create a prioritized list of applications to migrate 
## Task 2: Subtask 6: Create Discovery Tooling roll-out plan
#### Description
It is unlikely that the discovery tool will be collecting data from all targeted systems by the end of the discovery party. Likewise, if a discovery tool is not being used, data collection will typically require more time and manual effort.  In general, data collection (and agent install, if required) will follow a progressive approach throughout several days or weeks. Clarify these aspects and plan for the rollout accordingly.  Data collection is a key input for the upcoming portfolio analysis party and it is recommended to obtain at least 1 or 2 weeks of discovery data from all targeted systems before conducting a data analysis. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
•  Create a plan to iteratively collect the data requirements of migrating  applications
## Task 2: Subtask 7: Intall, Configure, and Test Discovery Tooling
#### Description
The AWS Discovery Agent is AWS software that you install on on-premises servers and VMs targeted for discovery and migration. Agents capture system configurations, system performance, running processes, and details of the network connections between systems. Agents support most Linux and Windows operating systems.
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Detailed knowledge of the migrating environment
#### Acceptance Criteria
• Interdependencies of the portfolio  
#### Acceptance Criteria
• Migration plan with appropriate workloads and timelines
## Task 2: Subtask 8: Initiate Discovery Tooling Data Collection
#### Description
Where possible, start data collection during the party targeting the first chunk of systems as defined in the rollout plan. Consider that rolling out discovery tooling requires troubleshooting, especially related to security constraints such as authentication, permissions, and firewall rules. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/Portfolio-Runbooks/AWS-Application-Discovery-Service.md)
#### Tools
AWS Application Discovery Service
## Task 2: Subtask 9: Complete Post Discovery Paty Open Items
#### Description
Review of party outcomes and next steps (for example, ad-hoc sessions to iterate over and finalize elements of the agenda).
#### Acceptance Criteria
•  Review of party outcomes and next steps
## Task 3: Portfolio Data Collection
#### Description
Data collection is the process of gathering metadata from applications and infrastructure. The process is iterative throughout all stages of assessment. Data quantity and fidelity increase as progress is made. At this stage, the focus is on gathering general data that can help to establish an initial inventory leading to the creation of a directional business case and the identification of initial migration candidates. The objective of this group of activities is to complete the data collection rollout (with the discovery tool collecting data from all targeted systems) and monitor its progress, collect manual information from infrastructure assets that cannot be targeted by the discovery tool (for example, legacy systems and secure zones), and to collect application metadata.
#### Tools
AWS Application Discovery Service
#### Tools
Inventory Template
#### Acceptance Criteria
• Data collected and  available on a defined data repository
## Task 3: Subtask 1: Monitor  progress of discovery tooling rollout
#### Description
Ensure that data collection is progressing and that any issues are being actively addressed. Assist the customer with obtaining support from the tooling vendor if required.
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Ensure the continuity of data collection without problems 
## Task 3: Subtask 2: Gather application metadata
#### Description
Work with the relevant teams to identify key application attributes such as application names, mapped infrastructure, environments, criticality, complexity, and others. Use the ongoing output of the discovery tool where possible in order to label auto-discovered applications. Use the Migration Portfolio Assessment (MPA) tool functionality to send customized online questionnaires to ingest application data whenever possible. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Tools
Inventory Template
#### Acceptance Criteria
• Work with the relevant teams to gather application metadata
#### Acceptance Criteria
• Use the MPA tool to gather additional metadata
## Task 3: Subtask 3: Perform manual discovery workshops and activities if applicable
#### Description
In most environments there are cases where the discovery tool of choice doesn?t support a given legacy system. Examples include old operating system versions and legacy platforms such as AS400 or Mainframe.  If these systems are in scope for migration, recommend and perform manual discovery. This might require connecting to those systems directly, or the use of scripts that can be obtained from the discovery tooling vendor or platform teams or by specialized AWS practices. Conduct manual discovery workshops when necessary. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
• Collect data manually for systems that don't support tools
## Task 4: Preliminary Portfolio Analysis
#### Description
The objective of this  group of activities is to perform a preliminary analysis of the collected data.
#### Tools
AWS Migration Evaluator
#### Tools
AWS Migration Evaluator
#### Acceptance Criteria
• Initial application and infrastructure inventory
#### Acceptance Criteria
• Migration evaluator directional business case 
#### Acceptance Criteria
• Prioritized applications identified
## Task 4: Subtask 1: Review Asset  and Dependency from Discovery Tooling Output
#### Description
This session is intended to review all available data and construct an initial inventory of applications and infrastructure and to identify gaps. For more information, see the Portfolio Data Collection Task.
#### Acceptance Criteria
• Review the data collected from the migrating environment data collection 
#### Acceptance Criteria
• Create an initial inventory of applications and infrastructure
## Task 4: Subtask 2: Directional Business Case
#### Description
Some discovery tools include the option to export data in a format that is suitable for the AWS Migration Evaluator. If this is not the case, obtain the latest AWS Migration Evaluator data import template, transfer the data, and create a new Migration Evaluator assessment and upload the data. 

For more information, see [Migration Evaluator](https://aws.amazon.com/migration-evaluator/)
#### Tools
AWS Migration Evaluator
#### Acceptance Criteria
• Create a new Migration Evaluator assessment and upload the data from those discovery tools that don?t support data in a format that suitable for the Migration Evaluator
## Task 4: Subtask 3: Identify Prioritized Applications
#### Description
Analyze the applications at a high-level. The expected outcome is to agree on the contents of the first migration wave and plan for a detailed assessment of those applications. Document the list of applications in the linked artifact. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Prioritized-Applications-(wave-1-or-pilots).md)
#### Acceptance Criteria
• Finalize the plan for the first migration wave
#### Acceptance Criteria
• Document the list of applications to be targeted in Wave 1 
## Task 5: Prioritized Applications Assessment
#### Description
The Prioritized Applications Assessment stage focuses on the detailed discovery of a subset of prioritized applications to produce an initial AWS architecture design and migration strategy. The strategy must take into account the estimated infrastructure run rate in AWS.
#### Tools
AWS Application Discovery Service
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Detailed application discovery
#### Acceptance Criteria
• An AWS application architecture design that includes an AWS run-rate estimate  
#### Acceptance Criteria
• A migration strategy that includes the handling of application dependencies
## Task 5: Subtask 1: Perform  Application Assessment Party
#### Description
The Application Assessment Party is a 1- to 3-day sprint-based, interactive event designed to assist the customer with the following: 
1) Prioritizing a subset of applications targeted for migration
2) Performing a detailed discovery
3) Conducting an AWS design session
4) Creating a draft migration strategy The party facilitates the identification of specific requirements and blockers for detailed application assessment, application design, and migration strategy for the in-scope applications, and resolves them. 

The duration of the party depends on the number of applications to be assessed and their complexity. The base estimate is of one day per application; the recommendations is to work with a maximum of 3 applications per party for a maximum duration of three days. However, this can change based on application complexity and customer needs.

#### Acceptance Criteria
• Prioritized  list of subset applications which are to be migrated to AWS. 
## Task 5: Subtask 2: Confirm Prioritized Applications
#### Description
The goal of this session is to establish which key attributes will determine the selection of applications for the party. In some cases, the applications that are being targeted will be known in advance. In other cases, it will be required to choose the most appropriate applications. The objective is to assist the customer in identifying key application attributes to determine priority. This includes assigning a corresponding weighting to the possible values of those attributes.  Next, define the attribute importance level for prioritization.The result will be a ranking of applications. If the weighting and criticality are correct, the top five will be good initial candidates for assessment. If the top applications don?t make sense, adjust the criteria as needed.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
•  Create a list of prioritized applications to be migrated to AWS
## Task 5: Subtask 3: Perform Prioritized Applications Deep Dive
#### Description
Use the suggested artifacts to conduct a detailed assessment. Ensure that the session includes the stakeholders that are needed to dive deep into the business, architecture, and technology aspects. The use of discovery tools for dependency analysis is highly recommended.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Prioritized-Applications-(wave-1-or-pilots).md)
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
•  Conduct a detailed assessment for the prioritized applications to be migrated to AWS
## Task 5: Subtask 4: Create first Draft for Prioritized Applications  Architecture Design
#### Description
After the data is collected for the prioritized applications that are to be migrated to AWS, create a first draft of a prioritized applications architecture design. Document, at a high-level, the functional and non-functional requirements for this architecture. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/2-Prioritized-Applications-Assessment/Template---Application-AWS-Architecture-Design-and-Migration-Strategy.md)

#### Acceptance Criteria
• Document the first cut of the migration architecture design with functional and non-functional requirements
## Task 5: Subtask 5: Create first Draft for Prioritized Applications  Migration Strategy
#### Description
The next step is to document the migration strategy for the prioritized applications.  Review the 7R terms and finalize the migration strategy based on the migration patterns.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/2-Prioritized-Applications-Assessment/Template---Application-AWS-Architecture-Design-and-Migration-Strategy.md)

#### Acceptance Criteria
• Document the first cut of the migration architecture strategy such as Rehost, Rearchitect, etc.
## Task 5: Subtask 6: Complete Post ApplicationAssessment Party Open  Items
#### Description
Review the application assessment party outcomes and the next steps to perform.

#### Acceptance Criteria
•  Finalize the next steps to perform
## Task 6: Portfolio Analysis and Migration Planning
#### Description
The Portfolio Analysis and Migration Planning task focuses on iterating the work initiated in the previous stages in enriching the portfolio data and baseline a migration wave plan.
#### Acceptance Criteria
• Infrastructure and application inventory
#### Acceptance Criteria
• A tested 7R disposition tree 
#### Acceptance Criteria
• Prioritization criteria 
#### Acceptance Criteria
• Validated wave 1 
#### Acceptance Criteria
• Migration wave plan (draft) 
#### Acceptance Criteria
• MPA export
## Task 6: Subtask 1: Plan Portfolio  Analysis Party
#### Description
The primary outcome of the analysis party is to extract meaning out of available data and initiate the full assessment of the portfolio of applications.  Typically, the analysis party follows 1-Portfolio Discovery and Initial Planning, although it can also be performed independently whenever data is already available from other sources. This can be the case when a discovery tool has been deployed or when previous discovery-related engagements have taken place.  

The main prerequisite is the availability of one full week of programmatic data collection as a minimum (or equivalent data) from all in-scope systems, including asset communication data, in order to evaluate application dependencies.
#### Acceptance Criteria
• Initiated  full assessment of the portfolio of applications
## Task 6: Subtask 2: Review Asset and Dependency Discovery Tooling Output
#### Description
A quick review of the available data. Typically, the output of the discovery tooling or equivalent data. The goal is to learn how to access the data and how it is presented. This is a high-level review to train attendees on data usage and format.
#### Acceptance Criteria
•  Completed review of the output from the discovery tools
## Task 6: Subtask 3: Iterate Applications metadata
#### Description
The following data points describe the information required to obtain a complete portfolio view of the applications in the migration and their associated infrastructure: 
 
1) Application attributes along with inventory, prioritization, and recommended fidelity levels 
2) Infrastructure attributes along with inventory, prioritization, and recommended fidelity levels 
3) Network attributes along with inventory, prioritization, and recommended fidelity levels 
4) Migration attributes along with inventory, prioritization, and recommended fidelity levels To collect the data in the previous list, use the discovery tools and iterate multiples. 
#### Acceptance Criteria
•  Collected a detailed list of applications metadata iteratively until the entire  portfolio data are completed. 
## Task 6: Subtask 4: Iterate 7R Disposition Tree
#### Description
The 7R disposition tree is used as a guide for application owners and architects, among others, to evaluate which path to take when migrating an application. Each project has unique circumstances and decision-making processes that need to be incorporated into the tree logic. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/3-Portfolio-Analysis-and-Migration-Planning/Artifact---7R-Disposition-Tree.md)
#### Acceptance Criteria
•  Documented the knowledge on 7R and justification for selecting any R strategy.
## Task 6: Subtask 5: Iterate Application Prioritization Criteria
#### Description
The goal of this session is to establish which key attributes will determine the order in which applications are to be migrated. This is a key input for constructing migration wave plans.If tooling in use lacks the capability/features to perform prioritization, use the Migration Portfolio Assessment. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Application-Prioritization-Criteria.md)
#### Acceptance Criteria
•  Prioritized a list of applications that are to be migrated to AWS. The list is  refreshed iteratively to reach a baselined version. 
## Task 6: Subtask 6: Draft Wave Plan
#### Description
The objective is to use the prioritization criteria and start shaping a wave plan. Wave planning can take several weeks. The intention is to outline a first draft and focus on validating the first few waves, especially Wave 1.  How much can be achieved during this task, will depend on the data available, the participants, and the size of the scope. If the discovery tool of choice doesn?t include wave planning features, you can use the MPA tool (available to AWS employees and partners) to construct the plan.  Ensure that all assets and communications data have been exported from the discovery tool (or equivalent) and imported it into MPA. This information is essential for the wave planning process. 

For more information, see [here](https://mpa.accelerate.amazonaws.com/.)
#### Acceptance Criteria
•  Created a first wave plan that includes the list of applications and prioritization criteria. 
## Task 6: Subtask 7: Complete Post Analysis Party Open Items
#### Description
Review  of party outcomes and next steps.
#### Acceptance Criteria
•  Finalized next steps to perform
## Task 6: Subtask 8: Baseline Application Prioritization Criteria
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure.  

Prioritization criteria must be baselined by the end of the Wave 1. This will form the base for the rest of the waves. Update the criteria before each wave.

#### Acceptance Criteria
•  Created a base application prioritization criterion and iterated it for the  future waves.
## Task 6: Subtask 9: Baseline 7R Disposition Tree
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure.  

When you establish a baseline for the portfolio, confirm a migration strategy for each application component. The migration strategy will be one of the 7 Rs for migration. A 7 R strategy must also be associated with each of the application's infrastructure components.
#### Acceptance Criteria
•  Confirmed that each application and its components are assigned on the 7Rs for  migration strategy.
## Task 6: Subtask 10: Baseline Portfolio Asset & Dependency  Discovery
#### Description
To  create high-confidence migration wave plans, you must establish a baseline  for the portfolio of applications and its associated infrastructure.   To establish a baseline version of the portfolio, including dependencies  and migration strategies.

#### Acceptance Criteria
•  Created a base application inventory and iterated it for the future waves.
## Task 6: Subtask 11: Baseline Application metadata
#### Description
To  create high-confidence migration wave plans, you must establish a baseline  for the portfolio of applications and its associated infrastructure.   Complement the data with information gathered from key stakeholders such as  application owners and infrastructure teams. Keep gathering data until you  obtain a complete portfolio inventory that matches the attributes and level  of fidelity for this stage. The resulting dataset will be essential in  driving the migration.
#### Acceptance Criteria
•  Created a base application metadata criteria and iterated it for the future  waves.
## Task 6: Subtask 12: Baseline Dependency Groups and Wave Plan
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure.  Technical dependencies can be described in four categories: 1) Application-to-infrastructure  2) Application-component 3) Application-to-application 4) Application-to-infrastructure services 

For more information, see [Baseline Application Portfolio](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/baseline-application-portfolio.html.)

#### Acceptance Criteria
•  Created base dependency groups and iterated them for the future waves.