# Terraform Docker IaC

This project demonstrates how to use **Terraform** to provision a **Docker container** using Infrastructure as Code (IaC) principles.

## 🚀 Objective

Provision a local Docker container (e.g., Nginx) using Terraform.

## 🛠 Tools Used

- [Terraform](https://developer.hashicorp.com/terraform)
- [Docker](https://www.docker.com/)
- Docker Provider for Terraform

## 📂 Project Structure

terraform-docker-iac/
├── main.tf # Terraform configuration
├── apply.log # Terraform apply execution logs (optional)
├── destroy.log # Terraform destroy logs (optional)
└── .gitignore # Ignore Terraform state and logs


## 🧑‍💻 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/terraform-docker-iac.git
cd terraform-docker-iac

2. Initialize Terraform

terraform init

3. Preview Plan

terraform plan

4. Apply the Configuration

terraform apply

✔️ This pulls the Nginx image and starts a container on port 8080.

Visit: http://localhost:8080
5. Check State

terraform state list

6. Destroy the Container

terraform destroy

✅ Outputs

    A running Docker container named nginx-terraform

    Terraform-managed state file and logs (optional)

📘 Reference

    Terraform Docker Provider Docs