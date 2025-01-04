The project focuses on building a highly available, scalable, and secure infrastructure in the Azure cloud, using Terraform and various Azure services.

Overview
This assignment demonstrates the use of Infrastructure as Code (IaC) principles to codify and provision resources in Azure. The infrastructure includes virtual networks, virtual machines (Linux and Windows), load balancers, and more, adhering to best practices for scalability, parameterization, and modular design.

Key objectives:

Codify Azure infrastructure using Terraform.
Ensure scalability and availability across multiple availability zones.
Automate deployment and provisioning with a non-interactive workflow.

Features
Technical Skills
Modular Terraform configurations for Azure resources.
Parameterization using input variables, locals, and output values.
Remote backend configuration for Terraform state management.
Use of provisioners to automate resource initialization.

Azure Services
Identity and Access: Configured with Microsoft Entra ID.
Networking: Virtual networks, subnets, and security groups.
Compute: Linux and Windows VMs with extensions installed.
Storage: Azure Files, blob containers, and recovery vaults.
Traffic Management: Load balancers for VM clusters.
Monitoring: Azure Monitor integration

# Setup Instructions

Clone this repository:
git clone https://github.com/Hadeeq10/Automation-Assignment.git
cd Automation-Assignment/assingment1

Initialize Terraform:
terraform init

Validate configuration:
terraform validate

Apply changes:
terraform apply --auto-approve
terraform refresh

Verify resources:
terraform state list | nl  
terraform output  

Destroy resources after validation:
terraform destroy --auto-approve

