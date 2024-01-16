
# Module: MHO - Perform migration wave 1
## Task 1: Validating source environment
#### Description
Validating source environment. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Validated source environment
## Task 2: Installing AWS Replication Agent and waiting for replication to complete.
#### Description
Install AWS Replication Agent and complete replication. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Installed AWS Replication Agent
#### Acceptance Criteria
• Completed replication
## Task 3: Updating the launch role.
#### Description
Update the launch role. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Launch role updated
## Task 4: Marking the instance 'Ready for test'.
#### Description
Mark the instance ready for test. This task is manual.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Mark the instance ready for test
## Task 5: Launching a test instance.
#### Description
Launch a instance ready for test. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Launch a instance
## Task 6: Testing the replicated instance.
#### Description
Test the replicated instance. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Tested the replicated instance
## Task 7: Marking the instance 'Ready for cutover'
#### Description
Marking the instance 'Ready for cutover'. This task is manual.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Mark the instance 'Ready for cutover'
## Task 8: Starting the cutover
#### Description
Starting the cutover. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Started the cutover
## Task 9: Validating the cutover readiness
#### Description
Validating the cutover readiness. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Cutover readiness validated.
## Task 10: Completing the cutover to AWS
#### Description
Completing the cutover to AWS. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Cutover completed.
## Task 11: Archive the server replication task
#### Description
Archive the server replication task. This task is automated.
#### Tools
Rehost applications on Amazon EC2
#### Acceptance Criteria
• Archive the server replication task.