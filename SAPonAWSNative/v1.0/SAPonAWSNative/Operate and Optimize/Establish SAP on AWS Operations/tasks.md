
# Module: Establish SAP on AWS Operations
## Task 1: Define SAP operations strategy on AWS
#### Description
After the migration to AWS is complete, establish an operational strategy in the following areas.
* **Availability**   -  Understanding your availability goals is the first step to help ensure that you focus on the factors important to your organization. This helps you to define criteria that can be used to propose a operational strategy that can meet your goals. 
*  **Disaster Recovery** : Designing, implementing, and maintaining a disaster recovery plan is critical for organizations running mission-critical applications, such as SAP.
* **Automation** : Automation should be considered as one the key aspects in your Operations strategy, creating and maintaining automation pipelines in AWS will  improve efficiency and productivity, which can translate into lower costs for your organization.
* **Monitoring & Alerting** : Ensue right level of Monitoring and alerting capabilities are in place for SAP systems on AWS. This would help to detect and react to failures impacting your SAP workload. Focus on prevention where possible. 
* **Backups** : Review SAP backup strategy for improvements, SAP workload on AWS offer additional capabilities for automation, retention and recovery of backups. 
*  **Security** SAP on AWS operations strategy should focus on taking advantage of cloud native AWS technologies to improve SAP security  of the landscape, in addition to the SAP recommended SAP security notes and guidelines.
* **Change and Release Management**: Adopt DevOps approaches that improve flow of changes into production, which allow refactoring, fast feedback on quality, and bug fixing. Integrate  build and deployment management systems for SAP change management.
#### Tools
Business Continuity Planning
#### Tools
AWS Systems Manager for SAP
#### Tools
AWS Backint Agent for SAP HANA
#### Tools
Architecture guidance for availability and reliability of SAP on AWS
#### Tools
AWS Backup Support for HANA 
#### Tools
Operational Excellence- SAP Well Architected Framework
## Task 2: Establish operational roles and responsibilities
#### Description
Ensure that the operational roles and responsibilities defined in the Mobilize phase are correct and current. Ths includes the following:
* Adopt support strategy and operational processes to run SAP on AWS effectively. 
* Have tracking mechanisms to regularly validate that you have the appropriate number of trained personnel to provide hands-on support for operational needs and that they have the appropriate SAP, AWS, or third-party certifications. 
* Train personnel and adjust personnel capacity as necessary to maintain effective support.
#### Tools
RACI templates
#### Acceptance Criteria
To ensure an effective SAP operations strategy is in place, a clear Roles & Responsibilities model (i.e. RACI Matrix) should be defined, covering internal Basis support, Cloud Ops, AWS/TAM, and any External partners; managed services, 3rd party, etc.
## Task 3: Implement Monitoring for the Migrated environment
#### Description
Establish best practices for monitoring of SAP workloads to ensure appropriate oversight and control is in place. In particular, focus on the areas of application/DB, security/compliance, logging, and cost monitoring. 
## Task 3: Subtask 1: Application and Database Monitoring
#### Description
[**Implement prerequisites for monitoring SAP on AWS**](https://docs.aws.amazon.com/wellarchitected/latest/sap-lens/best-practice-1-1.html)

SAP certification requirements for SAP on AWS are outlined in SAP Note 1656250. This note includes instructions for setting up the AWS Data Provider for SAP, enabling Amazon CloudWatch detailed monitoring, and using SAP enhanced monitoring for SAP NetWeaver solutions. Enabling these prerequisites helps ensure that your SAP workload state is able to be fully understood and investigated by AWS and SAP. These prerequisites should feed into your overall SAP monitoring strategy.


[**Implement infrastructure monitoring for SAP**](https://docs.aws.amazon.com/wellarchitected/latest/sap-lens/best-practice-1-2.html)

Set up your infrastructure monitoring to provide information about supporting services that are used to keep your SAP application running and supporting your users. Some examples include CPU and memory utilization, storage and filesystem usage and performance (IOPS and throughput), and network throughput. Include any dependent foundational services used by SAP, such as on-premises Active Directory services, DNS, and third-party tools, such as high availability (HA) and backup software. Evaluate AWS tools and SAP-specific tools from the AWS Marketplace that can help correlate and visualize this information, such as DataDog, Splunk, DynaTrace, and Avantra. Use this information to identify trends and determine when a corrective action is required.


[**Implement application and database monitoring for SAP**](https://docs.aws.amazon.com/wellarchitected/latest/sap-lens/best-practice-1-3.html)

Set up your application and database monitoring to provide information about its internal state, status, and achievement of business outcomes. Some examples include transaction response time, available work processes, queue depth, error and dump messages, stalled batch jobs, and transaction throughput. Use this information to determine when a corrective action is required. 
Continually monitor your SAP databases and establish alerts for common problems that can affect SAP system availability and performance. Common monitoring items include the following:

* Free space in data area
* Free space in logging area
* Excessive locking activity
* Cache utilization rates
* Average query response time
* Required security patches and hot fixes
* Top table sizes and growth

Base alerting thresholds on healthy patterns of historical productive usage of your system. Continually review and adjust your alarm thresholds to prevent problems and to react to workload changes or growth.

Consider Amazon Cloud Watch Application Insights for SAP HANA databases to analyze metric patterns using historical data to detect anomalies, and continuously track errors and exceptions from HANA, operating system, and infrastructure logs.
#### Tools
AWS CloudWatch
#### Tools
Best Practice 1.3 – Implement application and database monitoring for SAP
#### Tools
Best Practice 1.2 – Implement infrastructure monitoring for SAP
#### Tools
Monitor SAP using CloudWatch
#### Tools
 Best Practice 1.1 – Implement prerequisites for monitoring SAP on AWS
#### Acceptance Criteria
• List the application performance metrics that might be helpful in monitoring the overall SAP landscape . 
• Set a threshold for each metric and monitor for healthy performance. 
## Task 3: Subtask 2: Security & Compliance Monitoring
#### Description
Ensure robust security and compliance monitoring processes are established, in alignment with requirements defined in the mobilize phase. Key areas to focus on include:

* Identity and Access Management - As you run more workloads on AWS, you need robust identity management and permissions in place to ensure that the right people have access to the right resources under the right conditions. AWS offers a large selection of capabilities to help you manage your human and machine identities and their permissions.
* Logging and Monitoring - Have a strategic security plan that is supported by the appropriate logging, testing, and documented response methodology helps shape the proactive and reactive tasks that must be accomplished to ensure that all security challenges are met successfully.
* Infrastructure Protection - Infrastructure protection encompasses control methodologies, such as defense in depth, that are necessary to meet best practices and organizational or regulatory obligations. Use of these methodologies is critical for successful, ongoing operations in the cloud. Infrastructure protection is a key part of an information security program. It ensures that systems and services within your workload are protected against unintended and unauthorized access, and potential vulnerabilities
* Data Protection - Before architecting any workload, foundational practices that influence security should be in place. For example, data classification provides a way to categorize data based on levels of sensitivity, and encryption protects data by way of rendering it unintelligible to unauthorized access. These methods are important because they support objectives such as preventing mishandling or complying with regulatory obligations.
* Incident Response - Even with mature preventive and detective controls, your organization should implement mechanisms to respond to and mitigate the potential impact of security incidents. Your preparation strongly affects the ability of your teams to operate effectively during an incident, to isolate, contain and perform forensics on issues, and to restore operations to a known good state. Putting in place the tools and access ahead of a security incident, then routinely practicing incident response through game days, helps ensure that you can recover while minimizing business disruption.
#### Tools
AWS Identity and Access Management (IAM)
#### Tools
AWS Well-Architected Framework- Security Pillar
#### Tools
AWS SAP - Well Architected Security Pillar
#### Acceptance Criteria
• Processes established for Security & Compliance monitoring
## Task 3: Subtask 3: Log Monitoring
#### Description
A logging strategy in AWS involves setting up logging for various services to monitor and troubleshoot applications. CloudWatch Logs is a commonly used service for monitoring, storing, and accessing log files from various AWS services. In addition to CloudWatch Logs, you can also consider using other logging services like Amazon OpenSearch Service or custom centralized-logging solutions ( Dynatrace, Datalog,NewRelic etc..) for more advanced log management and analysis.Here are some key aspects for setting up logging in AWS.

* Identify log sources: Determine which AWS services, applications, and resources you want to generate logs from. This could include services like AWS Lambda, Amazon EC2, Amazon RDS, AWS S3, etc. Also, consider non-AWS sources such as on-premises systems or third-party applications.
* Define log retention policy: Determine how long you need to retain logs based on regulatory requirements, compliance standards, or your organization's needs. AWS CloudWatch Logs and Amazon S3 offer different storage options and pricing models for varying retention periods.
* Choose log aggregation: Decide on a central log aggregation solution. AWS provides services like Amazon CloudWatch Logs, AWS CloudTrail, and AWS X-Ray for log management and analysis. Alternatively, you can use third-party log management solutions integrated with AWS.
* Configure log collection: Set up the logging agents or SDKs for each source to collect and send logs to the chosen log aggregation service. This may involve installing agents, configuring log streams, or using APIs to send logs directly.
* Define log formats and standards: Establish a consistent log format and structure across your applications and resources. Adhering to a standard makes it easier to parse, search, and analyze logs efficiently.
* Implement log security: Protect your logs by ensuring proper access controls and encryption. Use AWS Identity and Access Management (IAM) policies to restrict access to logs based on roles and permissions. Consider enabling encryption in transit and at rest to safeguard log data.
* Enable real-time monitoring: Leverage log monitoring tools provided by AWS services like Amazon CloudWatch Alarms and AWS X-Ray to set up real-time alerts based on specific log events or metrics. This helps you proactively detect issues or anomalies.
* Utilize log analytics: Leverage log analysis solutions to gain insights and extract meaningful information from your logs. AWS services like Amazon Athena, Amazon Elasticsearch Service, or third-party tools can help with log analysis, log search, and log visualization.
* Implement automated log management: Automate log management tasks using AWS services like AWS CloudFormation, AWS CloudWatch Events, or AWS Lambda. This helps with log rotation, log backup, and archival processes.
* Regularly review and optimize: Continuously evaluate your logging strategy to ensure it meets your evolving needs. Review log volumes, performance impact, and costs regularly. Optimize log collection, retention, and analysis based on usage patterns and changing requirements.
#### Acceptance Criteria
• Implement a well defined logging strategy and provide mechanisms for improvements
## Task 3: Subtask 4: Cost Monitoring
#### Description
Cost monitoring on AWS is an important aspect of maintaining the reliability and performance of your AWS account, while ensure costs are under control. There are several tools available to monitor your AWS Billing and Cost Management usage.

* AWS Cost and Usage Reports track your AWS usage and provides estimated charges associated with your account. These reports contain line items for each unique combination of AWS products, usage type, and operation used in your AWS account. 
* AWS Cost Explorer allows you to view and analyze your costs and usage. You can monitor data for up to the last 12 months, forecast future spending, and get recommendations for purchasing Reserved Instances.
* AWS Budgets allows you to set custom budgets to track your costs and usage, and respond quickly to alerts received from email or SNS notifications if you exceed your threshold. 
* Trusted Advisor - can help you save cost with actionable recommendations by analyzing usage, configuration and spend. Examples include identifying idle RDS DB instances, underutilized EBS volumes, unassociated Elastic IP addresses, and excessive timeouts in Lambda functions.

Additional considerations:
* Monitoring costs can vary depending on the number of instances being monitored and the workload being monitored. For example, monitoring a large number of DB instances is more expensive than monitoring only a few. In addition, instances with compute-intensive workloads may have higher costs for monitoring.
* Managing Costs - it is recommended to set different granularities for different instances in your account. You should also enable detailed monitoring only when necessary, as detailed monitoring generates costs based on the number of metrics sent to Amazon CloudWatch.

#### Tools
AWS Trusted Advisor
#### Tools
AWS Cost and Usage Reports
#### Tools
EC2 Savings Plans
#### Tools
EC2 Reserved Instances
#### Tools
AWS Budgets
#### Acceptance Criteria
* Monitor cost usage of all the infrastructure components in AWS on a periodic  basis 
## Task 4: Automate key SAP Activities for SAP Operations
#### Description
Develop automation  solutions for  frequently run SAP activities. including provisioning and ongoing maintenance.
#### Tools
 aws-install-sap-with-jenkins-ansible
#### Tools
Terraform modules for deploying highly configurable SAP products on AWS. 
#### Tools
AWS Launch Wizard for SAP
#### Tools
AWS Cloudformation
#### Tools
Automating system provisioning
## Task 4: Subtask 1: Automate and set up Amazon Elastic Block Store (Amazon EBS) snapshots
#### Description

## Task 4: Subtask 2: Automate and set up EC2 Snapshot (AMI) activity
#### Description

## Task 4: Subtask 3: Automate alerts based on key events and thresholds
#### Description

## Task 4: Subtask 4: Automate and Setup SAP automatic scaling
#### Description
SAP application auto scaling, which automatically detects SAP application server demand and scales up or scales down Amazon EC2 instances accordingly. This capability can adapt to spikes and dips for concurrent user logins, month-end close, payment runs, and a variety of both predictable and unpredictable workloads. The capability can horizontally scale up (start new compute services as application servers) and scale down (stop existing compute services). The following are the benefits of this automation:

* Dynamic adjusting of application server capacity based on user demand
*    Running minimal baseline EC2 instances at the application layer
*    Reducing costs
*    Maintaining increased and scalable performance service level agreements (SLAs) for the business

#### Tools
Auto scaling SAP applications
## Task 4: Subtask 5: Scheduled, Automated clean SAP system shutdowns
#### Description
Automate startup and shutdown of SAP systems by using AWS services. This consistent and controlled process requires significantly less human intervention because it automates the monotonous, repetitive tasks and follows the sequence designed by SAP administrators. You can optionally add scheduling, notification, and alerts by using AWS services built for the cloud. In addition, this automation is capable of defining and handling dependencies between multiple SAP and non-SAP applications.
#### Tools
Automating startup and shutdown of SAP systems
## Task 4: Subtask 6: Setup Lifecycle policies on EBS, EFS and S3 for backups
#### Description

## Task 4: Subtask 7: SAP System Refresh automation
#### Description
Many enterprises require regular refreshes of their SAP systems in order to support testing and production operations. The manual refresh process can be time-consuming, costly, and tedious for SAP administrators. As an alternative to the manual process, you can use an automation that consists of server-less AWS services that collectively perform the system refresh process for you.
#### Tools
Automating SAP serverless refresh
#### Tools
Partner Solutions for SAP Refresh
## Task 4: Subtask 8: Automated SAP HANA patching
#### Description
Maintaining the SAP HANA database software version keeps the database on with supported software versions, and enables you to stay updated with security fixes and software improvements. Based on your release  strategy you can  automate the update of your SAP HANA database software version with AWS Systems Manager. 
#### Tools
Automated patching for SAP HANA
## Task 4: Subtask 9: Automate SAP Backups
#### Description
Automate SAP backups using a centralized backup management solution.
#### Tools
Automate and Simplify SAP HANA Backups with AWS Backup
#### Tools
 AWS Backint Agent
#### Tools
AWS Backup
## Task 5: Create run-books and troubleshooting documents for key activities
#### Description
Create operational run books and troubleshooting documentation. Runbooks are formally documented procedures to provide guidance in resolving specific incidents and ensuring the appropriate outcomes.  These procedures help to establish consistent and prompt responses to well-understood events.  Runbooks also help to define common SAP operational processes. It's important to establish Runbook version management and ensure a regular review cycle to keep it current and up-to-date. 
#### Tools
Runbooks for SAP landscape operations
## Task 5: Subtask 1: Create operational run-books for System Refresh
#### Description

## Task 5: Subtask 2: Create operational run-books for DR Testing
#### Description

## Task 5: Subtask 3: Create operational run-books for HA failover
#### Description

## Task 5: Subtask 4: Create operational run-books for OS security patching
#### Description
Create /Update Run books to apply security patches for OS, application and database.
## Task 5: Subtask 5: Create operational run-book for SAP patching and updates:
#### Description
Create run books for SAP Kernel Upgrades,  Support Packs,  Database Patches