
# Module: Monitoring of Dot NET application
## Task 1: Application monitoring using  Amazon CloudWatch
#### Description
The cornerstone for monitoring applications running on AWS is Amazon CloudWatch, a group of services that can store log files, track metrics, send alarms, and execute automated actions when specific events are triggered. Customizable CloudWatch dashboards can be used to monitor resources and view the metrics and alarms for your AWS resources
#### Tools
Amazon CloudWatch
#### Acceptance Criteria

Application performance KPIs has been defined
Key metrics, logs and alarms has been set up to continuously monitor the application resources and other technology stack.
## Task 1: Subtask 1: Define KPIs for application performance
#### Description

## Task 1: Subtask 2: Set up CloudWatch dashboards to monitor the resources
#### Description

## Task 1: Subtask 3: Set up CloudWatch alarms to monitor metrics
#### Description
Use cloud watch alarms to monitor metrics and trigger corresponding actions including automatic scaling or sending a notification to SNS topic
## Task 1: Subtask 4: Set up Amazon CloudWatch Application Insights
#### Description
Amazon CloudWatch Application Insights for .NET enables application owners to easily monitor their application stack. It automatically sets up and analyses important metrics and logs from across their application resources in real time, and uses machine learning techniques to discover anomalies and errors. CloudWatch Application Insights for .NET and SQL Server creates automated dashboards for detected problems, helping application owners troubleshoot faster and reduce the mean time to resolution (MTTR) for their application issues and improve Service Level Agreements (SLAs).
#### Tools
Amazon CloudWatch Application Insights
## Task 2: Trace request to application using AWS X-Ray
#### Description
AWS X-Ray collects data about requests that your application serves, and it helps you view, filter, and gain insights into that data to identify issues and opportunities for optimization.
#### Tools
AWS X-Ray
#### Acceptance Criteria
•	Application instrumented to send traces to X-Ray.
•	The incoming/outgoing requests to your application is visible through the AWS X-Ray console.

## Task 2: Subtask 1: Install and run the X-Ray daemon on the EC2 instance
#### Description

#### Tools
X-Ray daemon
## Task 2: Subtask 2: Instrument the .NET application to send traces to X-Ray
#### Description

#### Tools
AWS Distro for OpenTelemetry .NET
#### Tools
AWS X-Ray SDK for .NET
## Task 3: Monitor the IP traffic for your application using the Amazon VPC Flow Logs
#### Description
The VPC Flow Logs feature of Amazon Virtual Private Cloud (Amazon VPC) captures detailed information about the traffic going to and from network interfaces in your VPCs.
#### Tools
VPC Flow Logs
#### Acceptance Criteria
Flow log records are available to view and process in the destination (Amazon S3/CloudWatch logs/Kinesis Data Firehose)
## Task 3: Subtask 1: Identify the resource to create the flow log and the types of traffic to capture
#### Description

## Task 3: Subtask 2: Identify a destination for the flow log
#### Description

## Task 3: Subtask 3: Create a flow log from the console or using the AWS CLI for the identified resources
#### Description

## Task 4: Set up notifications/alerts for production issues
#### Description
This step involves setting up notifications to alert for any application issues. 
#### Acceptance Criteria
SMS/Email notifications has been set up to send alerts during a critical production issue.
## Task 4: Subtask 1: Set up email notifications using Amazon Simple Notification Service (Amazon SNS)
#### Description

#### Tools
Amazon SNS Notifications
## Task 4: Subtask 2: Set up SMS text notifications
#### Description

#### Tools
Amazon SNS text messaging
#### Tools
PagerDuty integration
## Task 4: Subtask 3: Set up Slack channel notification
#### Description

#### Tools
Slack set up using AWS Chatbot
## Task 5: Measure, monitor and analyze the business KPI's using Amazon Quicksights
#### Description
In this step the key business outcomes established in the initial Assess phase are measured to determine whether you’re accomplishing the business objectives.  Amazon Quicksight Dashboards are developed for continuous monitoring and tracking of the key business performance indicators.
#### Tools
Amazon Quicksight
#### Acceptance Criteria
•	Key business performance indicators are monitored and tracked regularly.
## Task 5: Subtask 1: Measure the key business performance indicators identified in the Assess phase
#### Description

## Task 5: Subtask 2: Create Quicksight dashboard to monitor and analyze the key business performance indicators
#### Description

## Task 6: Measure, monitor and analyze the business KPI's using 3rd party tools
#### Description
In this step the key business outcomes established in the initial Assess phase are measured to determine whether you’re accomplishing the business objectives.  Use 3rd part tools like Splunk to develop dashboards for continuous monitoring and tracking of the key business performance indicators.
#### Acceptance Criteria
•	Key business performance indicators are monitored and tracked regularly.
## Task 6: Subtask 1: Measure the key business performance indicators identified in the Assess phase
#### Description

## Task 6: Subtask 2: Select a 3rd party tool to monitor the business KPIs
#### Description

## Task 6: Subtask 3: Create dashboards to monitor and analyze the key business performance indicators in the selected tool
#### Description
