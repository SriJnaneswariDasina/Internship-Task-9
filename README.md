# Internship-Task-9

# Task 9 – Network Vulnerability Scanning

## Objective
To perform network vulnerability scanning using Nmap on a Linux system and understand open ports, services, OS detection, and potential risks.

## Tools Used
- Linux (Kali/Ubuntu)
- Nmap

## Steps Performed
1. Installed Nmap on Linux
2. Identified local network range
3. Discovered active hosts
4. Scanned open ports
5. Performed service enumeration
6. Detected operating system
7. Ran vulnerability detection scripts
8. Saved scan results

## Commands Used

nmap -sn 192.168.1.0/24
nmap 192.168.1.10
nmap -sV 192.168.1.10
sudo nmap -O 192.168.1.10
nmap --script vuln 192.168.1.10
nmap -sV -O --script vuln 192.168.1.10 -oN scan_report.txt

## Output

Scan results are saved in scan_report.txt.

## Key Learnings

Understanding open vs closed ports

Importance of service enumeration

Role of vulnerability scanning in cybersecurity

## Conclusion

This task improved my network reconnaissance skills and provided real-world exposure to vulnerability scanning techniques.





