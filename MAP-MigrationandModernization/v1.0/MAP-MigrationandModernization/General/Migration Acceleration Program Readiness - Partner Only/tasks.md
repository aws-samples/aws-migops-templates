
# Module: Migration Acceleration Program Readiness - Partner Only
## Task 1: MAP Funding Preparation and Qualification
#### Description
These tasks are intended to help AWS partners accelerate MAP funding submission and claim.
#### Tools
AWS Partner Funding Portal (APFP)
#### Acceptance Criteria
1. Successful understanding of processes and requirements for the MAP funding submission and claim process.
2. Successful preparation of the pre-requisite required for the MAP funding submission and claim process.
## Task 1: Subtask 1: Migration Acceleration Program (MAP) Guidance
#### Description
1. Understand the Migration Acceleration Program (MAP) funding benefits and AWS Partner Funding Portal prior to qualifying or applying for the AWS Migration Acceleration Program (MAP) Funding. Review the below guides on AWS Partner Central :-

* [AWS Partner Funding Benefits Guide - English](https://partnercentral.awspartner.com/partnercentral2/s/resources?Id=0690h000008hPVmAAM)
* [AWS Partner Funding Portal (APFP) User Guide - English](https://partnercentral.awspartner.com/partnercentral2/s/resources?Id=0698a00000DzyJrAAJ)
* [MAP Cash Fund Request Approval Flow](https://partnercentral.awspartner.com/partnercentral2/s/article?category=Funding_Operations_and_Management&article=MAP-Cash-Fund-Request-Approval-Flow)
	 
	 *Note the above guides are also available on AWS Partner Central in other languages and have been updated to reflect to MAP 2024 changes.*
	 
2. Recommended to undergo the 2024 Migration Acceleration Program (MAP) Update Session for Partners [[Session]](https://explore.skillbuilder.aws/learn/course/internal/view/elearning/19626/aws-partnercast-2024-migration-acceleration-program-map-pre-launch-updates-business) [[Slides]](https://partnercentral.awspartner.com/partnercentral2/s/resources?Id=0698W00000x4FtZQAU) to align on the program changes.

	*Note: Post guide reviews and enablement, you must update your current Migration and Modernization practice to reflect the new program changes especially in terms of program benefits, requirements and funding submission and approval process.* 
	
3. Start the Migration Acceleration Program (MAP) qualification process for the opportunity.
#### Tools
AWS Partner Funding Portal (APFP)
#### Acceptance Criteria
1. Awareness of the Migration Acceleration Program (MAP) benefits, updates and approval flow.
2. Completion of the migration and modernization practice update to reflect the Migration Acceleration Program (MAP) benefits and updates.
## Task 1: Subtask 2: Migration Scope Data Collection and Definition
#### Description
1. Work with the customer stakeholders to define the scope of the migration through a scoping workshop. It is important to include all application that will be migrated to the cloud within the next 24 months to be part of the Migration Acceleration Program (MAP) scope.  Please note, the Migration Acceleration Program (MAP) is signed for a period of 24 months hence to achieve greater benefits from the program a migration scope projection is required.

	*Note: Prior to the Assess Phase an initial scope should be defined and In the Mobilize Phase a more refined and confirmed scope should be defined prior to the signing of the Migration Acceleration Program (MAP) agreement letter.*
	
2. Leverage the [initial data collection prescriptive guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/understanding-initial-assessment-data-requirements.html) as the basis to define a standardize scoping questionnaire and a data collection template. If there is an existing data collection template defined ensure to align it with the data required in the initial data collection prescriptive guidance. This will ensure all data required for the migration and modernization scoping are adequately collected.

3. It is recommended to leverage the [Application Discovery Service Data Collection](https://docs.aws.amazon.com/application-discovery/latest/userguide/discovery-import.html) or the [Migration Portfolio Assessment Data Collection sheet](https://mpa.accelerate.amazonaws.com) to facilitate data collection where there is no pre-defined templates available. 

4. During the scoping workshop with the customer stakeholders, ensure the data collection sheet is collecting all required information especially covering the areas below :-  
* Modernization to AWS managed and native services.
* Migration and modernization of specialized workloads e.g. Databases, Data Analytics, Oracle and SAP. 
* Migration and modernization of VMWare workloads.

5. The migration and modernization scope defined will be used to build an optimize AWS cost to qualify the opportunity for the Migration Acceleration Program (MAP). Refer to the AWS Cost Calculation and Optimization task for details on building this optimized AWS cost.

6. Align the MAP migration and modernization scope with AWS for AWS Migration Acceleration Program (MAP) qualification :- 
* Business Alignment - AWS Partner Sales Manager (PSM), Partner Migration Program (PMP) lead and Migration Business Developer (BD).
* Technical Alignment - AWS Solution Architect.

7. Ensure the migration and modernization scope is aligned with AWS before Migration Acceleration Program (MAP) funding submission.

#### Acceptance Criteria
1. Completion of migration and modernization scope data collection.
2. Alignment with AWS on the migration and modernization scope.
3. Scope qualified for AWS Migration Acceleration Program (MAP).
## Task 1: Subtask 3: AWS Cost Calculation and Optimization
#### Description
1. Calculate the AWS cost of the resources that are part of the Migration Acceleration Program (MAP) migration and modernization scope leveraging the [AWS Pricing Calculator](https://calculator.aws/) or equivalent tooling or templates. The recommended tool is to leverage the AWS Pricing Calculator. 

	*Note: The optimized AWS cost calculation is required to qualify the opportunity for the Migration Acceleration Program (MAP).*

2. Ensure the calculated AWS Cost is optimized using the below general recommended guidance :-
*  Right-size instance based on specification peak utilization. In the absence of peak utilization values, consider to leverage AWS Migration Portfolio Assessment (MPA) default values ( 24% for CPU Peak Utilization, 59% for Memory Peak Utilization and 50% for Utilized Storage) as initial estimates.  
*  Consider Core Licensing requirements when right-sizing for Bring Your Own License (BYOL).
*  Set uptime based on environment and purchase the right pricing model based on the utilization. For instance uptime above 70% purchase Reserve Instance or Savings Plan.
*  Purchase of Savings Plan or Reserve Instance preferable No Upfront for a period of 1 to 3 years. However, this will vary depending on the budget allocated for the migration. 
*  Select the most cost effective storage service and type to leverage.  A list of AWS storage services and types can be found [here](https://aws.amazon.com/products/storage/).

3.  General guidance for initial AWS Cost optimization are as below. Please note the below assumptions are ONLY to be use to qualify the opportunity for the Migration Acceleration Program (MAP) where limited source data information are available else used to obtain source information for right-sizing and right-pricing.

    **For compute mainly EC2 - non production**
* If the resource uptime is 30%, leverage on-demand instances.
* If the resource uptime is 100%, leverage Reserve Instance or instance Savings plan for a period of 1 or 3 years.

    **For compute mainly EC2 - disaster recovery**
* Set the resource uptime to 2% and leverage on-demand instances.

    **For compute mainly EC2 - production**
* Set the resource uptime to 100% and leverage Reserve Instance or instance Savings plan for a period of 1 or 3 years.

    **For database mainly RDS - non production**
* Leverage Reserve Instance.
* Leverage Single-AZ setup.

    **For database mainly RDS - non production**
* Leverage Reserve Instance.
* Leverage Multi-AZ setup

    **For EBS volumes**
* Leverage gp3 volume types unless there are specific requirements.

    **For Backup storage**
* Leverage S3 and Glacier unless there are specific requirements.

4. It is recommended to define cost by application groups within the AWS Pricing Calculator or other relevant tooling or templates used. Within each application groups it is also important to further group the resources by specialized workloads e.g. VMWare, Database, Data Analytics, SAP or Oracle workloads. This is to ease the calculation of the Migration Acceleration Program (MAP) funding payables.

5.  Work with your AWS Solution Architect to review and further optimize the AWS calculator cost especially when it is a large Migration Acceleration Program (MAP) engagement and when the engagement includes Modernization services or target service complexities. 
#### Tools
AWS Calculator
#### Acceptance Criteria
1. Successful build of initial optimize AWS cost leveraging AWS calculator or equivalent tooling or templates.