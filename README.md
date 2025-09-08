# Terraform Simple Template

A simple Terraform template to get you started with infrastructure as code.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) >= 1.0
- Cloud provider credentials (AWS, Azure, GCP, etc.)

## Quick Start

1. Clone this repository:

   ```bash
   git clone https://github.com/vburckhardt/terraform-simple-template.git
   cd terraform-simple-template
   ```

2. Initialize Terraform:

   ```bash
   terraform init
   ```

3. Review the planned changes:

   ```bash
   terraform plan
   ```

4. Apply the configuration:

   ```bash
   terraform apply
   ```

## Files Structure

- `main.tf` - Main Terraform configuration
- `variables.tf` - Input variables
- `outputs.tf` - Output values
- `terraform.tfvars.example` - Example variables file

## Usage

1. Copy `terraform.tfvars.example` to `terraform.tfvars`
2. Update the variables in `terraform.tfvars` with your values
3. Run `terraform plan` to review changes
4. Run `terraform apply` to create resources

## Cleanup

To destroy the created resources:

```bash
terraform destroy
```

## VS Code Setup

This repository includes VS Code configuration with recommended extensions for Terraform development. Open the workspace in VS Code to automatically get extension recommendations.