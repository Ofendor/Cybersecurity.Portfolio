<p align="left">
  <a href="https://www.linkedin.com/in/emilio-mardones" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-emilio--mardones-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:milomardones.nc@proton.me">
    <img src="https://img.shields.io/badge/Email-Proton%20Mail-6D4AFF?style=flat-square&logo=protonmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://drive.proton.me/urls/M4S25QMFWG#2sGnu7eeo8jt" target="_blank">
    <img src="https://img.shields.io/badge/CV-Download-2EA44F?style=flat-square" alt="CV" />
  </a>
  <a href="https://github.com/Ofendor" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Ofendor-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.credly.com/users/emilio-mardones" target="_blank">
    <img src="https://img.shields.io/badge/Credly-Badges-FF6B00?style=flat-square&logo=credly&logoColor=white" alt="Credly" />
  </a>
</p>


```python
print("Kia ora koutou!")
```

## Introduction

My name is Emilio Mardones, and I am based in Aotearoa, New Zealand. I recently completed a Level 7 Diploma in Network Engineering & Cloud Computing and am building my career at the intersection of cloud infrastructure, networking, and cybersecurity.

This portfolio is an index of the hands-on projects, labs, and research I have published so far. My work spans:

- Cloud infrastructure labs in Azure, with growing focus on OpenStack and Kubernetes
- Network design, segmentation, and security hardening
- Malware analysis and sandbox research
- Python automation and IoT integrations
- Packet capture and protocol analysis with Wireshark and tcpdump
- Security reporting aligned with NIST and MITRE ATT&CK
- Continuous learning through TryHackMe and Hack The Box

This page will continue to evolve as I publish new labs, projects, and research.

## Skills & Tooling

- **Networking:** segmentation, hardening, DNS / ICMP / TCP analysis, tcpdump, Wireshark
- **Cloud & Infrastructure:** Azure, OpenStack, Kubernetes, Docker / Docker Compose
- **Security:** malware analysis, SIEM (Wazuh), threat intelligence, NIST, MITRE ATT&CK
- **Scripting:** Python, PowerShell, Bash

## Projects

### Infrastructure, Cloud & DevOps

| Project | Description | Stack | Status |
| --- | --- | --- | --- |
| [DevOps Portfolio Lab](https://github.com/Ofendor/devops-lab) | Six-phase DevOps build on a single Ubuntu 24.04 VM: Linux fundamentals, Docker with Prometheus/Grafana observability, Kubernetes (K3s) and cluster security, Ansible and GitLab CI/CD, and an integrated multi-service app (Flask/MySQL/Redis) behind an Nginx reverse proxy. Emphasis on infrastructure-as-code, container image scanning, and OpenStack / data-sovereignty concepts. | Ubuntu, Docker, Kubernetes (K3s), Ansible, Prometheus, Grafana, Nginx, Flask, MySQL, Redis, Trivy, Grype, GitLab CI | ✅ Completed |
| [SCADA IoT Lab — ICS Environment](https://github.com/Ofendor/scada-iot-lab) | Simulated ICS/SCADA environment modelling a fictional Auckland water treatment facility (AquaNet NZ, Avondale catchment). Streams six live sensor values — turbidity, E.coli, pH and nitrate from real LAWA 2004–2024 data, plus pipe pressure and flow from an EPANET hydraulic model — over MQTT into a Scada-LTS HMI dashboard, with a Python monitor logging readings and raising NPS-FM 2020 threshold alerts. Includes a security write-up on unencrypted MQTT/Modbus weaknesses, hardening steps, and real-world ICS incidents. | Python, paho-mqtt, Eclipse Mosquitto, Scada-LTS, ScadaBR, Docker Compose, MySQL, EPANET/EPyT, Ubuntu | ✅ completed |

### Systems Administration & Service Desk

| Project | Description | Stack | Status |
| --- | --- | --- | --- |
| [Service Desk Support Lab](https://github.com/Ofendor/Service-Desk-Support-Lab) | Windows Server 2022 domain (AD DS, DNS, DHCP) with a domain-joined Windows 11 client and a Debian/Docker osTicket ticketing system. Around two dozen PowerShell/Bash automation scripts, Group Policy work (password, lockout, logon-hours, drive mapping), WSUS patch management, Intune device enrolment, and realistic help-desk ticket simulations — onboarding, resets, account unlocks, NTFS/share permissions. | Windows Server 2022, Active Directory, DNS, DHCP, Group Policy, WSUS, Intune, PowerShell, osTicket, Docker, MariaDB, Nginx, Debian | 🔄 In Progress |

### Network & Traffic Analysis

| Project | Report | Status |
| --- | --- | --- |
| [DNS & ICMP Traffic Analysis with tcpdump](https://github.com/Ofendor/Portfolio1-Analysing-Network-communications) | <a href="https://ofendor.github.io/Portfolio1-Analysing-Network-communications/">Network traffic activity report</a> | ✅ |
| [TCP Protocol & SYN Handshake Log Analysis with Wireshark](https://github.com/Ofendor/Portfolio2-Analysing-Network-Attacks) | <a href="https://ofendor.github.io/Portfolio2-Analysing-Network-Attacks/">Network attack report</a> | ✅ |

### Malware Analysis

A self-directed malware analysis study conducted in an isolated VirtualBox environment, based on *Practical Malware Analysis* (Sikorski & Honig) and *Evasive Malware* (Cucci, 2024), following safe handling practices.

**Repository → [malware-analysis-lab](https://github.com/Ofendor/malware-analysis-lab)**

Documented inside the repository so far (open the repository above to read each entry):

| # | Lab | Category | Tools | Status |
| --- | --- | --- | --- | --- |
| 01a | Lab Setup & Safe Analysis Environment | Setup | VirtualBox, Windows LTSC, REMnux | ✅ |
| 01b | FLARE-VM Troubleshooting Log | Troubleshooting | Chocolatey, Python, DISM | ✅ |
| 02a | Sample Acquisition | Acquisition | 7-Zip, unrar, Linux | ✅ |
| 02b | Hash Verification & Threat Intelligence | Static | PEview, strings, VirusTotal | ✅ |
| 02c | SIEM Integration & NAT Simulation | Infrastructure | Wazuh, INetSim, DNSChef | ✅ |
| 03 | Static Analysis — String Extraction | Static | strings, FLOSS | 🔄 |
| 04 | Behaviour Analysis | Dynamic | Process Monitor, Wireshark, x64dbg | 🔄 |

## Certifications

**2024 — Google Cybersecurity Professional Certificate (Coursera)**
[Main certificate](https://drive.google.com/file/d/12MpTK7f06sfj6RC-NY48VOSnq_j2WYAd/view?usp=sharing) · [Credly profile](https://www.credly.com/users/emilio-mardones)

- [Foundations of Cybersecurity](https://coursera.org/share/48a44f7bd12d318186045eb7c62342da)
- [Managing Security Risks](https://coursera.org/share/ddb6c36249e444df898624cf9567aa05)
- [Network Security](https://coursera.org/share/38ab1d68036cb56bc093082ab335d0c1)
- [Linux and SQL](https://coursera.org/share/d751138500d05e5257d59fe6b137679b)
- [Assets, Threats, and Vulnerabilities](https://coursera.org/share/e3f8eafdd79dd50e8e778e00373cc625)
- [Detection and Response](https://coursera.org/share/9fe916483f218dddd8f544b0406db8a6)
- [Automating Security Tasks with Python](https://coursera.org/share/bf47f0e56b5dc708b5735105288cd2ec)
- [Communicating with Stakeholders and Escalating Incidents](https://coursera.org/share/147e4017a76017e37d87a52c821c5512)

**2024 — EC-Council**

- [SQL Injection Attacks](https://drive.google.com/file/d/13mJFjTMqs2Pk3WYhqKZf-saOyT6DciAt/view)
- *[Current]* Network Defense Fundamentals Career Path

**2024–2025 — Cisco Networking Academy**

- [Introduction to Cybersecurity](https://drive.google.com/file/d/1so9GHoRlknjTD5U9qUVI5D-QyJvhB06w/view?usp=sharing)
- [Network Technician: Network Basics](https://drive.google.com/file/d/19MKnnmIVnbhw2Y7ySmNnCkaStiEGDOHT/view?usp=sharing)
- *[Current]* Networking Devices and Initial Configuration
- *[Current]* Python 1 for Networking

**2024 — Cybrary**

- [The MITRE ATT&CK Framework](https://drive.google.com/file/d/1loLTSzUfVHYcjGc8u4asRxGAteYKu75M/view?usp=sharing)

**2024–2025 — TryHackMe**

- [Cybersecurity and Network Security](https://drive.google.com/file/d/1zY9YeLcZvC5ohbS7INzbhUxr8ySP_apz/view?usp=sharing)
- *[Current]* SOC Level 1 Career Path
