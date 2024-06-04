
# Module: Testing Strategy
## Task 1: Test Planning
#### Description
The purpose of this deliverable is to plan, design, and prepare for testing the configured or built system. Key deliverables during this phase include an agreed test strategy and test plan/test schedule. It is important to note the relevant prerequisites that should be in place before end to end takes places.

It is necessary to consider and plan for the testing cycles required during testing activities and understand what needs to be completed for testing. During this deliverable, existing tests, quality management processes, and procedures which may occur can be leveraged to support the project.

It is recommended that customers appoint a Test Manager to the project at the earliest opportunity. The Test Manager is then able to work with the module process leads as well as technical leads to build up knowledge of business processes before executing the User Acceptance Testing.
## Task 1: Subtask 1: Create Test Strategy
#### Description
The purpose of this task is to agree on the key elements of the test strategy and document them in the test strategy document. Typically, there is one signed and approved test strategy which will cover the entire project duration and is often owned jointly by the customer and the implementation partner. This step is very important as it defines how testing will be performed and completed in the project. All project members and stakeholders must agree and align to the agreed approach before testing starts.

Procedure:

1. Review the Test Strategy Template S4HANA Cloud in the attachments section and define which details the project specific test strategy document should contain.
2. Create the project specific test strategy document.
3. Sign off on the agreed test strategy by all project members and stakeholders.
## Task 1: Subtask 2: Determine Test Scope
#### Description
The purpose of this task is to define the scope of testing for a project, regardless if the project is executed independently or as part of a release; it needs to be determined to ensure the testing environments and testing artifacts are available for execution. With such a variety of testing cycles (e.g., Integration, Regression, Business Process, Performance, User Acceptance, etc.) available, it is essential to define the cycles that are required, such as supporting the planned conversion event, security roles and profile testing, testing the Hybrid two-tier Deployment Scenarios', Extensibility objects associated with a business process, and interface objects which are not related to business processes.

Procedure:

1. Evaluate the existing process and procedures to determine the testing cycles required to support the project.
2. Use existing processes and procedures to guide decision-making in selecting test cases and scripts. Reference the SAP Signavio Process Navigator for an example of a test script and process flow in the "**[SAP Best Practices - Process Flow and Test Script (Example J58)](https://me.sap.com/processnavigator/SolS/EARL_SolS-055/2023/SolP/J58?region=US)**" accelerator.
3. To effectively compile test cases and scripts, prioritize critical business apps/reports, evaluate frequently used apps/reports, and analyze past production support issues.
4. Determine the overall test data approach by aligning it with the data migration approach. The test data approach will be documented as part of the testing strategy.
5. Document the scope in the test strategy document, and execute the test scope in SAP Cloud ALM or other selected test management tools.
As a result, a test strategy and a defined set of test cycles, test cases, and test scripts in scope to support the conversion project are created.
## Task 1: Subtask 3: Create and Schedule an Overall Test Plan
#### Description
The purpose of this task is to create a test plan and optionally a detailed test schedule. The focus is to determine which of the required testing phases (e.g. Functional, Scenario, Integration, Regression, User Acceptance, Performance, etc.) are required to fulfill the quality gate criteria of the Realize phase. Furthermore, the start date, duration, criteria, and resources for each of the required testing phases needs to be planned.

Procedure:

Detailed test planning which covers tasks, dependencies, and durations that is integrated with the project plan should support the objective of mitigating risk both to the end-state solution and the cutover process required to position the end-state.

1. Define the test scope, containing:
Test cases
Test scenario definition
Dependencies
Prerequisites
2. Test scope agreement by the project team (customer and implementor), involved business process experts, and stakeholders.
3. Optional: Plan resources and timelines. Please refer to the Detailed Test Schedule Template accelerator below. It can be used for tracking and monitoring purposes during the testing phase. A detailed schedule can either be created for the entire project, or for each individual test phase. This can be achieved in SAP Cloud ALM, or other selected test management tool by creating multiple test plans, with dates, dedicated test cases and assigned testers. In addition, the test tracking is achieved by the tracking of the progress by test plan. It contains:
Key prerequisite testing activities
Scope items (test cases) and unique test case IDs
Dependencies and milestones
Test execution start dates and duration
Resource allocation
Timeline showing the testing tasks and when they will occur
Test status tracking (if required)
4. Evaluate and enable test management and test automation tools to support the testing phases. Execute the tasks within this activity utilizing the SAP Application Lifecycle Management Best Practices for Test Management. Tailor the templates for Test Strategy, and the high-level Functional Test Plan to your needs.
5. A detailed testing plan that is integrated with the project plan and aligned with the overall SAP Software Change Management strategy. The plan should support the objective of mitigating risk both to the end-state solution and the cutover process required to position the end-state by providing information to PMO and leadership in determining whether to deploy a solution into production.
#### Tools
Test Management Guide