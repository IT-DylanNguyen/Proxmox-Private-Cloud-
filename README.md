# Proxmox-Private-Cloud
Self-hosted private cloud for the foundation of future IT/Security projects

# 🖥️ Proxmox Private Cloud on Repurposed Hardware ☁️

## Overview
This project repurposes old PC hardware to build a **Proxmox Virtual Environment (PVE)**, transforming outdated components into a **private cloud** for IT projects, virtualization, and cybersecurity labs.

## 🔧 Project Objectives
- Convert old hardware into a **functional Proxmox server**
- Deploy **Windows, Linux, and security-focused VMs**
- Implement **networking, firewall rules, and remote access**
- Optimize hardware resources for **homelab IT experiments**
- Prepare for **SIEM & cybersecurity monitoring (Splunk, ELK Stack)**

## 🏗️ Hardware Used
| Component     | Model/Details |
|--------------|--------------|
| **CPU**      | Intel i7-8700 |
| **Motherboard** | MSI Z490-A PRO |
| **RAM**      | 32GB DDR4 |
| **Storage**  | 2x 512GB SSDs, 1TB HDD |
| **Power Supply** | 750W EVGA |
| **Case**     | Custom-built |

## 🛠️ Software & Technologies
- **Hypervisor**: Proxmox VE
- **Networking**: Eero Router (DHCP/NAT), Proxmox Bridge
- **Security Monitoring**: Splunk, ELK Stack (Future Implementation)
- **Virtual Machines**: 
  - **Windows 11** (for management & remote access)
  - **Ubuntu Server** (for Splunk/SIEM)
  - **Kali Linux** (for security testing)

## 🔌 Network Configuration
- Configured **DHCP & NAT** via **Eero router**
- Set up **Proxmox Bridge (vmbr0)**
- Allowed remote access through **firewall rules**
- Configured **static IPs for VMs**

## 📷 Project Images
### Hardware Assembly
![Hardware Setup]
![proxmox 1](https://github.com/user-attachments/assets/510b7cc4-1187-418d-9ea1-f15604ac17f8)
![proxmox 2](https://github.com/user-attachments/assets/0349f845-d81a-4a33-851e-12da394b560c)


### Proxmox Installation
![Proxmox Install]
![proxmox 3](https://github.com/user-attachments/assets/d0480828-f88e-4144-91aa-21c3b334bcda)
![proxmox 4](https://github.com/user-attachments/assets/145a1f9c-d0cc-46de-bc0a-81e8dc59d819)
![proxmox 5](https://github.com/user-attachments/assets/ee057d22-9f4d-4c05-8181-d08a3d00b530)
![proxmox 6](https://github.com/user-attachments/assets/271d8d43-53c0-42de-960f-a64812058014)
![proxmox 7](https://github.com/user-attachments/assets/e8db5e9c-f45f-4dc2-959c-0b91728bafab)
![proxmox 8](https://github.com/user-attachments/assets/8caf20de-a69b-47e6-ac93-0ce6e4d34d36)
![proxmox 9](https://github.com/user-attachments/assets/2cff20b5-8089-45c4-bfab-40ee875878fb)
![proxmox 10](https://github.com/user-attachments/assets/613db108-faf9-44e4-be5b-3d69b7511ce2)

### Virtual Machines Running
![VM Dashboard]
![proxmox 11](https://github.com/user-attachments/assets/65d1ad7e-aebc-4ed8-92d4-fe58f29fd55d)
![proxmox 12](https://github.com/user-attachments/assets/481699d0-ef84-4ad8-a64e-1d0c5e7d8d05)
![proxmox 13](https://github.com/user-attachments/assets/7d4527a9-455c-42d3-9b42-f23f9fb71f76)
![proxmox 14](https://github.com/user-attachments/assets/2459d816-2a2d-4cbd-9a81-b4cd4bc2066e)

## 🚀 Future Plans
- **Install & configure Splunk** for SIEM & log analysis
- **Set up ELK Stack** for log visualization
- **Automate VM deployments** via Ansible
- **Expand storage** with additional SSDs

## 🔗 References
- [Proxmox Official Documentation](https://pve.proxmox.com/wiki/Main_Page)
- [Tailscale VPN for Remote Access](https://tailscale.com/)
- [Splunk Free Trial](https://www.splunk.com/)

---
### 📌 *This project is a work in progress! Contributions & feedback are welcome!* 🚀
