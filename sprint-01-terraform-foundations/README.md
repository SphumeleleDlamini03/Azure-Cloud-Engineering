# Sprint 01 — Terraform Foundations

## Objective

Build a practical foundation in **Infrastructure as Code using Terraform and Microsoft Azure**.

## Focus

- Infrastructure as Code
- Terraform fundamentals
- Azure Provider
- Terraform state
- Variables & outputs
- `terraform init`
- `terraform plan`
- `terraform apply`
- `terraform destroy`

## Project Steps 
### 1. Configure Azure Access
- Used the Azure CLI to log into Azure from the terminal:
  ***`az login --tenant TENANT_ID`***
- Created a service principal with Contributor access to the subscription:
  ***`az ad sp create-for-rbac \ --role="Contributor" \ --scopes="/subscriptions/SUBSCRIPTION_ID"`***
- Configured the required environment variables so Terraform could authenticate with Azure using the service principal.
- The service principal was created for learning purposes with Contributor access at subscription scope. Credentials were supplied through environment variables and were not committed to the repository.
### 2. Deploy the Infrastructure
- Defined the Azure infrastructure using Terraform configuration files.
- Initialized the Terraform project and installed the required providers: **_`terraform init`_**
- Created and reviewed the execution plan: **_`terraform plan`_**
- Applied the Terraform configuration to Azure: **_`terraform apply`_**
### 3. Verify the Deployment
Verified that the Resource Group, Virtual Network, and three subnets were successfully created in Azure.

## Deployed Infrastructure
- Resource Group
- Virtual Network 
- Web Subnet
- App Subnet
- Data Subnet

## Project Diagram
<img width="1052" height="393" alt="Terraform foundation Diagram drawio" src="https://github.com/user-attachments/assets/565696fd-5892-418f-b2d1-5179ff483ce2" />

## Resources Deployed On Azure

## Tech Stack

- **Cloud:** `Microsoft Azure`
- **IaC:** `Terraform`
- **Identity**: `Microsoft Entra ID`
- **Authorization:** `Azure RBAC`
- **CLI:** `Azure CLI`

