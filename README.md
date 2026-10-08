# Terraform Docker Task

## Objective

Provision a local Docker container using Terraform.

## Tools Used

- Terraform
- Docker
- Nginx

## Project Description

This project demonstrates Infrastructure as Code (IaC) using Terraform to provision an Nginx Docker container locally.

Terraform uses the Docker provider to:

1. Pull the Nginx Docker image.
2. Create an Nginx container.
3. Map port 8080 on the host to port 80 inside the container.

## Terraform Configuration

The main Terraform configuration is available in `main.tf`.

## Commands Used

```powershell
terraform init
terraform validate
terraform plan
terraform apply
terraform state list
docker ps

## Result

Terraform successfully created:

- Docker image: `nginx:latest`
- Docker container: `terraform-nginx`
- Port mapping: `8080:80`

The Nginx application was successfully accessed through:

http://localhost:8080

## Screenshots

Execution screenshots are available in the `screenshots` folder.

## Author

Devikrishnakumar
