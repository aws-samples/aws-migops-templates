
# Module: Update launch plan checklist and execute
## Task 1: Ensure that the list of who will work on go-live is up to date
#### Description
The following resources are required for go-live and you will see them in the attachments tab based on decisions taken in the Mobilize phase. 

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
Designers
Developers
Customer - EDW
Developers
#### Acceptance Criteria
â€¢ Fill out the details in a spreadsheet and upload them as attachments to the journey. Ensure that you communicate with these stakeholders on potential go-live dates and give them a heads-up. 
## Task 2: Update the go-live checklist if required
#### Description
Diligently following the go-live checklist ensures migration success. For each subtask, ensure that you have a single-threaded owner (STO) responsible for it, collect ongoing status for each item (go or no-go), jot down priority (low, medium, or high), and add any notes if required. You will see the checklist in the attachments tab based on decisions taken in the Mobilize phase.
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment. 
## Task 2: Subtask 1: Update WS and carrier validation if needed
#### Description
Check and update details on the following: 

•	AWS account team on standby  
•	Amazon Connect service-limits increase verified  
•	Telephony carrier scheduled for forwarding main number to Amazon Connect  
•	One Inc team on standby  
•	CRM integration team on standby  
#### Acceptance Criteria
â€¢ If there are any changes to decisions made in the Mobilize phase, ensure that the latest decisions are recorded and uploaded as attachments.   
## Task 2: Subtask 2: Update launch communication plan if needed
#### Description
•	Situation room bridge  
•	Feedback plan - How will CSRs and supervisors report issues?  
  
  Issue template:  
  time of call: {}, caller ANI: {}, CSR username: {}, issue details, screenshots
  
•	Process for bug fixes
#### Acceptance Criteria
â€¢ If there are any changes to decisions made in the Mobilize phase, ensure that the latest decisions are recorded and uploaded as attachments.  
## Task 2: Subtask 3: Integration testing updates
#### Description
•	X API integration verified  
•	Y API integration verified  
•	Z API integration verified  
•	CRM API integration verified  
•	WFM API integration verified  
•	Conditions tested (holiday, emergency, temp message, after hours)  
•	Dynamic message updates tested  
•	Call transfers to external tested  
•	Call transfers to queue tested  
•	Deployment code pipeline tested  
•	ANY test configurations removed from production 
#### Acceptance Criteria
â€¢ If there are any changes to decisions made in the Mobilize phase, ensure the latest decisions are recorded and uploaded as attachments. 
## Task 2: Subtask 4: UAT testing updates
#### Description
•	Production agents loaded into Amazon Connect  
•	Connectivity testing complete (headsets, desktops taking calls)  
•	X self-service flow tested under all conditions  
•	Y flow tested under all conditions  
•	Z flow tested under agent and customer  
•	Callback in queue tested  
•	Test supervisor live monitoring and call recording access  
•	Agent transfers tested (legacy, external, queue transfers)  
•	All DID and TFNs tested  
#### Acceptance Criteria
â€¢ If there are any changes to decisions made in the Mobilize phase, ensure that the latest decisions are recorded and uploaded as attachments.
## Task 2: Subtask 5: Training status updates
#### Description
•	Agent training complete (CRM, Amazon Connect CCP)  
•	Supervisor training complete (live monitoring, dashboards, reports)  
•	Operational training complete (Amazon CloudWatch dashboards, support plan/responsibilities, etc.) 
#### Acceptance Criteria
â€¢ If there are any changes to decisions made in the Mobilize phase, ensure that the latest decisions are recorded and uploaded as attachments.    
## Task 2: Subtask 6: Monitoring updates 
#### Description
•	Amazon CloudWatch dashboards verified  
•	Amazon Connect metrics dashboards verified  
•	Amazon CloudWatch alarm thresholds verified and tested  
•	Call recordings verified  
•	Dashboards in legacy to monitor transfers verified  
•	AWS Config - if applicable  
•	AWS CloudTrail - if applicable  
•	Contact flow logs generated in Amazon CloudWatch  
•	Lambda logs generated in Amazon CloudWatch 
#### Acceptance Criteria
â€¢ If there are any changes to decisions made in the Mobilize phase, ensure that the latest decisions are recorded and uploaded as attachments.  
## Task 2: Subtask 7: Reporting updates
#### Description
Validate scheduled reports and test calls in production.
#### Acceptance Criteria
â€¢ If there are any changes to decisions made in the Mobilize phase, ensure that the latest decisions are recorded and uploaded as attachments.  
## Task 3: Launching with self-service
#### Description
This task enables planning to launch the contact center solution in Amazon Connect with self-service and plans cutover for POC. All checklists are available in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect)
## Task 3: Subtask 1: Plan a day during cutover window to launch with self-service and cutover 
#### Description
•	Send test calls for self-service  
•	Verify monitoring and metrics for customer self-service transactions  
•	Record everything that goes well and everything that doesn't go well. If work is disrupted, move to the rollback plan. 
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment.
#### Acceptance Criteria
â€¢ Add all details as comments in the task or create a working spreadsheet and upload it as an attachment.  
## Task 3: Subtask 2: Launch with agents
#### Description
All checklists are available in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect).  

•	Have agents log in to Amazon Connect and appear available in the dashboard  
•	Send a test call into the Amazon Connect number and verify that the call goes to the agent successfully  
•	Verify that the call is received in Amazon Connect  
•	Verify that the call record is written to Amazon S3  
•	Verify that the call is recorded  
•	Verify that the call and agent events are sent to the WFM system  
•	Verify that the carrier forwards the number to Amazon Connect {carrier?, how many numbers?}  
•	Verify that the call is received in Amazon Connect  
•	Verify that the call record is written to Amazon S3  
•	Verify that the call is recorded  
•	Verify that the call and agent events are sent to the WFM system  
•	Verify that the CTRs are found and that they contain all required attributes, queue info, etc.  
•	Continue monitoring the dashboard for metrics  
•	Feedback from agents and supervisors 
## Task 3: Subtask 3: Rollback planning
#### Description
Use the following procedure to roll lback if there are issues: 

•	Determine criteria: For example, if critical issues cannot be resolved in 4 hours  
•	Revert phone number forwarding back to the legacy system  
•	Update legacy agent speed dials  
•	Agents log back in to  the legacy system 
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
## Task 4: Security Checklist
#### Description
Record the name of the responsible person, status, priority, and any notes for each of the following items: 

•	Enabling default encryption on Amazon DynamoDB  
•	Uploading your public key to Amazon Connect to encrypt collected sensitive information  
•	Testing of secure IVR flow and ensuring that credit card entries are encrypted  
•	Securely storing the decryption keys into AWS Systems Manager Parameter Store  
•	Tightening S3 bucket permissions and creating a list or permission set of who has access to be informed on the customer side  
•	Restricting public access to the S3 bucket  
•	Enabling service-level logging for detection  
•	Enabling AWS KMS keys for Amazon Kinesis resources for Amazon Connect data streaming  
•	S3 bucket policies

#### Acceptance Criteria
â€¢ Ensure that a list of links is uploaded to the platform as comments or as an attachment. 