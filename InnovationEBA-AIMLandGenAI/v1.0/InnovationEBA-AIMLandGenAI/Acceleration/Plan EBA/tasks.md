
# Module: Plan EBA
## Task 1: Validate Scope, Business Value and Success Metrics of Use Case
#### Description
1. Validate scope of EBA and business value delivered  (e.g. reduce attrition by X% to drive revenue growth of Y%, productivity gains from error reduction, etc). 
2. A use case with meaningful business impact AND path to production; should not be a “demo” for a broad audience to generate interest in GenAI or demonstrate technology.
3. Define and document success criteria for EBA. 
4. Ability to measure business value post implementation.
5. Define build vs buy approach (Amazon Q vs. Bedrock vs. SageMaker)

*(Owner: EBA and Tech Lead with customer alignment)*
#### Tools
Innovation EBA (AIML-GenAI) - Validate Scope & Business Value
## Task 2: Path to Production Deployment
#### Description
1. Document measurable acceptance testing criteria for the model.
2. Define target operational parameters for production deployment readiness. 
3. Governance and operational processes to continue to maintain and enhance the model. 
4. Stakeholder alignment plan to stand up the use case architecture, operating it and consuming the output.
5. Define guardrails for security and responsible use of AI.
6. Define legal and regulatory considerations.

*(Owner: EBA and Tech Lead with customer alignment)*
#### Tools
Innovation EBA (AIML-GenAI) - Validate Path to Production
## Task 3: Determine EBA Workstreams
#### Description
Target minimum workstreams to accomplish the EBA goals, typically 3-4 is sufficient. AIML-GenAI EBAs typically include Data Processing/Engineering, Model Engineering, MLOps and Command Center workstreams. 

* **Data Processing/Engineering Worstream** - Focuses on identifying data producers (or sources), data ingestion, data governance, filtering sensitive data, and integration with external data/analytics tools such as snowflake (using AWS Data Wrangler).
* **Model Engineering Workstream** - Core workstream that is focused on the AI/ML/GenAI model building, training, evaluation and tuning of the model.
* **AIML Ops Workstream** - Focuses on automation and pipelines for repeatable MLOps framework.
* **Command Center Workstream** - Address escalations or resource needs and facilitate cross-workstream interaction.

Depending on the scope of activities and personnel involved, workstreams can be combined or broken up into logical configurations.

*(Owner: EBA and Tech leads)*
#### Tools
Configuring Workstreams - Template
#### Acceptance Criteria
Attach completed slides in the attach file section.
## Task 4: Identify Workstream Participants & Their Roles
#### Description
* Complete the template with Customer and AWS names and roles for each workstream. Attach completed slide in the attach files section below.
* Review the Role definitions for an EBA and the RACI Guidance before filling out the template.

*(Owner: EBA Lead)*
#### Tools
Innovation EBA (AIML-GenAI) - Participant Template with RACI Guidance 
## Task 5: Define And Activate Cadence
#### Description
EBA Planning is a shared responsibility of customer, partner and AWS; success of the EBA depends on it.

**Suggested Candence:**
* **Sponsor** - 2-3 times during the EBA cycle - 1/ At the start for alignment and goal setting, 2/ End of planning phase to prepare for EBA kick off, 3/ During EBA for daily standups and demo, and 4/ Post EBA readout and next steps
* **EBA leads** - Daily standups or at least 2-3 times per week to monitor progress
* **WS Leads** - 3x/week or as needed to complete pre-work
* **Other** - SMEs and workstream leads should hold working sessions as needed to make progress leading up to the EBA

*(Owner: EBA lead drives key cadence)*

#### Acceptance Criteria
Planning calls scheduled on everyone's calendar.
## Task 6: Assess and Schedule Required Trainings
#### Description
Identify training/workshops/immersion days required for the customer team to: 1/ familiarize them with the AWS services required for the use case 2/ successfully execute the EBA and 2/ setup a fly wheel effect for continued momentum beyond the EBA. 

*(Owner: EBA and Tech Lead)*
## Task 7: Prepare Participants For EBA And Execute Pre-work
#### Description
* Meet with participants to review scope and specific assignments.
* Hold a EBA watch party for the EBA Foundations training and ensure all participants have taken the training.
* Hold immersion days/training session on AWS Services as needed.
* Identify all pre-work for each workstream and update the workstream activities sub-tasks.
* Tech lead identifies pre-requisites and ensures completion. 
* Complete pre-work through a strong collaboration between customer and AWS participants. 
**NOTE: Customer owns the activity, AWS provides guidance.**


*(Owner: EBA and Tech Lead)*
#### Tools
EBA Foundations Training
## Task 8: Foundations Workstream - Planning Activities
#### Description
Execute the foundational workstream activities to setup the account environment for the use case deployment during the EBA. (*Owner: Tech Lead)*
## Task 8: Subtask 1: Create AWS accounts with network and security set up
#### Description

## Task 8: Subtask 2: Provision IAM/SSO access
#### Description

## Task 8: Subtask 3: Engage legal and security (if needed) given the heavy use of data and use of AI
#### Description

## Task 8: Subtask 4: Define security guardrails
#### Description

## Task 8: Subtask 5: Setup SageMaker Studio/Jumpstart/BedRock/ Amazon Q (access, initial setup, infrastructure requirements,  etc.)
#### Description

## Task 8: Subtask 6: Setup supporting services such as Kendra, OpenSearch, etc.
#### Description

## Task 9: Data Engineering Workstream - Planning Activities
#### Description
Complete the pre-work for the workstream to deliver successfully on the EBA workstream objectives. Add/modify the sub-tasks as required.  *(Owner: Tech Lead)*
## Task 9: Subtask 1: Identify sources of data and integrate external sources to bring data into S3
#### Description

## Task 9: Subtask 2: Conduct preliminary assessment of Data Processing Activities
#### Description

## Task 9: Subtask 3: Select data technology tools
#### Description

## Task 9: Subtask 4: Define data ingestion, governance, filtering/masking process
#### Description

## Task 9: Subtask 5: Collect data – label, ingest (stream or batch) and aggregate data
#### Description

## Task 9: Subtask 6: Conduct Data Processing Activities – clean, partition, scale, un-bias, balance and augment
#### Description

## Task 10: Model Engineering Workstream - Planning Activities
#### Description
Complete the pre-work for the workstream to deliver successfully on the EBA workstream objectives. Add/modify the sub-tasks as required. *(Owner: Tech Lead)*
## Task 10: Subtask 1: Build/select algorithm
#### Description

## Task 10: Subtask 2: Test SageMaker sample notebooks relevant for the ML use case
#### Description

## Task 10: Subtask 3: Create RAG Langchain / orchestrator lambda; begin prompt engineering  (if applicable)
#### Description

## Task 10: Subtask 4: Define evaluation criteria (offline or online) as well as human feedback
#### Description

## Task 11: ML Ops Workstream - Planning Activities
#### Description
Complete the pre-work for the workstream to deliver successfully on the EBA workstream objectives. Add/modify the sub-tasks as required. Refer to the life cycle slides below for planning. *(Owner: Tech Lead)*
#### Tools
AIML-GenAI Life Cycle
## Task 11: Subtask 1: Integrate with external continuous integration and continuous deployment (CI/CD) tools such as Git or SonarQube.
#### Description

## Task 11: Subtask 2: Establish level of model explainability
#### Description

## Task 11: Subtask 3: Create knowledge bases (if applicable)
#### Description

## Task 11: Subtask 4: Review the MLOps framework solution library.
#### Description
[ML Ops Solution Library](https://aws.amazon.com/solutions/implementations/mlops-workload-orchestrator/)
## Task 12: Plan EBA Logistics
#### Description
* Plan EBA logistics (use attached checklist under subtasks).
* Develop and finalize EBA agenda (use attached template under subtasks).
* Attach the finalized agenda in the attach file section below.

*(Owner: EBA Lead)*
## Task 12: Subtask 1: Plan EBA logistics
#### Description

#### Tools
EBA Logistics Planning Checklist
## Task 12: Subtask 2: Develop and finalize EBA agenda
#### Description

#### Tools
EBA Agenda Template with Example