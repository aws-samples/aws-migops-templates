
# Module: Re-platform dotNET Applications using App2Container
## Task 1: Pre-requisites
#### Description
The pre-requisites required for configuring environment for App2Container
#### Acceptance Criteria
• A2C is installed.
#### Acceptance Criteria
• Software requirements for A2C are met.
#### Acceptance Criteria
• The AWS profile configured has the required IAM permissions.
#### Acceptance Criteria
• AWS CLI is configured.
#### Acceptance Criteria
• Remote access to worker machine is configured in case A2C is running remotely (and not on application server).
## Task 1: Subtask 1: Download and install A2C: https://docs.aws.amazon.com/app2container/latest/UserGuide/start-step1-install.html
#### Description

#### Acceptance Criteria
• A2C is installed.
## Task 1: Subtask 2: Make sure you meet the requirements for: 1\ Operating system version, 2\ IIS Version, 3\ .NET framework version for the application you are contienrizing, 4\ Docker version
#### Description
Make sure you meet the requirements for: 1\ Operating system version, 2\ IIS Version, 3\ .NET framework version for the application you are contienrizing, 4\ Docker version. Details on this page: https://docs.aws.amazon.com/app2container/latest/UserGuide/supported-applications.html
#### Acceptance Criteria
• Software requirements for A2C are met.
## Task 1: Subtask 3: Make sure AWS CLI is configured and you have required IAM permission for A2C
#### Description
Make sure AWS CLI is configured and you have required IAM permission for A2C: https://docs.aws.amazon.com/app2container/latest/UserGuide/iam-a2c.html
#### Acceptance Criteria
• AWS CLI is configured.
#### Acceptance Criteria
• The AWS profile configured has the required IAM permissions.
## Task 1: Subtask 4: Optionally configure remote access to worker machine if running the tool remotely and not on the application server
#### Description

#### Acceptance Criteria
• Remote access to worker machine is configured in case A2C is running remotely (and not on application server).
## Task 2: Initilize App2Container
#### Description
For A2C, initilize workspace path to store artifacts, optionally provide S3 bucket to extract artifacts, optionally provide permission to upload logs, optionally provide permission to access usage metrics, optinally direct whether to use signed docker images.
#### Acceptance Criteria
• Able to initialize App2Container with no errors
## Task 2: Subtask 1: Initilize A2C and provide: 1\ workspace path to store artifacts, 2\ optionally provide S3 bucket to extract artifacts, 3\ optionally provide permission to upload logs, 4\ permission to access usage metrics, 5\ whether to use signed docker images
#### Description

#### Acceptance Criteria
• Able to initialize App2Container with no errors.
## Task 3: Discover & Analyze
#### Description
Gather a list of all the applications hosted on IIS Server and analyze them for containerization
#### Acceptance Criteria
• Able to discover and analyze applcation hosted on IIS serverwith no errors
## Task 3: Subtask 1: Run inventory command to gather list of hosted applications in the IIS server
#### Description

#### Acceptance Criteria
• Inventory command runs successfully and able to gather a list of hosted applications on IIS Server
## Task 3: Subtask 2: Locate the applicattion you want to containerize and run analyze command on the same
#### Description

#### Acceptance Criteria
• Analyze command executes successfully
## Task 4: Transform application to containers
#### Description
Extract and containerize the application
#### Acceptance Criteria
• Application is running on docker container
## Task 4: Subtask 1: Run the extract command if using a separate worker machine
#### Description

#### Acceptance Criteria
• Extract command executes successfully
## Task 4: Subtask 2: Run the containerize command
#### Description

#### Acceptance Criteria
• Application is running on docker container
## Task 5: Deployment
#### Description
Deployment configuration and application deployment
#### Acceptance Criteria
• Container Image is hosted on Amazon ECR
#### Acceptance Criteria
• DevOps pipeline is generated
#### Acceptance Criteria
• The containers are running using the configured orchestrator: ECS\EKS\AppRunner
## Task 5: Subtask 1: Run generate app deployment command to generate the deployment
#### Description

#### Acceptance Criteria
• Deployment manifest is generated
## Task 5: Subtask 2: Configure container secrets
#### Description

#### Acceptance Criteria
• Container secrets are configured
## Task 5: Subtask 3: Configure containers and attributes specific for that application container
#### Description

#### Acceptance Criteria
• Other container configurations (if required) are completed
## Task 5: Subtask 4: Configure container deployment - 1\ which orchestrator to use, 2\ task parametes, 3\ ports, 4\ environment, 5\ ECR parameters, 6\ ECS\EKS\AppRunner parameters
#### Description

#### Acceptance Criteria
• Continer deployment parameters are configured
## Task 5: Subtask 5: Configure deployment pipelines: Options: 1\ AWS CodePipeline, 2\ Jenkins, OR 3\ Azure DevOps
#### Description
Configure deployment pipelines from one of these three options: 1\ AWS CodePipeline, 2\ Jenkins, 3\ Azure DevOps
#### Acceptance Criteria
• Deployment pipelines are configured
## Task 5: Subtask 6: Run the deployment command which deploys using CI/CD pipelines to AWS services based on different configurations
#### Description

#### Acceptance Criteria
• Application is deployed without any errors
## Task 6: Testing
#### Description
Integration testing for the containerized application
#### Acceptance Criteria
• Based on customer's processes testing is performed to make sure functional scenarios are executing as expected
## Task 6: Subtask 1: Perform integration testing on AWS
#### Description

#### Acceptance Criteria
• Integration testing is completed and bugs, if any, are fixed
## Task 7: Clean Up
#### Description
Clean up tasks after application is containerized
#### Acceptance Criteria
• App2Container is removed from the application server
#### Acceptance Criteria
• Credential profile for AWS which was used for A2C is removed
## Task 7: Subtask 1: Remove app2container from the application server
#### Description

#### Acceptance Criteria
• A2C is removed from the environment
## Task 7: Subtask 2: Remove credentials profile for AWS which was used for A2C
#### Description

#### Acceptance Criteria
• Credentials profile created for user to operate A2C in the environement is removed