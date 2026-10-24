# Small Business Network Security Design

## 1. Project Overview
This project presents a secure network design for a small
business with approximately 20 employees.

The design aims to improve network segmentation, access
control, wireless security, monitoring, and data protection.

## 2. Project Objectives
- Design a segmented office network using VLANs.
- Propose firewall rules and access control.
- Separate employee devices from guest Wi-Fi.
- Recommend secure wireless access and MFA.
- Improve security monitoring and backup practices.

## 3. Business Scenario
A small business uses employee computers, printers,
wireless devices, and internal servers.

Without proper network segmentation and access control,
unauthorised access could expose business systems and data.

## 4. Proposed Network Components
- Internet connection
- Firewall and router
- Managed network switch
- Employee computers
- Wireless access point
- Internal servers
- Guest wireless network
- Monitoring and backup systems

## 5. Network Segmentation

| VLAN | Purpose | Example subnet |
|---|---|---|
| VLAN 10 | Employees | 192.168.10.0/24 |
| VLAN 20 | Guest Wi-Fi | 192.168.20.0/24 |
| VLAN 30 | Servers | 192.168.30.0/24 |
| VLAN 40 | IT management | 192.168.40.0/24 |

These are example private network addresses.

## 6. Security Controls
- Firewall rules based on least privilege.
- WPA3 wireless security where supported.
- Multi-factor authentication for administrative accounts.
- Restricted access between VLANs.
- Centralised security logging.
- Regular patching and vulnerability reviews.
- Encrypted backups and recovery testing.

## 7. Testing Plan
- Verify that guest devices cannot access internal servers.
- Verify that only authorised users can access management systems.
- Check firewall logs for blocked traffic.
- Test backup restoration.
- Review wireless security settings.

## 8. Expected Benefits
The proposed design aims to reduce unnecessary network
access, improve visibility, and limit the spread of incidents.

## 9. Limitations
This is a conceptual design, not a deployed production network.
Actual security depends on implementation, testing, monitoring,
and ongoing maintenance.

## 10. Learning Outcomes
This project develops my understanding of network security,
VLANs, firewall policies, access control, and technical reporting.

## Disclaimer
This project is for educational purposes. All network
addresses and scenarios are examples.

