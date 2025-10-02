# Terraform Simple Template

A simple, minimal Terraform template to help you get started with infrastructure as code. Terraform lets you define your cloud resources in code instead of clicking through web consoles.

## What's Included

This template contains the essential files for any Terraform project:

- **main.tf** - Where you define your infrastructure resources
- **variables.tf** - Defines the inputs your infrastructure needs
- **terraform.tfvars** - Contains the actual values for your variables
- **providers.tf** - Sets up the cloud provider connections
- **outputs.tf** - Specifies what information to show after deployment
- **version.tf** - Ensures everyone uses compatible versions

## Quick Start

1. Clone this repository:

   ```bash
   git clone https://github.com/vburckhardt/terraform-simple-template.git
   cd terraform-simple-template
   ```

2. Edit `terraform.tfvars` to add your specific configuration values

3. Initialize Terraform (downloads necessary providers):

   ```bash
   terraform init
   ```

4. Review the planned changes:

   ```bash
   terraform plan
   ```

5. Apply the configuration to create resources:

   ```bash
   terraform apply
   ```

## Cleanup

To remove all resources created by this template:

```bash
terraform destroy
```

## VS Code Setup

This repository includes VS Code configuration with recommended extensions for Terraform development. Open the workspace in VS Code to automatically get extension recommendations.