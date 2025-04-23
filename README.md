# DevOps-Azure
CICD Pipeline for Financial Application:

App repo in GitHub
Infra (AKS, ACR, Azure Key Vault) is provisioned via Terraform
GitHub OIDC is configured for Azure auth
Artifactory is used as Docker registry (JFrog or Nexus)
AKS uses Helm for deployments
Azure Key Vault holds secrets like DB credentials, keys, etc.
