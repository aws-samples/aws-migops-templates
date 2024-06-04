
# Module: Testing
## Task 1: Test Preparation
#### Description
Prepare the environment and the test team to perform the testing. Sample activities include: ensuring the availability of the testers and performing knowledge transfers to get everyone up to speed. In addition, the testing tool(s) are set up and a kickoff meeting occurs. All users are set up in the testing tools at this point with the respective business roles assigned to perform testing activities. Creation/adaptation of test automation scripts. Setup of master data for testing.

#### Acceptance Criteria
You have applications created in Migration Hub
## Task 1: Subtask 1: Prepare Testing Prerequisites
#### Description
The purpose of this task is to prepare the prerequisites for testing. This is to ensure the availability of testers, Test Management Systems like SAP Cloud ALM (if used), or to ensure the availability and accessibility of the Testing Automation Tool(s) (if used).

In order to ensure the availability of testers and provide key knowledge transfer, a kick-off meeting is advisable during this project phase. The Test Phase Kick Off Template accelerator can be used to prepare and execute the kick-off Meeting. If test automation is in scope, then the technical resources should also be planned if any.

If using SAP Cloud ALM as a Test Management System, then the test preparation should take place in the tool directly. You can use the project scope to easily identify the business processes which require testing. You can also view all the requirements created during the fit-to-standard workshops and created dedicated test cases for these requirements.
Prerequisites:

Define test scenarios and test data
Apps Used:

SAP Cloud ALM (if used) Test Preparation, Requirements, and Processes
Selected Test Automation Tool(s) (if used)
Procedure:

Confirm the availability of testers and perform knowledge transfers.
Confirm test tool setup.
Leverage the [Test Phase Kick-Off](https://support.sap.com/content/dam/SAAP/SAP_Activate/S4H_497%20Test%20Phase%20Kick%20Off%20Template.pptx) Template accelerator for the kick-off meeting preparation and execution.
If using SAP Cloud ALM, prepare test cases based on process flow, application activities, and requirements.
#### Tools
Test phase kick off template
## Task 1: Subtask 2: Set Up Selected Third Party Automated Testing Tools
#### Description
The purpose of this task is to enable the selected test automation tools from the Test Strategy. This depends on the tools which were selected, and dedicated accelerators should be provided by the different vendors.

Procedure:

1. Select the third-party test automation tool(s) from the Test Strategy.
2. Enable users and review the documentation on the selected test automation tool(s).

## Task 1: Subtask 3: Create Test Plan
#### Description
The purpose of this task is to develop a comprehensive test plan, which involves organizing a sequence of standard or customized test cases/test scripts in a specific manner to outline the entire business process.

Test plans are sets of test cases executed together to represent end-to-end business processes in specific test cycles, helping you run your testing activities in iterations. Test plans consist of groups of test cases executed together to define end-to-end business processes within specific test cycles.

This approach facilitates iterative testing activities, encompassing various test cases such as Automated Test Cases, Manual Test Cases, and Test Cases executed on integrated systems during integration scenarios. The test plan holds immense significance as an artifact during the testing process as it enables monitoring the successful execution of tests.

Procedure:

1. Review the end-to-end business processes and define the scope of the Test Plan.
2. If you use SAP Cloud ALM as your Test Management Tool:
* Create the Test Cases in the SAP Cloud ALM > Test Preparation App either manually or by integrating automation providers with SAP Cloud ALM.
* Create test plans to categorize test cases in the Test Plan Overview section of SAP Cloud ALM > Test Preparation App.
* You can find additional information on SAP Cloud ALM Test Plans available in the Help - SAP Cloud ALM Test Plans accelerator.
3. If you are managing Test Plans Manually or using a third-party Test Management Tool:
* Create the test plan and add the relevant business processes to it.
* Different test plans should be created for the different phases of the project (i.e., User Acceptance Tests, Regression Tests, Performance Tests, etc.).
## Task 2: Test Execution
#### Description
Execution or previously created test plan(s). Any errors identified in the test execution need to be reviewed along with all corresponding documentation that was captured in the logs. The testing/project team should resolve failed cases and re-run the test plan to ensure they are run successfully.

## Task 3: Perform Dress Rehearsal
#### Description
The purpose of this task is to rehearse the cutover procedure by executing the steps in a test environment. The rehearsal test or sometimes referred to as a dress rehearsal is inclusive of all steps and details of the cutover plan; however, some step can only be simulated.

The rehearsal will confirm the process, ownership, sequence, and duration of the cutover procedures. Defects are logged and the process updated until the plan can be executed without issue.

The cutover rehearsal can occur in a separate client, instance or in the non-live production environment.

Prerequisite:

Completed cutover procedure.
System for testing.

Procedure:

1. Execute the cutover plan in its entirety in a non-productive environment, which is representative of the current state and end-state of production.
2. Resolve defects and refine the process based on knowledge gained during execution of the process.
## Task 4: ISV Partner Spotlight - Tricentis - Realize phase
#### Description
Using the Test strategy from the Discover phase, defining key performance metrics, and set up an effective operating model to ensure smooth execution and monitoring. Empower the strategic enterprise team to drive organizational objectives with the necessary testing tools, resources, and authority. Develop a comprehensive test plan that outlines methods, schedules, and resources for validating system functionality. Refine the testing process by prioritizing test cases based on potential risks to maximize efficiency and project success outcomes. Equip the test team with a structured quality playbook to guide testing procedures and ensure adherence to high standards. Train the testing team on how to utilize the quality playbook that provides detailed guidelines and standards for effective test execution. Design a robust test data management strategy to ensure the availability and integrity of data in the project's development environment.

Solutions:
* Tricentis Test Automation for SAP integrated with SAP Cloud ALM 
* Tricentis Test Automation for SAP integrated with SAP Solution Manager
* SAP Change Impact Analysis by Tricentis
* SAP Enterprise Continuous Testing by Tricentis
* SAP Enterprise Performance Testing by Tricentis
* SAP Enterprise Data Integrity Testing by Tricentis