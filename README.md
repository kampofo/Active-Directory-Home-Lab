# Active Directory Home Lab  

## Overview  
This project is a hands-on **Active Directory (AD) home lab** built using **VirtualBox, Windows Server 2022, and Windows 10**. The lab simulates a small corporate environment where a domain controller manages authentication, DHCP, DNS, NAT, and Windows clients.  

The goal of this project was to strengthen my knowledge of:  
- **Active Directory Domain Services (AD DS)**  
- **Networking services (DHCP, DNS, NAT)**  
- **Domain user and client management**  
- **Automation with PowerShell**  

---

## Lab Setup  
- **Domain Controller (DC)**: Windows Server 2022  
- **Client Machine**: Windows 10 Pro  
- **Virtualization**: VirtualBox  
- **Domain**: `mydomain.com`  

---

## Key Configurations  
- Installed **AD DS** and promoted server to Domain Controller.  
- Created **Organizational Units (OUs)** for admins and employees.  
- Configured **DHCP** (scope: `172.16.0.100 – 172.16.0.200`) and **NAT** for network connectivity.  
- Automated **bulk user creation** with PowerShell (1,000 accounts).  
- Joined a **Windows 10 client** to the domain and validated login with AD credentials.  

---

## Screenshots  
*(Add screenshots here in order — e.g., AD DS install, OU setup, DHCP config, PowerShell script run, client domain join success, etc.)*  

---

## Key Takeaways  
- Built and configured an **Active Directory domain** from scratch.  
- Learned how **DNS, DHCP, and NAT** integrate into a domain environment.  
- Automated large-scale **user account creation** with PowerShell.  
- Successfully **joined and authenticated a client machine** within the domain.  

---

## Next Steps  
- Implement **Group Policy Objects (GPOs)** for centralized management.  
- Explore **permissions, shares, and security policies** across the domain.  
- Expand the lab with **additional clients or servers** for more advanced scenarios.  
