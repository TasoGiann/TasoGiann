<h1 align="center">Tasos Giannoulis</h1>
<p align="center"><b>SOC Analyst (Tier 1)</b> — alert triage · log analysis · incident documentation</p>
<p align="center">
<a href="https://www.linkedin.com/in/tasos-giannoulis/"><img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<img src="https://img.shields.io/badge/Focus-SOC%20Analyst%20(Tier%201)-0B3D91?style=for-the-badge">
<img src="https://img.shields.io/badge/Security%2B-In%20Progress-C1440E?style=for-the-badge">
<img src="https://img.shields.io/badge/Location-Greece%20%C2%B7%20Remote%20-004080?style=for-the-badge">
</p>
---
 
I work an alert from the first log line to a written conclusion someone else can act on.
 
Three years of frontline account-security work — compromised access, failed authentication, phishing reports, all under GDPR and client security procedure — plus a home SOC where I ingest Windows Security and Sysmon telemetry into Splunk and build detections against it. Second year of a BSc in Cybersecurity & Networks, studying for **CompTIA Security+ (SY0-701)**, exam September 2026.
 
Long term I'm heading for **DFIR**. The road there runs through a SOC, so that's what I'm building for now.
 
Everything in these repositories is my own lab work, written up in my own words.
 
---
 
## What I can do today
 
| Capability | Evidence |
|---|---|
| Triage Windows authentication and process-execution alerts (4624, 4625, 4688, 7045, 1102) | [`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs) |
| Write SPL searches and detections in Splunk against Sysmon telemetry | [`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs) |
| Build and baseline an instrumented lab environment from scratch | [`dfir-home-lab`](https://github.com/TasoGiann/dfir-home-lab) |
| Run first-minute triage on a compromised Linux host | [`linux-triage-toolkit`](https://github.com/TasoGiann/linux-triage-toolkit) |
| Analyse phishing emails — headers, sender infrastructure, payload reputation | TryHackMe SEC1 · lab writeups |
| Document a case to an audit-ready standard a Tier 2 can pick up | every writeup here |
 
---
 
## Repositories
 
### [`dfir-home-lab`](https://github.com/TasoGiann/dfir-home-lab)
Full build documentation for the lab everything else runs on — VirtualBox topology, Sysmon configuration, logging policy, and captured baselines (processes, listening sockets, services, Run keys).
*Shows:* environment setup, logging design, systematic documentation.
 
### [`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs)
Hands-on detection and triage work: Splunk searches over Windows Security and Sysmon logs, detections mapped to MITRE ATT&CK, and triage walkthroughs structured as hypothesis → evidence → conclusion.
*Shows:* the core Tier 1 loop — alert in, defensible answer out.
 
### [`linux-triage-toolkit`](https://github.com/TasoGiann/linux-triage-toolkit)
Bash tooling for the first minutes on a suspect Linux host: processes, network connections, persistence locations, recent modifications.
*Shows:* scripting, Linux internals, incident-response instinct.
 
> **Next up:** Windows artifact walkthroughs (Prefetch, Amcache, ShimCache, event logs) and network forensics writeups from public pcaps.
 
---
 
## Home Lab
 
Segmented, host-only lab on VirtualBox — an MSI Cyborg 15 acting as a very small SOC.
 
| Component | Setup |
|---|---|
| SIEM | Splunk — Windows Security and Sysmon logs into a dedicated index |
| Windows target | Windows 11 — Sysmon, PowerShell script-block logging, process auditing |
| Linux target | Ubuntu Server |
| Analyst workstation | Parrot OS |
| Network | Host-only, isolated |
| Baselines | Processes, listening sockets, SUID binaries, services, Run keys |
 
Build documentation: [`dfir-home-lab`](https://github.com/TasoGiann/dfir-home-lab)
 
---
 
## Skills
 
**Detection & SIEM** — Splunk (SPL), Windows Event Log analysis, Sysmon telemetry, MITRE ATT&CK mapping, alert triage and escalation
 
**Windows** — authentication and process-creation events, registry persistence, PowerShell for triage, Eric Zimmerman's tools (EvtxECmd, PECmd, MFTECmd)
 
**Linux** — journalctl, `grep`/`awk`/`sed` pipelines, `lsof`, `ss`, systemd analysis, Bash scripting
 
**Network** — TCP/IP, DNS, HTTP/S, Wireshark, tcpdump
 
**Learning** — Volatility 3, Autopsy, Sigma rules
 
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
 
**SOC Analyst (Tier 1)** · Security Analyst · Junior Incident Response · Blue team roles across the EU — remote, hybrid or on-site. Open to relocation.
 
📧 tasos.giannoulis@proton.me · 💼 [LinkedIn](https://www.linkedin.com/in/tasos-giannoulis/)
 
---
 
<sub>Everything in my repositories is original work, done in my own lab, written in my own words. I use AI as a tutor and sparring partner — never as a ghostwriter for anything that gets published.</sub>
 
