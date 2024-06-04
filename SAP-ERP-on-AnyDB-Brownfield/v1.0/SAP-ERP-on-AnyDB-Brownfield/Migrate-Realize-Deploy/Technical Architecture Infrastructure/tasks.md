
# Module: Technical Architecture Infrastructure
## Task 1: System Go-Live
#### Description
This is the checkpoint for Technical Architecture Infrastructure as a pre-condition for the final business sign-off for productive use.As part of this Go-Live process for brownfield systems, the system will be included into the productive monitoring. 

## Task 2: Quality System Initial Access and Setup
#### Description
The purpose of this deliverable is to set up a Quality System.

Before converting an SAP system, or installing a new one you will need to download SAP software from SAP Service Marketplace. The planning of such a change event is done in the Maintenance Planner. After entering the required data, the Maintenance Planner fills your download basket, and creates a control file (“stack-xml”), which is later on required for the conversion and installation tools. The Maintenance Planner has been described in the activity Transition Planning of the Explore phase - Please make yourself familiar with the tool, enter the required information, and download the corresponding software including stack-xml. S

Prerequisite:

The Development system has been set up successfully.
Receive Quality System
## Task 2: Subtask 1: Access Quality System and Reset Password
#### Description
Access Quality System and Reset Password
The purpose of this task is for the System Administrator to receive the e-mails with the URL, login ID, and password for the Quality System. Additionally, the System Administrator will be prompted to reset their password on initial login.

Prerequisite

You have received an initial system
You have conducted Fit-to-Standard workshops
You have passed Quality Gate and successfully closed the Explore phase
Procedure

1. Locate the provisioning e-mails sent to the System Administrator with system details.
2. Confirm delivery and access of the initial system.
3. Locate additional provisioning e-mail to verify your identity. Verify your identity and request security code. You will be prompted via e-mail on how to verify your identity and access user credentials.
4. Reset the SAP S/4HANA password using the Technical User URL and the Technical Username.
5. Access the SAP S/4HANA Quality System.
## Task 2: Subtask 2: Create Users in the Quality System
#### Description
The purpose of this task is to create the users in the Quality System that will participate in the implementation project. Additional users can be added at any time in the future. SAP S/4HANA Cloud Private Edition provides test users ready to be used by the project team.
## Task 2: Subtask 3: Transport Fiori Rapid Activation
#### Description
The purpose of this task is to transport the Fiori Rapid activation task list from the Development system to the Q-System and P-system or any other post Development system.

Procedure:

1. Follow the step-by-step guidance in the SAP S/4HANA Fiori Rapid Activation Transport Move to Production Strategy accelerator. The guide provides steps required to run the Fiori transport after initial Fiori activation in the Development System. An overview of the required steps is the following:
2. Move customizing and Workbench transports request to your target system/client
3. Run Rapid Activation task lists with selected tasks
4. Assign roles to users and test Fiori Launchpad / Apps

## Task 2: Subtask 4: Setup Quality System for System Conversion
#### Description
The purpose of this task is to provide a viable, correctly configured quality assurance environment that is available for use by the project team to test configuration and development in a “production-like” environment. QAS is not installed as new – instead, the old QAS system is converted to SAP S/4HANA.

Prerequisites:

The migration approach has been validated in a Sandbox System
A detailed migration plan is in place
The cleanup of the production system before the migration has started
Procedure:

1. Review the SAP Note 3226548 - SAP S/4HANA 2022 - application-specific notes in system conversion and check what needs to be done on application level before and after conversion. Depending on the transport landscape configuration, there may be a need to perform multiple iterations of the conversion to solidify and finalize the cutover plan. Executing test migrations will validate the end-state of the conversion, as well as provide the figures for expected system downtime. Depending on the approach and the transport landscape configuration, there may be a requirement to execute additional sandbox conversions to optimize the cutover procedure.
2. Transport development and configuration changes from the new SAP S/4HANA Cloud Private Edition Development System to the Quality System.
3. Review the Fiori apps required configuration of the Quality System.
## Task 3: Production System Initial Access and Setup
#### Description
The purpose of this deliverable is to access the Production system and to set up the initial user access.
## Task 3: Subtask 1: Access Production System and Reset Password
#### Description
The purpose of this task is for the customer system administrator to receive the emails with the URL, login ID, and password for the P-System.

Prerequisite

You have received the Quality System
You have passed Quality Gate and successfully closed the Explore phase
Procedure

Locate the provisioning e-mails sent to the System Administrator with system details.
Locate additional provisioning e-mail to verify your identity.
Verify your identity and request security code. You will be prompted via e-mail on how to verify your identity and access user credentials.
Reset the SAP S/4HANA password using the Technical User URL and the Technical Username.
## Task 3: Subtask 2: Transport Fiori Rapid Activation
#### Description
The purpose of this task is to transport the Fiori activations from the Development system to the Quality System and Production system or any other post Development system. This task can include activations for:

SAP Business Roles, Fiori launchpad and features activated in the task Activate SAP Fiori in the Initial System
Custom business roles created and activated in the task Create your custom business roles
Procedure:

1. Confirm the list of business roles (custom business roles and any SAP Business Roles) to be transported.
2. Follow the step-by-step guidance in the SAP S/4HANA Fiori Rapid Activation Transport Move to Production Strategy accelerator. The guide provides steps required to run the Fiori transport after initial Fiori activation in the Development System. An overview of the required steps is the following:
* Move customizing and Workbench transports request to your target system/client
* Run Rapid Activation task lists with selected tasks
* Assign roles to users and test Fiori Launchpad / Apps
## Task 3: Subtask 3: Set up Production System
#### Description
The purpose of this task is to prepare the Production System for use by the project team to execute final Go-Live simulations. This system will be used as the future Production system to go Go-Live.

Prerequisite:

A Production System is available
Procedure

1. Execute the technical installation of the required SAP Products for the Production System as documented in the technical design document. See the installation guide for how to install the components.
2. Run the technical system setup as documented in the administration guide.
3. Transport development and configuration changes from the Quality system to the Production system. Consider also the manual rework activities as described in the administration guide.
4. Prepare the production system for Go-Live simulations