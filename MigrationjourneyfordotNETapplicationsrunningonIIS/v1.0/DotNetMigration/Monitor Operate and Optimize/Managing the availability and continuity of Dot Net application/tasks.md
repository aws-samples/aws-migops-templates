
# Module: Managing the availability and continuity of Dot Net application
## Task 1: Set up back up solution for your application
#### Description
Building cloud-enabled backup solutions requires careful consideration of existing technology investments, recovery objectives, and available resources. Timely restoration after disasters and security events will help you maintain system availability and business continuity. Back up your data and documentation according to a defined schedule.
#### Tools
AWS Backup
#### Acceptance Criteria
•	Implemented a back up solution for the data
•	Tested the backup and restore process 

## Task 1: Subtask 1: Identify and implement a suitable back up solution
#### Description
Assess your applications to determine what data has to be backed up and the frequency of the back up and implement a back up solution accordingly
## Task 1: Subtask 2: Test and monitor back up process at regular intervals
#### Description
After the backup solution is setup, test it to check if back up is successful and restore is working smoothly.
## Task 2: Implement a Disaster Recovery (DR) strategy
#### Description
Identify the threat, risk, impact, and cost of different disaster scenarios for each workload and specify Recovery Time Objectives (RTOs) and Recovery Point Objectives (RPOs) accordingly. Implement your chosen disaster recover strategy leveraging multi-AZ or multi-Region architecture. Consider leveraging chaos engineering to improve resiliency and performance with controlled experiments. Review and test you plans regularly and adjust your approach based on lessons learned.
#### Tools
AWS Resilience Hub
#### Tools
AWS Backup
#### Tools
AWS Elastic Disaster Recovery (DRS)
#### Acceptance Criteria
•	Defined the RTO/RPO 
•	Architected and implemented the Disaster Recovery (DR) solution
•	Conducted drills for the implemented DR solution
•	Created and reviewed the business continuity plan (BCP)
## Task 2: Subtask 1: Identify the threat, risk, impact, and cost of different disaster scenarios for each workload
#### Description

## Task 2: Subtask 2: Specify Recovery Time Objectives (RTOs) and Recovery Point Objectives (RPOs) based on business requirements
#### Description

## Task 2: Subtask 3: Implement your chosen disaster recovery strategy
#### Description
Leverage  multi-AZ or multi-Region architecture to implement the disaster recovery.
## Task 2: Subtask 4: Perform Disaster Recovery drills
#### Description
Leverage chaos engineering to improve resiliency and performance with controlled experiments and drills.
## Task 2: Subtask 5: Review and test the business continuity plan (BCP) regularly
#### Description
Review test plans regularly and adjust your approach based on lessons learned.