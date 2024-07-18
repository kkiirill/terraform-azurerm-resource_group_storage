# Terraform AzureRM Resource Group and Storage Account Module

## Usage

```hcl
module "resource_group_storage" {
  source               = "github.com/kkiirill/terraform-azurerm-resource_group_storage"
  resource_group_name  = "terraform-module"
  location_for_rg      = "East US"
  storage_account_name = "mystorageaccount"
}