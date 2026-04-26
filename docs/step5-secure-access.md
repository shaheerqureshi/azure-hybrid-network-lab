## Step 5: Secure Access with Azure Bastion

To enhance security, the public IP address was removed from the virtual machine, eliminating direct internet exposure.

### Implementation
- Public IP removed from VM
- Azure Bastion deployed within the VNet
- Created dedicated subnet: AzureBastionSubnet (10.0.3.0/27)

### Benefits
- Secure RDP access without exposing VM to the internet
- Eliminates need to open inbound ports
- Reduces attack surface

### Outcome
Successfully connected to the VM using Azure Bastion via the Azure Portal.

This approach aligns with enterprise security best practices for managing remote access to cloud resources.
