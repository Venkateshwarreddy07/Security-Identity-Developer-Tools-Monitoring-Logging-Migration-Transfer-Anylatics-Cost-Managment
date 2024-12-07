# Security-Identity-Developer-Tools-Monitoring-Logging-Migration-Transfer-Anylatics-Cost-Managment

Security & Identity

IAM (Users, Groups, Roles, Policies)

	• Concepts:
		○ IAM: Manages permissions and access for AWS services.
	• Real-Time Example:
		○ A company creates IAM roles for developers with least privilege to access only necessary S3 buckets and EC2 instances.
	• Use Cases:
		○ Secure multi-user environments, resource access control.
	• Secondary Options: Azure AD, GCP IAM.

AWS KMS, CloudHSM

	• Concepts:
		○ KMS: Key management service for encryption.
		○ CloudHSM: Dedicated hardware security for sensitive encryption.
	• Real-Time Example:
		○ KMS: Encrypting customer PII in S3 buckets.
		○ CloudHSM: Storing encryption keys for financial transactions.
	• Use Cases:
		○ KMS: General encryption and decryption.
		○ CloudHSM: High-security encryption for regulatory compliance.
	• Secondary Options: HashiCorp Vault.

AWS Secrets Manager, Systems Manager Parameter Store

	• Concepts:
		○ Secrets Manager: Securely stores secrets like API keys.
		○ Parameter Store: Stores configuration data and secrets.
	• Real-Time Example:
		○ Secrets Manager: Storing database credentials for an RDS instance.
		○ Parameter Store: Keeping environment variables for Lambda functions.
	• Use Cases:
		○ Secrets Manager: Rotatable secrets.
		○ Parameter Store: App configuration management.
	• Secondary Options: Azure Key Vault, HashiCorp Vault.

6. Developer Tools

AWS CodePipeline, CodeBuild, CodeDeploy, CodeCommit

	• Concepts:
		○ CodePipeline: Automates CI/CD pipelines.
		○ CodeBuild: Compiles and builds code.
		○ CodeDeploy: Automates deployment.
		○ CodeCommit: Git-based source control.
	• Real-Time Example:
		○ A DevOps team uses CodePipeline to automate the testing and deployment of a new web application.
	• Use Cases:
		○ CI/CD automation for software projects.
	• Secondary Options: Jenkins, GitHub Actions, Azure DevOps.

AWS CloudFormation, AWS CDK

	• Concepts:
		○ CloudFormation: Infrastructure as Code (IaC) service using templates.
		○ AWS CDK: High-level programming model for IaC.
	• Real-Time Example:
		○ Deploying a multi-tier web app using CloudFormation templates.
	• Use Cases:
		○ IaC for repeatable deployments.
	• Secondary Options: Terraform, Pulumi.

7. Monitoring & Logging

Amazon CloudWatch

	• Concepts:
		○ Monitors AWS resources and applications via logs, metrics, and alarms.
	• Real-Time Example:
		○ A startup monitors API latency using CloudWatch alarms.
	• Use Cases:
		○ Performance and cost optimization.
	• Secondary Options: Datadog, New Relic.

AWS CloudTrail

	• Concepts:
		○ Logs AWS API calls for governance and compliance.
	• Real-Time Example:
		○ Tracking unauthorized IAM access attempts.
	• Use Cases:
		○ Auditing and monitoring user actions.
	• Secondary Options: Splunk, SIEM tools.

8. Migration & Transfer

AWS Migration Hub, Application Migration Service

	• Concepts:
		○ Centralized tracking of migrations to AWS.
	• Real-Time Example:
		○ Migrating on-premises apps to EC2 using Application Migration Service.
	• Use Cases:
		○ Large-scale cloud migrations.
	• Secondary Options: VMware HCX, Azure Migrate.

9. Analytics

Amazon Glue, Athena, QuickSight

	• Concepts:
		○ Glue: ETL service for data preparation.
		○ Athena: Query data in S3 with SQL.
		○ QuickSight: BI dashboards.
	• Real-Time Example:
		○ Athena: Querying S3 logs for user analytics.
		○ QuickSight: Sales dashboards for executives.
	• Use Cases:
		○ Glue: Data pipelines.
		○ Athena: Ad hoc querying.
		○ QuickSight: BI reporting.
	• Secondary Options: Tableau, Looker.

10. Cost Management

AWS Budgets, Cost Explorer

	• Concepts:
		○ Budgets: Set usage and cost alerts.
		○ Cost Explorer: Analyze spending patterns.
	• Real-Time Example:
		○ A company sets budgets for EC2 usage.
	• Use Cases:
		○ Cost control and forecasting.
	• Secondary Options: CloudHealth, Spot.io.

