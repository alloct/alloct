<div align="center">

# alloct

**Breaking things, then documenting the cleanup.**

</div>

---

I work both sides of security: adversary emulation and C2 infrastructure on one end, incident response, threat hunting, and detection engineering on the other. Day to day that runs from small business to enterprise. This page points to the tools I build and the notes I keep as I go.

## Tools I build

| Project | What it is | Stack |
| :------ | :--------- | :---- |
| [The Privacy Cookbook](https://github.com/alloct/privacy-cookbook) | Privacy and OPSEC knowledge base. Threat models before tools, sourced claims, zero trackers. Live at [theprivacycookbook.com](https://theprivacycookbook.com). | Eleventy · JS |
| [Trailmark](https://github.com/alloct/trailmark-ti) | Forensic browser-history viewer. Finds and parses history artifacts across a triage image, recovers hot WAL data, defangs every URL in its reports. | Python · Qt |
| [Aegis](https://github.com/alloct/Win11-Aegis-Optimize) | Windows 10/11 debloat, privacy, and hardening. Every change is journaled and reversible down to a single tweak. | PowerShell |
| [Aegis Light](https://github.com/alloct/aegis-light-linux) | Idempotent Debian/Ubuntu hardening. `--dry-run` preview and a generated rollback script for every run. | Bash |
| [Security Posture Reviews](https://github.com/alloct/Security-Posture-Reviews) | MSP assessment tool: scores client posture, ingests Nessus output, and generates reports. | FastAPI |
| [Job Jacker](https://github.com/alloct/job-jacker) | Watches job boards, filters postings against YAML rules, pushes matches to Discord. | Python |

## Writeups & labs

**Offensive & red team**
- [C2 Labs](https://github.com/alloct/C2-Labs) — Sliver C2 setup and initial testing
- [Oops, I Dropped My Artifacts](https://github.com/alloct/Oops-My-Artifacts) — infostealer proof of concept for IR/detection demos
- [DLL Sideloading Demo](https://github.com/alloct/DLLsideloading-BasicDemo) — identifying and abusing the Windows DLL search order
- [OWASP Top 10](https://github.com/alloct/OWASP-Top-10) · [CTF Writeups](https://github.com/alloct/Capture-The-Flags)

**Defensive, DFIR & detection**
- [DFIR](https://github.com/alloct/DFIR) — playbooks and checklists (BEC/M365 triage)
- [Threat Hunting & Intel](https://github.com/alloct/Threat-Intelligence-and-Hunts) — hunts, IOC work, Splunk intrusion detection
- [SIEM Query Building](https://github.com/alloct/SIEM-Query-Building) — detection logic and CrowdStrike queries
- [CrowdStrike Resources](https://github.com/alloct/Crowdstrike) — custom IOA rules and RTR scripts
- [Endpoint Security](https://github.com/alloct/Endpoint-Security-Collection) · [Cyber Defense Frameworks](https://github.com/alloct/Cyber-Defense-Frameworks) · [Network Analysis & IDS](https://github.com/alloct/Network-Security-and-Analysis-Collection)

**OSINT & CTI**
- [Canadian OSINT Toolbox](https://github.com/alloct/OSINT-Canada) — curated OSINT resources for Canadian investigations
- [OSINT Writeups](https://github.com/alloct/OSINT-Writeups)

**Vulnerability management**
- [Vulnerability Scanning & Patching](https://github.com/alloct/Vulnerability-Scanning-and-Patching) — Nessus scanner build and tuning

## Tools & technologies

### 🔴 Offensive Security & Red Teaming
<div>
  <img src="https://img.shields.io/badge/Kali_Linux-557C9C?style=for-the-badge&logo=kali-linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Cobalt_Strike-FF0000?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Sliver_C2-4B0082?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Mythic_C2-1A1A1A?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Metasploit-2A2A2A?style=for-the-badge&logo=metasploit&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
  <img src="https://img.shields.io/badge/Impacket-66CC66?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Mimikatz-4169E1?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/BloodHound-CC0000?style=for-the-badge&logo=neo4j&logoColor=white" />
  <img src="https://img.shields.io/badge/MITRE_Caldera-8B0000?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/GoPhish-FF9933?style=for-the-badge&logo=maildotru&logoColor=white" />
  <img src="https://img.shields.io/badge/Evilginx-800000?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/CrackMapExec_/_NetExec-66CC66?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Covenant-CC0000?style=for-the-badge&logoColor=white" />
</div>

### 🔵 Digital Forensics & Incident Response (DFIR)
<div>
  <img src="https://img.shields.io/badge/KAPE-5E4B8B?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Volatility-00517F?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Autopsy-E8820C?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/FTK_Imager-003087?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/REMnux-604A7B?style=for-the-badge&logo=debian&logoColor=white" />
  <img src="https://img.shields.io/badge/Velociraptor-1DB954?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Ghidra-305609?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/YARA_%2F_Sigma-1565C0?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Chainsaw-B22222?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Hayabusa-990000?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Eric_Zimmerman_Tools-8B0000?style=for-the-badge&logo=windows&logoColor=white" />
</div>

### 🟠 Cyber Threat Intelligence (CTI) & OSINT
<div>
  <img src="https://img.shields.io/badge/MISP-005D8C?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Maltego-E05A00?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/VirusTotal-42B4E6?style=for-the-badge&logo=virustotal&logoColor=white" />
  <img src="https://img.shields.io/badge/Shodan-FF4000?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Censys-4B0082?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/GreyNoise-111111?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Proofpoint-F9611A?style=for-the-badge&logoColor=white" />
</div>

### 🛡️ Endpoint Security & EDR
<div>
  <img src="https://img.shields.io/badge/CrowdStrike_Falcon-2A3681?style=for-the-badge&logo=CrowdStrike&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Defender_for_Endpoint-00A4EF?style=for-the-badge&logo=Microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Bitdefender-D82C20?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Hornet_Security-222222?style=for-the-badge&logoColor=white" />
</div>

### 📊 SIEM & Security Monitoring
<div>
  <img src="https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=Microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=Splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white" />
  <img src="https://img.shields.io/badge/Wazuh-E8820C?style=for-the-badge&logoColor=white" />
</div>

### 🌐 Network & Vulnerability Management
<div>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=Wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-4E9A06?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Snort-CC0000?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Nessus-00C176?style=for-the-badge&logo=tenable&logoColor=white" />
</div>

### ☁️ Cloud & Infrastructure
<div>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Datto_BCDR-0078D7?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Veeam-00B140?style=for-the-badge&logo=veeam&logoColor=white" />
  <img src="https://img.shields.io/badge/Acronis-0033A0?style=for-the-badge&logo=acronis&logoColor=white" />
</div>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alloct)

</div>
