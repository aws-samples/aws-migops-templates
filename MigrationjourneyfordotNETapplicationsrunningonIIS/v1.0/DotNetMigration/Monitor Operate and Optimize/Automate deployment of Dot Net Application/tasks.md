
# Module: Automate deployment of Dot Net Application
## Task 1: Automate provision of infrastructure to host .NET applications by creating AWS CloudFormation templates
#### Description
Leverage AWS CloudFormation to create and provision AWS infrastructure for your application predictably and repeatedly. 

You can start with an existing template or create a new template.  You can look at AWS Quick Starts, which are open-source and available on [GitHub](https://github.com/aws-quickstart). On the [AWS Quick Starts home page](https://aws.amazon.com/quickstart/?solutions-all.sort-by=item.additionalFields.sortDate&solutions-all.sort-order=desc&awsf.filter-content-type=*all&awsf.filter-tech-category=*all&awsf.filter-industry=*all), you can search the catalog by partner, product, or keyword, and you can filter by common use cases. Also look at [AWS Labs](https://github.com/awslabs), another open-source GitHub organization with a number of sample [AWS CloudFormation templates](https://github.com/awslabs/aws-cloudformation-templates) developed by AWS and by the community of AWS Partners and customers.
#### Tools
Best practices when automating your deployments with AWS CloudFormation
#### Tools
AWS CloudFormation
#### Acceptance Criteria
•	AWS CloudFormation templates are in place to automate the creation of AWS resources.
## Task 1: Subtask 1: Create template by writing code in either YAML or JSON format
#### Description
You can start with an existing template or create a new template.  You can look at AWS Quick Starts, which are open-source and available on [GitHub](https://github.com/aws-quickstart). On the [AWS Quick Starts home page](https://aws.amazon.com/quickstart/?solutions-all.sort-by=item.additionalFields.sortDate&solutions-all.sort-order=desc&awsf.filter-content-type=*all&awsf.filter-tech-category=*all&awsf.filter-industry=*all), you can search the catalog by partner, product, or keyword, and you can filter by common use cases. Also look at [AWS Labs](https://github.com/awslabs), another open-source GitHub organization with a number of sample [AWS CloudFormation templates](https://github.com/awslabs/aws-cloudformation-templates) developed by AWS and by the community of AWS Partners and customers.
## Task 1: Subtask 2: Define the AWS resources in the cloud formation template
#### Description

#### Tools
Template reference 
## Task 1: Subtask 3: Test the AWS CloudFormation template
#### Description
You can validate the AWS CloudFormation templates for syntactic errors with [AWS CloudFormation Linter](https://github.com/aws-cloudformation/cfn-lint) (cfn-lint) . Cfn-lint analyzes AWS CloudFormation templates and checks for syntactic errors.

You can use [TaskCat](https://aws-ia.github.io/taskcat/) to automate the  AWS CloudFormation testing. It deploys your AWS CloudFormation template in multiple AWS Regions and generates a report with a pass/fail grade for each region. 

#### Tools
AWS CloudFormation Linter 
#### Tools
TaskCat
## Task 1: Subtask 4: Create a stack based on the template code
#### Description

## Task 2: Automate provision of infrastructure to host .NET applications using AWS Cloud Development Kit (AWS CDK)
#### Description
Leverage AWS CDK to you write your infrastructure provisioning code in C#.  You can define cloud infrastructure in code using AWS Cloud Development Kit (AWS CDK) and provision it through AWS CloudFormation.

Refer the [AWS CDK Examples repository](https://github.com/aws-samples/aws-cdk-examples) for examples of AWS CDK stacks and apps. 
#### Tools
AWS Cloud Development Kit (AWS CDK)
#### Acceptance Criteria
•	Created and deployed a CDK project to provision the infrastructure
## Task 2: Subtask 1: Create a CDK project
#### Description
Create an AWS CDK project in C# using familiar tools including Visual Studio, Visual Studio Code, the dotnet command, and the NuGet package manager.
#### Tools
AWS CDK in C#
## Task 2: Subtask 2: Build, synthesize and deploy the AWS CDK app
#### Description
The stacks defined in your AWS CDK app can be synthesized and deployed individually or together using the cdk synth and cdk deploy. 
#### Tools
AWS CDK Toolkit
## Task 3: Build a CI/CD pipeline for automating app builds, tests and deployments
#### Description
Leverage the Dev Ops tooling to build a continuous integration and continuous deployment pipeline for the .NET application that automates the building, testing and deploying of the source code to the AWS environment.

#### Tools
AWS Code Pipeline
#### Tools
AWS Code Build
#### Tools
AWS Code Deploy
#### Tools
AWS Code commit
#### Acceptance Criteria
•	Automated the build, test and deployment of application with a CI/CD pipeline
## Task 3: Subtask 1: Set up code repository and version control system
#### Description
Depending on your use case, identify and set up a source code repository for your application code.
#### Tools
AWS Code Commit
## Task 3: Subtask 2: Set up the build stage in the pipeline
#### Description
In this step, determine the build server to use and implement the stage in the pipeline that builds the application source code. 
#### Tools
AWS CodeBuild
## Task 3: Subtask 3: Incorporate automated testing to validate the builds
#### Description
In this step, ensure that multiple types of testing from unit test to integration and functional tests are incorporated into the code build pipeline. Ensure the test results are generated as reports.
## Task 3: Subtask 4: Set up the deployment stage to automate application deployments
#### Description
Choose an application deployment strategy for final release to production environment. Leverage the infrastructure as code options such as AWS CloudFormation templates and deployment services like AWS CodeDeploy to automate the application deployments.
#### Tools
AWS CodeDeploy
## Task 3: Subtask 5: Monitor and test the CI/CD pipeline
#### Description
