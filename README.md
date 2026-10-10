# Kevin Florencio

**Security researcher — bug bounty, detection engineering, and blue-team labs.**

<a href="https://www.linkedin.com/in/kevin-florencio-b8a571298/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGNpcmNsZSBjeD0iNCIgY3k9IjQuNSIgcj0iMi40Ii8%2BPHBhdGggZD0iTTIgOC40aDR2MTMuMUgyeiIvPjxwYXRoIGQ9Ik04LjIgOC40aDMuOHYxLjljLjktMS41IDIuNy0yLjMgNC42LTIuMyAzLjQgMCA1LjQgMi4yIDUuNCA2LjN2Ny4yaC0zLjh2LTYuOGMwLTIuMS0xLTMuMi0yLjctMy4yLTEuOCAwLTMuMSAxLjItMy4xIDMuNXY2LjVIOC4yeiIvPjwvc3ZnPg%3D%3D&logoColor=white" /></a>
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
built on Splunk and Discord, with a **locally hosted Mistral 7B** doing the
analysis. Adapted from the MyDFIR reference build, swapping the hosted LLM and
Slack for a local model and Discord so triage runs fully offline.

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
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMTIgMS41IDIxLjUgNC44djcuNGMwIDUuNS0zLjggOS4yLTkuNSAxMC4zQzYuMyAyMS40IDIuNSAxNy43IDIuNSAxMi4yVjQuOFpNMTIgOC4xYzMuNiAwIDYuMiAyLjYgNy4yIDQuMS0xIDEuNS0zLjYgNC4xLTcuMiA0LjFTNS44IDEzLjcgNC44IDEyLjJDNS44IDEwLjcgOC40IDguMSAxMiA4LjFaTTEyIDEwLjJhMiAyIDAgMSAwIDAgNCAyIDIgMCAwIDAgMC00WiIvPjwvc3ZnPg%3D%3D&logoColor=white" />
    <img src="https://img.shields.io/badge/-Wazuh-005C8A?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMTIgMS41IDIxLjUgNC44djcuNGMwIDUuNS0zLjggOS4yLTkuNSAxMC4zQzYuMyAyMS40IDIuNSAxNy43IDIuNSAxMi4yVjQuOFpNNi40IDcuNmgyLjJsMS4zIDUuNiAxLjMtNS42aDEuNmwxLjMgNS42IDEuMy01LjZoMi4ybC0yLjQgOC44aC0xLjlMMTIgMTEuMWwtMS4zIDUuM0g4LjhaIi8%2BPC9zdmc%2B&logoColor=white" />
    <img src="https://img.shields.io/badge/-KQL-0062AD?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZD0iTTIuNSAzLjRoMTIuNHYyLjRIMi41ek0yLjUgOGg5LjZ2Mi40SDIuNXpNMi41IDEyLjZoNi42VjE1SDIuNXoiLz48cGF0aCBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0xNS42IDEwLjNhNC42IDQuNiAwIDEgMCAwIDkuMiA0LjYgNC42IDAgMCAwIDAtOS4yWm0wIDIuMmEyLjQgMi40IDAgMSAxIDAgNC44IDIuNCAyLjQgMCAwIDEgMC00LjhaIi8%2BPHBhdGggZD0ibTE4LjkgMTcuNiAxLjUtMS41IDMuMSAzLjEtMS41IDEuNXoiLz48L3N2Zz4%3D&logoColor=white" />
    <img src="https://img.shields.io/badge/-MITRE_ATT&CK-C8102E?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZD0iTTIuNCAyLjZoNS40djYuMUgyLjR6TTkuMyAyLjZoNS40djguNkg5LjN6TTE2LjIgMi42aDUuNHY0LjZoLTUuNHpNMi40IDEwLjJoNS40djQuNkgyLjR6TTkuMyAxMi43aDUuNHY0LjZIOS4zek0xNi4yIDguN2g1LjR2Ni4xaC01LjR6TTIuNCAxNi4zaDUuNHY1LjFIMi40ek05LjMgMTguOGg1LjR2Mi42SDkuM3pNMTYuMiAxNi4zaDUuNHY1LjFoLTUuNHoiLz48L3N2Zz4%3D&logoColor=white" />
</div>

**Threat Intelligence & Automation**
<div>
    <img src="https://img.shields.io/badge/-OpenCTI-001BFF?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGcgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjEuNyI%2BPHBhdGggZD0iTTEyIDEyIDQuNiA1LjRNMTIgMTJsNy42LTQuNk0xMiAxMnY4LjQiLz48L2c%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMy4yIi8%2BPGNpcmNsZSBjeD0iNC4xIiBjeT0iNC44IiByPSIyLjciLz48Y2lyY2xlIGN4PSIyMC4xIiBjeT0iNi44IiByPSIyLjciLz48Y2lyY2xlIGN4PSIxMiIgY3k9IjIxIiByPSIyLjciLz48L3N2Zz4%3D&logoColor=white" />
    <img src="https://img.shields.io/badge/-Local_LLMs-412991?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNNi4yIDYuMmgxMS42djExLjZINi4yWm0yLjQgMi40djYuOGg2LjhWOC42WiIvPjxwYXRoIGQ9Ik04LjQgMS42aDEuOXYzLjRIOC40ek0xMy43IDEuNmgxLjl2My40aC0xLjl6TTguNCAxOWgxLjl2My40SDguNHpNMTMuNyAxOWgxLjl2My40aC0xLjl6TTEuNiA4LjRINXYxLjlIMS42ek0xLjYgMTMuN0g1djEuOUgxLjZ6TTE5IDguNGgzLjR2MS45SDE5ek0xOSAxMy43aDMuNHYxLjlIMTl6Ii8%2BPHBhdGggZD0iTTEwLjQgMTAuNGgzLjJ2My4yaC0zLjJ6Ii8%2BPC9zdmc%2B&logoColor=white" />
</div>

**Offensive Security**
<div>
    <img src="https://img.shields.io/badge/-Burp_Suite-FF6633?&style=for-the-badge&logo=burpsuite&logoColor=white" />
    <img src="https://img.shields.io/badge/-Nmap-214478?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiPjxwYXRoIGQ9Ik0zLjIgMTkuNWE4LjggOC44IDAgMCAxIDE3LjYgMCIvPjxwYXRoIGQ9Ik03LjYgMTkuNWE0LjQgNC40IDAgMCAxIDguOCAwIi8%2BPC9nPjxwYXRoIGQ9Ik0xLjQgMTkuM2gyMS4ydjIuM0gxLjR6Ii8%2BPGNpcmNsZSBjeD0iMTcuNCIgY3k9IjguNCIgcj0iMi41Ii8%2BPC9zdmc%2B&logoColor=white" />
    <img src="https://img.shields.io/badge/-API_Security-6BA539?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIuMSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJNNi42IDMuMkM0LjQgMy4yIDQuNCA5LjggMi4zIDkuOGMyLjEgMCAyLjEgNi42IDQuMyA2LjYiLz48cGF0aCBkPSJNMTcuNCAzLjJjMi4yIDAgMi4yIDYuNiA0LjMgNi42LTIuMSAwLTIuMSA2LjYtNC4zIDYuNiIvPjxwYXRoIGQ9Ik05LjQgMTIuM3YtMS45YTIuNiAyLjYgMCAwIDEgNS4yIDB2MS45Ii8%2BPC9nPjxwYXRoIGQ9Ik04LjEgMTIuMWg3Ljh2Ni40SDguMXoiLz48L3N2Zz4%3D&logoColor=white" />
    <img src="https://img.shields.io/badge/-Frida-E86337?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMTIgMS44YzUuNCAwIDkuMiAzLjIgOS4yIDggMCA0LjktMy44IDEyLjQtOS4yIDEyLjRTMi44IDE0LjcgMi44IDkuOGMwLTQuOCAzLjgtOCA5LjItOFptLTMuMiA3YTIgMiAwIDEgMCAwIDQgMiAyIDAgMCAwIDAtNFptNi40IDBhMiAyIDAgMSAwIDAgNCAyIDIgMCAwIDAgMC00WiIvPjwvc3ZnPg%3D%3D&logoColor=white" />
    <img src="https://img.shields.io/badge/-Ghidra-FF6600?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMS44IDEzLjQgNi42IDcuNmw0LjIgMS4xTDEzLjEgMy42bDIuNSA1LjMgNyAyLjItMi40IDIuOCAyLjIgMi40LTcuMSAzLjRINy4zWm0xMi4zLTIuNmExLjQgMS40IDAgMSAwIDAgMi44IDEuNCAxLjQgMCAwIDAgMC0yLjhaIi8%2BPC9zdmc%2B&logoColor=white" />
    <img src="https://img.shields.io/badge/-Android_Security-3DDC84?&style=for-the-badge&logo=android&logoColor=white" />
</div>

**Digital Forensics**
<div>
    <img src="https://img.shields.io/badge/-Volatility-4B275F?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMS42IDYuNGgyMC44djguNEgxLjZabTMgMi4xdjQuMmgyLjNWOC41Wm00LjIgMHY0LjJIMTFWOC41Wm00LjIgMHY0LjJoMi4zVjguNVptNC4yIDB2NC4yaDIuM1Y4LjVaIi8%2BPHBhdGggZD0iTTIuOCAxNmgyLjR2My4ySDIuOHpNNy4xIDE2aDIuNHYzLjJINy4xek0xMS40IDE2aDIuNHYzLjJoLTIuNHpNMTUuNyAxNmgyLjR2My4yaC0yLjR6TTIwIDE2aDIuNHYzLjJIMjB6Ii8%2BPC9zdmc%2B&logoColor=white" />
    <img src="https://img.shields.io/badge/-KAPE-0B6E4F?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZD0iTTEwLjYgMS44aDIuOHY2LjRoLTIuOHoiLz48cGF0aCBkPSJNMTIgMTMuNCA2LjYgNy42aDEwLjh6Ii8%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMi40IDE0LjZoMTkuMnY3LjZIMi40Wm0yLjMgMi4ydjMuMmgxNC42di0zLjJaIi8%2BPC9zdmc%2B&logoColor=white" />
    <img src="https://img.shields.io/badge/-FTK_Imager-B02A37?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMTIgMS45YTEwLjEgMTAuMSAwIDEgMCAwIDIwLjIgMTAuMSAxMC4xIDAgMCAwIDAtMjAuMlptMCAyLjRhNy43IDcuNyAwIDEgMSAwIDE1LjQgNy43IDcuNyAwIDAgMSAwLTE1LjRaIi8%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMi42Ii8%2BPHBhdGggZD0ibTE0LjkgMTMuOSAxLjgtMS42IDQuNCA1LTEuOSAxLjZ6Ii8%2BPC9zdmc%2B&logoColor=white" />
</div>

**Platforms & Infrastructure**
<div>
    <img src="https://img.shields.io/badge/-Windows_Server-0078D6?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPHBhdGggZD0iTTIuNiAyLjhoOC4ydjguMkgyLjZ6TTEzLjIgMi44aDguMnY4LjJoLTguMnpNMi42IDEzLjRoOC4ydjguMkgyLjZ6TTEzLjIgMTMuNGg4LjJ2OC4yaC04LjJ6Ii8%2BPC9zdmc%2B&logoColor=white" />
    <img src="https://img.shields.io/badge/-Active_Directory-0B5394?&style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGcgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjEuOCIgZmlsbD0ibm9uZSI%2BPHBhdGggZD0iTTEyIDcuMnY0LjRNNS40IDE3di0yLjZoMTMuMlYxNyIvPjxwYXRoIGQ9Ik0xMiAxMS42djIuOCIvPjwvZz48Y2lyY2xlIGN4PSIxMiIgY3k9IjQuMiIgcj0iMy4yIi8%2BPHBhdGggZD0iTTIuNiAxN2g1LjZ2NC40SDIuNnpNOS4yIDE3aDUuNnY0LjRIOS4yek0xNS44IDE3aDUuNnY0LjRoLTUuNnoiLz48L3N2Zz4%3D&logoColor=white" />
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
