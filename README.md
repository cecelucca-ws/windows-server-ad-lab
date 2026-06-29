# Windows Server Enterprise Lab

## Overview

This repository documents a complete enterprise-style Windows Server environment built for hands-on learning and professional portfolio development.

The lab simulates a corporate infrastructure using Hyper-V and Windows Server technologies.

## Technologies

- Active Directory Domain Services
- DNS
- DHCP
- Hyper-V
- RRAS
- NAT
- Group Policy
- File Services
- PowerShell
- PKI
- Windows Client Management

## Lab Roadmap

| Module | Status |
|----------|----------|
| Active Directory Foundation | ✅ |
| DNS Integration | ✅ |
| DHCP Deployment | ✅ |
| Hyper-V Networking | ✅ |
| RRAS NAT | ✅ |
| Group Policy | ⏳ |
| File Services | ⏳ |
| PowerShell Automation | ⏳ |
| PKI | ⏳ |

## Architecture

```text
Internet
   |
Router
   |
Domain Controller
├─ External NIC
└─ Internal NIC
       |
Internal Hyper-V Switch
       |
Workstations
