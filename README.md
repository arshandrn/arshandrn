# Hi, I'm Arshand R N

**ECE Graduate | Aspiring SOC Analyst | Blue Team**  
📍 Coimbatore, Tamil Nadu, India  
🔗 [Portfolio](https://arshand-portfolio.web.app) • [LinkedIn](https://linkedin.com/in/arshandrn)

---

## About Me

B.E. ECE graduate with 3+ years of hands-on cybersecurity 
practice. I build lab environments that simulate real enterprise 
attacks and practice detection using industry-standard tools 
across SIEM, EDR, and NIDS layers.

Completed 20+ SOC alert investigations on LetsDefend with 
MITRE ATT&CK mapping and incident reporting. Actively seeking 
SOC Analyst and Blue Team roles.

---

## Projects

### 🔴 Comprehensive SOC Simulation — Splunk + Wazuh + Snort
**[View Repo](https://github.com/arshandrn/soc-splunk-wazuh-snort)**

Full-chain cyberattack simulation detected across all 3 SOC layers.
Attack chain: Nessus recon → SMB brute force → malware drop → 
Meterpreter C2 reverse shell on port 4444.

- Snort + Cisco Talos feeds detected network reconnaissance (108 SYN scan events)
- Wazuh FIM caught EICAR payload drop instantly
- Custom Snort rule caught C2 traffic on port 4444
- Sysmon Event ID 1 in Splunk reconstructed full process tree

`Splunk` `Wazuh` `Snort` `Metasploit` `Sysmon` `Nessus` `Kali Linux`

---

### 🟠 Simulated SOC — Nessus + Snort IDS
**[View Repo](https://github.com/arshandrn/simulated-soc-nessus-snort)**

3-VM lab: vulnerability discovery → custom IDS rules → attack simulation → detection.

- Nessus found 48 Apache + 44 PHP + 12 SSL vulnerabilities
- Wrote 5 custom Snort rules mapped directly to CVE findings
- All 5 attack types (curl, nmap, hydra, mysql, SYN scan) detected

`Nessus` `Snort` `Kali Linux` `Hydra` `CVE-2017-15715` `CVE-2019-11043`

---

### 🟡 Honeypot Attack Detection — Cowrie + Splunk
**[View Repo](https://github.com/arshandrn/honeypot-cowrie-splunk)**

Deployed Cowrie SSH/Telnet honeypot on Ubuntu. Forwarded 
captured attack logs to Splunk Enterprise via Universal Forwarder.

- Captured Nmap recon probes and SSH login attempts
- 12 events ingested into Splunk for SIEM analysis
- Validated full SOC workflow: recon → capture → forward → detect

`Cowrie` `Splunk` `Nmap` `Ubuntu` `VirtualBox`

---

### 🔵 Secure Enterprise Network Infrastructure
**[View Repo](https://github.com/arshandrn/enterprise-network-infrastructure)**

End-to-end enterprise network design in Cisco Packet Tracer.
5 VLANs, HSRP redundancy, Zero-Trust ACLs, NAT/PAT, port security.

- HSRP failover in under 3 seconds
- Zero-Trust ACL blocks Guest VLAN from internal subnets
- Port security triggers err-disabled on rogue device connection
- All 5 verification tests passed

`Cisco Packet Tracer` `HSRP` `VLANs` `ACL` `NAT` `Port Security`

---

## SOC Alert Investigations

**20+ investigations** completed on LetsDefend SOC Analyst platform.

Each investigation covers:
- Alert triage and false positive analysis
- Packet and log analysis
- Sandbox correlation (ANY.RUN, Hybrid Analysis, VirusTotal)
- MITRE ATT&CK mapping
- Incident report and remediation playbook

🔗 [View LetsDefend Profile](https://app.letsdefend.io/user/defender20)

---

## Cybersecurity Internship — CyberWarLab (Dec 2025 – Jan 2026)

- OWASP Top 10 exploitation using DVWA (SQLi, XSS, Command Injection)
- Reconnaissance with Shodan, Amass, Nmap, Wireshark, Dirb
- MITRE ATT&CK and Cyber Kill Chain mapping
- Full CTF: exploited Pluck CMS via CVE-2023-50564 → RCE → DB access → root

---

## Tools & Skills

| Category | Tools |
|---|---|
| SIEM | Splunk Enterprise |
| EDR | Wazuh |
| IDS/IPS | Snort + Cisco Talos |
| Vulnerability Assessment | Nessus Essentials |
| Attack Simulation | Kali Linux, Metasploit, Hydra, Nmap |
| Network | Cisco Packet Tracer, Wireshark |
| Threat Intel | OSINT, VirusTotal, AbuseIPDB, Cisco Talos |
| Cloud | AWS (EC2, S3, Route53, ELB), Azure, GCP |
| OS | Windows, Linux, Kali, Kali Purple |

---

## Certifications

| Certification | Issuer | Year |
|---|---|---|
| Fortinet Certified Associate in Cybersecurity | Fortinet | 2025 |
| Blue Team Junior Analyst | Security Blue Team | 2025 |
| SOC Analyst Learning Path | LetsDefend | 2025 |
| Privacy & Security in Online Social Media (ELITE) | NPTEL | 2025 |
| 17 Courses Completed | Splunk | 2026 |
| Cyber Job Simulation | Deloitte (Forage) | 2025 |
| Networking + Linux + Cybersecurity | Cisco | 2024-2025 |

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-arshandrn-blue?logo=linkedin)](https://linkedin.com/in/arshandrn)
[![Portfolio](https://img.shields.io/badge/Portfolio-arshand--portfolio.web.app-green)](https://arshand-portfolio.web.app)
[![LetsDefend](https://img.shields.io/badge/LetsDefend-defender20-orange)](https://app.letsdefend.io/user/defender20)
