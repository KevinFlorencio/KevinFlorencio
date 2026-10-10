# Kevin Florencio

**Security researcher — bug bounty, detection engineering, and blue-team labs.**

<a href="https://www.linkedin.com/in/kevin-florencio-b8a571298/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://kevinflorencio.github.io/"><img src="https://img.shields.io/badge/-Blog-FF5722?&style=for-the-badge&logo=jekyll&logoColor=white" /></a>

---

## About

IT graduate (Colegio EPI) with a background in HBO ICT at Fontys University of
Applied Sciences, currently preparing for my next study programme.

I work across both sides of security. On the defensive side I build and
instrument lab environments — SIEM pipelines, threat-intelligence platforms,
honeypots, and SOC automation — and document the process end to end. On the
offensive side I hunt on public bug bounty programmes, which is where the
theory gets tested against real attack surfaces.

Based in Aruba 🇦🇼.

## Focus

My goal is a career in penetration testing. I am building breadth
deliberately — systems administration, SOC analysis, detection engineering, and
API and mobile security — because effective offensive work depends on
understanding how environments are actually run, monitored, and defended.

## Bug Bounty

Started hunting at the end of July 2026 as a way to apply what I was learning.
Results in the first month on Bugcrowd:

- First four-figure bounty — **$2,500** for a **P2** severity finding
- **100% accuracy** on my researcher profile
- Ranked **#1 in Aruba** on the Bugcrowd leaderboard for August 2026

I report through coordinated disclosure, on in-scope targets only.

## Projects

| Project | Area | Link |
|---|---|---|
| SOC Automation 2.0 — AI-driven alert triage pipeline | SOAR / Automation | [Notes](https://1drv.ms/o/c/bcc4a3d2e192beb1/IgAcBGFw3ZAZTahQKcmnOHSnAVH9dWf5SWk1jWuTmtajtPM?e=8GE1Z2) |
| Bug Radar — multi-platform bug bounty program tracker | Tooling | [Repo](https://github.com/KevinFlorencio/bug-bounty-radar) |
| OpenCTI threat-intel pipeline — ongoing | CTI | [Write-up](https://kevinflorencio.github.io/) |
| T-Pot honeypot on Vultr with ELK analysis | Threat Hunting | Write-up on request |
| Active Directory lab build | Infrastructure | [Repo](https://github.com/KevinFlorencio/Setting-up-Active-Directory) |
| Splunk deployment in the AD lab | SIEM | Private — available on request |
| ELK / Elastic stack setup | SIEM | Private — available on request |
| Wazuh home lab | Detection | Private — available on request |

**SOC Automation 2.0** — an alert ingestion, enrichment, and triage pipeline
built on Splunk, n8n, and Discord, with a **locally hosted Mistral 7B** doing
the analysis. Adapted from the MyDFIR reference build, swapping the hosted LLM
and Slack for a local model and Discord so triage runs fully offline.

**Bug Radar** — aggregates the public HackerOne, Bugcrowd, and YesWeHack APIs
into one self-hosted dashboard: 587+ programs with filters, freshness
tracking, and a feed of newly added targets. Python collector, single-file
frontend, no API keys required.

**T-Pot honeypot** — a multi-honeypot framework deployed on Vultr, feeding
captured attack traffic into the Elastic Stack. Used it to practise KQL-based
threat hunting against live opportunistic attack traffic.

## Technical Skills

**SIEM, Detection & Threat Hunting**
<div>
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" />
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Wazuh-005C8A?&style=for-the-badge&logo=wazuh&logoColor=white" />
    <img src="https://img.shields.io/badge/-KQL-0078D4?&style=for-the-badge&logo=microsoftazure&logoColor=white" />
    <img src="https://img.shields.io/badge/-MITRE_ATT&CK-C8102E?&style=for-the-badge&logo=mitre&logoColor=white" />
</div>

**Threat Intelligence & Automation**
<div>
    <img src="https://img.shields.io/badge/-OpenCTI-001BFF?&style=for-the-badge&logo=opencti&logoColor=white" />
    <img src="https://img.shields.io/badge/-n8n-EA4B71?&style=for-the-badge&logo=n8n&logoColor=white" />
    <img src="https://img.shields.io/badge/-Local_LLMs-412991?&style=for-the-badge&logo=ollama&logoColor=white" />
</div>

**Offensive Security**
<div>
    <img src="https://img.shields.io/badge/-Burp_Suite-FF6633?&style=for-the-badge&logo=burpsuite&logoColor=white" />
    <img src="https://img.shields.io/badge/-Nmap-214478?&style=for-the-badge&logo=nmap&logoColor=white" />
    <img src="https://img.shields.io/badge/-API_Security-6BA539?&style=for-the-badge&logo=openapiinitiative&logoColor=white" />
    <img src="https://img.shields.io/badge/-Frida-E86337?&style=for-the-badge&logo=frida&logoColor=white" />
    <img src="https://img.shields.io/badge/-Ghidra-FF6600?&style=for-the-badge&logo=ghidra&logoColor=white" />
    <img src="https://img.shields.io/badge/-Android_Security-3DDC84?&style=for-the-badge&logo=android&logoColor=white" />
</div>

**Digital Forensics**
<div>
    <img src="https://img.shields.io/badge/-Volatility-4B275F?&style=for-the-badge&logo=linuxfoundation&logoColor=white" />
    <img src="https://img.shields.io/badge/-KAPE-005571?&style=for-the-badge&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/-FTK_Imager-E34F26?&style=for-the-badge&logo=databricks&logoColor=white" />
</div>

**Platforms & Infrastructure**
<div>
    <img src="https://img.shields.io/badge/-Windows_Server-0078D6?&style=for-the-badge&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/-Active_Directory-0078D4?&style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Linux-FCC624?&style=for-the-badge&logo=linux&logoColor=black" />
    <img src="https://img.shields.io/badge/-Docker-2496ED?&style=for-the-badge&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/-Google_Cloud-4285F4?&style=for-the-badge&logo=googlecloud&logoColor=white" />
</div>

**Scripting**
<div>
    <img src="https://img.shields.io/badge/-Python-3776AB?&style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/-Bash-4EAA25?&style=for-the-badge&logo=gnubash&logoColor=white" />
</div>

## Certifications

| Certification | Issuer | Earned |
|---|---|---|
| eJPT — Junior Penetration Tester | INE | May 2025 |
| Certified API Security Analyst | APIsec University | Oct 2024 |
| API Security Fundamentals | APIsec University | Feb 2024 |
| Ethical Hacker | Cisco | Jan 2024 |
| Kusto Detective | Microsoft Azure Data Explorer | Nov 2023 |

## Courses & Training

- **AI/ML Mobile Pentesting** — Mobile Hacking Lab *(in progress; won at the 2026 Mobile Hacking Lab Conference)*
- **Practical Windows Forensics** — TCM Security *(Dec 2024)* — NTFS artifacts, memory analysis, Volatility, KAPE, FTK Imager
- **Introduction to Threat Hunting & Hunting with Elastic** — Hack The Box Academy *(Sep 2024)*
- **Implement Load Balancing on Compute Engine** — Google Cloud Skills Boost *(Jun 2024)*
- SOC Radar Academy *(Feb 2025)*

## Writing

I document labs, research, and certification notes on my blog:
**[kevinflorencio.github.io](https://kevinflorencio.github.io/)**
