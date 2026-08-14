# Week 02 – Enterprise Infrastructure Planning

## Project Overview

This project presents the Enterprise Infrastructure Plan for **ABC Startup Solutions**, a newly established software development company with 20 employees operating on a single office floor.

The project focuses on planning the company's foundational IT infrastructure before deployment. It includes the company profile, hardware inventory, software inventory, network inventory, enterprise network topology, system administration roles, infrastructure recommendations, and personal reflection.

The goal of this project is to design a practical, secure, reliable, and scalable IT infrastructure that supports the company's daily business operations.

---

## Learning Objectives

Through this project, I was able to:

- Explain the roles and responsibilities of a System Administrator.
- Identify the hardware, software, and networking requirements of a small business.
- Prepare professional IT inventories.
- Design an enterprise network topology.
- Create technical documentation using Markdown.
- Present infrastructure planning professionally.
- Apply organization, technical communication, and critical-thinking skills.

---

## Company Scenario

**Company Name:** ABC Startup Solutions

**Nature of Business:** Software Development Company

**Office Location:**  
2nd Floor, ABC Business Center, National Highway,  
Barangay San Isidro, Santa Rosa, Laguna, Philippines

### Employee Distribution

| Department | Employees |
|---|---:|
| Information Technology | 5 |
| Human Resources | 4 |
| Finance | 5 |
| Sales | 6 |
| **Total** | **20** |

The company currently has no computers, server, network, Internet infrastructure, or security policies. The infrastructure plan was therefore designed from scratch.

---

## Hardware Inventory Summary

The proposed hardware infrastructure includes:

| Hardware | Quantity |
|---|---:|
| Desktop Computers | 16 |
| Laptops | 4 |
| Server | 1 |
| Router | 1 |
| Managed Switch | 1 |
| Network Printers | 2 |
| UPS | 2 |
| Wireless Access Points | 2 |
| NAS Storage | 1 |
| External Backup Drives | 2 |
| Monitors | 20 |

The hardware was selected based on the needs of 20 employees and the company's requirement for reliable computing, networking, storage, backup, and power protection.

---

## Software Inventory Summary

The proposed software environment includes:

| Software | Purpose |
|---|---|
| Windows 11 Pro | Employee workstation operating system |
| Ubuntu Server | Server operating system |
| Microsoft 365 Apps | Office productivity |
| Visual Studio Code | Software development |
| Git | Version control |
| GitHub Desktop | Repository management |
| VirtualBox | Virtualization and testing |
| Google Chrome | Web browsing |
| Microsoft Defender | Endpoint security |
| AnyDesk | Authorized remote support |
| 7-Zip | File compression and extraction |

These applications support software development, office productivity, system administration, security, collaboration, and technical support.

---

## Network Inventory Summary

The proposed network infrastructure includes:

| Network Equipment | Quantity |
|---|---:|
| ISP Modem / ONT | 1 |
| Router | 1 |
| Firewall | 1 |
| Managed Switch | 1 |
| Wireless Access Point | 2 |
| Patch Panel | 1 |
| CAT6 Cable | 300 meters |
| RJ45 Connectors | 50 |

The network is designed to provide secure Internet access, wired connectivity, wireless connectivity, server access, and shared printer access.

---

## Enterprise Network Diagram

The network topology was designed using Draw.io.

The topology includes:

- Internet
- ISP Modem
- Router
- Firewall
- Managed Switch
- Server
- Wireless Access Point
- Printer
- IT Department
- HR Department
- Finance Department
- Sales Department

### Network Topology

![Enterprise Network Topology](diagrams/Enterprise-Network-Topology.png)

[View Network Topology PDF](diagrams/Enterprise-Network-Topology.pdf)

---

## Technologies Used

- Draw.io – Network topology design
- Microsoft Word – Technical documentation
- PDF – Final infrastructure plan
- GitHub – Version control and portfolio documentation
- Markdown – README documentation
- Windows 11 Pro – Client operating system
- Ubuntu Server – Server operating system
- Git – Version control
- VirtualBox – Virtualization

---

## System Administration Roles

The project covers four important System Administration roles:

### Helpdesk Technician
Provides first-line technical support, troubleshoots user issues, documents incidents, and escalates complex problems.

### Network Administrator
Manages routers, switches, firewalls, wireless networks, IP addressing, network security, and connectivity.

### Linux System Administrator
Manages Linux servers, users, permissions, storage, services, updates, security, and backups.

### Cloud Administrator
Manages cloud resources, identity and access, storage, networking, monitoring, security, backups, and cloud costs.

### Collaboration

These four professionals work together to maintain reliable and secure IT operations. The Helpdesk Technician handles initial user issues and escalates technical problems when necessary. The Network Administrator maintains network connectivity and security, while the Linux System Administrator manages server infrastructure. The Cloud Administrator handles cloud-based services and resources. Through proper documentation, communication, escalation, and teamwork, they ensure that the organization's IT infrastructure remains available, secure, and efficient.

---

## Infrastructure Recommendations

The infrastructure plan recommends:

- Business-grade fiber Internet connection
- Business-class server with sufficient processing power and ECC memory
- RAID 1 storage for important server data
- 3-2-1 backup strategy
- Firewall and network segmentation
- Regular operating system and software updates
- Microsoft Defender for Windows endpoints
- Strong password policy
- Multi-factor authentication where available
- Least-privilege access
- Future expansion of network ports, storage, wireless coverage, and Internet bandwidth

These recommendations are intended to provide a secure, reliable, and scalable infrastructure for the startup.

---

## Challenges Encountered

One of the main challenges was determining realistic hardware and network requirements for a company with only 20 employees. It was necessary to balance cost, performance, security, and future expansion.

Another challenge was designing the network topology so that the Internet connection, router, firewall, managed switch, server, wireless access point, printer, and departments were logically connected.

Preparing the inventories also required careful consideration of the purpose and quantity of each hardware, software, and network component.

---

## Reflection

This project helped me understand that system administration requires proper planning before actual deployment. I learned how to identify business requirements and translate them into hardware, software, network, security, and backup requirements.

The most challenging part was designing an infrastructure that is realistic for a startup while still providing security, reliability, and room for future growth.

The project also improved my understanding of network topology, IT inventories, system administration roles, technical documentation, and infrastructure recommendations.

Overall, this activity helped me develop practical skills that can be useful in becoming a System Administrator.

---

## References

- ITEP 414 – System Administration and Maintenance, Week 2 Portfolio Project.
- Cisco – Network Administration and Networking Certification Resources.
- Linux Foundation – Linux System Administration and LFCS Resources.
- AWS – AWS Cloud Practitioner Resources.
- Globe Business – Business Internet Services.

---

## Project Deliverables

- `EnterpriseInfrastructurePlan.pdf`
- `README.md`
- `diagrams/Enterprise-Network-Topology.png`
- `diagrams/Enterprise-Network-Topology.pdf`
