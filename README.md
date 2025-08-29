# Office Network Lab

A complete home lab for a small office network using Windows Server 2025, Windows 11, Firewall, and Wazuh SIEM.  
Built in VMware Workstation and GNS3.

---

## Topology
<img width="1194" height="656" alt="Topology" src="https://github.com/user-attachments/assets/cd437748-5b52-4d50-b497-cd500651793f" />

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
| 1 | DHCP configuration | <img width="836" height="656" alt="DHCP" src="https://github.com/user-attachments/assets/3338aafc-df57-4eaf-923f-9836c8531bf8" /> |
| 2 | Wazuh alerts dashboard | ![Wazuh](screenshots/wazuh.png) |
| 3 | Firewall rule table | ![Firewall](screenshots/firewall.png) |
