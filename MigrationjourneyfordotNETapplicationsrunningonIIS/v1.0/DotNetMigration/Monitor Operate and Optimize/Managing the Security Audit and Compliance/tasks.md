
# Module: Managing the Security Audit and Compliance
## Task 1: Set up AWS CloudTrail to view the API calls and create notifications to troubleshoot and remediate quickly.
#### Description
AWS CloudTrail is an AWS service that helps you enable operational and risk auditing, governance, and compliance of your AWS account. Actions taken by a user, role, or an AWS service are recorded as events in CloudTrail. Events can include actions taken in the AWS Management Console, AWS Command Line Interface (AWS CLI), and AWS SDKs and APIs.
#### Tools
AWS CloudTrail
#### Acceptance Criteria
CloudTrail logs are available in the Amazon S3 bucket.
CloudWatch alarms has been set up to send notifications for unusual activities in your accounts.
## Task 1: Subtask 1: Create a CloudTrail trail
#### Description

#### Tools
CloudTrail trail
## Task 1: Subtask 2: Configure CloudTrail with CloudWatch Logs to monitor trail logs
#### Description

#### Tools
Monitoring CloudTrail Log Files with Amazon CloudWatch Logs
## Task 1: Subtask 3: Create CloudWatch alarms that are triggered according to thresholds and time periods that you specify.
#### Description

#### Tools
Creating CloudWatch alarms for CloudTrail events
## Task 2: Set up and configure rules in AWS Config to evaluate resources and enforce compliance
#### Description
AWS Config provides a detailed view of the resources associated with your .NET application, including how they are configured, how they are related to one another, and how the configurations and their relationships have changed over time.
#### Tools
AWS Config
#### Acceptance Criteria
Verified that AWS config is recording the configuration changes from console or using AWS CLI.
## Task 2: Subtask 1: Identify the resource types for AWS config to record
#### Description

## Task 2: Subtask 2: Set up an Amazon S3 bucket to receive configuration snap shot and configuration history files
#### Description

## Task 2: Subtask 3: Set up an Amazon Simple Notification Service (Amazon SNS) to send configuration and compliance notifications.
#### Description

## Task 2: Subtask 4: Grant AWS Config the permissions it needs to access the Amazon S3 bucket and the Amazon SNS topic.
#### Description

## Task 2: Subtask 5: Specify the rules that you want AWS Config to use to evaluate compliance information for the recorded resource types.
#### Description

## Task 2: Subtask 6: Create conformance packs that contains the list of AWS Config managed or custom rules and remediation actions.
#### Description

## Task 3: Secure .NET application secrets
#### Description
Ensure proper methods are in place to manage, store and retrieve sensitive data for your application like database credentials, API keys and application configurations.
#### Tools
AWS Secrets Manager
#### Tools
AWS Prescriptive Guidance
#### Acceptance Criteria
The application secrets and connection strings are stored securely in AWS Secrets Manager or Parameter Store 
## Task 3: Subtask 1: Set up AWS Secrets Manager to store sensitive data
#### Description
Manage, retrieve, and rotate database credentials, application credentials, OAuth tokens, API keys, and other secrets throughout their lifecycles by implementing AWS Secrets Manager.
## Task 3: Subtask 2: Secure application configurations using AWS Systems Manager Parameter Store
#### Description
Parameter Store, a capability of AWS Systems Manager, provides secure, hierarchical storage for configuration data management and secrets management.
#### Tools
AWS Systems Manager Parameter Store