# POC Portfolio

A collection of my automation scripts and virtual lab configurations for Windows Server 2022 and Linux environments.

## Projects

### 0. Dracs VmMt (Virtual Machine Management Tool)
- **Dracs-VmMt:** A centralized orchestration and tracking tool for virtual lab environments. Features include batch startup of VMs, individual VM control, and an integrated lookup dashboard for tracking NAT port forwarding rules, allowing for quick SSH connections without having to manually check hypervisor settings for each lab. Currently supports VirtualBox, with V2.0 expansion into VMware integration in development.
![Dracs VmMt Showcase](https://youtube.com/shorts/CGiZnRA7y6k)

### 1. Active Directory Automation
- **ActiveDirectory-Mass-Provisioning-Script:** Automated 1,000+ user account creation and OU management.
![AD Mass Provisioning Screenshot](./ActiveDirectory-Mass-Provisioning-Script.jpeg)

- **CSV-to-AD-Bulk-Importer:** Robust bulk import tool with `try/catch` error handling for existing accounts.
![CSV to AD Importer Screenshot](./CSV-to-AD-Bulk-Importer.jpeg)

### 2. Lab Infrastructure & Networking
- **Multi-Distro-VirtualBox-Lab:** Configured virtualized network environments running multiple Linux distributions (Arch, Kali, Debian, Ubuntu, Fedora Server).
![VirtualBox Environment](./virtualbox-labs.jpeg)

- **NAT Port Forwarding Configuration:** Implemented custom NAT port forwarding rules (e.g., mapping Host Port 2224 to Guest Port 22) to allow external SSH connectivity into isolated test environments.
![Port Forwarding Config](./port-forwarding-config.jpeg)

- **Lab Management Tool:** Inventory tracking script for host/guest port mappings.
![Lab Management Tool Screenshot](./Lab%20Management%20Tool.jpeg)

## Proof of Concept
I have included screenshots verifying my manual type 2 hypervisor configurations, network routing rules, and Active Directory scripting environments.
