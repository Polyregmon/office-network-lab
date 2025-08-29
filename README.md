# Office Network Lab

A complete home lab for a small office network using Windows Server 2025, Windows 11, Firewall, and Wazuh SIEM.  
Built in VMware Workstation and GNS3.

---

## Topology
[<img width="1194" height="656" alt="Topology" src="https://github.com/user-attachments/assets/cd437748-5b52-4d50-b497-cd500651793f" />](https://github.com/Polyregmon/office-network-lab/blob/main/docs/screenshots/Topology.png)

---

## Services Configured
### Core Network
- DHCP
- DNS
- Active Directory Domain Services (AD DS)
- File Server with permissions
- Group Policy Objects (GPOs)

### Security
- Firewall with NAT and ACL rules
- Wazuh SIEM for:
  - Log collection
  - Intrusion detection
  - Alerting and reporting

---

## Tools Used
- VMware Workstation
- Windows Server 2025
- Windows 11
- GNS3 (for routing)
- pfSense(for firewall)
- Wazuh SIEM (latest stable version)
- Kali Linux (for testing)

---

## Skills Gained
- Domain design and administration
- Firewall rule design and troubleshooting
- SIEM configuration and log analysis
- Active Directory and DNS troubleshooting
- Security event detection and response
- Integration of multiple network services

---

## How to Reproduce
1. Clone the repo or download the documentation.
2. Follow the Step-by-step.md guide for:
   - Network core setup
   - Firewall configuration
   - Wazuh server installation and agent setup
3. Test and verify connectivity and security alerts.

---

## Screenshots
| Step | Description | Screenshot |
|-------|-------------|------------|
| 1 | DHCP configuration | https://github.com/Polyregmon/office-network-lab/blob/17eebd843f6f1677f70ba90bba4f35923730c613/docs/screenshots/DHCP.png |
| 2 | Wazuh alerts dashboard | [<img width="836" height="656" alt="DHCP" src="https://github.com/user-attachments/assets/e53f5d1b-26d6-4d31-a4e0-4ff04eb47690" />](https://github.com/Polyregmon/office-network-lab/blob/main/docs/screenshots/Wazuh.jpg) |
| 3 | Firewall rule table |[ <img width="836" height="656" alt="DHCP" src="https://github.com/user-attachments/assets/a38ef0aa-04d5-407f-a683-c28347dc3689" />](https://github.com/Polyregmon/office-network-lab/blob/main/docs/screenshots/Firewall%20Rules.jpg)|
