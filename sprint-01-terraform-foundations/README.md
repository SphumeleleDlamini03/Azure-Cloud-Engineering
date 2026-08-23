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

## Deployed Infrastructure
- Resource Group
- Virtual Network 
- Web Subnet
- App Subnet
- Data Subnet

## Project Steps 
### 1. Configure Azure Access
- Used the Azure CLI to log into Azure from the terminal:
  *az login --tenant TENANT_ID*
- Created a service principal with Contributor access to the subscription:
  *az ad sp create-for-rbac \ --role="Contributor" \ --scopes="/subscriptions/SUBSCRIPTION_ID"*

## Project Diagram
<img width="1052" height="393" alt="Terraform foundation Diagram drawio" src="https://github.com/user-attachments/assets/565696fd-5892-418f-b2d1-5179ff483ce2" />
