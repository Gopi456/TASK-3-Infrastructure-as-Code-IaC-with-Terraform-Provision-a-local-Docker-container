# Terraform Docker Container IaC Project

## Objective
Provision a local NGINX Docker container using Terraform.

---

## Tools Used
- Terraform
- Docker
- Docker Provider Plugin (kreuzwerker/docker)

---

## How to Run

1. Start Docker Engine or Docker Desktop.
2. Run the following commands:

```bash
terraform init
terraform plan
terraform apply
terraform state list
docker ps
terraform destroy
```

---

## Files

- `main.tf`: Terraform config for Docker container
- `output/`: Screenshots of each command execution

---

## Outcome

This project demonstrates:
- Terraform initialization and execution
- Container provisioning using Infrastructure as Code (IaC)
- Resource state tracking and cleanup
