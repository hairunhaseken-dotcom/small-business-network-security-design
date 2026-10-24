# Proposed Network Architecture

```mermaid
flowchart TD
    Internet((Internet)) --> FW[Firewall and Router]
    FW --> SW[Managed Switch]

    SW --> V10[ VLAN 10 - Employees ]
    SW --> V20[ VLAN 20 - Guest Wi-Fi ]
    SW --> V30[ VLAN 30 - Servers ]
    SW --> V40[ VLAN 40 - IT Management ]

    V10 --> PC[Employee Computers]
    V20 --> Guest[Guest Devices]
    V30 --> Server[Business Servers]
    V40 --> Admin[Admin Workstation]

    FW --> Logs[Security Logging]
```

## Security Design Notes

- Guest Wi-Fi should not access internal business systems.
- Server access should be restricted to authorised services.
- Administrative access should be limited to approved devices.
- Inter-VLAN traffic should follow explicit firewall policies.
- Security logs should be protected from unauthorised changes.
