# AWS ALB + Auto Scaling Lab

This project provisions a scalable, load-balanced web application infrastructure using Terraform on AWS.

## 🚀 Features

- VPC with 2 public subnets (in different AZs)
- Internet Gateway & Route Tables
- Application Load Balancer (ALB)
- Launch Template for web servers
- Auto Scaling Group with desired capacity of 2
- User Data to install Apache and serve a test page

## 🌐 Architecture

```
Users --> ALB --> EC2 (Auto Scaling Group)
         |
       Public Subnets in 2 AZs
         |
        VPC with Internet Gateway
```

## 🧰 How to Run

### Prerequisites
- AWS CLI setup with credentials
- Terraform installed (>=1.0)

### Steps
```bash
git clone https://github.com/YOUR_USERNAME/aws-alb-autoscaling-lab.git
cd aws-alb-autoscaling-lab
terraform init
terraform apply
```

### Cleanup
```bash
terraform destroy
```

## 📌 Author
- [LinkedIn](https://linkedin.com/in/your-profile)
- [GitHub](https://github.com/YOUR_USERNAME)