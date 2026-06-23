# Abdulla Bagishev

**Systems & Security Engineer** | Specializing in Windows Internals, Low-Level Programming, and Infrastructure Defense.

Focused on systems security, low-level engineering, and infrastructure defense. My technical portfolio centers on operating system subsystems, automation, and threat detection. By combining a practical foundation in C programming, systems architecture, and security operations, I target engineering roles that demand a deep, bottom-up understanding of the stack. Driven by continuous, self-directed research to stay ahead of the ever evolving tech world and security trends.

## Technology Stack

### Systems & Low-Level Development
<div>
    <img src="https://img.shields.io/badge/-C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
    <img src="https://img.shields.io/badge/-Bash_&_PowerShell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
    <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</div>

### Security Operations & Infrastructure Defense
<div>
    <img src="https://img.shields.io/badge/-Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-ELK_Stack-005571?style=for-the-badge&logo=elastic-stack&logoColor=white" />
    <img src="https://img.shields.io/badge/-pfSense-000000?style=for-the-badge&logo=pfsense&logoColor=white" />
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
</div>

### Cloud, Virtualization & Automation
<div>
    <img src="https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
    <img src="https://img.shields.io/badge/-VMware-607078?style=for-the-badge&logo=vmware&logoColor=white" />
    <img src="https://img.shields.io/badge/-Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
    <img src="https://img.shields.io/badge/-Linux_(RHEL/Debian)-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</div>

---

## Project Directory

### Systems Programming & OS Internals
* **[SysMonitor-Core](LINK)** *(In Development)*
  A modular systems programming project designed to audit process integrity levels and interact with Windows security tokens utilizing the Win32 API and `SeDebugPrivilege`.
* **[WindowsCommandShell]((https://github.com/Abdullah-ElPsyKo/WindowsCommandShell))**
  A low-level C implementation demonstrating custom I/O redirection (`>` and `<`) via the native Windows API. Implements explicit kernel handle inheritance (`SECURITY_ATTRIBUTES`) and process manipulation by overriding `STARTUPINFO` standard streams before spawning child processes via `CreateProcessW`.

### Security Engineering & Log Analysis
* **[linux-attack-detection-splunk](https://github.com/Abdullah-ElPsyKo/linux-attack-detection-splunk)**
  An end-to-end telemetry engineering lab deploying Splunk Enterprise to capture and parse enriched endpoint logs. Implements custom `auditd` kernel rules via `rsyslog` to track process executions (`execve`), persistence vectors, and SUID abuse, mapped directly to the MITRE ATT&CK framework with custom SPL dashboards.
* **[rocky-linux-9-hardening](https://github.com/Abdullah-ElPsyKo/rocky-linux-9-hardening)**
  Automated security hardening modules and security policy enforcement scripts written in Bash, targeting high-severity findings on Rocky Linux 9 systems.

### Offensive & Defensive Security Operations
* **[Modular-C2-Framework](https://github.com/Abdullah-ElPsyKo/Modular-C2-Framework)**
  A modular post-exploitation framework in Python utilizing a dynamic JSON configuration architecture. Features remote runtime module loading via threading, leveraging the GitHub API as a transport layer for configuration management and data exfiltration. Includes modules for network enumeration (TTL-based OS detection), port scanning, and reverse-shell backdoor functionality.
* **[ansible-cowrie-honeypot](https://github.com/Abdullah-ElPsyKo/ansible-cowrie-honeypot)**
  Automated deployment of an SSH/Telnet honeypot for low-interaction threat intelligence gathering.

### Enterprise Infrastructure & Automation
* **[OpenSCAP-Ansible_rl9](https://github.com/Abdullah-ElPsyKo/OpenSCAP-Ansible_rl9)**
  An Infrastructure as Code (IaC) configuration pipeline automating OpenSCAP compliance scanning against CIS Level 1 benchmarks on Rocky Linux 9. Features distributed execution via Semaphore UI, automated scheduling, and an authenticated Flask-based HTTPS reporting engine.
* **[pfSense Security Gateway](https://github.com/Abdullah-ElPsyKo/Securing_Networks_pfSense/tree/main)**
  Design and deployment of a multi-zone network architecture (WAN, LAN, DMZ) isolated via multi-vNIC hypervisor allocation. Enforces strict inter-zone firewall policies, edge GeoIP filtering via pfBlockerNG, and deep packet inspection using Suricata in inline IPS mode accelerated by Netmap kernel tuning.
## Education
* **Professional Bachelor in ICT: Cybersecurity & Cloud** – Artesis Plantijn University College
* **CS50x: Introduction to Computer Science** – Harvard University (edX)
