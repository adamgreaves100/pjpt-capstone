# PJPT Capstone

Penetration testing writeups completed as part of the mid-course Capstone for the 
**[Practical Junior Penetration Tester (PJPT)](https://certifications.tcm-sec.com/pjpt/)** 
certification by TCM Security.

Each writeup documents my methodology and the course instructor's methodology if I was either unable to compromise the machine or if their solution differed drastically from my own. I have also listed the tools used and findings for each target machine.

---

## Boxes

| Machine | Status | Writeup |
|---------|--------|---------|
| Blue | ✅ Complete | [View Writeup](01-Blue/README.md) |
| Academy | ✅ Complete | [View Writeup](02-Academy/README.md) |
| Dev | ✅ Complete | [View Writeup](03-Dev/README.md) |
| Butler | ✅ Complete | [View Writeup](04-Butler/README.md) |
| Blackpearl | ✅ Complete | [View Writeup](05-Blackpearl/README.md) |

---

## Tools Used
- **Kali Linux** — primary attack platform
- **Nmap** — port scanning and enumeration
- **Metasploit** — exploitation framework
- **SMBclient** — SMB enumeration
- **Nikto** — web server vulnerability scanning
- **Dirbuster / dirb / ffuf** — web directory enumeration
- **Hashcat** — password hash cracking
- **Netcat** — listener for reverse shell connections
- **LinPEAS** — Linux privilege escalation enumeration
- **pspy** — process monitoring without root privileges
- **Python HTTP Server** — file transfer via temporary web server
- **John the Ripper / fcrackzip** — password cracking
- **NFS tools** (showmount, mount) — share enumeration and access
- **GTFOBins** — privilege escalation techniques
- **SSH** — remote access to target system
- **Burp Suite** — HTTP interception and credential brute forcing (Intruder)
- **Jenkins Script Console** — Groovy code execution for initial access
- **WinPEAS** — Windows privilege escalation enumeration
- **PrintSpoofer** — token impersonation privilege escalation
- **msfvenom** — reverse shell payload generation
- **certutil** — file download on Windows targets
- **dnsrecon** — DNS enumeration and reverse lookup
- **Python TTY spawn** — interactive shell upgrade

---

## Disclaimer
These writeups are completed in a controlled lab environment as part of formal 
certification training. They are not intended as guides for unauthorised access 
to any system.