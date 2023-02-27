# Getting Started with Okta - Terraform Edition

## Installation

```bash
brew install terraform
```

## Usage

1. Initialize your terraform workspace, this will give you a `.terraform` directory to hold all provider code, and establish the folder as a "terraform-able" configuration.

```bash
git clone https://github.com/lt-brlara/tf-getting-started-with-okta.git

cd tf-getting-started-with-okta

terraform init
```

2. Modify the `main.tf` file to point to your okta domain and base URL.

3. Attempt to plan.

```bash
terraform plan
```

You will be prompted for your Okta token.

4. Assuming all looks good, attempt to apply:

```bash
terraform apply
```
