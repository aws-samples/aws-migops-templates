
# Module: Operations-Support
## Task 1: User Access and Security Implementation
#### Description
The purpose of this task is to verify and update user authorizations, roles, and user classifications to ensure compliant use.

Prerequisite:

All SAP users are setup in all productive systems with the related roles and authorizations.
Delete users or change validity dates for users no longer in scope.
Apps Used:

System Measurement Program (Transaction USMM)
System Measurement Details in SAP for Me
SAP for Me – Private Cloud Consumption
Procedure:

1. For SAP S/4 HANA Cloud Core productive systems

Select correct pricelist in the system measurement program (transaction USMM) to activate the correct user types for classification.
Example:
06 - SAP S/4HANA Private Cloud Edition or
07 - SAP ERP Private Cloud Edition

2. Implement 3113382 - Authorization-based SAP S/4HANA User Simulation / FUE Projection in your core systems.
3. Run the report SLIM_USER_CLF_HELP with the most recent PCE / RISE ruleset attached to the note. The ruleset determines based on authorization objects of the core, the resulting use types for SAP Private Cloud editions.
4. Understand which roles and authorizations drive the resulting classification.
5. Please note: If there are users in your SAP S/4HANA Cloud core systems that only use engines and no further core functionality, please classify them manually as SAP S/4HANA Cloud Technical Engine Use.
6. Review results and adjust role and authorization concept where required.

For Engine-Only / Extra Stack productive systems (if applicable)

Assign all engine users manually to the following use type:
SAP S/4HANA Cloud Technical Engine Use.

## Task 2: Operations Implementation
#### Description

The purpose of this deliverable is to ensure changes to the support operations are implemented following the operations roadmap defined in the explore phase.
## Task 2: Subtask 1: Implement Operations Support Process and Tools
#### Description
The purpose of this task is to ensure changes to the support operations are implemented following the operations roadmap defined in the explore phase. See the Evaluate Impact on Operations task.

Procedure

Collect detailed operations requirements. The changes to the support framework are implemented and the activity is often managed through detailed IT change requests.
Implement changes to Roles and Responsibilities. Refer to the SAP S/4HANA Cloud Private Edition - Roles and Responsibilities Summary accelerator.
Document and test support processes and procedures. This includes incident management, problem management, access management, change management, and test management.
Setup and adjust operations supporting tools.
Create and document an operation handbook. Store the documentation in a central repository.
Setup Knowledge Transfer. The support resources prepare to run the new solution. Knowledge transfer is done through a combination of activities, including formal training, self-study, shadowing, and on-the-job training.
.
## Task 2: Subtask 2: Plan Transition and Handover
#### Description
The purpose of the task is to review the overall program transition and handover planning in order to identify gaps for your future Customer COE organization. This is the baseline to ensure a smooth handover procedure from project organization to the post-Go-Live support organization.

The Customer COE organization must ensure that core competencies are being developed and that the right procedures, boards, bodies and roles are in place for post go-live operations phase. Access Customer COE and CIO Guides and Media Library from the Customer Center Of Expertise portal for detailed information.

Procedure:

1. Identify skill and knowhow gaps of your future Customer COE staff.
2. Define a clear Knowledge Transfer Strategy.
3. Consider onboarding of 3rd party providers as well as in some cases Customer COE processes might be outsourced
## Task 3: Operational Readiness
#### Description
The purpose of this task is to ensure the operations and support organization is prepared to run the new SAP S/4HANA solution. The activity provides a defined support approach for monitoring and measuring day-to-day support operations.

Procedure

1. Check if all operational aspects have been implemented as planned. Refer to the Implement Operations Support task in the Realize phase. The following topics need to be covered:
* Roles and Responsibilities
* Support Processes and Procedures
* Operations Support Tools and documentation
* Knowledge Transfer
2. Review the SAP S/4HANA Cloud Private Edition - Roles and Responsibilities Summary accelerator for more information on SAP roles and responsibilities.
3. Establish key users according to the prior defined key user model.
4. Finalize hiring and the onboarding process of internal Customer COE staff.
#### Tools
SAP S4 HANA - Roles and Responsibilities
## Task 4: Production Cutover
#### Description
The purpose of this deliverable is to execute the cutover plan and ready the business and system for productive use. The cutover plan contains both business process tasks as well as system tasks. It is executed in the days prior to the go-live date.

Examples of potential tasks in the cutover list are as follows. Based on the solution, not all may be applicable.

* Setting up and initializing the production system
* Setting up and verifying interface connections
* Migration or creation of master data
* Migration of order objects (i.e. purchase orders, sales orders, etc)
* User creation/access
* Go/no go decision points
* Closing the legacy systems
* Notification of impacted 3rd parties
* Completing all required documentation for regulatory purposes
## Task 4: Subtask 1: Execute Cutover Tasks per the Cutover Plan
#### Description
The purpose of this task is to cutover to the productive system, obtain the customer approval (sign-off), validate that the go-live acceptance criteria have been met, and confirm the successful go-live.

Procedure:

1. Execute the cutover to Production following the task defined in the cutover plan.
2. Document the actual duration of each step to support future projects.
3. Capture any variances to the plan along with the decision maker who approved the change.
4. The cutover manager(s) should proactively notify task owners of upcoming tasks, to ensure their availability.
5. Regularly communicate status to stakeholders.
6. Test and validate the systems after the cutover has finished.
7. Obtain the production approval sign-off, which documents the agreement with the stakeholders that cutover tasks have been successfully executed.
## Task 5: Production Hypercare Support
#### Description
The purpose of this deliverable is to provide sufficient and timely support of the transition to production process to ensure stabilization of the solution and related business processes. During the production hypercare support period the operational processes will be embedded into the organization.
## Task 5: Subtask 1: Provide Hypercare Support
#### Description
The purpose of this task is to provide a pre-defined period of hypercare to stabilize the solution, business processes ,and to ensure timely and adequate response in case of urgent go-live issues. The dedicated support from the project team for a limited timeframe ensures the adoption of the new solution and help address processes and configuration topics efficiently.

Procedure:

Review the [SAP S/4HANA Cloud Private Edition - Roles and Responsibilities Summary](https://www.sap.com/about/agreements/policies/hec-services.html?search=roles%20&sort=latest_desc&tag=language%3Aenglish) accelerator, to understand the roles and responsibilities.
Establish a process for addressing adoption issues that end-users identify during the first days and weeks of using the system – leverage existing customer tools for IT ticketing.
Ensure business users know who to contact with questions – customer key business users should be available to help address adoption issues.
Define Business user issue-reporting and escalation processes.
Define and follow the process for raising SAP support tickets for software issues. Monitor the raised tickets and follow-up with SAP Support.
## Task 6: Handover to Support Organization
#### Description
Once the hyper care phase ends it is important to fully enable the regular support organization at customer site to safely and securely operate the new SAP S/4HANA system. This includes (but is not limited to):

The finalization of system documentation
The finalization of operational procedures as part of the operations handbook
The check of the customer support organization

Procedure
1. Resolve and Close Open Issues
2. Handover Operations Responsibility
## Task 6: Subtask 1: Resolve and Close Open Issues
#### Description
The purpose of this task is to achieve a closure of all open project issues which is a prerequisite for the final project closure.

Procedure:

The purpose of this task is to achieve a closure of all open project issues.
In case this is not possible within acceptable time, prepare for an agreement with the IT operations team to take responsibility to resolve and close the issue. Hand over the current analysis and correction state to the IT operations team.
## Task 6: Subtask 2: Handover Operations Responsibility
#### Description
In this task, operations responsibility is formally handed over from the team who operated the new SAP S/4HANA system (usually a mix of resources from the project team and IT support) to the IT support operations team.

Prerequisites

System documentation is complete and available.
Operations procedures are fully documented in the operations handbook.
The IT support operations team is set up and trained to safely and securely operate and troubleshoot the new SAP S/4HANA system.
The top issues and priority incidents identified during hyper care, are either solved, or there is a documented work around and move-forward plan available.
Procedure

Hand over operations responsibility to the IT support operations team.