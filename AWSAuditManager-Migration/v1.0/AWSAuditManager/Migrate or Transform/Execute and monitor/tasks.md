
# Module: Execute and monitor
## Task 1: Enable AWS Audit Manager and check for pre-requisite
#### Description
* Make sure you must adhere to the pre-requisites for using AWS Audit Manager
 [Pre-Requisites](https://docs.aws.amazon.com/audit-manager/latest/userguide/setup-prerequisites.html)
* Make sure you have enabled AWS Audit Manager service
 [Setup](https://docs.aws.amazon.com/audit-manager/latest/userguide/setup-audit-manager.html)




## Task 2: Follow the AWS Audit Manager recommendations
#### Description
For an optimal experience in Audit Manager, we strongly recommend that you enable the following AWS services:

AWS Organizations – You can use Organizations to run Audit Manager assessments over multiple accounts and consolidate evidence into a delegated administrator account.

AWS Security Hub and AWS Config – When you enable these AWS services, they can be used as a data source type for the controls in your Audit Manager assessments. Audit Manager can then report the results of compliance checks directly from these services.

[For more details on recommendations](https://docs.aws.amazon.com/audit-manager/latest/userguide/setup-recommendations.html)
## Task 3: Build custom Config rules (If needed)
#### Description
Build custom config rules to support custom controls as defined in the Mobilize phase
[AWS Config Rules supported by AWS Audit Manager](https://docs.aws.amazon.com/audit-manager/latest/userguide/control-data-sources-config.html)
## Task 4: Control Updates (If needed)
#### Description
Build custom controls based on the requirement defined in Mobilize phase
[Creating a custom control](https://docs.aws.amazon.com/audit-manager/latest/userguide/create-controls.html)
## Task 5: Framework updates
#### Description
Validate the [standard frameworks that are available in AWS Audit Manager](https://docs.aws.amazon.com/audit-manager/latest/userguide/framework-overviews.html) based on requirements. [Create one or more custom frameworks](https://docs.aws.amazon.com/audit-manager/latest/userguide/custom-frameworks.html) for your custom requirements.Add custom controls and custom Config rules to the custom frameworks.
## Task 6: Launch with Assessment
#### Description
[Create an assessment ](https://docs.aws.amazon.com/audit-manager/latest/userguide/create-assessments.html) using the standard or custom framework of your choice, or start with the [CIS Benchmark for CIS Amazon Web Services Foundations Benchmark v1.4.0](https://docs.aws.amazon.com/audit-manager/latest/userguide/CIS-1-4.html) 
## Task 7: Monitoring updates
#### Description
Verify the following:
* [AWS Audit Manager dashboard](https://docs.aws.amazon.com/audit-manager/latest/userguide/dashboard.html)
* [AWS Security Hub](https://aws.amazon.com/security-hub/) (if applicable)
* [AWS Config](https://aws.amazon.com/config/) (if applicable)

#### Acceptance Criteria
Wait for 24 hours to view data on dashboard
Verify there is evidence showing up from Config
Verify there is evidence showing up from Sec Hub

## Task 8: Reporting Updates
#### Description
Validate assessment reports and CSV exports
[Assessment Report](https://docs.aws.amazon.com/audit-manager/latest/userguide/assessment-reports.html) 
[CSV Export from Evidence Finder](https://docs.aws.amazon.com/audit-manager/latest/userguide/viewing-search-results-in-evidence-finder.html) 
#### Acceptance Criteria
Customer is able to generate, validate and download the assessment reports.
Customer is able to view all the required information in the CSV exports.

## Task 9: Dashboards and metrics to display
#### Description
The [Audit Manager dashboard](https://docs.aws.amazon.com/audit-manager/latest/userguide/dashboard.html) must be up and running after 24 hours of assessment creation.
## Task 10: Troubleshoot Issues
#### Description
Troubleshoot issues that you encounter when working with AWS Audit Manager using the [troubleshooting guide](https://docs.aws.amazon.com/audit-manager/latest/userguide/troubleshooting.html).