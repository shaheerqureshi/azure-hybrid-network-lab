## Step 3: Network Security Group (NSG) Configuration

A Network Security Group (NSG) was implemented to control inbound traffic to the virtual network.

### Configuration
- NSG Name: nsg-vm
- Applied to: subnet-vm

### Security Rule
- Allowed RDP (Port 3389) access from a specific public IP address only
- Protocol: TCP
- Priority: 1000

### Design Considerations
- Restricted administrative access to a single trusted IP
- Followed the principle of least privilege
- Prevented unauthorized access from the internet

This setup enhances security by ensuring that only authorized users can access virtual machines within the subnet.
