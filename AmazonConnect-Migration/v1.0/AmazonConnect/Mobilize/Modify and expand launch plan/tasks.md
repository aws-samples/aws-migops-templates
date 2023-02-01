
# Module: Modify and expand launch plan
## Task 1: Update list of individuals who will work on go-live and communicate
#### Description
The following resources are required for go-live: 
Customer - Network
Escalations for firewall rules and access issues.
 
Customer - Call center 
Operations - @xxxx
Supervisors (escalated issues)
 
Customer - Reporting
Developers

Customer - SSO/ADFS
Security administrators

AWS
TAM, account manager, account SA
ProServe
Vendor - CRM


Vendor - WFM


Vendor - Other

Customer - IVR
designers
developers  

Customer - EDW
developers
#### Acceptance Criteria
â€¢ Fill out the details in a spreadsheet and upload it as an attachment. Ensure that you communicate with these stakeholders on potential go-live dates and give them a heads-up. 
## Task 2: Prepare the go-live checklist
#### Description
Diligently following the go-live checklist (download from [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect)) will ensure the success of the migration. For each subtask, ensure that you have a single-threaded owner (STO) responsible for it, collect ongoing status for each item (go or no-go), write down the priority (low, medium, or high), and add any necessary notes. 
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 1: WS and carrier validation
#### Description
Check and record details on the following:  

•	AWS account team on standby  
•	Amazon Connect service-limits increase verified  
•	Telephony carrier scheduled for forwarding main number to Amazon Connect  
•	One Inc team on standby  
•	CRM integration team on standby  
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 2: Launch communication plan
#### Description
•	Sitatuion room bridge  
•	Feedback plan: How will CSRs and supervisors report issues?  
  
  Issue template:  
  time of call:{}, caller ANI:{}, CSR username:{}, issue details, screenshots  

•	Process for bug fixes
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 3: Integration testing
#### Description
•	X API integration verified  
•	Y API integration verified  
•	Z API integration verified  
•	CRM API integration verified  
•	WFM API integration verified  
•	Conditions tested (holiday, emergency, temp message, after hours)  
•	Dynamic message updates test  
•	Call transfers to external tested  
•	Call transfers to queue  
•	Deployment code pipeline tested  
•	All test configurations removed from production 
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 4: UAT testing
#### Description
•	Production agents loaded into Amazon Connect  
•	Connectivity testing complete (headsets, desktops taking calls)  
•	X self-service flow tested under all conditions  
•	Y flow tested under all conditions  
•	Z flow tested with agent and customer  
•	Callback in queue tested  
•	Test supervisor live monitoring and call recording access  
•	Agent transfers tested (legacy, external, queue transfers)  
•	All DID and TFNs tested  
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 5: Training status
#### Description
•	Agent training complete (CRM, Amazon Connect CCP)  
•	Supervisor training complete (live monitoring, dashboards, reports).  
•	Operational training complete (Amazon CloudWatch dashboards, support plan and responsibilities, etc.)
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 6: Monitoring 
#### Description
•	Amazon CloudWatch dashboards verified  
•	Amazon Connect metrics dashboards verified  
•	Amazon CloudWatch alarms thresholds verified and tested  
•	Call recordings verified  
•	Verify dashboards in legacy to monitor transfers  
•	AWS Config if applicable  
•	AWS CloudTrail  if applicable  
•	Contact flow logs generated in Amazon CloudWatch  
•	Lambda logs generated in Amazon CloudWatch 
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 7: Reporting
#### Description
Validate scheduled reports and test calls in production. 
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment
## Task 3: Launching with self-service
#### Description
This task makes it possible to plan to launch the contact center solution in Amazon Connect with self-service and plans cutover for POC. All checklists are available in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect). 
## Task 3: Subtask 1: Plan a day during cutover window to launch with self-service and cutover 
#### Description
•	Send test calls for self-service.  
•	Verify monitoring and metrics for customer self-service transactions.  
•	Record everything that goes well and does not go well. If work is disrupted, move to the rollback plan. 
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment.
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment.  
## Task 3: Subtask 2: Launch with agents
#### Description
All checklists are available in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect).   

•	Checklist to make it possible for agents to log in and start working in Amazon Connect  
•	Ensure that agents log in to Amazon Connect and appear available in the dashboard  
•	Send test call into the Amazon Connect number and verify that the call goes to the agent successfully  
•	Verify that the call is received in Amazon Connect  
•	Verify that the call record is written to Amazon S3  
•	Verify that the call is recorded  
•	Verify that the call and agent events are sent to the WFM system  
•	Verify that the carrier forwards the number to Amazon Connect {carrier?, how many numbers?}  
•	Verify that the call is received in Amazon Connect  
•	Verify that the call record is written to Amazon S3  
•	Verify that the call is recorded  
•	Verify that the call and agent events are sent to WFM system  
•	Verify that the CTRs are found and that they contain all required attributes, queue info, etc.  
•	Continue monitoring the dashboard for metrics  
•	Obtain feedback from agents and supervisors
## Task 3: Subtask 3: Rollback planning
#### Description
The following is the procedure to rollback if there are issues: 

•	Establish criteria – for example, if a critical issue cannot be resolved in 4 hours  
•	Revert phone number forwarding back to legacy  
•	Update legacy agent speed dials  
•	Ensure that agents log back in to legacy 
## Task 3: Subtask 4: Dashboards and metrics to display
#### Description
The following dashboards must be up and running: 

•	Amazon CloudWatch dashboard - Amazon Connect system health  
•	Lex Analytics dashboard   
•	Amazon Connect metrics dashboard  
•	WFM dashboard? 
#### Acceptance Criteria
â€¢ Ensure that links are updated and a list is uploaded to the platform as comments or as an attachment. 
#### Acceptance Criteria
â€¢ Ensure links are updated and a list is uploaded to the platform as comments or as an attachment. 
## Task 4: Security checklist
#### Description
Ensure that you specify the person responsible, status, priority, and any notes for each of the following items: 

•	Enabling default encryption on Amazon DynamoDB  
•	Uploading our public key to Amazon Connect to encrypt collected sensitive information  
•	Testing secure IVR flow - credit card entries are encrypted  
•	Securely storing decryption keys used into AWS Systems Manager Parameter Store  
•	Tightening S3 bucket permissions - establishing a clear list or permission set to specify who has access to be informed on the customer side  
•	S3 bucket public access is turned off  
•	Turning on service-level logging for detection  
•	Enabling an AWS KMS key for Amazon Kinesis resources for Amazon Connect data streaming  
•	Setting S3 bucket policies  
#### Acceptance Criteria
â€¢ Ensure that a list of links is uploaded to the platform as comments or as an attachment. 