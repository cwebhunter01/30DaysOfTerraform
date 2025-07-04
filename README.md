 # Day 3: Deploying a Basic Web Server with Terraform

In this challenge, I deployed a t2.micro EC2 instance on AWS using Terraform. The instance automatically installs Nginx on launch using a user data script.

## Files
- `main.tf`: Defines AWS provider and EC2 instance
- `variables.tf`: Centralizes configurable values
- `user_data.sh`: Bootstraps Nginx on launch
- `outputs.tf`: Exposes public IP for access

## Commands Used
```bash(nano)
terraform init
terraform plan
terraform apply

 
 ## Display

 ## 🖼️ Screenshot

![Nginx Web Server Deployed](./Asset/day3-IaC-ubuntu.pngec2-nginx-screenshot.png)
![VS-Code + Terraform to deploy Aws ec2 Instance](./Asset/day3-IaC.png)
