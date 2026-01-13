# aws-tfe-eks-project
Built a modular AWS EKS cluster using Terraform with reusable VPC and EKS modules. Implemented public/private subnets, IGW, NAT Gateway, routing, and separate IAM roles for EKS control plane and worker nodes. Focused on scalable, production-style IaC design.

AWS EKS Cluster Provisioning using Terraform (Modular Approach)

🔧 Architecture Overview
* Custom VPC with public and private subnets
* Internet Gateway for public subnets
* NAT Gateway for outbound access from private subnets
* Route tables and subnet associations
* Amazon EKS Cluster

Separate IAM roles for:
* EKS control plane
* EKS worker nodes

📁 Project Structure
* Modular Terraform design for VPC and EKS
* variables.tf for configurable inputs
* outputs.tf for reusable outputs
* Main Terraform configuration file for orchestration
* Designed for reusability and environment scalability

🎯 Key Learnings
* Infrastructure as Code best practices
* AWS networking fundamentals (IGW, NAT, routing)
* IAM role separation and least-privilege design
* Real-world EKS provisioning using Terraform modules

🔗 Documentation
AWS: https://docs.aws.amazon.com/
Kubernetes: https://kubernetes.io/docs/home/
Terraform: https://developer.hashicorp.com/terraform/docs

