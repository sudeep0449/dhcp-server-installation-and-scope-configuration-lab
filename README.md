# DHCP Server Installation and Scope Configuration Lab

## Lab Overview

A hands-on Windows Server 2022 lab focused on installing and configuring the DHCP Server role, integrating it with Active Directory, creating a DHCP scope, and managing IP address allocation for a domain network (`sudeep.local`).

## Environment

- **Platform:** Windows Server 2022 (`winserver2022.sudeep.local`), running in Oracle VirtualBox
- **Domain:** Active Directory-integrated (`sudeep.local`)
- **DHCP Scope:** `192.168.1.100` – `192.168.1.200`
- **Subnet Mask:** `255.255.255.0` (/24)
- **DNS Server (scope option):** `192.168.1.10`

## Topics Covered

- DHCP Server role installation
- DHCP Server authorization in Active Directory
- DHCP console management
- DHCP scope creation via the New Scope Wizard
- IPv4 scope and IP address range configuration
- Subnet mask configuration
- DHCP lease duration configuration
- Default gateway configuration
- DNS server and parent domain (scope options) configuration
- Active Directory integration
- Centralized network address management

## Conclusion

Successfully deployed and configured a DHCP Server in Windows Server 2022, including scope creation, gateway and DNS integration, and centralized IP address management for an Active Directory domain environment.

## Full Documentation

[`DHCP Server Installation and Scope Configuration in ADDS lab.pdf`](<./DHCP Server Installation and Scope Configuration in ADDS lab.pdf>) contains the full step-by-step write-up with all implementation screenshots.

## Author

**Sudeep Kumar Chaurasiya**

Bachelor of Information Technology (Networking / Cyber Security)
Melbourne Institute of Technology, Sydney

GitHub: [github.com/sudeep0449](https://github.com/sudeep0449)
