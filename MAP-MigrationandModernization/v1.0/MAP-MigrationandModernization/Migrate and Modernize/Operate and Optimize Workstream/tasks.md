
# Module: Operate and Optimize Workstream
## Task 1: Cost Optimization
#### Description
1. Perform an AWS cost analysis on the  application workload within 4 - 12 weeks post migration and modernization.

	*Note: Alternatively,  you could evaluate the need to run a [FinOps Experience-Based Acceleration (EBA)](https://aws.amazon.com/experience-based-acceleration/) to build standardize approach to cost optimization on AWS. It is recommended to run FinOps Experience-Based Acceleration (EBA) for a larger group of application rather than individual application hence the timeline of execution of the Experience-Based Acceleration (EBA) is critical.*

2. Leverage [AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/), [AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/) or any other partner tooling (preferably available on the [AWS Marketplace](https://aws.amazon.com/marketplace)) with right-sizing advisory capability to obtain the right-sizing recommendation and the optimize instance type based on utilization and usage patterns. 

3. Select an AWS pricing module and decide on the term of commitment based on the application roadmap.  For details and best practices on pricing modelling selection, leverage the [select the best pricing model ](https://docs.aws.amazon.com/wellarchitected/latest/cost-optimization-pillar/select-the-best-pricing-model.html) guidelines outlined under the [AWS Well Architected Cost Optimization Pillar](https://docs.aws.amazon.com/wellarchitected/latest/cost-optimization-pillar/welcome.html).

4. Brief the customer on the pricing model purchase and obtain commitment. 

5. Purchase and document the pricing model purchase under the application operation runbook documentation.

6. Ensure to purchase the pricing model at the account where the workloads are running as recommended in the [consolidated billing calculation process](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/con-bill-blended-rates.html#Calculation_Process).
#### Acceptance Criteria
1. Successful execution of the AWS cost optimization.
2. Successful purchase of pricing model as part of the AWS cost optimization activities.
## Task 1: Subtask 1: FinOps Experience-Based Acceleration (EBA)
#### Description
1. Evaluate the requirements to execute a [FinOps Experience Based Acceleration (EBA)](https://aws.amazon.com/experience-based-acceleration/) to accelerate the assessment of the current AWS cloud spend and build standardize mechanism and processes for cost optimization as part of the post migration process and financial governance for the cloud operating model.

2. Leverage the [Experience-based acceleration engagement delivery kit](https://apg-library.amazonaws.com/content/c33bd17e-da06-4701-8bd4-30e174c551a0) when evaluating, planning and executing the FinOps EBA.

3. Leverage the AWS Customer Solution Manager (CSM) and AWS Solution Architect support during the planning and executing of the EBA.
#### Acceptance Criteria
1. Successful FinOps Experience Based Acceleration (EBA) planning and execution.
2. Accelerated optimized cloud spend on AWS.
## Task 2: Performance Optimization
#### Description
1. Perform an AWS performance analysis on the application workload within 4 - 12 weeks post migration and modernization.

2. Under the AWS peformance analysis evaluate each migrated or modernize application on the below areas :-
* Sizing accuracy of the current AWS services.
* Scaling requirements, configuration and supportability of the applications.
* AWS service or feature suitability to meet performance requirements

3. For performance right-sizing accuracy, [AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/), [AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/) or any other partner tooling with right-sizing advisory capability to obtain the right-sizing recommendation and the optimize instance type based on utilization and performance usage patterns. 

4. For scaling requirements, first understand if the components of the application is stateful or stateless.
* **Stateless Application** - recommended to leverage horizontal scaling approach to meet performance requirements. [AWS Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html) and database sharding are good example of an horizontal scaling approach.
* **Stateful Application** - recommended to leverage vertical scaling to meet performance requirements.

5. For AWS service or feature suitability evaluate the below areas :- 
* **Serverless usage** - understand if the service can run serverless based on the application usage pattern and requirements
* **Purpose build services** - redesign application component to leverage purpose build service such as managed  container services, databases service and data store services.

6. Leverage the [AWS Well Architected Performance Efficiency Pillar](https://docs.aws.amazon.com/wellarchitected/latest/performance-efficiency-pillar/welcome.html) as guidance when carrying out the AWS performance analysis. 

7. Document the required changes from an architecture, service selection, configuration, and cost standpoint. Present the changes and obtain commitment from the customer to execute the changes.

8. Define a cutover and rollback plan to execute the changes.

9. Execute the changes and perform continuous monitoring on the impact of the changes from a performance and cost standpoint.

10. Adjust configuration or rollback in scenarios where the target performance are unmet. Document all changes as part of the application operation runbook.
#### Acceptance Criteria
1. Successful execution of the AWS performance optimization.
2. Ensure the architecture, service configuration, scaling option and resource type are optimized to meet application performance requirements and cost optimization requirements.
## Task 3: Continuous Governance
#### Description
1. Continue to monitor the AWS environment leveraging the monitoring tools deploy during the Operating Model Workstream. Obtain field feedback on areas of improvement through deployed ticketing system.

2. Based on field feedback and AWS Service updates continue to review and update current operation processes and AWS cloud practice.

3.  It is also recommended to Improve cloud observability by monitoring at an application code, function and business logic level. This can be implemented by leveraging application performance monitoring tools. Leverage the [AWS APM Guide](https://aws.amazon.com/what-is/application-performance-monitoring/) and [AWS partner tooling](https://docs.aws.amazon.com/wellarchitected/latest/management-and-governance-guide/integrated-observability-partners.html).

4. Continue to ensure the teams managing the AWS cloud are trained and certified leveraging  [AWS Training Portal](https://www.aws.training/) and [AWS Skillbuilder](https://skillbuilder.aws/).

5. Schedule and execute periodic Well Architect Reviews (WAR) atleast two times a year - 6 months apart.  It is also recommended to execute Well Architected Review when there are major updates from an AWS Architectural standpoint to the application. Leverage the [AWS Well-Architected documentation](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) and  [How to perform Well-Architected Framework Review](https://aws.amazon.com/blogs/mt/how-to-perform-a-well-architected-framework-review-part1/) as requirements and process reference when executing the Well Architected Framework Review. 

6. Continue to monitor AWS usage optimization leveraging [AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/), [AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/) or any other partner tooling with right-sizing advisory capability to obtain the right-sizing recommendation and the optimize instance type based on utilization and usage patterns.

#### Tools
AWS Compute Optimizer
#### Tools
AWS Trusted Advisor
#### Tools
AWS Well-Architected Framework
#### Acceptance Criteria
1. Successful establishment and enforcing of continuous governance and improvement gathering post migration and modernization.

#### Acceptance Criteria
2. Successful establishment of cloud observability to obtain in-depth insights to improve application features, functions, performance and cost.
3. Successful establishment of learning path and update sessions for resources managing the cloud.
#### Acceptance Criteria
4. Successful assurance of the AWS environment setup are complying to AWS Best Practices governed by the AWS Well Architected Framework.