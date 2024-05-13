# Configure Azure Firewall and Policy in Azure Portal

## Objective

This project aimed to configure a secure and functional network environment within Azure by setting up a Virtual Network (VNet), deploying a virtual machine (VM), and integrating a firewall with specific policies and rules. The purpose was to establish a protected network that can handle both inbound and outbound connections effectively, utilizing Azure's network and security services to ensure data integrity and accessibility.

### Skills Learned

- Virtual Network Creation: Learned to create and configure a Virtual Network (VNet) within Azure, understanding the importance of network isolation and segmentation.
- Subnet Configuration: Gained proficiency in managing multiple subnets within a VNet for organized network traffic and role-based resource allocation.
- Firewall Deployment: Developed skills in setting up Azure Firewall, creating and managing firewall policies, and applying application and network rules to control traffic flow.
- Virtual Machine Deployment: Acquired hands-on experience in deploying and configuring VMs within the Azure environment, understanding VM settings and network configurations.
- Routing and DNS Management: Configured route tables and custom DNS settings to ensure proper routing of traffic through the firewall and external DNS resolution.
- Security Rules Implementation: Implemented application and network rules in the firewall to allow or deny specific types of traffic, enhancing the security posture of the network.

### Tools Used

- Azure Portal: Primary interface for configuring and managing all Azure services, including VNets, VMs, and firewalls.
- Azure CLI/PowerShell: Used for scripting and automation tasks within the Azure environment.
- Remote Desktop Protocol (RDP): Utilized for remote management of the virtual machine.
Network Monitoring and Management Tools: Employed to monitor network traffic and ensure compliance with security policies.
- DNS Management Tools: Used for configuring and managing DNS settings to facilitate external domain name resolution.

## Steps
Create VNET<img width="1431" alt="Screenshot 2024-05-13 at 2 54 10 PM" src="https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/95e5ad08-0ded-465c-9361-54c50483e6a1">

Edit Subnets<img width="830" alt="Screenshot 2024-05-13 at 2 54 57 PM" src="https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/fe31abeb-7be6-4c5d-acbc-5f5d888cec49">

Add another subnet<img width="829" alt="Screenshot 2024-05-13 at 2 55 53 PM" src="https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/d9955cc5-e164-4b58-b469-cf6d195e7552">

Create a VM<img width="1434" alt="Screenshot 2024-05-13 at 2 56 44 PM" src="https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/14727e69-4342-4671-b44b-3447328d2579">

Deploy Azure Firewall&Policy<img width="1435" alt="Screenshot 2024-05-13 at 2 57 53 PM" src="https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/a6acbec9-0557-4654-9475-0eea7359b328">

Create a Default Route


<img width="325" alt="Screenshot 2024-05-13 at 2 59 09 PM" src="https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/4b8e6543-38a2-475f-bb15-017605ebe674">

Configure the Application Rule![Screenshot 2024-05-11 at 9 21 24 PM](https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/97481b2a-b386-4612-8206-bf601d75ca66)

Change the Primary and Secondary DNS Address![Screenshot 2024-05-11 at 9 34 26 PM](https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/1d1518ae-c8fc-4cd4-9c34-b721601839a3)

Test and Confirm Firewall

<img width="672" alt="Screenshot 2024-05-13 at 3 03 03 PM" src="https://github.com/Hunter102002/Configure-Azure-Firewall-and-policy-using-Azure-Portal/assets/98543129/7dd10a49-cf8e-493c-b4d0-0e39c1a605ae">
