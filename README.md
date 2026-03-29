# Active Directory Lab Setup
I built an Active Directory in Windows Server 2019 virtual machine, and configured a domain and connected client machines through Windows 10 virtual machine. My goal is to understand how majority of companies use an Active Directory to manage networks, users, authentication and resources.

<img width="1811" height="1082" alt="image" src="https://github.com/user-attachments/assets/ad0bca75-ba79-4966-8eee-8a5887fa7794" />


# ⚙️ Lab Setup
 - **Server**: Windows Server 2019 (Domain Controller)
 - **Client**: Windows 10
 - **Network**: NAT + Internal Network

# 🧱 Services Configured 
 **Network Configuration**: NAT will get the addressing come from the home router. Internal Network will be configured through the Domain Controller (Windows Server 2019) giving the Internal Network an IP address, Subnet Mask, and a DNS.
+ <img width="1278" height="717" alt="image" src="https://github.com/user-attachments/assets/c65d0728-36fd-47c2-8463-c78f29e25f0c" />


**DNS (Domain Name System)**: Configured a domain name resolution for admins and clients. This ensures that clients are able to locate the domain controller through a private internal network.
+ <img width="1280" height="721" alt="image" src="https://github.com/user-attachments/assets/e3a60742-863a-4263-9463-e130aa816bb9" />

**Routing/Remote Access Service**: Configured the Routing and Remote Access to allow internal clients/devices to connect to the Internet using one public IP address (Network Address Translation).

+ <img width="621" height="442" alt="image" src="https://github.com/user-attachments/assets/d8f0de19-851e-4f4b-ad95-4cb5d2a589e0" />

**DHCP (Dynamic Host Configuration Protocol)**: DHCP is a network protocol that automatically assigns IP addresses to devices on a network. On the Active Directory, DHCP is configured by adding a scope allows grouping of IP addresses for devices on a subnet that DHCP can lease to clients. This reduces the need for manual network configuration.

+ <img width="1275" height="718" alt="image" src="https://github.com/user-attachments/assets/a9498824-8f76-4644-82c9-343d17703b95" />

**Adding Users with a PowerShell Script**: 
<!--


Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
