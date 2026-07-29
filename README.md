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

Everything in these repositories is my own lab work, written up in my own words.

---

## What I can do today

| Capability | Evidence |
|---|---|
| Triage Windows authentication and process-execution alerts (4624, 4625, 4688, 7045, 1102) | [`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs) |
| Write SPL searches and detections in Splunk against Sysmon telemetry | [`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs) |
| Build and baseline an instrumented lab environment from scratch | [`dfir-home-lab`](https://github.com/TasoGiann/dfir-home-lab) |
| Run first-minute triage on a compromised Linux host | [`linux-triage-toolkit`](https://github.com/TasoGiann/linux-triage-toolkit) |
| Investigate a PCAP and reconstruct what happened on the wire | HTB Sherlock *Vantage* |
| Analyse phishing emails — headers, sender infrastructure, payload reputation | TryHackMe SEC1 · lab writeups |
| Document a case to an audit-ready standard a Tier 2 can pick up | every writeup here |

---

## What I'm training on

Structured study, not a reading list — each item below is hands-on work I've either finished or am working through now.

### SIEM, detection & monitoring
Splunk with a dedicated index for Windows Security and Sysmon logs · SPL searches and detections · Wazuh alert analysis · KQL query practice · SIEM fundamentals from the Google Cybersecurity certificate

### Incident handling
NIST incident-response lifecycle · Cyber Kill Chain · MITRE ATT&CK mapping · TheHive case management · alert triage and escalation procedure · audit-ready case documentation

### Threat detection labs
Credential-dumping detection (`mimikatz.exe`) · persistence hunting via Event ID 7045 · brute-force detection on service accounts · logon-failure and process-creation analysis

### Network analysis
Network traffic analysis · Wireshark and tcpdump · PCAP investigation (HTB Sherlock *Vantage* — OpenStack breach) · TCP/IP, DNS, HTTP/S, ports and protocols

### Systems
Windows internals and Event Log analysis · registry persistence locations · PowerShell for triage · Sysmon configuration and telemetry · Linux (`journalctl`, `lsof`, `ss`, systemd, `grep`/`awk`/`sed`) · Bash scripting · Active Directory fundamentals

### Security fundamentals
CompTIA Security+ SY0-701 domains — threats and attacks, architecture, security operations, governance and risk · cryptography · access control and Zero Trust concepts · GDPR and data protection in practice

---

## Repositories

### [`soc-analyst-labs`](https://github.com/TasoGiann/soc-analyst-labs)
Hands-on detection and triage work: Splunk searches over Windows Security and Sysmon logs, detections mapped to MITRE ATT&CK, and triage walkthroughs structured as hypothesis → evidence → conclusion.
*Shows:* the core Tier 1 loop — alert in, defensible answer out.

### [`dfir-home-lab`](https://github.com/TasoGiann/dfir-home-lab)
Full build documentation for the lab everything else runs on — VirtualBox topology, Sysmon configuration, logging policy, and captured baselines (processes, listening sockets, services, Run keys).
*Shows:* environment setup, logging design, systematic documentation.

### [`linux-triage-toolkit`](https://github.com/TasoGiann/linux-triage-toolkit)
Bash tooling for the first minutes on a suspect Linux host: processes, network connections, persistence locations, recent modifications.
*Shows:* scripting, Linux internals, incident-response instinct.

> **Next up:** Windows event-log detection writeups and network-analysis walkthroughs from public PCAPs.

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

## Certifications & Education

| | |
|---|---|
| **In progress** | CompTIA Security+ (SY0-701) — exam September 2026 |
| **Certified** | TryHackMe Cyber Security 101 (SEC1) · Google Cybersecurity Professional Certificate |
| **Next** | HTB Certified Defensive Security Analyst (CDSA) — currently working through the path |
| **Degree** | BSc (Hons) Cybersecurity & Networks — University of East London · second year, ongoing |

---

## Open to

**SOC Analyst (Tier 1)** · Security Analyst · Junior Incident Response · Blue team roles across the EU — remote, hybrid or on-site. Open to relocation.

📧 tasos.giannoulis@proton.me · 💼 [LinkedIn](https://www.linkedin.com/in/tasos-giannoulis/)

---

<sub>Everything in my repositories is original work, done in my own lab, written in my own words. I use AI as a tutor and sparring partner — never as a ghostwriter for anything that gets published.</sub>
