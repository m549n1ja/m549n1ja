# John Medina
**Cloud DFIR & Detection Engineering | Incident Response | Multi-Cloud Forensics**

I'm a U.S. Navy veteran with eight years in mine warfare, operating manned and unmanned maritime systems in high-stress environments across the Strait of Hormuz and the Gulf of Aden, now focused on cloud DFIR and detection engineering.

My training runs through SANS: GFACT, GSEC, GCIH, and FOR509 complete, with the GCFR exam in October 2026 and the SANS.edu Applied Cybersecurity Certificate finishing with GPCS, which begins in October. The labs exist to do two things: turn course material into hands-on experience, and get real reps with the tools and concepts in highest demand in today's job market. Every project starts with a real attack, ends with a validated detection, and gets documented like an incident report.

[![GFACT](https://img.shields.io/badge/GIAC-GFACT-red?style=flat-square)](https://www.credly.com/badges/098be4d8-7f32-4679-ad9e-be2ef62d3641)
[![GSEC](https://img.shields.io/badge/GIAC-GSEC-red?style=flat-square)](https://www.credly.com/badges/aaab9600-2758-41f9-ad4e-2664178b6478)
[![GCIH](https://img.shields.io/badge/GIAC-GCIH-orange?style=flat-square)](https://www.giac.org)
[![Veteran](https://img.shields.io/badge/U.S.-Veteran-1a1a2e?style=flat-square)](https://github.com/m549n1ja)

---

## Now

- **GCFR** (GIAC Cloud Forensics & Response): exam October 2026
- **SEC510 → GPCS** (Cloud Security Controls & Mitigations): begins October 2026
- **SANS.edu Applied Cybersecurity Certificate (ACS)**: completes with GPCS
- Packaging the Microsoft Sentinel detection lab. Multi-cloud IR lab is next in line.

---

## Projects

| Repo | What it proves | Status |
|------|----------------|--------|
| [active-directory-attack-defense](https://github.com/m549n1ja/active-directory-attack-defense) | AD kill chain · BloodHound · 6 validated KQL detections · DC telemetry-gap finding · Hardening | ✅ Live |
| [homelab-elk-soc](https://github.com/m549n1ja/homelab-elk-soc) | SIEM engineering · ELK 8.x · 29k+ indexed events · MITRE-mapped detections | ✅ Live |
| sentinel-kql-detection-lab | Microsoft Sentinel · KQL analytics · Entra ID · cloud-SOC operations | ✅ Live |
| multi-cloud-ir-lab | AWS/Azure/GCP log forensics · SOF-ELK · full IR report | 🗓️ Next |

Every claim in this table is checkable. Open the repo and read the evidence.

---

## The Lab

A full SOC homelab on physical hardware: OPNsense firewall, ELK SIEM, Windows and Linux endpoints, a dedicated Kali attack machine, Suricata IDS, and a Raspberry Pi sensor node.

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

The physical lab covers the on-prem side. A live Microsoft Sentinel workspace with Entra ID and Azure Activity connected covers cloud detection.

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

## Certifications

| Cert | Status |
|------|--------|
| GCIH (SEC504) | ✅ Complete |
| GSEC | ✅ Complete |
| GFACT | ✅ Complete |
| FOR509, Enterprise Cloud Forensics & IR | ✅ Course complete, SANSFIRE 2026 |
| GCFR | ⏳ Exam October 2026 |
| GPCS (SEC510) | 🗓️ Begins October 2026 |
| SANS.edu Applied Cybersecurity Certificate (ACS) | 🎓 Completes with GPCS |

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-John_Medina-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/john-m-5aab3194)
[![GitHub](https://img.shields.io/badge/GitHub-m549n1ja-181717?style=flat-square&logo=github)](https://github.com/m549n1ja)

Open to Cloud SOC Analyst, DFIR, and Incident Response roles. Remote, Federal, Europe.
