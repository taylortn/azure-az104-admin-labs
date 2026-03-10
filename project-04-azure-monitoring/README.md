# Project 04 — Azure Monitoring & Alerts

## Overview

This project demonstrates how to configure Azure Monitor to track resource activity and create alert rules based on defined thresholds. For this lab, monitoring was configured for an Azure Storage Account and connected to an Action Group for notifications.

This project focuses on observability, proactive monitoring, and operational awareness in Azure environments.

## Skills Demonstrated

- Azure Monitor configuration
- Metric-based alert rule creation
- Action Group setup
- Email notification integration
- Resource monitoring and observability
- Azure governance through tagging

## Azure Services Used

- Microsoft Azure
- Azure Monitor
- Azure Alerts
- Action Groups
- Azure Storage Account

## Architecture

Azure Subscription  
│  
└── Resource Group  
    ├── Storage Account  
    └── Azure Monitor  
        └── Alert Rule  
            └── Action Group  
                └── Email Notification

## Steps Performed

1. Navigated to the Azure Storage Account resource.
2. Opened the Monitoring and Alerts section.
3. Created a new alert rule based on a storage metric.
4. Configured an Action Group for email-based notification.
5. Applied governance tags for project organization.
6. Reviewed and deployed the monitoring configuration.

## Monitoring Configuration

- Resource monitored: Azure Storage Account
- Alert type: Metric alert
- Notification method: Email via Action Group

## Security / Operations Concept Demonstrated

This project demonstrates proactive cloud operations by configuring resource monitoring and automated alerting. This allows administrators to identify unusual activity and respond quickly to potential issues.

## Result

Azure Monitor was successfully configured to track the selected resource and trigger an alert using an Action Group. This project demonstrates practical experience with Azure observability and operations monitoring.

## Screenshots

See the `screenshots` folder for configuration proof and monitoring setup images.
