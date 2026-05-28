# Hi, I'm Arshand R N 👋

**Self-trained SOC Analyst | B.E. ECE Graduate | Blue Team**

📍 Coimbatore, Tamil Nadu, India

[![Portfolio](https://img.shields.io/badge/Portfolio-arshand--portfolio.web.app-blue)](https://arshand-portfolio.web.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-arshandrn-0077B5?logo=linkedin)](https://linkedin.com/in/arshandrn)
[![LetsDefend](https://img.shields.io/badge/LetsDefend-defender20-orange)](https://app.letsdefend.io/user/defender20)

---

## About Me

Self-trained SOC Analyst with hands-on experience building 
real detection pipelines - not just theoretical knowledge.

- Engineered a full-stack **Splunk + Wazuh + Snort** SOC lab 
  that caught a simulated end-to-end cyberattack including C2
- Wrote **5 custom Snort rules** mapped to real CVEs with 
  **100% detection rate** across all simulated attack types
- Engineered a hybrid-cloud SOC automation pipeline using Splunk SOAR, reducing Tier-1 incident triage time from minutes to seconds
- Deployed Cowrie honeypot capturing **12 structured events** 
  including attacker IP, session commands, and session duration
- Completed **20+ SOC alert investigations** with MITRE ATT&CK 
  mapping and incident reporting on LetsDefend
- Secondary strength in enterprise network design - VLAN, 
  HSRP, Zero-Trust ACL, NAT/PAT in Cisco Packet Tracer

---

## Projects

### 🔴 Comprehensive SOC Simulation - Splunk + Wazuh + Snort
> Primary focus: Full-chain attack detection across SIEM + EDR + NIDS

**[View Repo](https://github.com/arshandrn/soc-splunk-wazuh-snort)**
&nbsp;|&nbsp;
**[View Report](https://arshand-portfolio.web.app/assets/soc.pdf)**

Architected a 3-VM SOC lab with a unified detection pipeline.
Simulated a complete cyberattack and detected every stage.

| Attack Stage | Tool Used | Detection Result |
|---|---|---|
| Nessus SYN Recon | Snort NIDS | 108 alerts aggregated in Splunk |
| SMB Brute Force | Wazuh + Splunk | 51 Event ID 4625 failures logged |
| Payload Drop (EICAR) | Wazuh FIM | Flagged instantly via Syscheck |
| Meterpreter C2 Port 4444 | Custom Snort Rule | Critical alert triggered |
| Post-Exploitation | Sysmon Event ID 1 | 125 events - full process tree |

`Splunk` `Wazuh` `Snort` `Cisco Talos` `Metasploit` `Sysmon` `Nessus` `Kali Linux`

---
### 🟣 Automated Threat Detection and Incident Triage using Splunk SOAR
> Primary focus: Hybrid-cloud SOC automation, zero-touch triage, and DFIR enrichment

**[View Repo](https://github.com/arshandrn/automated-incident-triage)**
&nbsp;|&nbsp;
**[View Report](https://arshand-portfolio.web.app/assets/Incident_Triage.pdf)**
&nbsp;|&nbsp;
**[View Video](https://1drv.ms/v/c/ca84ccba0e93da2d/IQCOaduqe4PkSbiTWT0drfRfAS1BpGq1HGq-RDu2ThfD-TA?e=G4TGam)**

Engineered a hybrid-cloud pipeline bridging on-premise endpoint detection with cloud-hosted orchestration via ngrok reverse tunnels.

- Built an automated Splunk SOAR playbook with conditional logic to ingest JSON telemetry, deduplicate alerts, and auto-provision analyst tickets
- Integrated **TheHive** (Case Management) and **Cortex** (DFIR) for automated active observable analysis
- Positively identified simulated WannaCry ransomware hashes automatically via VirusTotal APIs
- Exported confirmed IOCs directly to **MISP**, mapped automatically to MITRE ATT&CK Galaxy tags

`AWS` `Splunk SOAR` `Wazuh` `TheHive` `Cortex` `MISP` `Sysmon` `Atomic Red Team` `ngrok`

---
### 🟠 Simulated SOC — Nessus + Snort IDS
> Primary focus: CVE-driven detection engineering

**[View Repo](https://github.com/arshandrn/simulated-soc-nessus-snort)**
&nbsp;|&nbsp;
**[View Report](https://arshand-portfolio.web.app/assets/IDS.pdf)**

Scanned a deliberately vulnerable Windows VM, discovered real
CVEs, wrote custom Snort rules per finding, validated with attacks.

- Nessus identified **4 CVE families** across Apache, PHP, MySQL, SSL
- Authored **5 custom Snort rules** mapped to Nessus findings
- Achieved **100% detection rate** across all 5 simulated attack types
- Attack types: banner disclosure, SYN scan, SSL anomaly, brute-force, weak login

`Nessus` `Snort` `Kali Linux` `Hydra` `CVE-2017-15715` `CVE-2019-11043` `CVE-2012-2122`

---

### 🟡 Honeypot Attack Detection - Cowrie + Splunk
> Primary focus: Attacker behavior capture and SIEM integration

**[View Repo](https://github.com/arshandrn/honeypot-cowrie-splunk)**
&nbsp;|&nbsp;
**[View Report](https://arshand-portfolio.web.app/assets/Honeypot.pdf)**

Deployed Cowrie SSH/Telnet honeypot and forwarded structured
logs to Splunk Enterprise via Universal Forwarder.

- Captured **12 structured events** including attacker source IP,
  session commands, and a **224.6-second SSH session**
- Validated full SOC workflow: Nmap recon -> SSH intrusion -> SIEM

`Cowrie` `Splunk` `Splunk Universal Forwarder` `Nmap` `Ubuntu` `Kali Linux`

---

### 🔵 Secure Enterprise Network Infrastructure
> Supporting skill: Understanding what SOC analysts are defending

**[View Repo](https://github.com/arshandrn/enterprise-network-infrastructure)**
&nbsp;|&nbsp;
**[View Report](https://arshand-portfolio.web.app/assets/network.pdf)**

Designed a multi-departmental enterprise network with security
controls - giving real infrastructure context to SOC work.

- 5 VLANs (HR, Finance, IT, Guest, IoT) with inter-VLAN routing
- HSRP failover in under 3 seconds
- Zero-Trust Extended ACL blocking Guest VLAN from internal subnets
- Port security triggers err-disabled on rogue device connection
- All 5 verification tests passed

`Cisco Packet Tracer` `HSRP` `VLANs` `ACL` `NAT/PAT` `Port Security`

---

## SOC Alert Investigations

**20+ investigations** on LetsDefend SOC Analyst platform with
full lifecycle from alert triage to incident documentation.

**Each investigation includes:**
- Alert triage and false positive reduction
- Log and packet analysis
- Sandbox correlation - ANY.RUN, Hybrid Analysis, VirusTotal
- MITRE ATT&CK technique mapping
- Remediation playbook and knowledge-base entry

🔗 [View LetsDefend Profile](https://app.letsdefend.io/user/defender20)

---

## Experience

### Cybersecurity Intern - CyberWarLab *(Dec 2025 - Jan 2026)*

- OWASP Top 10 exploitation via DVWA - SQLi, XSS, Command Injection
- Reconnaissance using Shodan, Amass, Nmap, Wireshark, Dirb
- Cyber Kill Chain + MITRE ATT&CK attacker behavior mapping
- Full CTF: exploited Pluck CMS via **CVE-2023-50564** -> RCE
  -> DB access -> privilege escalation to root
  
**[View Report](https://1drv.ms/f/c/ca84ccba0e93da2d/IgDk64FNTJmSQZzCBcWO2zhIAatZRBxpglM4Yf3p881DvXM?e=wi5kVn)**
&nbsp;

---

## Skills

### Cybersecurity & SOC

| Category | Details |
|---|---|
| SIEM & SOAR | Splunk Enterprise, Splunk SOAR, Wazuh - playbooks, correlation, FIM |
| Incident Response | TheHive, Cortex - automated case management, active analyzers |
| IDS/NIDS | Snort - custom rule writing, Talos feed integration |
| Vulnerability Assessment | Nessus Essentials - CVE mapping, remediation |
| Threat Intelligence | MISP, Cisco Talos, OSINT, VirusTotal, AbuseIPDB |
| Attack Simulation | Atomic Red Team, Kali Linux, Metasploit, msfvenom, Hydra |
| Endpoint Forensics | Sysmon, Windows Event Logs, process tree analysis |
| Frameworks | MITRE ATT&CK, Cyber Kill Chain |
| Security Skills | Playbook automation, Alert triage, IOC analysis, EDR/XDR, log analysis |

### Networking

| Category | Details |
|---|---|
| Protocols | OSI/TCP-IP, DNS, DHCP, HTTP/HTTPS, VLAN, VPN |
| Security | Firewall, ACL, NAT/PAT, port security |
| Tools | Cisco Packet Tracer, Wireshark, tcpdump |
| Concepts | Subnetting, inter-VLAN routing, HSRP, Zero-Trust |

### Other
`PowerShell` `Bash` `AWS (EC2, S3, Route53, ELB)` `Azure` `GCP`
`MySQL` `MongoDB` `Windows` `Linux` `Kali Purple`

---

## Certifications

| Certification | Issuer | Year |
|---|---|---|
| Cybersecurity Defense Analyst | Cisco | 2026 |
| 17 Courses Completed | Splunk | 2026 |
| SOC Analyst Learning Path | LetsDefend | 2025 |
| Fortinet Certified Associate in Cybersecurity | Fortinet | 2025 |
| Blue Team Junior Analyst Pathway | Security Blue Team | 2025 |
| Cyber Job Simulation | Deloitte (Forage) | 2025 |
| Privacy & Security in Online Social Media - ELITE | NPTEL | 2025 |
| Networking + Linux + Cybersecurity | Cisco | 2024-2025 |

---

## Education

**B.E. Electronics & Communication Engineering (Honors)**

Hindusthan College of Engineering and Technology

Coimbatore, Tamil Nadu | 2022 – 2026 | CGPA: 7.9 (till 7th sem)
