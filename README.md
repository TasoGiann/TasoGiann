# Tasos Giannoulis
 
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tasos-giannoulis/)
[![Focus](https://img.shields.io/badge/Focus-SOC%20Analyst-0B3D91?style=for-the-badge)]()
[![Location](https://img.shields.io/badge/Location-Greece-004080?style=for-the-badge)]()
 
**SOC Analyst (Tier 1)** in the making — alert triage, log analysis and incident documentation.
Currently studying for **CompTIA Security+ (SY0-701)** and in the second year of a BSc in Cybersecurity & Networks at Metropolitan College, in partnership with the University of East London. Based in Greece, open to remote.
 
Long term I'm heading for **DFIR — Digital Forensics & Incident Response**. The route there runs through a SOC, so that's what I'm building for now: the triage, log and reporting skills a Tier 1 analyst uses every day, with forensics depth added on top as I go.
 
Everything in these repos is work I've actually done in my own lab, written up in my own words.
 
---
 
## What I'm working on
 
**Alert triage and log analysis** — Windows Security and Sysmon telemetry in Splunk: logon failures, process creation, persistence in Run keys and services. Building the habit of going from an alert to a defensible conclusion.
 
**Investigative method** — hypothesis → evidence → revised hypothesis → conclusion. Every writeup here is structured that way on purpose, because that's what an analyst is actually paid for.
 
**Writing clearly** — security work is judged on the report. I treat every README and writeup as a writing sample.
 
**Breadth before depth** — disk, memory, network and log analysis, without specialising yet. The plan is to stay broad while I get into a SOC, then deepen toward forensics.
 
---
 
## Repositories
 
- **[`dfir-home-lab`](https://github.com/TasoGiann/dfir-home-lab)** — documented lab build: VirtualBox setup, network topology, Sysmon configuration, baseline captures and lessons learned.
- **[`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs)** — hands-on SOC work: detection engineering, log analysis and incident triage exercises.
- **[`linux-triage-toolkit`](https://github.com/TasoGiann/linux-triage-toolkit)** — Bash tooling for first-minute triage on a Linux host during an incident.
*Next up:* Windows artifact walkthroughs (Prefetch, Amcache, ShimCache, event logs) and network forensics writeups from public pcaps.
 
---
 
## Home Lab
 
A segmented, host-only lab where the work above is done.
 
- **Analyst workstation:** Parrot OS
- **Windows target:** Windows 11 — Sysmon, PowerShell script-block logging and process auditing enabled
- **Linux target:** Ubuntu Server
- **SIEM:** Splunk, ingesting Windows Security and Sysmon logs into a dedicated index
- **Platform:** MSI Cyborg 15 / VirtualBox / host-only networking
- **Baselines captured:** running processes, listening sockets, SUID binaries, enabled services, Run keys
Full build documentation lives in the `dfir-home-lab` repo.
 
---
 
## Tools & Techniques
 
**SIEM / detection:** Splunk (SPL searches and detections), Windows Event Log analysis (4624, 4625, 4688, 7045, 1102), Sysmon telemetry, MITRE ATT&CK
 
**Network analysis:** Wireshark, tcpdump
 
**Windows:** registry forensics, PowerShell for triage, Eric Zimmerman's tools (EvtxECmd, PECmd, MFTECmd)
 
**Linux:** journalctl, grep/awk/sed pipelines, lsof, ss, systemd analysis, Bash scripting
 
**Forensics (learning):** Volatility 3, Autopsy
 
**Environments:** Windows 10/11, Linux (Parrot, Ubuntu), VirtualBox
 
---
 
## Certifications
 
**Completed**
- Google Cybersecurity Professional Certificate
- TryHackMe Cyber Security 101 (SEC1)
**In progress**
- CompTIA Security+ (SY0-701) — exam September 2026
**Next**
- HTB Certified Defensive Security Analyst (CDSA) — hands-on blue team certification, the practical follow-on to Security+
---
 
## Education
 
**BSc (Hons) Cybersecurity & Networks** — Metropolitan College, Greece, in partnership with **University of East London**, UK · second year, ongoing
 
---
 
## Open to
 
SOC Analyst (Tier 1) · Security Analyst · Junior Incident Response · Blue team roles across the EU — remote, hybrid or on-site. Open to relocation.
 
---
 
## Contact
 
- **LinkedIn:** [tasos-giannoulis](https://www.linkedin.com/in/tasos-giannoulis/)
- **Email:** tasos.giannoulis@proton.me
---
 
<sub>Everything in my repositories is original work, done in my own lab, written in my own words. I use AI as a tutor and sparring partner — never as a ghostwriter for anything that gets published.</sub>
