# hello-aws

A simple Apache webserver, running on AWS EC2 and serving files from EBS volume.  

## Requirements
* Terraform (v0.12+ recommended)
 
## Usage
Set environment variables for AWS access keys
```
export AWS_ACCESS_KEY_ID=****************
export AWS_SECRET_ACCESS_KEY=****************
```

Execute Terraform to provision AWS resources
```
terraform init
terraform apply
```
