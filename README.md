# Terraform + Ansible WordPress Infrastructure as Code

This project aims to provide an automated setup for provisioning and configuring a single WordPress server using Terraform and Ansible.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed on your machine:

- Terraform (version X.X.X)
- Ansible (version X.X.X)

## Getting Started

To get started with this project, follow the steps below:

1. Clone this repository to your local machine.
2. Navigate to the project directory: `cd wp-iac`.
3. Update the `variables.tf` file with your desired configuration.
4. Run `terraform init` to initialize the Terraform environment.
5. Run `terraform plan` to review the infrastructure changes.
6. Run `terraform apply` to provision the infrastructure.
7. Access your WordPress site by navigating to the server's public IP address in your web browser.

## Configuration

The `variables.tf` file contains the configurable options for this project. Update the values according to your requirements before running Terraform.

## Cleanup

To clean up and destroy the provisioned infrastructure, run `terraform destroy` in the project directory.
