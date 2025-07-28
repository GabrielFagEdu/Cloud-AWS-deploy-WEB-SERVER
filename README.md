Cloud AWS Web Server Deployment with Terraform
This project provisions a complete Apache web server environment using AWS services, Infrastructure as Code (IaC) with Terraform (HCL), and includes:

Apache Web Server

S3 Bucket for static files

Flask API served via Gunicorn with 4 workers

Automated provisioning via Terraform

Requirements
An active AWS account

AWS CLI configured

Terraform installed

How to Deploy
Clone this repository

Navigate to the infrastructure directory

Run the following commands:
terraform init
terraform apply
Type yes to confirm the deployment

Wait approximately 5 minutes for provisioning to complete 
Output Once deployed, your environment will be running:

Apache web server on port 80

Flask application via Gunicorn in port 5000
