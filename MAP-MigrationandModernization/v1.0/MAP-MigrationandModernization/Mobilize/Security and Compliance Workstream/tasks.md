
# Module: Security and Compliance Workstream
## Task 1: Security and Compliance Immersion Day
#### Description
1. Engage AWS Solution Architect to plan and conduct the AWS Security and Compliance Immersion Day.

2. The AWS Security and Compliance Immersion Day should cover the below areas :-
*  [AWS Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/).
*  [AWS Security and Compliance Services](https://aws.amazon.com/products/security/).
*  [AWS Security and Compliance Maturity Development Best Practices ](https://docs.aws.amazon.com/prescriptive-guidance/latest/strategy-accelerating-security-maturity/introduction.html).
*  [AWS Security and Compliance Mobilization Best Practices](https://docs.aws.amazon.com/prescriptive-guidance/latest/strategy-migration/security-risk-and-compliance.html).
*  [AWS Compliance Programs](https://aws.amazon.com/compliance/programs/).
*  AWS Security and Compliance Validation and [Penetration Testing](https://aws.amazon.com/security/penetration-testing/).

3. The objective of the Immersion Day is to baseline the customer's understanding on AWS Security and Compliance services, capability, requirement and best practices to accelerate the security and compliance planning and implementation task.
#### Acceptance Criteria
1. Completion of the AWS Security and Compliance Immersion Day.
2. Customer aligned and possess good understanding on AWS Security and Compliance services, capability, requirement and best practices.
## Task 2: Security and Compliance Planning and Implementation
#### Description
1. Activities to accelerate security and compliance planning and implementation are as below :- 

* Security, Risk and Compliance Assessment.
* Security, Risk and Compliance Framework Mapping, Design and Alignment.
* Security, Risk and Compliance Implementation, Integration and Validation.
* Security Operations and Continuous Governance. 

2. Leverage [Mobilize offering delivery kits](https://apg-library.amazonaws.com/content/67f8c788-8100-4dd1-a87d-c66fe5d0ee27#) to guidance for the security, risk and compliance detail planning areas.

3.  [AWS Migration Lens Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/migration-lens/migration-lens.html) when planning and implementing AWS security and compliance 
#### Acceptance Criteria
1. Successful security, risk and compliance assessment.
2. Successful security, risk and compliance framework mapping, design and alignment.
#### Acceptance Criteria
3. Successful security and compliance implementation, integration and validation.
4. Successful security operations and continuous governance.
## Task 2: Subtask 1: Security, Risk and Compliance Assessment
#### Description
1. Leverage a discovery workshop format to collect customers Security, Risk and Compliance information as below :-
*  Requirements
*  Processes
*  Controls
*  Policies 
*  Tooling
*  Regulatory
*  Operational Integrations (DevSecOps)
*  Configuration Management 
*  Change Management Process
*  Security and Compliance Roadmap
*  Current Security and Compliance Challenges
*  Security Reference Architecture
*  Security, Risk and Compliance Documentation

2. Leverage a standardize data collection template with questionnaire to collect the above information.

3. Discovery data collection template should collect Security, Risk and Compliance information with reference to the below 6 epics :-
*  Infrastructure Protection
*  Data Protection
*  Incident Detection and Response
*  Identity Access and Management
*  Security Controls
*  Workload Specific Requirements

4. Leverage the [AWS Migration Security Checklist (MSR)](https://partnercentral.awspartner.com/partnercentral2/s/resources?Id=0698W0000104I0ZQAU) and [AWS Well Architected - Migration Lens ](https://docs.aws.amazon.com/wellarchitected/latest/migration-lens/migration-lens.html) and [AWS Secure Migrations Framework](https://docs.aws.amazon.com/prescriptive-guidance/latest/secure-migrations-framework/introduction.html) as guidance when collecting the above information.

5. Understand the customer Security, Risk and Compliance appetite or change threshold to adequately plan ability to change for the cloud.
#### Acceptance Criteria
1. Successful collection of required customer's Security, Risk and Compliance information to successfully plan the Cloud Security Architecture and Posture.
## Task 2: Subtask 2: Security, Risk and Compliance Framework Mapping, Design and Alignment
#### Description
1. Review discovered Security, Risk and Compliance Information collected from the Security Discovery Workshop.

2. Leverage the Security Framework Mapping Template Document to define, map, validate and document requirements of the 6 security epics from the below lens :-
* People
* Processes
* Controls
* Policies
* Tooling
* Operational Integrations (DevSecOps)
* Security Reference Architecture

3. Security, Risk and Compliance Framework Mapping will be executed through targeted security epic workshop with the customer stakeholders.

4. Data from the Security Framework Mapping Workshops will be used to design and document  the customers Cloud Security Reference Architecture and Cloud Security Operating Model .

5. Leverage the [AWS Security Reference Architecture (SRA)](https://docs.aws.amazon.com/prescriptive-guidance/latest/security-reference-architecture/welcome.html), [AWS Well Architected Framework Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) and [AWS Security Whitepaper ](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/welcome.html) as references for AWS Security Best Practices during the cloud security design and posture building.

6. Define AWS Security Baseline to enforce standardize account and workload security and compliance. When defining the AWS Security Baseline ensure to leverage the [AWS Security Startup Baseline](https://docs.aws.amazon.com/prescriptive-guidance/latest/aws-startup-security-baseline/welcome.html) prescriptive guidance for definition requirements and best practice guidance.

7. Leverage the [AWS Compliance Center ](https://aws.amazon.com/financial-services/security-compliance/compliance-center/) for regulatory compliance guidance when designing Cloud Security Reference Architecture.

8. Security Change Management process update definition and documentation.

9. Define Security Validation process and coverage areas.  Ideally Security Validation should cover the below areas :- 
*  **Workload Specific Vulnerability Assessment / Penetration Testing** - Validate Operating System, Application, Database or Network security of workloads running on AWS Services. Leverage existing defined tools and test scripts and ensure compliance to [AWS Penetration Testing Guidelines](https://aws.amazon.com/security/penetration-testing/) when carrying out these assessments.
*   **AWS Security Best Practice Validation** - Validate if AWS implementation complies to AWS Well Architected Framework and other selected benchmarks like Center for Internet Security (CIS). Leverage the [AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/), [Prowler](https://aws.amazon.com/blogs/security/use-aws-fargate-prowler-send-security-configuration-findings-about-aws-services-security-hub/), [Service Screener](https://github.com/aws-samples/service-screener-v2), [Self-Service Security Assessment](https://github.com/awslabs/aws-security-assessment-solution) or any other AWS Marketplace ISV tooling that can assist the validation criteria.
#### Acceptance Criteria
1. Successful completion of Security, Risk and Compliance Framework Mapping Workshops.
2. Successful definition, design and documentation of Security Reference Architecture and Security Operating Model.
## Task 2: Subtask 3: Security and Compliance Implementation, Integration and Validation
#### Description
1. Security, Risk and Compliance team readiness (enablement) and changes to implement, validate and establish continuous governance of security and compliance in the cloud.

2. Adjustment of Security, Risk and Compliance threshold and risk register. 

3. Security, Risk and Compliance Change Management process enforcement.

4. Security Architecture Component rollout and enforcement as per the defined processes, baseline, policies, controls and tools in the below order :-
*  **Platform Security** - Landing Zone, Account Security, Network Security, Platform Level Identity and Access Control, Security Baseline, Platform Level Logging, Monitoring and Alerting
*  **AWS Services** -  Instance/Service Security Protection, Network Security, Instance Level Identity and Access Control , Encryption, Updates and Patch management, Instance/Service Level Logging, Monitoring and Alerting.
*  **Operating System (OS)** - Antivirus, Malware and Worms Protection, Security Configuration, Network Security, Operating System (OS) Level Identity and Access Control , Encryption, Updates and Patch management, Operating System (OS) Level Logging, Monitoring and Alerting.
* **Application /Databases (DB)** - Security Configuration, Code/Schema Security,  Application/DB level Identity and Access Control, Encryption, Updates and Patch management, Application/DB Level Logging, Monitoring and Alerting.

	*Note: This is executed in parallel with Landing Zone Deployment, Workload Migration and Operating Model Implementation.*

5. Rollout and enforce defined security and compliance processes, baseline, policies, controls and tools at the below integration areas :-
* **Networking** - Network within and external to the AWS Cloud.
* **Hybrid IT Landscape** - IT Environments besides AWS Cloud example On-Premises, Public Clouds, Private Clouds, Colocations.
* **External Softwares or Service**s - Softwares and Services by Independent Software Vendors (ISV) that are not self managed by the customers and hosted externally from the customers environment.
* **Cloud Operating Model** - Integration with the AWS Cloud Operating Model Services to provide DevSecOps capability.

	*Note: This is executed in parallel with Landing Zone Deployment, Workload Migration and Operating Model Implementation.*

6. Rollout and enforcement Security, Risk and Compliance validation process.

7. Security and Compliance implementation and runbook documentation.
#### Acceptance Criteria
1. Successful implementation and enforcement of Security, Risk and Compliance processes, baseline, policies, controls, configuration as per the defined Security Reference Architecture and Security Operating Model.
## Task 2: Subtask 4: Security Operations and Continuous Governance
#### Description
1. Conduct the below post implementation security and compliance sessions :-
*   Security and Compliance implementation and operations knowledge transfer sessions 
*   Security and Compliance Implementation Documentation and Runbook Handover Session.

2. Ensure the security operations team is capable and is practicing continuous security and compliance monitoring and event management based on the defined process.

3. Ensure the security operations team is capable in handling event management based on the defined process.

4. Ensure and enforce Security and Compliance validation is planned as per the customers internal and external audit requirements. Validation should comply to the [Well Architected Framework Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) and Migration Security Requirement (MSR) Checklist.

	*Note : Plan to conduct Well Architected Review and Security Vulnerability Assessment Audits at least once Bi-Quarterly if there are no customer requirements on audit frequency.*
#### Acceptance Criteria
1. Successful validation and enforcement of continuous monitoring and event management by Security Operations Team to ensure continuous governance.