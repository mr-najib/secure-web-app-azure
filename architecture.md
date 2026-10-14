# Secure Azure Web Application

## Architecture

### Application Deployment
GitHub Repository
↓
GitHub Actions CI/CD
↓
Azure App Service (Node.js 22)
↓
Public HTTPS Website

### Identity and Security
Azure App Service
↓
User-Assigned Managed Identity
↓
Azure RBAC
↓
Azure Key Vault

### Private Storage Connectivity
Azure App Service
↓
VNet Integration
↓
Storage Private Endpoint
↓
Azure Blob Storage

Private DNS resolves the storage endpoint to its private IP address.

### Monitoring
Azure App Service
↓
Application Insights
↓
Log Analytics Workspace

## Security Features

- HTTPS access to the web application
- Private endpoint for Azure Blob Storage
- User-assigned managed identity
- Role-based access control (RBAC)
- Azure Key Vault for secrets
- Application Insights monitoring
- GitHub Actions automated deployment

## Azure Region

South Africa North 
