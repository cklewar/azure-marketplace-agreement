# AZURE-MARKETPLACE-AGREEMENT

This repository consists of Terraform templates to create Azure Marketplace agreement.

## Usage

- Clone this repo with: `git clone --recurse-submodules https://github.com/cklewar/azure-marketplace-agreement`
- Enter repository directory with: `cd azure-marketplace-agreement`
- Obtain F5XC API certificate file from Console and save it to `cert` directory
- Pick and choose from below examples and add mandatory input data and copy data into file `main.tf.example`.
- Rename file __main.tf.example__ to __main.tf__ with: `rename main.tf.example main.tf`
- Initialize with: `terraform init`
- Apply with: `terraform apply -auto-approve` or destroy with: `terraform destroy -auto-approve`

### Example Output

```bash

```

## Create Azure Marketplace Agreement

```bash
terraform import module.f5xc_azure_marketplace_agreement_single_nic.azurerm_marketplace_agreement.f5xc_azure_ce_singel_nic /subscriptions/e9cbbd48-704d-4dfa-bf62-60edda755a66/providers/Microsoft.MarketplaceOrdering/agreements/volterraedgeservices/offers/volterra-node/plans/volterra-node
terraform import module.f5xc_azure_marketplace_agreement_multi_nic.azurerm_marketplace_agreement.f5xc_azure_ce /subscriptions/e9cbbd48-704d-4dfa-bf62-60edda755a66/providers/Microsoft.MarketplaceOrdering/agreements/volterraedgeservices/offers/entcloud_voltmesh_voltstack_node/plans/freeplan_entcloud_voltmesh_voltstack_node_multinic
terraform import module.f5xc_azure_marketplace_agreement_app_stack.azurerm_marketplace_agreement.f5xc_azure_ce /subscriptions/e9cbbd48-704d-4dfa-bf62-60edda755a66/providers/Microsoft.MarketplaceOrdering/agreements/volterraedgeservices/offers/entcloud_voltmesh_voltstack_node/plans/freeplan_entcloud_voltmesh_voltstack_node
```

```hcl

```