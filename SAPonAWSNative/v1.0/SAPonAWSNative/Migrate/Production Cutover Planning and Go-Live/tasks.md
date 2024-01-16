
# Module: Production Cutover Planning and Go-Live
## Task 1: Define a cutover plan and application owners
#### Description
Define a cutover plan which covers all the activities that must be completed for each SAP migration Wave. The cutover plan will be a comprehensive and detailed guide of all activities to be performed.  For each task, the cutover plan should detail the sequence of activities, expected duration, planned timing, ownership, and Success criteria.
Core tasks should include at least the following:

* Uptime preparation activities
	* User locking/Unlocking | Pausing/Resume Batch / Interface Jobs 
* Downtime activities
	* Export/Import
	* Golden Backup
	* Data Migration
* Post-migration activities
	* Technical validation post-migration activities
	* Rollout/cutover planned 
* Other activities
	* Define communication cadence for both technical and business audiences
	* IT Change Management approval activities (to be coordinated with IT teams, Infra, Servicedesk, etc)
		* Success criteria for each task
		* Ownership for each task

#### Acceptance Criteria
• Defined cutover plan for SAP migration to AWS
• Verified migration step-by-step run book (as executed in Dryrun)
• Communication plan for cutover
• Approved IT change management process
## Task 2: Plan to conduct SAP and AWS readiness checks prior to go-live
#### Description
In preparation for the SAP Production migration go-live(s), it is important to ensure the readiness of both the SAP systems and AWS resources. This activity validates the design and build of your SAP implementation / migration project and provides a final safeguard to uncover any potential roadblocks during go-live.

There are a range of checks that can be performed to help ensure the system readiness, but at a minimum, 
1) A Well Architected Review with SAP Lens should be conducted with your AWS account team
2) Plan to have SAP MaxAttention checks like Landscape Verification Check / Going Live Check with SAP.
3) A detailed SAP on AWS technical go-live checklist should be developed by the project team, including key findings/actions that arose from the Well-architected Review & SAP GoingLive Checks

Note: SAP offers premium engagement support with their ActiveAttention and MaxAttention support plans, which includes the SAP GoingLive Check, SAP MaxAttention Landscape Verification check.

Additional checks can be performed depending on your support levels. AWS also offers a Go-live Check as a service through AWS ProServe, and SAP TAM for Enterprise Support customer.  Please consult with your account team for more information.
#### Tools
SAP GoingLive Check
#### Tools
SAP ActiveAttention
#### Tools
AWS Well Architected Framework / SAP Lens
#### Tools
 AWS Professional Services
#### Tools
SAP MaxAttention
#### Tools
AWS Enterprise Support
#### Acceptance Criteria
• Completed readiness checks and finalize go-live checklist
## Task 2: Subtask 1: Conduct Well Architected Review with SAP Lens
#### Description
Engage your AWS account team's SAP specialists to coordinate a Well Architected Review with SAP Lens, which is a collection of customer-proven design principles and best practices for ensuring SAP workloads on AWS are well-architected. It highlights some of the most common areas for improvement, aligned to the six pillars of the AWS Well-Architected Framework — operational excellence, security, reliability, performance efficiency, cost optimization, and sustainability.

Reviews are recommended to be done at key milestones in the product lifecycle, including prior to go-live, in order to identify any critical issues that might need addressing before go-live, or areas that could be improved before or immediately after go-live. The outcome of the review is a set of actions that should improve the customer's SAP migration and ongoing operational processes. 
#### Tools
SAP Lens - AWS Well-Architected Framework
#### Acceptance Criteria
• Complete Well-Architected Review w/ SAP Lens for one or more of the pillars
## Task 2: Subtask 2: SAP on AWS technical go-live checklist
#### Description
A detailed SAP on AWS technical go-live checklist should be developed by the project team in order to ensure a smoothly orchestrated go-live cutover process. See attached template for guidance on the areas that should be reviewed in the checklist.
#### Tools
SAP on AWS technical go-live checklist
#### Acceptance Criteria
• Complete SAP on AWS technical go-live checklist
## Task 3: Provision Production Infrastructure
#### Description
Ensure the infrastructure for all SAP application servers and databases are provisioned and configured using the chosen automation tools (used during the non-prod phase/or dryruns). 

#### Tools
AWS Launch Wizard for SAP
#### Tools
AWS Migration Hub Orchestrator
#### Acceptance Criteria
• Preparation for the production environment is complete. The provisioned infrastructure will need to be validated to ensure it is setup similar to the customer source environment.
## Task 3: Subtask 1: Validate Base Infrastructure is setup for Production migration
#### Description
Ensure the infrastructure for all Production SAP application servers and databases are provisioned and configured using the chosen automation tools (identified during Mobilize phase). This could be Launch Wizard/cloud formation, terraform, ansible, CHEF, puppet, AWS Systems Manager, Jenkins.
#### Acceptance Criteria
• All the provisioned infrastructure will need to be validated to ensure it is setup similar to the customer source environment 
## Task 3: Subtask 2: Ensure supporting AWS services provisioned
#### Description
Other supporting AWS services provisioned and/or configured: networking, security
## Task 3: Subtask 3: Prepare SAP support processes
#### Description
Prepare SAP support processes for Production;  Firefighter elevated access, Ensure SAP Go-Live Support process is initiated, etc
## Task 4: Execute Production Cutover
#### Description
After all the pre-cutover to production formalities are completed, execute the production cutover. This task must involve the following:
1. Work with customer and partners to track and address any migration issues promptly and capture potential optimizations for PGL support team.
2. Communication to stakeholders regarding the cutover timelines and application downtime (if needed)
3. Perform the core production cutover, including data migration activities
4. Switch the application and database endpoints to the new environment in AWS
5. Smoke testing to ensure that the cutover was executed successful
6. Update Readiness checklist scorecard and hold Go/No-go
7. Communication to stakeholders regarding the completion of the cutover
#### Acceptance Criteria
• Successful cutover completion
## Task 4: Subtask 1: Conduct a go/no-go meeting
#### Description
Conduct a go/no-go meeting ensuring readiness across people, process and Technology. Typically this is conducted in a meeting setting with all the stakeholders on a call and getting verbal confirmation for each of the respective leaders. Results from testing and known issues and accepted risk will be presented by the Project team to all stakeholders
## Task 4: Subtask 2: Prepare for Production migration
#### Description
Run test scenarios on source/on-prem SAP systems (pre-migration) for the systems/business process identified for the migration wave & document verification test results.


#### Acceptance Criteria
• Pre-migration test results captured and stored in common repository
## Task 4: Subtask 3: Execute core cutover tasks during system downtime
#### Description
Initiate system downtime on on-prem environment and execute the core cutover tasks including the data migration
#### Acceptance Criteria
• Core migration completed, SAP system ready for post-downtime activities
## Task 4: Subtask 4: Execute post-downtime cutover tasks
#### Description
Bring SAP system up on AWS to execute the remaining cutover tasks, post data migration
#### Acceptance Criteria
• SAP on AWS system migration tasks completed, ready for post-verification
## Task 4: Subtask 5: Perform post-migration verification
#### Description
Run test scenarios on post-migration AWS environments for the systems/business process identified for the migration wave & document verification test results.
#### Acceptance Criteria
• Post-migration test results captured and stored in common repository
## Task 4: Subtask 6: Compare verification results
#### Description
Compare and confirm source/pre-migration and target/post-migration test results, and document/mitigate/resolve all discrepancies
#### Acceptance Criteria
• Fully tested and verified SAP systems on AWS
## Task 5: Establish Hypercare support & close project
#### Description
Immediately after the cutover is completed, provide a support plan to ensure a successful SAP migration to AWS. This task must involve the following:

* Plans for post-launch support for operations, monitoring, capability planning, etc.
* Work with customer and partners to establish Hypercare support team & processes
* Make final adjustments, and close your project.
#### Acceptance Criteria
• Hypercare support process (meeting cadence, issue tracking, escalation process, etc)
## Task 5: Subtask 1: Setup initial operational activities
#### Description
Setting up your new environment's operational activities, such as resuming monitoring and backup schedules
## Task 5: Subtask 2: Close project
#### Description
Gaining stakeholder approvals on project closure documentation and close project
#### Acceptance Criteria
• Approved project closure documentation