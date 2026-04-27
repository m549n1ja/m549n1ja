# John Medina
**Security Operations | Incident Response | Threat Detection**

U.S. Veteran transitioning into cybersecurity with a focus on SOC engineering, DFIR, and detection-as-code. I build enterprise-grade security infrastructure in my homelab — not to follow tutorials, but to understand how attacks work and how to detect them.

[![GFACT](https://img.shields.io/badge/GIAC-GFACT-red?style=flat-square)](https://www.giac.org)
[![GSEC](https://img.shields.io/badge/GIAC-GSEC-red?style=flat-square)](https://www.giac.org)
[![GCIH](https://img.shields.io/badge/GIAC-GCIH-orange?style=flat-square)](https://www.giac.org)
[![GSOC](https://img.shields.io/badge/GIAC-GSOC-blue?style=flat-square)](https://www.giac.org)
[![Veteran](https://img.shields.io/badge/U.S.-Veteran-1a1a2e?style=flat-square)](https://github.com/m549n1ja)

---

## What I'm Building

A full SOC homelab running on physical hardware — OPNsense firewall, ELK SIEM, Windows and Linux endpoints, a dedicated Kali attack machine, Suricata IDS, and a Raspberry Pi sensor node. Every project starts with a real attack scenario, ends with a detection, and gets documented like an incident report.

```
[OPNsense FW] → [Core Switch] → [Ryzen 9 Hypervisor | 64GB]
                                      ├── ELK-SIEM       192.168.10.100
                                      ├── WIN10-ENDPOINT 192.168.10.133
                                      ├── LINUX-ENDPOINT 192.168.10.155
                                      └── Kali VM        192.168.10.20
                               → [RPi5 | Zeek + Honeypot  192.168.10.50]
                               → [Chromebox | Suricata IDS 192.168.10.51]
                               → [Zenbook | Vuln Targets   192.168.10.30]
```

---

## Projects

| Repo | What It Proves | Status |
|------|---------------|--------|
| [homelab-elk-soc](https://github.com/m549n1ja/homelab-elk-soc) | SIEM engineering · Detection rules · Log analysis | 🔨 Building |
| sentinel-kql-detection-lab | Microsoft Sentinel · KQL analytics · Logic Apps | ⏳ Soon |
| active-directory-attack-defense | AD kill chain · BloodHound · Hardening | ⏳ Soon |
| threat-detection-lab | Red vs Blue · Full kill chain · MITRE ATT&CK | ⏳ Soon |
| dfir-incident-report | DFIR investigation · Volatility 3 · IR report | ⏳ Soon |
| detection-as-code | Sigma rules · YARA · MITRE mapping | ⏳ Soon |
| soc-runbooks | SOC SOPs · Triage · Escalation · Containment | ⏳ Soon |

---

## Detection Rules (MITRE ATT&CK)

| Technique | Description | Status |
|-----------|-------------|--------|
| T1110.001 | Brute Force — Password Guessing | ✅ Active |
| T1136.001 | New Local User Account Created | ✅ Active |
| T1059.001 | Suspicious PowerShell Execution | ✅ Active |
| T1053.005 | Scheduled Task Creation | ✅ Active |
| T1021.001 | RDP Login from External IP | ✅ Active |
| T1046 | Firewall Deny Spike | 🔨 Building |
| T1543.003 | New Service Installed | ⏳ Planned |
| T1003.001 | LSASS Memory Access | ⏳ Planned |
| T1558.003 | Kerberoasting | ⏳ Planned |
| T1071.004 | DNS Tunneling Indicator | ⏳ Planned |

---

## Tools

![ELK](https://img.shields.io/badge/ELK-8.x-005571?style=flat-square&logo=elastic)
![Sentinel](https://img.shields.io/badge/Microsoft-Sentinel-0078D4?style=flat-square&logo=microsoft)
![Kali](https://img.shields.io/badge/Kali-Linux-557C94?style=flat-square&logo=kali-linux)
![Suricata](https://img.shields.io/badge/Suricata-IDS-EF6C00?style=flat-square)
![Zeek](https://img.shields.io/badge/Zeek-NSM-2196F3?style=flat-square)
![Sigma](https://img.shields.io/badge/Sigma-Rules-2196F3?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark)
![VMware](https://img.shields.io/badge/VMware-Workstation-607078?style=flat-square&logo=vmware)
![OPNsense](https://img.shields.io/badge/OPNsense-Firewall-D94F00?style=flat-square)
![MITRE](https://img.shields.io/badge/MITRE-ATT%26CK-red?style=flat-square)
![AWS](https://img.shields.io/badge/Azure-M365-0078D4?style=flat-square&logo=microsoftazure)

---

## Cert Roadmap

| Cert | Status |
|------|--------|
| GFACT | ✅ Complete |
| GSEC | ✅ Complete |
| GCIH (SEC504) | ✅ Complete |
| GSOC (SEC450) | 🔄 In Progress |
| GPCS (SEC510) | ⏳ Planned |
| GCIA (SEC503) | ⏳ Oct 2026 |

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-John_Medina-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-m549n1ja-181717?style=flat-square&logo=github)](https://github.com/m549n1ja)

*Open to SOC Analyst · DFIR · Incident Responder roles — Remote & Federal*
