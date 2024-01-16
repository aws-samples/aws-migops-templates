
# Module: Re-host dot net application using AWS Application Migration Service
## Task 1: Pre-requisites
#### Description
Setup pre-requisites
#### Acceptance Criteria
• The required IAM roles and policies are created.
#### Acceptance Criteria
• The required templates are configured.
## Task 1: Subtask 1: Initialize AWS MGN using the AWS Console
#### Description
AWS Application Migration Service (AWS MGN) must be initialized upon first use from within the
    AWS MGN console by creating a replication template. https://docs.aws.amazon.com/mgn/latest/ug/mgn-initialize-console.html  
## Task 1: Subtask 2: Create the replication template 
#### Description
Follow the steps on this page  to create the replication template https://docs.aws.amazon.com/mgn/latest/ug/mgn-initialization-templates.html 
## Task 1: Subtask 3: Alternatively, Initialize AWS MGN using the API
#### Description
To initialize AWS MGN using the API, follow the steps described on this page https://docs.aws.amazon.com/mgn/latest/ug/mgn-initialize-api.html 
## Task 1: Subtask 4: Optionally configure remote access to worker machine if running the tool remotely and not on the application server
#### Description

## Task 2: First time setup
#### Description
 
#### Acceptance Criteria
• Replication template is successfully created.
## Task 2: Subtask 1: Follow the steps on this page for the first time setup https://docs.aws.amazon.com/mgn/latest/ug/first-time-setup-gs.html
#### Description

## Task 3: Add source servers 
#### Description
 
#### Acceptance Criteria
• Each server is in Ready for testing status.
## Task 3: Subtask 1: Follow the steps on this page to add source servers https://docs.aws.amazon.com/mgn/latest/ug/adding-servers-gs.html
#### Description

## Task 4: Configure launch settings 
#### Description
 
#### Acceptance Criteria
• Launch settings successfully modified to fit application(s) need.
## Task 4: Subtask 1: Follow the steps on this page to configure launch settings https://docs.aws.amazon.com/mgn/latest/ug/configuring-target-gs.html
#### Description

## Task 5: Launch test instance 
#### Description
 
#### Acceptance Criteria
• Each source server successfully tested.
## Task 5: Subtask 1: Follow the steps on this page to launch test instance https://docs.aws.amazon.com/mgn/latest/ug/launching-test-gs.html
#### Description

## Task 6: Launch a cutover instance 
#### Description
Follow the steps on this page to launch a cutover instance https://docs.aws.amazon.com/mgn/latest/ug/launch-cutover-gs.html
#### Acceptance Criteria
• Successfully cutover server marked as archived.
#### Acceptance Criteria
• Cutover for each source sever successfully completed.
## Task 6: Subtask 1: Follow the steps on this page to launch a cutover instance https://docs.aws.amazon.com/mgn/latest/ug/launch-cutover-gs.html
#### Description
