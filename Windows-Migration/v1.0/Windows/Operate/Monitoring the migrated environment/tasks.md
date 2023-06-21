
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
AWS CloudFormation
#### Tools
AWS CloudWatch
#### Tools
AWS Key Management Service
#### Tools
AWS Secrets Manager
#### Tools
AWS CloudTrail
#### Tools
AWS Identity and Access Management (IAM)
#### Tools
AWS Security Groups
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