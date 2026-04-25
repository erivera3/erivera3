# Eladio Rivera  
**IT Support | System Administration | Networking**

Boarding Director with 12+ years managing high-accountability environments, transitioning into IT support and system administration with a focus on infrastructure, access control, and system operations.

Experience building and managing lab environments across Active Directory, Azure, virtualization, network infrastructure, and security, emphasizing troubleshooting, system behavior, escalation workflows, and real-world operational scenarios.

---

## 🛠 Core IT Skills
- Active Directory administration  
- Help desk workflows & ticketing systems (osTicket)  
- Windows & Azure lab environments  
- Virtualization (Proxmox)  
- Networking fundamentals (TCP/IP, DNS, DHCP, VLANs)  
- Firewall configuration (OPNsense / pfSense)  
- Troubleshooting & system diagnostics  
- Technical documentation  

---

## 💻 IT Support & System Administration Labs

### 🔹 Help Desk & Ticketing Systems (osTicket)
- [osTicket: Deployment in Azure (Web Application Simulation)](https://github.com/erivera3/osticket-prereqs/)  
- [osTicket: Help Desk Deployment & Service Configuration (Enterprise Simulation)](https://github.com/erivera3/post-install-config)  
- [osTicket: Ticket Lifecycle Examples (Enterprise Simulation)](https://github.com/erivera3/ticket-lifecycle)  

**Skills:** ticket workflows, user support, troubleshooting, escalation, system configuration  

---

### 🔹 Microsoft Azure & Active Directory
- [Active Directory Deployment in Azure (Enterprise Simulation)](https://github.com/erivera3/configure-ad/)  
- [Azure Network Security Groups (NSGs) & Traffic Inspection (Enterprise Simulation)](https://github.com/erivera3/azure-network-protocols)  

**Skills:** user/group management, domain services, cloud environments, network security  

---

### 🔹 Homelab Infrastructure (Enterprise-Style Lab)
- Homelab: Proxmox, TrueNAS, Active Directory, DNS, Firewall *(repo coming soon)*  

---

## ⚡ Infrastructure Evolution & Engineering Decisions

This environment was built through multiple iterations based on real-world constraints: power, heat, noise, and system limitations.

### Phase 1 — Dual Legacy Systems
- Separate systems for:
  - Proxmox (virtualization)
  - TrueNAS (storage)
- Removed GTX 970 GPU to reduce heat and power consumption
- Converted systems to headless operation

### Phase 1A — Thermal Optimization
- Cleaned systems using compressed air
- Reapplied CPU thermal paste
- Reduced fan load and improved cooling efficiency

### Phase 1B — Airflow Redesign
- Identified inefficient fan layout (5 fans causing turbulence)
- Corrected airflow path (front → back)
- Eliminated heat recirculation

**Key Insight:** More fans ≠ better cooling — airflow design matters

---

### Phase 2 — Storage Consolidation (UGREEN NAS)

**Problem:**
- Multiple HDDs scattered across systems
- No centralized storage
- Poor data organization

**Solution:**
- Purchased UGREEN DXP4800 Pro NAS
- Replaced factory OS with TrueNAS SCALE

**Actions:**
- Backed up original OS using Rescuezilla
- Verified disk image integrity
- Removed drives before install (data protection)
- Installed TrueNAS and prepared ZFS pools

**Outcome:**
- Centralized storage system
- Improved data organization
- Full control over NAS environment

---

### Phase 3 — Network & Router Evolution
- Reflashed routers:
  - DD-WRT → OpenWRT
- Learned limitations of consumer firmware
- Transitioned to more flexible network control

---

### Phase 4 — Firewall Architecture
- Built dedicated firewall system (Intel N150, 4 NICs)
- Tested pfSense → migrated to OPNsense
- Learned:
  - interface mapping
  - routing
  - firewall segmentation

---

### Phase 5 — Virtualization Strategy Expansion
- Installed Proxmox on firewall hardware
- Virtualized:
  - OPNsense (firewall)
  - Pi-hole (DNS filtering)

**Outcome:**
- Service isolation
- Flexible infrastructure design
- Consolidated network services

---

### Phase 6 — Modern Infrastructure Upgrade
- Migrated to Minisforum MS-A2
- 32GB DDR5 + NVMe + ZFS

**Result:**
- Reduced power consumption
- Lower heat and noise
- Stable 24/7 operation

---

### Phase 7 — Active Directory & DNS
- Deployed Windows Server 2022 (DC01)
- Created domain: lab.local
- Configured DNS (192.168.1.20)

**Work Performed:**
- Created DNS records
- Fixed DNS failures (systemd-resolved)
- Integrated DHCP with domain DNS

---

### Phase 8 — Real-World Deployment (School Systems)

- Acquired decommissioned school computers
- Removed from legacy Active Directory domain
- Performed full disk sanitization
- Installed Zorin OS

**Deployment:**
- ~13 systems used for:
  - Scratch programming
  - hardware introduction for students

---

### Phase 9 — OS Deployment Strategy (PXE Attempt)

**Goal:**
- Automate deployment using PXE server

**Actions:**
- Built Ubuntu PXE server
- Attempted network ISO deployment

**Challenges:**
- PXE complexity (DHCP/TFTP/bootloader)
- Time constraints

**Final Solution:**
- Used 4 USB drives with Balena Etcher
- Deployed OS in parallel manually

**Outcome:**
- Successful deployment to all systems

**Key Insight:**
Automation is powerful—but execution under constraints is critical

---

## 🧩 What These Projects Demonstrate
- Real-world IT problem solving  
- Infrastructure-level thinking  
- Root-cause analysis and iteration  
- System lifecycle management  
- Hardware + software integration  
- Adaptability under constraints  

---

## 🚨 Operational Incident Response (Transferable Skills)

- [Wildfire Incident Response System](https://github.com/erivera3/wildfire-incident-response-system/)  
- Earthquake Response Protocol *(coming soon)*  
- Campus Security Intruder Response *(coming soon)*  

**Skills:** incident response, escalation, coordination, decision-making  

---

## 📘 Certifications & Coursework
- Google IT Support Certificate  
- Google Networking Certificate  

---

## 🎯 Current Focus
- Networking & VLAN segmentation  
- Firewall deployment (OPNsense)  
- Active Directory expansion  
- Infrastructure documentation  

---

## 🤝 Connect
- [LinkedIn](https://www.linkedin.com/in/eladiorivera/)  
- [GitHub](https://github.com/erivera3)
