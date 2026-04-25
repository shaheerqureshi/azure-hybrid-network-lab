## Step 2: Virtual Network and Subnet Design

A Virtual Network (VNet) was created to simulate an isolated cloud network environment.

### Configuration
- VNet Name: vnet-hybrid-lab
- Address Space: 10.0.0.0/16

### Subnet Design
- subnet-vm: 10.0.1.0/24 → Hosts virtual machines
- subnet-private: 10.0.2.0/24 → Reserved for private endpoints

### Design Considerations
- A /16 address space was selected to allow scalability and future subnet expansion
- Subnet segmentation improves security and traffic isolation
- Workloads are separated based on function (compute vs private services)

This approach aligns with enterprise cloud networking best practices and mirrors on-premise network segmentation strategies.
