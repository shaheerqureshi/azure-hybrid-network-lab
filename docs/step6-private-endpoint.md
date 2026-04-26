## Step 6: Private Endpoint for Storage

A private endpoint was configured for the storage account to enable secure access over the virtual network.

### Configuration
- Storage Account: sthybridlab###
- Private Endpoint: pe-storage
- Subnet: subnet-private

### Benefits
- Traffic remains within Azure network
- Eliminates public exposure
- Enhances data security

### Outcome
The storage account is now accessible via a private IP within the VNet.
