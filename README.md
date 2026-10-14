# Secure Azure Web Application

# Project Overview

Deployed a Node.js web application on Microsoft Azure using cloud networking, managed identities, private endpoints, Azure Key Vault, GitHub Actions, and Application Insights.

# Technologies Used

- Microsoft Azure App Service (Linux, Node.js 22)
- Azure Virtual Network and Subnets
- Azure Private Endpoint and Private DNS
- Azure Storage Account
- Azure Key Vault
- Azure Managed Identity and RBAC
- Azure Application Insights and Log Analytics
- GitHub Actions CI/CD

# Architecture

- Public HTTPS access to Azure App Service
- Outbound VNet integration for private connectivity
- Private Endpoint for Azure Blob Storage
- Managed Identity for authentication without hardcoded credentials
- Key Vault for secure secret management
- GitHub Actions for automated deployment
- Application Insights for monitoring and troubleshooting

# Implementation

1. Created Azure infrastructure in South Africa North.
2. Deployed a Node.js application to Azure App Service.
3. Configured GitHub Actions deployment.
4. Integrated App Service with an Azure Virtual Network.
5. Created a private endpoint and private DNS configuration for Blob Storage.
6. Configured Azure Key Vault and managed identities.
7. Assigned Azure RBAC permissions.
8. Enabled Application Insights and verified telemetry collection.
9. Verified that the website was accessible through HTTPS.

# Validation

- Confirmed successful website deployment.
- Verified private DNS resolution for Azure Storage.
- Confirmed HTTPS connectivity to the Blob endpoint.
- Verified Key Vault reference resolution.
- Observed application request telemetry in Application Insights.

# Project Evidence

Screenshots of the working website and Azure resources are included in this repository.

# Future Improvements

- Add infrastructure as code using Terraform or Bicep.
- Implement authenticated Blob Storage operations.
- Configure and test Azure Monitor alerts.
- Add automated application tests.

# Skills Demonstrated

Azure Administration | Cloud Networking | Identity and Access Management | Cloud Security | CI/CD | Monitoring | Troubleshooting
