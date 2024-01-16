
# Module: Optimize SAP environment on AWS
## Task 1: Optimize AWS resources based on SAP utilization
#### Description
Scale up resources only when needed, rather than scaling up or out months or quarters ahead of an actual business need. Start with the smallest possible computing capacity. It’s easy to add capacity later and resize before business processes change or before new processes go live in the environment. Auto scaling up and out brings additional benefits because it’s an automatic response to current conditions and usage patterns.
Designing for easy scale-up also includes configuring the SAP HANA database and the SAP instances to dynamically adjust the amount of memory used or number of work processes depending on available resources in the virtual machine (VM). Keep the instance design simple: One SAP instance per VM.
#### Tools
AWS Right Sizing
#### Tools
AWS Trusted Advisor
#### Tools
AWS Compute Optimizer
## Task 2: CleanUp Unnecessary Resources
#### Description
Clean-Up Unused resources
S3 Buckets , EFS, Temporary Migration Backups, Binaries.
Test SGs,

## Task 3: Run SAP Well Architected Framework (SAP Lens) on a schedule
#### Description
The SAP Lens is based on insights that AWS has gathered from customers, AWS Partners, and our SAP specialist community. The lens has been designed to help you adopt a cloud native approach to running SAP. It highlights some of the most common areas for improvement, aligned to the six pillars of the AWS Well-Architected Framework — operational excellence, security, reliability, performance efficiency, cost optimization, and sustainability.
#### Tools
 SAP Lens JSON file
#### Tools
SAP Lens - AWS Well-Architected Framework
#### Acceptance Criteria
• Generated Assessment Report with findings and recommendations for customer