# Active Directory & Splunk Home Lab

## 📌 Project Overview
This home lab demonstrates my ability to deploy and configure a basic enterprise environment using Vultr virtual machines. I installed and set up a Windows Server 2022 Domain Controller, a Splunk server for log monitoring, and a Windows test machine to simulate a user endpoint. This project showcases core skills required for an entry-level IT help desk role, including server setup, Active Directory management, and basic log monitoring.

## 🖥️ Lab Setup
**Platform:** Vultr Virtual Machines  
**Virtual Machines Deployed:**
- **Windows Server 2022:** Configured as the Domain Controller with Active Directory and DNS.
- **Splunk Server:** Installed Splunk Enterprise for log collection and monitoring.
- **Windows Test Machine:** Joined to the domain for testing user logins and Splunk log forwarding.

## 🔑 Key Tasks Performed
✅ Provisioned VMs in Vultr  
✅ Installed Windows Server 2022 and promoted to Domain Controller  
✅ Configured Active Directory Domain Services (AD DS) and DNS  
✅ Created Organizational Units (OUs) for users and computers  
✅ Added sample user accounts and security groups  
✅ Installed Splunk Enterprise and set up basic log collection  
✅ Connected the Windows test machine to the domain and verified event log forwarding to Splunk

## 🗺️ Diagram
Include a simple network diagram in `/Diagrams/` showing:
- Vultr Cloud
  - Domain Controller (Windows Server 2022)
  - Splunk Server
  - Windows Test Machine
  - How they communicate (IP addresses, domain structure)

## 📸 Screenshots
Add relevant screenshots in the `/Screenshots/` folder, such as:
- AD Users and Computers (showing OUs and users)
- Splunk Dashboard with example logs
- Windows Test Machine joined to the domain

## ⚡ Skills Demonstrated
- VM provisioning in the cloud (Vultr)
- Windows Server installation & Active Directory configuration
- User and group management
- Basic Splunk installation and log monitoring
- Documentation and diagramming

## 🗂️ How to Reproduce
1. Deploy three VMs on Vultr: Windows Server 2022, Splunk Server, Windows 10 test machine.
2. Install and configure AD DS on the Server 2022 VM.
3. Set up DNS to support domain join.
4. Create OUs, users, and groups.
5. Install Splunk Enterprise on the Splunk VM and configure to receive logs.
6. Join the test machine to the domain and verify log forwarding to Splunk.

## 📞 Contact
Connect with me on [LinkedIn][(https://www.linkedin.com/in/iric-harris/)] to discuss this project or my IT journey.
