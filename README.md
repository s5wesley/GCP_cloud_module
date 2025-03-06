# Terraform Project Directory Structure

📂 Terraform_Project
├── 📂 Environments
│ ├── 📂 Development
│ │ ├── 📄 main.tf
│ │ ├── 📄 outputs.tf
│ │ ├── 📄 terraform.tfvars
│ │ ├── 📄 variables.tf
│ ├── 📂 Production
│ │ ├── 📄 main.tf
│ │ ├── 📄 outputs.tf
│ │ ├── 📄 terraform.tfvars
│ │ ├── 📄 variables.tf
│ ├── 📂 Staging
│ │ ├── 📄 main.tf
│ │ ├── 📄 outputs.tf
│ │ ├── 📄 terraform.tfvars
│ │ ├── 📄 variables.tf
│
├── 📂 Modules
│ ├── 📂 EC2
│ │ ├── 📄 main.tf
│ │ ├── 📄 outputs.tf
│ │ ├── 📄 variables.tf
│ ├── 📂 VPC
│ │ ├── 📄 main.tf
│ │ ├── 📄 outputs.tf
│ │ ├── 📄 variables.tf
│
├── 📂 Scripts
│ ├── 📄 init.sh
│ ├── 📄 teardown.sh
│
├── 📄 backend.tf
├── 📄 main.tf
├── 📄 outputs.tf
├── 📄 provider.tf
├── 📄 variables.tf