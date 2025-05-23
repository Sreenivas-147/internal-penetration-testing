# Internal Penetration Testing Project

## Overview
This project simulates an internal penetration test within a controlled virtual environment. The goal was to identify live hosts, scan ports, enumerate services, and exploit known vulnerabilities to demonstrate real-world internal threat scenarios.

## Tools Used
- Netdiscover
- Nmap
- FTP Client
- Metasploit Framework

## Key Highlights
- Discovered and exploited **ProFTPD 1.3.3c** vulnerability (CVE-2010-4221) to gain **root access**
- Demonstrated internal threat simulation from reconnaissance to post-exploitation
- Provided actionable mitigation steps to harden network services

## Folder Structure
- `report/`: Detailed penetration testing report
- `screenshots/`: Evidence from each step (network scan, Nmap, exploit)
- `tools_used.txt`: List of tools and commands used

## Exploit Summary
Used Metasploit’s `exploit/unix/ftp/proftpd_133c_backdoor` with reverse shell payload to compromise the vulnerable FTP server.

## Recommendation
- Patch ProFTPD immediately
- Disable unused services like FTP
- Harden SSH configurations
- Regular internal assessments

## Author
**Thammisetti Sreenivasulu**  
sreenivasuluthammisetti147@gmail.com
