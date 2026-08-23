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

## Project Steps and Key takeaays
- Defined the infrastructure using Terraform.
- Utilized azue CLI to log onto azure via ther terminal: bash command  *az login --tenant tenantID*
- Once logged in I created a servise principal using bash. command: *az ad sp create-for-rbac --role="Contributor" --scopes="/subscriptions/SUBSCRIPTION_ID"*

## Project Diagram
<img width="1052" height="393" alt="Terraform foundation Diagram drawio" src="https://github.com/user-attachments/assets/565696fd-5892-418f-b2d1-5179ff483ce2" />
