
# Module: Refactor dotNET monolithic application to microservices - using AWS Microservice Extractor
## Task 1: Gather code artifacts
#### Description
All code artifacts are gathers and code is upgraded to a minimum of .NET framrwork 4.0
#### Acceptance Criteria
• All the code artifacts related to the application are gathered
#### Acceptance Criteria
• Application is upgraded to atleast .NET framework 4.0
#### Acceptance Criteria
• Application that is being assessed builds successfully
## Task 1: Subtask 1: Gather all code artifacts for the solution that's being upgraded
#### Description

#### Acceptance Criteria
• All the code artifacts related to the application are gathered
## Task 1: Subtask 2: Upgrade the .NET framework version to minimum .NET fx 4
#### Description

#### Acceptance Criteria
• Application is upgraded to atleast .NET framework 4.0
## Task 1: Subtask 3: Fix build errors. Make sure the solution builds.
#### Description

#### Acceptance Criteria
• Application that is being assessed builds successfully
## Task 2: Prerequisites
#### Description
This tasks guides the user to ensure all the pre-requisites related to IAM permissions, system configuration and software requirements are met
#### Acceptance Criteria
• Proper IAM permissions are configured to use Microservice Extractor
#### Acceptance Criteria
• MSBuild is installed on the system
#### Acceptance Criteria
• Microservice Extractor is downloaded and installed
#### Acceptance Criteria
• System requirements for Microservice Extractor are met
## Task 2: Subtask 1: Make sure you have MSBuild installed on the system (it is automatically installed if you are using Visual Studio)
#### Description

#### Acceptance Criteria
• MSBuild is installed on the system
## Task 2: Subtask 2: Make sure you meet system requirements
#### Description
Make sure you meet system requirements listed on: https://docs.aws.amazon.com/microservice-extractor/latest/userguide/microservice-extractor-prerequisites.html
#### Acceptance Criteria
• System requirements for Microservice Extractor are met
## Task 2: Subtask 3: Make sure you have IAM permissions
#### Description
Make sure you have IAM permissions listed here: https://docs.aws.amazon.com/microservice-extractor/latest/userguide/microservice-extractor-prerequisites.html
#### Acceptance Criteria
• Proper IAM permissions are configured to use Microservice Extractor
## Task 2: Subtask 4: Download and install Microservice Extractor
#### Description
Download and install Microservice Extractor from: https://s3.us-west-2.amazonaws.com/aws.serviceextract.download/latest/windows/ServiceExtract.exe
#### Acceptance Criteria
• Microservice Extractor is downloaded and installed
## Task 3: Configurations and Settings
#### Description
Task for ensuring Microservice Extractor is configured
#### Acceptance Criteria
• Optionally data sharing is enabled
#### Acceptance Criteria
• AWS profile is configured for Microsoervice Extractor
#### Acceptance Criteria
• Working directory si created and updated in the setttings
#### Acceptance Criteria
• Optionally runtime profiling metrics are configured
#### Acceptance Criteria
• If required, automated grouping option is enabled and corresponding S3 bucket is configured
## Task 3: Subtask 1: Setting up for account runtime profiling metrics
#### Description
If you want to take into account runtime profiling metrics as well, please make sure you have these setup: https://docs.aws.amazon.com/microservice-extractor/latest/userguide/microservice-extractor-install.html
#### Acceptance Criteria
• Optionally runtime profiling metrics are configured
## Task 3: Subtask 2: Add a named profile for AWS CLI
#### Description
Add a named profile for AWS CLI: https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html#cli-configure-files-using-profiles
#### Acceptance Criteria
• AWS profile is configured for Microsoervice Extractor
## Task 3: Subtask 3: Optionally you can enable automated groupings. Create the corresponding S3 bucket if you have this setting enabled.
#### Description

#### Acceptance Criteria
• If required, automated grouping option is enabled and corresponding S3 bucket is configured
## Task 3: Subtask 4: Add/Update working directory
#### Description

#### Acceptance Criteria
• Working directory si created and updated in the setttings
## Task 3: Subtask 5: Enable/Disable usage data sharing
#### Description

#### Acceptance Criteria
• Optionally data sharing is enabled
## Task 4: Scan/Onboard the application
#### Description
Task for onboarding application
#### Acceptance Criteria
• Path for the code is provided
#### Acceptance Criteria
• Optionally runtime profiling data is provided
#### Acceptance Criteria
• MSBuild path is provided
#### Acceptance Criteria
• Optionally .NET Core portability analysis is enabled
## Task 4: Subtask 1: Provide path to the solution file for your code which you want to scan
#### Description

#### Acceptance Criteria
• Path for the code is provided
## Task 4: Subtask 2: Provide MSBuild path
#### Description

#### Acceptance Criteria
• MSBuild path is provided
## Task 4: Subtask 3: Optionally provide runtime profiling data csv file
#### Description

#### Acceptance Criteria
• Optionally runtime profiling data is provided
## Task 4: Subtask 4: Optionally enable analysis of .NET Core portability
#### Description

#### Acceptance Criteria
• Optionally .NET Core portability analysis is enabled
## Task 4: Subtask 5: Onboard the application
#### Description

#### Acceptance Criteria
• Application is onboarded
## Task 5: Analyze Visualization and Group Components
#### Description
Task for analyzing visualization and creating groups for extraction
#### Acceptance Criteria
• Visualization generated by Microservice Extractor is analyzed and groups are created for extraction
## Task 5: Subtask 1: Analyze the visualization by: 1\ Viewing node details, 2\ Looking at dependencies, 3\ Filtering nodes, 4\ Viewing runtime profiling information
#### Description

#### Acceptance Criteria
• Visualization generated by Microservice Extractor to modify or create groups is analyzed
## Task 5: Subtask 2: Add canvases to see specific layouts of nodes, edges and groups
#### Description

#### Acceptance Criteria
• Canvases are added for specific layout of nodes, edges and groups
## Task 5: Subtask 3: Create custom groups to visualize a segmentation of the service. You can optionally get automated groupings.
#### Description

#### Acceptance Criteria
• Custom groups are created for extraction to microservices
## Task 6: Prepare for extraction
#### Description
Group is prepared for extraction
#### Acceptance Criteria
• Shared State Access for classes are extracted as a group
#### Acceptance Criteria
• Between creating remote endpoint v/s library is taken for the group being extracted
#### Acceptance Criteria
• Decision is taken between refactoring methods to call extracted microservice vs not refactoring the same
## Task 6: Subtask 1: Refactor usage of any Shared State Access for classes that are being extracted as part of the group
#### Description

#### Acceptance Criteria
• Shared State Access for classes are extracted as a group
## Task 6: Subtask 2: Take refactoring decisions for microservice being extracted: 1\ Remote Endpoints OR 2\ Library
#### Description

#### Acceptance Criteria
• Between creating remote endpoint v/s library is taken for the group being extracted
## Task 6: Subtask 3: Take refactoring decisions for the monolith: 1\ Refactor methods to call extracted microservice OR 2\ Do not refactor
#### Description

#### Acceptance Criteria
• Decision is taken between refactoring methods to call extracted microservice vs not refactoring the same
## Task 7: Extract and optionally port while extracting
#### Description
Extraction and optional porting of microservice is addressed by this task
#### Acceptance Criteria
• Extraction of microservice from monolith and optional porting is completed
## Task 7: Subtask 1: Decide if you while extracting if you want to port: 1\ Microservice, 2\ Monolith
#### Description

#### Acceptance Criteria
• Extraction of microservice from monolith and optional porting is completed
## Task 8: Manual refactoring changes
#### Description
Manual changes to fix errors
#### Acceptance Criteria
• Build errors if any are manually fixed
## Task 8: Subtask 1: Manually fix any build issues/logic issues in the extracted/calling code
#### Description

#### Acceptance Criteria
• Build errors, if any, are manually fixed
## Task 9: Optionally port from legacy .NET fx to .NET 6+
#### Description
Port microservice to .NET 6+ if not already ported
#### Acceptance Criteria
• If you have only extracted in the previous step then porting is considered using AWS Toolkit for .NET Refactoring
## Task 9: Subtask 1: Follow the module "Re-platform dot NET Applications using AWS Toolkit for dot NET Refactoring"
#### Description

#### Acceptance Criteria
• If you have only extracted in the previous step then porting is considered using AWS Toolkit for .NET Refactoring
## Task 10: Testing
#### Description
Application testing
#### Acceptance Criteria
• Application Testing is completed
## Task 10: Subtask 1: Debug and test applications locally
#### Description

#### Acceptance Criteria
• Locally test and fix the application, and ensure all errors are fixed
## Task 10: Subtask 2: Perform integration testing on AWS
#### Description

#### Acceptance Criteria
• Integration testing is completed and bugs, if any, are fixed
## Task 11: Deployment
#### Description
Application deployment
#### Acceptance Criteria
• Application is deployed on AWS with DevOps configured
## Task 11: Subtask 1: Create DevOps pipeline for microservice
#### Description

#### Acceptance Criteria
• DevOps pipeline for the extracted microservice application(s) is created
## Task 11: Subtask 2: Create DevOps pipeline for monolithic application
#### Description

#### Acceptance Criteria
• DevOps pipeline for monolithic application is created
## Task 11: Subtask 3: Deploy the application on production
#### Description

#### Acceptance Criteria
• Application is deployed on AWS