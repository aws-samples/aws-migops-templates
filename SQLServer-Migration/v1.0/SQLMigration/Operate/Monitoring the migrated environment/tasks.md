
# Module: Monitoring the migrated environment
## Task 1: Application  Performance Monitoring
#### Description
Application performance monitoring is the process of tracking key software application performance metrics using monitoring software and telemetry data. This ensures system availability, optimizes service performance and response times, and improves user experiences.It is critical to monitor the performance of the overall system as well as individual components of the system. For more information, see [AWS CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html.)

#### Tools
AWS CloudWatch
#### Acceptance Criteria
• Set a threshold for each metric and monitor for healthy performance. 
#### Acceptance Criteria
• List the application performance metrics that might be helpful in monitoring the overall application. 
## Task 2: Security & Compliance Monitoring
#### Description
Check  against the security posture established in the Mobilize phase for each  workload.   
1) Identity and Access Management  
2) Logging and Monitoring  
3) Infrastructure Protection  
4) Data Protection   
5) Incident Response
#### Tools
Amazon Identity and Access Management (IAM)
#### Tools
Amazon CloudWatch
#### Tools
AWS CloudTrail
#### Tools
AWS Key Management Service
#### Tools
AWS CloudFormation
#### Tools
AWS Security Groups
#### Tools
AWS Secrets Manager
#### Tools
Amazon GaurdDuty
#### Acceptance Criteria
•  Monitor and satisfy all the security metrics detailed in the Mobilize phase.
## Task 3: Cost Monitoring
#### Description
AWS Cost and Usage Reports provides estimated charges associated with AWS account. Each report contains line items for each unique combination of AWS products, usage type, and operation that are used in AWS account. Customize AWS Cost and Usage Reports to aggregate the information by the hour, day, or month.For more information, see [AWS Cost and Usage Reports](https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html.)
#### Tools
AWS Cost and Usage Reports
#### Acceptance Criteria
•  Monitor cost usage of all the infrastructure components in AWS on a periodic  basis 
## Task 4: Protecting Windows Workloads with AWS Backup
#### Description
AWS Backup is a fully-managed service that makes it easy to centralize and automate data protection across AWS services, in the cloud, and on premises. Using this service, you can configure backup policies and monitor activity for your AWS resources in one place. It allows you to automate and consolidate backup tasks that were previously performed service-by-service, and removes the need to create custom scripts and manual processes. With a few clicks in the AWS Backup console, you can automate your data protection policies and schedules.
#### Tools
AWS Backup
## Task 5: Managing Windows workloads with AWS Systems Manager Fleet Manager
#### Description
Fleet Manager, a capability of AWS Systems Manager, is a unified user interface (UI) experience that helps you remotely manage your nodes running on AWS or on premises. With Fleet Manager, you can view the health and performance status of your entire server fleet from one console. You can also gather data from individual nodes to perform common troubleshooting and management tasks from the console. This includes connecting to Windows instances using the Remote Desktop Protocol (RDP), viewing folder and file contents, Windows registry management, operating system user management, and more. To get started with Fleet Manager, open the Systems Manager console. In the navigation pane, choose Fleet Manager.
#### Tools
AWS Fleet Manager
## Task 6: Monitor the status of Windows services with Amazon CloudWatch
#### Description
Amazon CloudWatch is basically a metrics repository. Migrated Windows workloads put metrics into the repository, and you retrieve statistics based on those metrics. If you put your own custom metrics into the repository, you can retrieve statistics on these metrics as well.
## Task 7: Monitoring applications with Amazon CloudWatch Application Insights
#### Description
Amazon CloudWatch Application Insights facilitates observability for your applications and underlying AWS resources. It helps you set up the best monitors for your application resources to continuously analyze data for signs of problems with your applications. Application Insights, which is powered by SageMaker and other AWS technologies, provides automated dashboards that show potential problems with monitored applications, which help you to quickly isolate ongoing issues with your applications and infrastructure. The enhanced visibility into the health of your applications that Application Insights provides helps reduce mean time to repair (MTTR) to troubleshoot your application issues.
#### Tools
Amazon CloudWatch Application Insights