
# Module: Portfolio Assessment
## Task 1: Portfolio Analysis and Migration Planning
#### Description
This first stage of assessment focuses on the initial steps of obtaining and analyzing data at the Portfolio Level. The main objective is to identify business drivers and collect general data from applications and infrastructure in order to obtain an initial view of the portfolio, including high-level technical and business attributes such as application names, environment, product versions, criticality, performance values, and others. This is key in order to understand the scope of the project, identify initial migration candidates, and inform the business case.
## Task 1: Subtask 1: Review Application Infrastructure Attributes and Data Requirements
#### Description
Capturing application and infrastructure metadata (regardless of the source) is an iterative approach. It can take several weeks to obtain the desired level of detail. The recommendation is to focus on the data that can be obtained now and to keep enriching the data set as more data become available. A full inventory list includes tooling, assessment process, prioritization, migration strategy, and wave planning. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
## Task 1: Subtask 2: Perform manual discovery workshops and activities if applicable
#### Description
In most environments there are cases where the discovery tool of choice doesnít support a given legacy system. Examples include old operating system versions and legacy platforms such as AS400 or Mainframe. If these systems are in scope for migration, recommend and perform manual discovery. This might require connecting to those systems directly, or the use of scripts that can be obtained from the discovery tooling vendor or platform teams or by specialized AWS practices. Conduct manual discovery workshops when necessary. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
## Task 1: Subtask 3: Review Asset and Dependency from Discovery Tooling Output
#### Description
This session is intended to review all available data and construct an initial inventory of applications and infrastructure and to identify gaps. For more information, see the Portfolio Data Collection Task.
## Task 1: Subtask 4: Identify Prioritized Applications and perform deepdive
#### Description
Analyze the applications at a high-level. The expected outcome is to agree on the contents of the first migration wave and plan for a detailed assessment of those applications. Document the list of applications in the linked artifact. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Prioritized-Applications-(wave-1-or-pilots).md)
## Task 2: Building Migration Waveplan
#### Description
The Prioritized Applications Assessment stage focuses on the detailed discovery of a subset of prioritized applications to produce an initial AWS architecture design and migration strategy. The strategy must take into account the estimated infrastructure run rate in AWS.
## Task 2: Subtask 1: Create first Draft for Prioritized Applications Architecture Design
#### Description
After the data is collected for the prioritized applications that are to be migrated to AWS, create a first draft of a prioritized applications architecture design. Document, at a high-level, the functional and non-functional requirements for this architecture.

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/2-Prioritized-Applications-Assessment/Template---Application-AWS-Architecture-Design-and-Migration-Strategy.md)

## Task 2: Subtask 2: Baseline 7R Disposition Tree
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure. 

When you establish a baseline for the portfolio, confirm a migration strategy for each application component. The migration strategy will be one of the 7 Rs for migration. A 7 R strategy must also be associated with each of the application's infrastructure components.
## Task 2: Subtask 3: Baseline Dependency Groups and Wave Plan
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure. Technical dependencies can be described in four categories: 1) Application-to-infrastructure 2) Application-component 3) Application-to-application 4) Application-to-infrastructure services 

For more information, see [Baseline Application Portfolio](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/baseline-application-portfolio.html.)
