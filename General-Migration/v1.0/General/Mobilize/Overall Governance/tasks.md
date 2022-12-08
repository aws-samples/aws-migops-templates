
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
Review Customer�s current state project  management methods and capabilities.

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