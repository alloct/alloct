<!-- Banner -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8B0000,100:0d1117&height=210&section=header&text=alloct&fontColor=ffffff&fontSize=72&fontAlignY=36&desc=breaking%20things%2C%20then%20documenting%20the%20cleanup&descAlignY=58&descAlign=50&descSize=18" alt="alloct" />
</div>

<!-- Roles -->
<div align="center">
  <a href="https://github.com/alloct">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=2800&pause=700&color=D1001F&center=true&vCenter=true&width=720&lines=Adversary+emulation+%26+C2+infrastructure;Incident+response+%26+threat+hunting;Detection+engineering;Security+tooling+I+actually+ship" alt="roles" />
  </a>
</div>

<br/>

<div align="center">

I work both sides of security. On offense that means adversary emulation and C2 infrastructure.<br/>
On defense it means incident response, threat hunting, and detection engineering.<br/>
The work runs from small business through enterprise. Everything below is either a tool I built or notes I kept along the way.

</div>

<br/>

<!-- Quick nav -->
<div align="center">
  <a href="#tools-i-build"><img src="https://img.shields.io/badge/Tools-8B0000?style=for-the-badge" /></a>
  <a href="#writeups--labs"><img src="https://img.shields.io/badge/Writeups-1A1A1A?style=for-the-badge" /></a>
  <a href="#stack"><img src="https://img.shields.io/badge/Stack-1A1A1A?style=for-the-badge" /></a>
  <a href="https://theprivacycookbook.com"><img src="https://img.shields.io/badge/Live_Site-D1001F?style=for-the-badge" /></a>
</div>

<br/>

## Tools I build

<a id="tools-i-build"></a>

| Project | What it is | Stack |
| :------ | :--------- | :---- |
| [The Privacy Cookbook](https://github.com/alloct/privacy-cookbook) | Privacy and OPSEC knowledge base. Threat models before tools, sourced claims, zero trackers. Live at [theprivacycookbook.com](https://theprivacycookbook.com). | Eleventy `·` JS |
| [Trailmark](https://github.com/alloct/trailmark-ti) | Forensic browser-history viewer. Finds and parses history artifacts across a triage image, recovers hot WAL data, defangs every URL in its reports. | Python `·` Qt |
| [Aegis](https://github.com/alloct/Win11-Aegis-Optimize) | Windows 10/11 debloat, privacy, and hardening. Every change is journaled and reversible down to a single tweak. | PowerShell |
| [Aegis Light](https://github.com/alloct/aegis-light-linux) | Idempotent Debian and Ubuntu hardening. Dry run preview plus a generated rollback script for every run. | Bash |
| [Security Posture Reviews](https://github.com/alloct/Security-Posture-Reviews) | MSP assessment tool. Scores client posture, ingests Nessus output, and generates reports. | FastAPI |
| [Job Jacker](https://github.com/alloct/job-jacker) | Watches job boards, filters postings against YAML rules, pushes matches to Discord. | Python |

<br/>

## Writeups & labs

<a id="writeups--labs"></a>

<table>
<tr>
<td valign="top" width="50%">

**Offensive & red team**
- [C2 Labs](https://github.com/alloct/C2-Labs): Sliver C2 setup and initial testing
- [Oops, I Dropped My Artifacts](https://github.com/alloct/Oops-My-Artifacts): infostealer POC for IR and detection demos
- [DLL Sideloading Demo](https://github.com/alloct/DLLsideloading-BasicDemo): abusing the Windows DLL search order
- [OWASP Top 10](https://github.com/alloct/OWASP-Top-10)
- [CTF Writeups](https://github.com/alloct/Capture-The-Flags)

**OSINT & CTI**
- [Canadian OSINT Toolbox](https://github.com/alloct/OSINT-Canada): curated resources for Canadian investigations
- [OSINT Writeups](https://github.com/alloct/OSINT-Writeups)

**Vulnerability management**
- [Scanning & Patching](https://github.com/alloct/Vulnerability-Scanning-and-Patching): Nessus scanner build and tuning

</td>
<td valign="top" width="50%">

**Defensive, DFIR & detection**
- [DFIR](https://github.com/alloct/DFIR): playbooks and checklists (BEC and M365 triage)
- [Threat Hunting & Intel](https://github.com/alloct/Threat-Intelligence-and-Hunts): hunts, IOC work, Splunk intrusion detection
- [SIEM Query Building](https://github.com/alloct/SIEM-Query-Building): detection logic and CrowdStrike queries
- [CrowdStrike Resources](https://github.com/alloct/Crowdstrike): custom IOA rules and RTR scripts
- [Endpoint Security](https://github.com/alloct/Endpoint-Security-Collection)
- [Cyber Defense Frameworks](https://github.com/alloct/Cyber-Defense-Frameworks)
- [Network Analysis & IDS](https://github.com/alloct/Network-Security-and-Analysis-Collection)

</td>
</tr>
</table>

<br/>

## Stack

<a id="stack"></a>

<details open>
<summary><b>🔴 Offensive & red teaming</b></summary>
<br/>
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
  <img src="https://img.shields.io/badge/NetExec-66CC66?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Covenant-CC0000?style=for-the-badge&logoColor=white" />
</div>
</details>

<details>
<summary><b>🔵 Digital forensics & incident response</b></summary>
<br/>
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
</details>

<details>
<summary><b>🟠 Threat intelligence & OSINT</b></summary>
<br/>
<div>
  <img src="https://img.shields.io/badge/MISP-005D8C?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Maltego-E05A00?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/VirusTotal-42B4E6?style=for-the-badge&logo=virustotal&logoColor=white" />
  <img src="https://img.shields.io/badge/Shodan-FF4000?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Censys-4B0082?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/GreyNoise-111111?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Proofpoint-F9611A?style=for-the-badge&logoColor=white" />
</div>
</details>

<details>
<summary><b>🛡️ Endpoint security & EDR</b></summary>
<br/>
<div>
  <img src="https://img.shields.io/badge/CrowdStrike_Falcon-2A3681?style=for-the-badge&logo=CrowdStrike&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Defender-00A4EF?style=for-the-badge&logo=Microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Bitdefender-D82C20?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Hornet_Security-222222?style=for-the-badge&logoColor=white" />
</div>
</details>

<details>
<summary><b>📊 SIEM & monitoring</b></summary>
<br/>
<div>
  <img src="https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=Microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=Splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white" />
  <img src="https://img.shields.io/badge/Wazuh-E8820C?style=for-the-badge&logoColor=white" />
</div>
</details>

<details>
<summary><b>🌐 Network, vuln & cloud</b></summary>
<br/>
<div>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=Wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-4E9A06?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Snort-CC0000?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Nessus-00C176?style=for-the-badge&logo=tenable&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Veeam-00B140?style=for-the-badge&logo=veeam&logoColor=white" />
  <img src="https://img.shields.io/badge/Acronis-0033A0?style=for-the-badge&logo=acronis&logoColor=white" />
</div>
</details>

<br/>

## Activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=alloct&show_icons=true&hide_rank=true&hide_border=true&bg_color=0d1117&title_color=D1001F&icon_color=D1001F&text_color=c9d1d9" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alloct&layout=compact&hide_border=true&bg_color=0d1117&title_color=D1001F&text_color=c9d1d9&langs_count=8" alt="top languages" />
</div>

<br/>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alloct)
[![Website](https://img.shields.io/badge/theprivacycookbook.com-D1001F?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://theprivacycookbook.com)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:8B0000&height=120&section=footer" alt="" />
