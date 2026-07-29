<h1 align="center">Tasos Giannoulis</h1>
<p align="center"><b>SOC Analyst (Tier 1)</b> — alert triage · log analysis · incident documentation</p>

<p align="center">
<a href="https://www.linkedin.com/in/tasos-giannoulis/"><img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<img src="https://img.shields.io/badge/Focus-SOC%20Analyst%20(Tier%201)-0B3D91?style=for-the-badge">
<img src="https://img.shields.io/badge/Security%2B-In%20Progress-C1440E?style=for-the-badge">
<img src="https://img.shields.io/badge/Location-Greece%20%C2%B7%20Remote%20OK-004080?style=for-the-badge">
</p>

---

I work an alert from the first log line to a written conclusion someone else can act on.

Coming from a customer support background, I now run a home SOC where I ingest Windows Security and Sysmon telemetry into Splunk and build detections against it. Second year of a BSc in Cybersecurity & Networks, studying for **CompTIA Security+ (SY0-701)**, exam September 2026.

Everything here is my own lab work, written up in my own words.

---

## SOC Lab

Segmented, host-only lab on VirtualBox — a very small SOC I run end to end.

| Component | Setup |
|---|---|
| SIEM | Splunk — Windows Security and Sysmon logs into a dedicated index |
| Windows target | Windows 11 — Sysmon, PowerShell script-block logging, process auditing |
| Linux target | Ubuntu Server |
| Analyst workstation | Parrot OS |
| Network | Host-only, isolated |
| Baselines | Processes, listening sockets, SUID binaries, services, Run keys |

Detection and triage work from this lab lives in **[`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs)** — SPL searches over Windows Security and Sysmon logs, detections mapped to MITRE ATT&CK, and triage walkthroughs structured as hypothesis → evidence → conclusion.

---

## What I'm learning right now

**CompTIA Security+ (SY0-701)** — exam September 2026. Threats and attacks, architecture, security operations, governance and risk.

**HTB Academy — CDSA path.** Incident handling: NIST response lifecycle, Cyber Kill Chain, MITRE ATT&CK mapping, TheHive case management. Detection labs: credential dumping, persistence via Event ID 7045, brute-force alerts on service accounts.

**Splunk and detection engineering** — writing SPL against my own Sysmon and Windows Security telemetry, and turning alerts into documented cases.

**Windows event analysis** — logon and process-creation events (4624, 4625, 4688, 7045, 1102), registry persistence, PowerShell for triage.

**Network traffic analysis** — Wireshark and tcpdump, PCAP investigation, TCP/IP, DNS, HTTP/S.

---

## Certifications & Education

| | |
|---|---|
| **In progress** | CompTIA Security+ (SY0-701) — exam September 2026 |
| **Certified** | TryHackMe Cyber Security 101 (SEC1) · Google Cybersecurity Professional Certificate |
| **Next** | HTB Certified Defensive Security Analyst (CDSA) |
| **Degree** | BSc (Hons) Cybersecurity & Networks — Metropolitan College, in partnership with University of East London · second year, ongoing |

---

## Open to

**SOC Analyst (Tier 1)** · Security Analyst · Blue team roles across the EU — remote, hybrid or on-site. Open to relocation.

📧 tasos.giannoulis@proton.me · 💼 [LinkedIn](https://www.linkedin.com/in/tasos-giannoulis/)

---

<sub>Everything in my repositories is original work, done in my own lab, written in my own words. I use AI as a tutor and sparring partner — never as a ghostwriter for anything that gets published.</sub>
