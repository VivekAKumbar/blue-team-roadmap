<div align="center">

```
██████╗ ██╗     ██╗   ██╗███████╗    ████████╗███████╗ █████╗ ███╗   ███╗
██╔══██╗██║     ██║   ██║██╔════╝    ╚══██╔══╝██╔════╝██╔══██╗████╗ ████║
██████╔╝██║     ██║   ██║█████╗         ██║   █████╗  ███████║██╔████╔██║
██╔══██╗██║     ██║   ██║██╔══╝         ██║   ██╔══╝  ██╔══██║██║╚██╔╝██║
██████╔╝███████╗╚██████╔╝███████╗       ██║   ███████╗██║  ██║██║ ╚═╝ ██║
╚═════╝ ╚══════╝ ╚═════╝ ╚══════╝       ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝
                R O A D M A P  —  V I V E K  A  K U M B A R
```

**SOC Analyst Track · Blue Team · Zero to Hired**

[

![Progress](https://img.shields.io/badge/Overall_Progress-5%25-yellow?style=flat-square&logo=target)

](https://github.com/VivekAKumbar/blue-team-roadmap)
[

![Phase](https://img.shields.io/badge/Current_Phase-01_Networking-1a365d?style=flat-square)

](https://github.com/VivekAKumbar/blue-team-roadmap)
[

![Started](https://img.shields.io/badge/Started-Sep_2026-green?style=flat-square)

](https://github.com/VivekAKumbar/blue-team-roadmap)
[

![Goal](https://img.shields.io/badge/Goal-SOC_Analyst_Role-gold?style=flat-square)

](https://github.com/VivekAKumbar/blue-team-roadmap)

*I update this daily. Every checkbox ticked = a skill earned.*

</div>

---

## 🗺️ Phase Overview

| # | Phase | Status | Progress |
|:-:|-------|:------:|----------|
| 01 | [Networking Fundamentals](#-phase-01--networking-fundamentals) | 🟡 In Progress | `░░░░░░░░░░` 0% |
| 02 | [Windows Essentials](#-phase-02--windows-essentials) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 03 | [Linux Command Line](#-phase-03--linux-command-line) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 04 | [Scripting & Automation](#-phase-04--scripting--automation) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 05 | [Security Fundamentals](#-phase-05--security-fundamentals) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 06 | [Blue Team Tools](#-phase-06--blue-team-tools) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 07 | [Certifications](#-phase-07--certifications) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 08 | [Hands-On Practice](#-phase-08--hands-on-practice) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 09 | [Build Your Portfolio](#-phase-09--build-your-portfolio) | ⬜ Not Started | `░░░░░░░░░░` 0% |
| 10 | [Get Hired](#-phase-10--get-hired) | ⬜ Not Started | `░░░░░░░░░░` 0% |

> **How I track:** Every ✅ = completed. Every 🟡 = in progress. I commit to this repo every day I study — even one checkbox counts.

---

## 🌐 Phase 01 — Networking Fundamentals

> **Timeline:** Weeks 1–4 · **Effort:** 2–3 hrs/day
> Every security alert involves network traffic. You can't investigate threats without understanding how data moves.

### 1.1 OSI Model & TCP/IP Stack
- [ ] The 7-layer OSI model and how it maps to the 4-layer TCP/IP model
- [ ] What happens at each layer (Physical, Data Link, Network, Transport, Session, Presentation, Application)
- [ ] How encapsulation works — data → segment → packet → frame → bits
- [ ] Which layer an attack targets and why it matters for detection

### 1.2 IP Addressing & Subnetting
- [ ] IPv4 address structure (32-bit, dotted decimal notation)
- [ ] Private vs public IP ranges (10.x.x.x, 172.16–31.x.x, 192.168.x.x)
- [ ] CIDR notation (/24, /16, /8) and what they mean
- [ ] Subnet masks — calculate network/host portions
- [ ] NAT (Network Address Translation) and why it exists
- [ ] IPv6 basics (128-bit, hexadecimal notation)

### 1.3 Critical Protocols & Ports

| Protocol | Port | Security Relevance |
|----------|------|--------------------|
| DNS | 53 | DNS tunneling, DGA detection |
| HTTP | 80 | Credential theft, malware delivery |
| HTTPS | 443 | C2 hiding in TLS |
| SSH | 22 | Brute force, unauthorized access |
| RDP | 3389 | #1 ransomware entry vector |
| SMTP | 25 | Phishing, spoofing |
| FTP | 20/21 | Credential sniffing, exfiltration |
| SMB | 445 | EternalBlue, lateral movement |
| LDAP | 389/636 | Active Directory attacks |
| Kerberos | 88 | Kerberoasting, Golden Ticket |
| Syslog | 514 | Log analysis, SIEM ingestion |

- [ ] Memorized all protocols and ports above

### 1.4 Network Devices & Architecture
- [ ] Routers — Layer 3, forward between networks
- [ ] Switches — Layer 2, forward within networks
- [ ] Firewalls — stateful vs stateless packet filtering
- [ ] Proxies — forward vs reverse
- [ ] IDS vs IPS — detect vs prevent
- [ ] VLANs — logical network segmentation
- [ ] DMZ — demilitarized zone for public-facing services

### 1.5 Wireshark Basics
- [ ] Packet capture fundamentals
- [ ] Display filters vs capture filters
- [ ] Following TCP streams
- [ ] Identifying common protocols visually
- [ ] Spotting anomalous traffic patterns

### 📚 Resources
| Resource | Type |
|----------|------|
| [Professor Messer Network+ N10-009](https://www.youtube.com/playlist?list=PLG49S3nxzAnlCJiCrOYuRYb6cne864a7G) | 87-episode free course |
| [TryHackMe Pre-Security Path](https://tryhackme.com/path/outline/presecurity) | Interactive labs |
| [Cisco NetAcad — Intro to Networks](https://www.netacad.com/) | Free course |
| [Practical Networking](https://www.youtube.com/@PracticalNetworking) | YouTube |
| [Subnetting Practice](https://subnettingpractice.com/) | Drill site |

### ✅ Phase 01 Completion Checklist
- [ ] Can explain OSI and TCP/IP stack
- [ ] Can subnet an IP and calculate ranges
- [ ] Memorized all critical protocols and ports
- [ ] Understand router / switch / firewall / proxy roles
- [ ] Can capture and read basic traffic in Wireshark
- [ ] Completed TryHackMe Pre-Security networking rooms

---

## 🖥️ Phase 02 — Windows Essentials

> **Timeline:** Weeks 3–6 · **Effort:** 2–3 hrs/day
> 90%+ of enterprise environments run Windows with Active Directory. Windows Event Logs are your primary SOC data source.

### 2.1 Active Directory
- [ ] Domains, forests, and trusts — hierarchical structure
- [ ] Users, groups, and OUs — how access is organized
- [ ] Group Policy Objects (GPO) — how settings are enforced
- [ ] Kerberos authentication — TGT, TGS, service tickets
- [ ] NTLM — legacy protocol, pass-the-hash attacks
- [ ] Domain Controllers — most critical servers in the enterprise

### 2.2 Windows Event IDs (Must Memorize)

| Event ID | Log | Meaning | Why It Matters |
|----------|-----|---------|----------------|
| 4624 | Security | Successful logon | Track access |
| 4625 | Security | Failed logon | Brute force detection |
| 4648 | Security | Explicit credential logon | Lateral movement |
| 4672 | Security | Special privileges assigned | Admin access |
| 4688 | Security | New process created | Malware execution |
| 4720 | Security | User account created | Persistence |
| 4728 | Security | Added to security group | Privilege escalation |
| 1102 | Security | Audit log cleared | Almost always malicious |
| 7045 | System | New service installed | Malware persistence |
| 4104 | PowerShell | Script block logging | Malicious PS detection |
| 1 | Sysmon | Process creation | Detailed process tracking |
| 3 | Sysmon | Network connection | C2 communication |
| 11 | Sysmon | File creation | Malware delivery |
| 22 | Sysmon | DNS query | DNS-based C2, DGA |

- [ ] Memorized all Event IDs above
- [ ] Can read Event Log sequences and identify attack patterns

### 2.3 PowerShell for Investigation
- [ ] `Get-WinEvent` — filter security events
- [ ] `Get-Process` — list running processes
- [ ] `Get-NetTCPConnection` — check network connections
- [ ] `Get-ScheduledTask` — find persistence mechanisms
- [ ] `Get-ChildItem -Recurse` — find recently modified files

### 2.4 Sysmon
- [ ] Installed Sysmon with SwiftOnSecurity config
- [ ] Understand key Sysmon Event IDs (1, 3, 7, 8, 10, 11, 13, 22)
- [ ] Know how Sysmon enhances default Windows logging

### 2.5 Persistence Locations
- [ ] Registry run keys (`HKLM\SOFTWARE\...\Run`)
- [ ] Services (`services.msc`) — malware installs as service
- [ ] Scheduled Tasks — automated persistence
- [ ] WMI subscriptions — advanced persistence

### 📚 Resources
| Resource | Type |
|----------|------|
| [TryHackMe Windows Fundamentals 1, 2, 3](https://tryhackme.com/room/windowsfundamentals1xbx) | Labs |
| [TryHackMe Active Directory Basics](https://tryhackme.com/room/winadbasics) | Lab |
| [TryHackMe Windows Event Logs](https://tryhackme.com/room/windowseventlogs) | Lab |
| [TryHackMe Sysmon](https://tryhackme.com/room/sysmon) | Lab |
| [13Cubed — Windows Forensics](https://www.youtube.com/@13Cubed) | YouTube |

### ✅ Phase 02 Completion Checklist
- [ ] Understand Active Directory structure
- [ ] Can explain Kerberos authentication flow
- [ ] Memorized critical Windows Event IDs
- [ ] Can read Event Log sequences for attack patterns
- [ ] Know basic PowerShell investigation commands
- [ ] Understand Sysmon and its key Event IDs
- [ ] Know common persistence locations
- [ ] Completed TryHackMe Windows rooms

---

## 🐧 Phase 03 — Linux Command Line

> **Timeline:** Weeks 4–7 · **Effort:** 2 hrs/day
> Most security tools and servers run Linux. You need terminal fluency.

### 3.1 Navigation & File Operations
- [ ] `pwd`, `ls -la`, `cd`, `find`, `tree`
- [ ] `cat`, `head`, `tail -f`, `less`, `cp`, `mv`
- [ ] `chmod`, `chown` — permissions and ownership
- [ ] Understanding rwx permissions and octal notation

### 3.2 Text Processing (Used Daily in Log Analysis)
- [ ] `grep` — search for patterns, `-i`, `-r`, `-c` flags
- [ ] `awk` — extract specific fields from logs
- [ ] `sed` — find and replace
- [ ] `sort | uniq -c | sort -rn` — count unique occurrences
- [ ] `wc -l` — count lines
- [ ] `cut` — extract CSV/delimited fields
- [ ] Piping commands with `|`

### 3.3 System & Process Investigation
- [ ] `ps aux` — list all running processes
- [ ] `top` / `htop` — real-time process monitoring
- [ ] `netstat -tulnp` / `ss -tulnp` — listening ports
- [ ] `who`, `w`, `last` — logged-in users, login history
- [ ] `df -h`, `free -h` — disk and memory usage

### 3.4 Key Directories for Blue Team
```
/var/log/         → System and application logs
/var/log/auth.log → Authentication logs (SSH, sudo)
/etc/passwd       → User accounts
/etc/shadow       → Password hashes
/etc/crontab      → Scheduled tasks
/tmp/             → Malware often lands here
/proc/            → Virtual filesystem with process info
```
- [ ] Know where to find all log files above
- [ ] Can use `tail -f` to monitor logs in real-time

### 3.5 Bash Pipelines
- [ ] Count failed SSH login attempts from auth.log
- [ ] Extract top 10 source IPs from an access log
- [ ] Find files larger than 100MB (data staging detection)
- [ ] Monitor live logs for error/warning keywords

### 📚 Resources
| Resource | Type |
|----------|------|
| [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) | Wargame (34 levels) |
| [TryHackMe Linux Fundamentals 1, 2, 3](https://tryhackme.com/room/linuxfundamentalspart1) | Labs |
| [LetsDefend — Linux for Blue Team](https://app.letsdefend.io/training/lessons/linux-for-blue-team) | Course |
| [Explainshell](https://explainshell.com/) | Command explainer |
| [The Linux Command Line (Free PDF)](https://linuxcommand.org/tlcl.php) | Book |

### ✅ Phase 03 Completion Checklist
- [ ] Navigate the Linux filesystem comfortably
- [ ] Use grep, awk, sed for text processing
- [ ] Understand file permissions (rwx, chmod, chown)
- [ ] Chain commands with pipes
- [ ] Know where to find important log files
- [ ] Monitor processes and network connections
- [ ] Completed OverTheWire Bandit levels 0–15
- [ ] Completed TryHackMe Linux Fundamentals rooms

---

## 🐍 Phase 04 — Scripting & Automation

> **Timeline:** Weeks 5–8 · **Effort:** 2–3 hrs/day
> You don't need to be a developer. You need functional scripting — parse logs, call APIs, automate repetitive tasks.

### 4.1 Python Core
- [ ] Variables, data types, control flow (if/for/while)
- [ ] Functions and modules
- [ ] File I/O — reading/writing text, CSV, JSON
- [ ] Error handling — `try/except`
- [ ] Lists, dictionaries, sets

### 4.2 Security-Relevant Python Libraries
- [ ] `open()` — parse log files line by line
- [ ] `re` — regex pattern matching in logs
- [ ] `requests` — call APIs (VirusTotal, AbuseIPDB)
- [ ] `json` — parse structured API responses
- [ ] `csv` — parse alert exports
- [ ] `hashlib` — calculate MD5/SHA256 for IOC checking

### 4.3 Python Projects Built
- [ ] Log Parser — extract and count unique IPs from a log file
- [ ] IP Reputation Checker — query AbuseIPDB/VirusTotal API
- [ ] Hash Lookup Tool — calculate file hash, check VirusTotal
- [ ] Phishing URL Analyzer — extract and scan URLs from emails
- [ ] Port Scanner — check if common ports are open

### 4.4 Bash Scripting
- [ ] Variables, conditionals, loops in Bash
- [ ] Monitor failed SSH logins and alert on threshold
- [ ] Automate log rotation and archival

### 4.5 PowerShell Scripting
- [ ] Find suspicious process names with `Get-Process`
- [ ] Query events with `Get-WinEvent`
- [ ] Export findings to CSV

### 4.6 SQL Basics
- [ ] `SELECT`, `WHERE`, `GROUP BY`, `HAVING`, `ORDER BY`
- [ ] Aggregate functions — `COUNT()`, `SUM()`
- [ ] Write a query to find IPs with >50 failed logins in 1 hour

### 4.7 Regular Expressions
- [ ] IP address pattern: `\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}`
- [ ] MD5 hash: `[a-fA-F0-9]{32}`
- [ ] SHA256: `[a-fA-F0-9]{64}`
- [ ] URLs: `https?://[^\s]+`
- [ ] Email: `[\w.-]+@[\w.-]+\.\w+`
- [ ] Practiced on [regex101.com](https://regex101.com/)

### 📚 Resources
| Resource | Type |
|----------|------|
| [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) | Free book |
| [TryHackMe Python Basics](https://tryhackme.com/room/pythonbasics) | Lab |
| [SQLBolt](https://sqlbolt.com/) | Interactive SQL |
| [Regex101](https://regex101.com/) | Practice tool |

### ✅ Phase 04 Completion Checklist
- [ ] Write Python scripts to parse log files
- [ ] Use `requests` library to call APIs
- [ ] Comfortable with regex pattern matching
- [ ] Write basic Bash automation scripts
- [ ] Know essential PowerShell investigation commands
- [ ] Understand basic SQL (SELECT, WHERE, GROUP BY)
- [ ] Built at least 2 small security Python tools

---

## 🔒 Phase 05 — Security Fundamentals

> **Timeline:** Weeks 6–10 · **Effort:** 2–3 hrs/day
> Core concepts that appear in every certification, every interview, and every day on the SOC floor.

### 5.1 Core Principles
- [ ] CIA Triad — Confidentiality, Integrity, Availability with real examples
- [ ] Authentication (AuthN) vs Authorization (AuthZ) vs Accounting
- [ ] Non-repudiation — digital signatures
- [ ] Least Privilege — minimum access needed
- [ ] Defense in Depth — multiple security layers
- [ ] Zero Trust — never trust, always verify

### 5.2 Common Attack Types
- [ ] Phishing — detection: email gateway logs, header analysis
- [ ] Brute Force — detection: multiple 4625 events, lockouts
- [ ] Credential Stuffing — detection: many accounts, single source
- [ ] Malware types — virus, trojan, worm, RAT, ransomware
- [ ] SQL Injection — detection: WAF alerts, unusual DB queries
- [ ] Man-in-the-Middle — detection: cert warnings, ARP anomalies
- [ ] Lateral Movement — detection: unusual logon patterns, PsExec
- [ ] Privilege Escalation — detection: 4672, 4728 on unexpected accounts
- [ ] Data Exfiltration — detection: unusual outbound, DNS tunneling
- [ ] Supply Chain Attack — detection: unexpected update behavior

### 5.3 Cyber Kill Chain
- [ ] Reconnaissance
- [ ] Weaponization
- [ ] Delivery
- [ ] Exploitation
- [ ] Installation
- [ ] Command & Control
- [ ] Actions on Objectives

### 5.4 MITRE ATT&CK Framework
- [ ] Understand the 14 tactics
- [ ] Can navigate [attack.mitre.org](https://attack.mitre.org/)
- [ ] Can map an attack to techniques
- [ ] Can identify detection gaps using ATT&CK

### 5.5 Security Frameworks
- [ ] NIST CSF 2.0 — 5 functions: Identify, Protect, Detect, Respond, Recover
- [ ] NIST SP 800-61 — 4 IR phases
- [ ] CIS Controls v8.1 — 18 prioritized controls
- [ ] ISO 27001 — ISMS international standard

### 5.6 Incident Response (NIST SP 800-61)
- [ ] Preparation — IR plans, tools, training
- [ ] Detection & Analysis — triage, true vs false positive
- [ ] Containment — isolate affected systems
- [ ] Eradication — remove threat completely
- [ ] Recovery — restore from clean backups
- [ ] Post-Incident — report, lessons learned, rule updates

### 📚 Resources
| Resource | Type |
|----------|------|
| [TryHackMe SOC Level 1 Path](https://tryhackme.com/path/outline/soclevel1) | Learning path |
| [Professor Messer Security+ SY0-701](https://www.youtube.com/playlist?list=PLG49S3nxzAnl4QDVqK-hOnoqcSKEIDDuv) | 177 free videos |
| [MITRE ATT&CK](https://attack.mitre.org/) | Framework |
| [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) | Framework |

### ✅ Phase 05 Completion Checklist
- [ ] Explain CIA Triad with real-world examples
- [ ] Know common attacks and their detection methods
- [ ] Know the Cyber Kill Chain stages
- [ ] Navigate MITRE ATT&CK and map techniques
- [ ] Understand NIST IR framework phases
- [ ] Know NIST CSF 2.0 five functions
- [ ] Completed TryHackMe SOC Level 1 Path (50%+)

---

## 🔧 Phase 06 — Blue Team Tools

> **Timeline:** Weeks 8–14 · **Effort:** 2–3 hrs/day
> These are the tools you'll use every day in a SOC. SIEM first, then expand.

### 6.1 Splunk
- [ ] Install Splunk Free (500MB/day)
- [ ] Ingest Windows Event Logs
- [ ] Write basic SPL queries
- [ ] Find failed logins: `index=windows EventCode=4625`
- [ ] Detect brute force with time bucketing
- [ ] Hunt for PowerShell execution events
- [ ] Build a SOC monitoring dashboard
- [ ] Complete Splunk BOTS CTF

### 6.2 Microsoft Sentinel / KQL
- [ ] Understand KQL basics
- [ ] Query `SigninLogs` for failed sign-ins
- [ ] Query `DeviceProcessEvents` for suspicious processes
- [ ] Complete KC7 KQL training game

### 6.3 Wazuh
- [ ] Install Wazuh (unlimited, free)
- [ ] Connect Windows and Linux agents
- [ ] Review built-in detection rules
- [ ] Configure custom alert thresholds

### 6.4 Network Detection
- [ ] Wireshark — deep packet analysis, follow TCP streams
- [ ] Suricata — IDS/IPS, write/modify signatures
- [ ] Zeek — network metadata extraction
- [ ] tcpdump — CLI packet capture
- [ ] Analyzed a PCAP from malware-traffic-analysis.net

### 6.5 EDR Concepts
- [ ] Understand EDR vs antivirus
- [ ] Know major players: CrowdStrike, Defender for Endpoint, SentinelOne
- [ ] Understand behavioral vs signature-based detection
- [ ] Know what XDR extends EDR to include

### 6.6 Detection Rules
- [ ] Understand SIGMA rules — vendor-agnostic detection
- [ ] Read and modify an existing SIGMA rule
- [ ] Understand YARA rules — malware pattern matching
- [ ] Write a basic YARA rule

### 6.7 Threat Intelligence Tools
- [ ] [VirusTotal](https://www.virustotal.com/) — file/URL/IP analysis
- [ ] [AbuseIPDB](https://www.abuseipdb.com/) — IP reputation
- [ ] [URLScan.io](https://urlscan.io/) — URL analysis
- [ ] [ANY.RUN](https://any.run/) — interactive malware sandbox
- [ ] [Hybrid Analysis](https://www.hybrid-analysis.com/) — free malware analysis

### 6.8 Forensics Tools
- [ ] Volatility 3 — memory forensics
- [ ] Autopsy — disk forensics
- [ ] FTK Imager — disk imaging
- [ ] Chainsaw — Windows Event Log hunting
- [ ] Run Volatility on a memory dump challenge

### ✅ Phase 06 Completion Checklist
- [ ] Write basic Splunk SPL queries
- [ ] Write basic KQL queries
- [ ] Analyze packet captures with Wireshark
- [ ] Understand IDS/IPS concepts
- [ ] Know EDR and the major players
- [ ] Explain SIGMA and YARA rules
- [ ] Familiar with forensic tools
- [ ] Know common threat intel platforms
- [ ] Installed Splunk Free or Wazuh in a VM

---

## 📜 Phase 07 — Certifications

> **Timeline:** Months 3–6

### 7.1 CompTIA Security+ (SY0-701)
- [ ] Complete Professor Messer's 177 free videos
- [ ] Practice exams — score 85%+ consistently
- [ ] Schedule and pass exam ($425)
- [ ] **Status:** ⬜ Not started

### 7.2 Microsoft SC-200
- [ ] Complete Microsoft Learn SC-200 path (free)
- [ ] Pass the exam ($165)
- [ ] **Status:** ⬜ Not started

### 7.3 BTL1 — Blue Team Level 1
- [ ] Complete Security Blue Team BTJA free pathway
- [ ] Purchase BTL1 training + exam (~$495)
- [ ] Pass the 24-hour hands-on lab exam
- [ ] **Status:** ⬜ Not started

### 7.4 Future Targets
- [ ] CompTIA CySA+
- [ ] HTB CDSA
- [ ] CCD — Certified CyberDefender

---

## 🏋️ Phase 08 — Hands-On Practice

> **Timeline:** Months 4–8 · Ongoing

### TryHackMe
- [ ] Pre-Security Path
- [ ] SOC Level 1 Path (50–80 hours)
- [ ] SOC Level 2 Path

### Blue Team Labs Online
- [ ] BTJA Free Pathway (6–7 hours)
- [ ] 10+ investigations completed

### LetsDefend
- [ ] SOC Analyst Path
- [ ] 20+ alerts triaged

### CyberDefenders
- [ ] 5+ Blue Team CTF challenges
- [ ] Writeups published for each

### Hack The Box
- [ ] 5+ Sherlock labs completed
- [ ] IR reports written for each

### Challenge Log
| Date | Platform | Challenge | Outcome |
|------|----------|-----------|---------|
| — | — | — | — |

---

## 📁 Phase 09 — Build Your Portfolio

> **Timeline:** Months 5–9

### Home Lab
- [ ] Hypervisor set up (Proxmox or VirtualBox)
- [ ] Windows Server 2022 + Active Directory deployed
- [ ] Windows 10/11 VM joined to domain
- [ ] Sysmon installed on all Windows VMs
- [ ] SIEM deployed (Wazuh or Splunk)
- [ ] Security Onion for network monitoring
- [ ] Lab documented with architecture diagram

### Projects
- [ ] SIEM Deployment + Custom Dashboards
- [ ] Adversary Emulation with Atomic Red Team
- [ ] Phishing Analysis Pipeline
- [ ] IR Reports from CTF Challenges
- [ ] APT Threat Intelligence Brief
- [ ] CyderSec — documented as portfolio project

### Publishing
- [ ] GitHub updated with all projects
- [ ] 5+ blog posts / writeups published
- [ ] LinkedIn updated with projects
- [ ] SIGMA or YARA rule contributed to open-source (bonus)

---

## 🚀 Phase 10 — Get Hired

> **Timeline:** Months 8–12

### Resume
- [ ] One-page, ATS-optimized
- [ ] Technical Skills with SIEM, Splunk, MITRE ATT&CK keywords
- [ ] Projects section with home lab and CTF achievements
- [ ] Quantified bullet points

### LinkedIn
- [ ] Headline: `SOC Analyst | SIEM | Incident Response | Threat Detection | Security+`
- [ ] About section with skills, goals, GitHub link
- [ ] Posting CTF writeups and lab builds regularly

### Applications
- [ ] Applying 5–10 positions per week
- [ ] Targeting MSSPs as primary entry point

### Interview Prep
- [ ] CIA Triad explained with examples
- [ ] Phishing investigation walkthrough
- [ ] Brute force detection walkthrough
- [ ] Suspicious process (macro → PowerShell) scenario
- [ ] Lateral movement detection scenario
- [ ] Ransomware response scenario
- [ ] 2–3 incident stories from labs/CTFs ready

---

## 📊 Weekly Activity Log

| Week | Focus | Hours | Highlights |
|------|-------|-------|------------|
| Week 1 | Setup + Phase 01 start | — | — |

---

## 📚 Free Resources

| Resource | Type |
|----------|------|
| [Professor Messer](https://www.youtube.com/@professormesser) | Security+ & Network+ |
| [John Hammond](https://www.youtube.com/@_JohnHammond) | CTFs, DFIR, malware |
| [13Cubed](https://www.youtube.com/@13Cubed) | Windows forensics |
| [The DFIR Report](https://thedfirreport.com/) | Real intrusion analyses |
| [TryHackMe](https://tryhackme.com/) | Structured learning paths |
| [LetsDefend](https://letsdefend.io/) | SOC workflow simulation |
| [CyberDefenders](https://cyberdefenders.org/) | Blue Team CTF |
| [Hack The Box](https://www.hackthebox.com/) | Sherlocks, CDSA track |
| [MITRE ATT&CK](https://attack.mitre.org/) | Framework reference |
| [Regex101](https://regex101.com/) | Regex practice |

---

<div align="center">

```
[ VIVEK A KUMBAR ] [ SOC ANALYST IN TRAINING ] [ BLUE TEAM ]
```

[

![GitHub](https://img.shields.io/badge/GitHub-VivekAKumbar-181717?style=flat-square&logo=github)

](https://github.com/VivekAKumbar)
[

![TryHackMe](https://img.shields.io/badge/TryHackMe-Profile-red?style=flat-square&logo=tryhackme)

](https://tryhackme.com/p/VivekAKumbar)

*Roadmap structure adapted from [keraattin/Blue-Team-Roadmap](https://github.com/keraattin/Blue-Team-Roadmap)*

</div>
