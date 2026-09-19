# Implementing Entra ID and Hybrid Connectivity

### [Link to Demonstrations and Labs](https://emlykf.gitbook.io/implementing-entra-id-and-hybrid-connectivity)

## Project Scenario

You are an IT administrator for a growing organization that has recently decided to move part of its IT infrastructure to the cloud. The main goals are to make things more flexible, improve scalability, and reduce operational costs. The organization also wants seamless integration between its existing on-premises environment and the new cloud infrastructure.

To meet these goals, your task is to use Microsoft Entra ID to manage user identities and connect the on-premises network with Azure. This will allow easy user management, secure cloud access, and reliable communication between on-premises and cloud environments.

## What We Will Do

* Setting up Microsoft Entra ID
* Synchronizing on-premises Active Directory with Microsoft Entra ID
* Implementing SSO and MFA
* Establishing hybrid connectivity using a VPN gateway
* Testing and validating the hybrid connectivity setup

## Prerequisites

* Active Azure Subscription
* On-premises Active Directory domain controller
* Firewall (e.g., Sophos)
* Virtual machine (Linux or Windows)

## Architecture Diagram

![Architecture Diagram](https://github.com/emlykf/Implementing-Entra-ID-and-Hybrid-Connectivity/blob/02324020fd3cae794f1b1d66762bbbd06eeb6520/Architecture%20Diagram.png)

## Resources

* [Installing Windows Server 2019 on Proxmox](https://youtu.be/kOdf4_QPrZw?si=Cdr8iDqtL8AeIARk)
* [Setting up Active Directory in Windows Server 2019](https://youtu.be/h3sxduUt5a8?si=v43OIUcGIycWqtuS)&#x20;
* [Setting up Microsoft Entra Connect on your on-premises AD domain controller](https://youtu.be/LR8009GgGAQ?si=a7c_b_NZLVb1JjGD)
* [Installing Windows 11 on Proxmox](https://youtu.be/9FCDIavw3EM?si=4SvEivXfz7rpqh4G)
* [Installing Sophos Firewall on Proxmox](https://youtu.be/86xl2c-S9vc?si=SndZCn2_XbA92Rwh)
* [Setting up Azure Site-to-Site VPN on-premises](https://youtu.be/tD4nmBW7m8w?si=4ott-GDsT6qVN4Q9)

## Cleanup your resources

If you are working with **your own subscription,** remember to delete the lab resources after finishing the labs. This will ensure resources are freed up and cost is minimized. The easiest way to delete the lab resources is to delete the lab resource group.
