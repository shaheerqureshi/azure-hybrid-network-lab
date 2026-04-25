## Step 4: Virtual Machine Deployment

A Windows Server virtual machine was deployed within the secured subnet.

### Configuration
- VM Name: vm-lab-01
- Network: vnet-hybrid-lab
- Subnet: subnet-vm

### Security
- No public inbound ports were opened during deployment
- Access is controlled through Network Security Group (NSG) rules
- RDP access is restricted to a specific trusted IP address

### Outcome
Successfully deployed and accessed the VM using RDP, validating network connectivity and security configuration.

This step demonstrates secure deployment of compute resources within a segmented cloud network.
