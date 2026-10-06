# Terraform Docker Container - DevOps Internship Task 3

## Objective

Provision a local Docker container using Terraform Infrastructure as Code (IaC).

## Tools Used

- Terraform
- Docker
- Nginx

## What I Did

1. Configured the Docker provider in Terraform.
2. Pulled the Nginx Docker image.
3. Created an Nginx container using Terraform.
4. Exposed the container on port 8082.
5. Used `terraform init`.
6. Used `terraform validate`.
7. Used `terraform plan`.
8. Used `terraform apply`.
9. Checked Terraform state.
10. Verified the container using Docker.
11. Destroyed the infrastructure using `terraform destroy`.

## Commands

```bash
terraform init
terraform validate
terraform plan
terraform apply
terraform state list
docker ps
terraform destroy
