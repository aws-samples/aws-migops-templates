
# Module: Technical Architecture Infrastructure
## Task 1: Schedule System Go-Live checks
#### Description
Schedule Go-Live check 8 weeks before the Go-Live date

#### Tools
AWS Migration Evaluator
#### Tools
Portfolio playbook templates
#### Tools
AWS Migration Competency Partners
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• A list of application components prioritized based on the business and technical rules.
## Task 1: Subtask 1: Define the  application prioritization process
#### Description
There are three process options for prioritizing applications:

1) Manual complexity scoring: Use complexity scoring criteria to assess the difficulty of migrating each application
2) Application nomination: Application owners nominate applications for migration
3) Discovery tool: Define criteria within the parameters of the discovery tool, and then the tool analyzes the applications and provides a final  complexity score.For more information, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-portfolio-playbook/prioritization.html#prioritization-1)
#### Tools
AWS Application Discovery Service
#### Tools
AWS Migration Evaluator
#### Tools
AWS Migration Competency Partners
#### Tools
Portfolio playbook templates
#### Acceptance Criteria
•  Prioritization process based on discovery tools
## Task 1: Subtask 2: Define the application prioritization rules
#### Description
Define application prioritization rules, to determine the migration order of the applications. 

Create rules to assess the priority of each application so you can schedule the application in the appropriate wave. 

Common business and technology rules include the following:  
1) Specifying the order and schedule for migrating data centers  
2) Prioritizing business units  
3) Capturing deadlines for critical business applicationsFor more information, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-portfolio-playbook/prioritization.html#prioritization-2)
#### Tools
Portfolio playbook templates
#### Acceptance Criteria
•  Defined prioritization rules
## Task 1: Subtask 3: Finalize the application prioritization process
#### Description
Define how the  portfolio workstream uses the rules and processes to prioritize applications.  This is the process that the portfolio workstream references in the  implementation stage of the migration.
#### Tools
Portfolio playbook templates
#### Acceptance Criteria
• Finalized  process for prioritization
## Task 2: Sizing Verification
#### Description
Verify that the initial sizing details provided are still correct and also address any possible performance issues identified during performance testing, or increased data or load that was not initially captured.

## Task 3: Security & Audit Verification
#### Description
Engage customer internal security teams and audit partners in advance of Cutover, to verify all requirements have been met. Ensure there is enough lead time to apply remediations to ensure no impact to the Go-Live event and reduce risk of having security exceptions.

## Task 4: System Go-Live
#### Description
This is the checkpoint for Technical Architecture Infrastructure as a pre-condition for the final business sign-off for productive use.As part of this Go-Live process for brownfield systems, the system will be included into the productive monitoring. In brownfield scenarios, the PL will work with the CDM. In greenfield scenarios the PL will have rolled off the project after the initial system handover.
