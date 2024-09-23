
# Module: Planning and Governance Workstream
## Task 1: Migration Project Governance
#### Description
The activities to formalize the migration plan and project governance are as below :-
* Migration Wave Planning
* Migration Team Resource Allocation
* Migration Communication Plan and Tracking
* Migration RACI definition or update

#### Acceptance Criteria
1. Definition of migration project governance - RACI and Communication Plan.
2. Resource Allocation.
3. Definition of migration wave group plan.
## Task 1: Subtask 1: Migration Wave Planning & Work Breakdown Structure (WBS) Creation
#### Description
1. Perform sprint planning for scheduled waves . 

2. Refer to the [large migration play book](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-migration-playbook/task-one-sprint-planning.html) and [wave planning](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/wave-planning.html) for best practices on sprint planning.

3. Create a Work Breakdown Structure (WBS) using suitable tools or in standardize template. This should include :-
 * Phases
 * Tasks
 * Sub-tasks, 
 * Task Dependencies 
 * Resource allocation, 
 * Task Expected Start and End Dates
 * Task Expected Effort
 * Task Actual  Start and End Dates
 * Task Actual Effort

4. Ensure the critical path areas identified in the cloud readiness assessment are also addressed as part of the wave plan.
#### Tools
Migration Hub - Journeys
#### Acceptance Criteria
1. Successful scheduling of migration wave group.
2. Successful documentation of migration wave group.
## Task 1: Subtask 2: Migration Team Resource Allocation
#### Description
1. Analyse the list of project resources required for the tasks in the current sprint plan and Work Breakdown Structure (WBS).

2. Identify and allocate project team member resources to the tasks based on the skill and proficiency level as tracked in the resource/employee training tracker. Refer to [large migration foundation playbook](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-foundation-playbook/team-org.html) for resource allocation best practices.

3. Periodically review and update the Work Breakdown Structure (WBS) with changes in tasks, and resource allocations, along with start and end date information.
#### Acceptance Criteria
1. Successful migration team definition and resource allocation.
## Task 1: Subtask 3: Migration Communication Plan and Tracking
#### Description
1. Summarize the progress of the migration phases and tasks as tracked in the sprint planning and Work Breakdown Structure (WBS) documents.

2. Schedule and track ongoing migration communication through defined communication plan mechanism. Refer to the [large migration play book](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-governance-playbook/stage2.html) as best practice reference to execute migration communication.

3. Maintain & review the Risks, Actions, Issues and Dependencies (RAID) log for any risks and issues identified and include these in your project status reporting based on the decided reporting mechanism and frequency. Ensure transparency in communication to all relevant stakeholders.
#### Acceptance Criteria
1. Successful definition of the migration communication plan.
2. Successful establishment of RAID log.
## Task 1: Subtask 4: Define Detailed RACI (Responsible, Accountable, Consulted, Informed) Matrix
#### Description
1. Review and extend the high-level RACI matrix defined in the Assess Phase into a detail RACI definition based on the mobilize and migration activity requirements. 

2. Refer to the [large migration foundation playbook](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-foundation-playbook/team-org.html#raci) for best practices in defining the RACI leveraging the required steps and starter template.

2. Share the updated RACI matrix with all stakeholders on an ongoing basis in the status report.
#### Acceptance Criteria
1. Successful creation or update of detailed migration RACI.
## Task 2: Migration Financial Governance
#### Description
Creating migration financial governance by configuring the below areas :-
* Financial Reporting
* Billing Alerts
#### Acceptance Criteria
1. Successful configuration of financial reporting.
2. Successful configuration of billing alerts.
## Task 2: Subtask 1: Financial Reporting Process Creation
#### Description
1. Create a financial reporting process. For best practice guidance refer to the prescriptive guidance [financial reporting steps](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-governance-playbook/task-project-management.html#step-financial-reporting).

2. Project manager should be aware of AWS Billing and Cost Management concepts and best practices . For best practice reference refer to [AWS cost management documentation](https://docs.aws.amazon.com/cost-management/latest/userguide/what-is-costmanagement.html)
#### Acceptance Criteria
1. Successful configuration of financial reporting.
## Task 2: Subtask 2: Enable Billing Alerts
#### Description
1. Create and enable AWS Billing alerts to obtain early billing alarms and ensure the AWS migrations are being executed within expected spend/budget. For best practices, refer to [AWS cost monitoring](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html).

2. Leverage the [create a billing alarm user guide](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html).

3. Ensure the delivery team is part of the team that will be alerted when there is a pricing spike.  
#### Acceptance Criteria
1. Successful enabling of AWS Billing alerts to ensure migration are executed within the expected spend/budget.
## Task 3: MAP Tagging
#### Description
1. Define MAP Tagging deployment strategy as part of Operating Model Tagging Management outlining :-
* Tagging rollout timeline
* Tagging deployment approach - automated (Infrastructure as Code (IaC) or tooling) or manual (tag editor or console)
* Tagging responsibility

2. Ensure MAP Tagging deployment strategy is documented as part of the cloud operating model tagging strategy under the operating model runbook.

3. Ensure MAP Tagging process and tag information are documented in the cloud operating model runbook. Leverage [MAP Tagging Documentation](https://s3.us-west-2.amazonaws.com/map-2.0-customer-documentation/html/AWSMapDocs/what-is-service.html) as reference.

4. It is recommended to undertake the [MAP Tagging Guidelines](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/20323/aws-partnercast-map-tagging-guidelines-technical) training on AWS Skillbuilder prior to implementing the tags to obtain understanding on the tagging methodology, tagging execution requirements, best practices and common mistakes to avoid during the tagging process. This will accelerate and ensure accuracy during the MAP tagging deployment.
#### Tools
MAP Tagging Documentation
#### Acceptance Criteria
1. Successful inclusion of MAP tagging as part of the AWS tagging strategy.
#### Acceptance Criteria
2. Ensure MAP Tagging will be executed during the pilot  Migration in the Migration and Modernization Experience Workstream and 
    Application Wave Group Migration in the Migrate and Modernize Phase.