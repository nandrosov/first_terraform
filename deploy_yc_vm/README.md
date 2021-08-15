## Description

Terraform manifest deploys VM in the yandex-cloud and provisions Nginx with ansible playbook

## Usage

Clone git repository
```
git clone https://github.com/nandrosov/first_terraform.git
```
Copy and edit `terraform.tfvars` with your credentials
```
cd deploy_yc_vm
cp ./terraform.tfvars.example ./terraform.tfvars
vi ./terraform.tfvars
```
Apply terraform manifest
```
terraform init
terraform plan
terraform apply
```