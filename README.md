# Comparative Study of Monitoring Tools for Cloud & On-Prem



## Which is better - AWS CloudWatch Vs Datadog/ New Relic?

## AWS CloudWatch:

Amazon CloudWatch is the all-purpose monitoring service for AWS. The tool provides a unified view of AWS resources and applications, including those that run on premises in Outposts.

CloudWatch features fall into five broad categories:

- Data collection -  CloudWatch aggregates logs and collects built-in AWS resource metrics, such as EC2 CPU utilization, API Gateway latency or container infrastructure data.

- Monitoring - CloudWatch provides a dashboard that centralizes all operational data. This function also includes alarms for abnormal readings, log and metrics correlation, and Application Insights for SQL Server and .NET workloads. Custom dashboards and alarms help IT admins correlate data and events across resources and flag anomalies.

- Action -  CloudWatch Events or metrics can automatically trigger management tasks, such as auto scaling an EC2 instance pool, or custom actions carried out by command-line interface scripts, Lambda functions or SNS topic notifications.

- Analysis -  CloudWatch can graphically display historical data via canned or custom-built views. It can also perform calculations on data or feed other Amazon data analysis services for more sophisticated study.
Compliance and security. CloudWatch integrates with AWS Identity and Access Management to enforce role-based access controls on CloudWatch data and automatically encrypt stored data.





## Cons: 

- CloudWatch can't monitor non-AWS cloud services or user-managed infrastructure. In addition, the tool has limited to no visibility into telemetry from the OS stack and running applications.

- For more advanced analysis and automation, CloudWatch also requires users to export data to other services and to develop custom scripts, Lambda functions, business intelligence routines or machine learning models.

## Datadog & New Relic:

Datadog and New Relic provide unified infrastructure and application performance monitoring suites that include an extensive set of service integrations, pre-built dashboards and data analysis models. Along with competitors such as AppDynamics, both Datadog and New Relic are good options for organizations that want to add AWS infrastructure into a multi-platform monitoring and alerting system.
