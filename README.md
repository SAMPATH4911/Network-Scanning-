🌐 Network Scanning
Network scanning is a crucial phase in ethical hacking and cybersecurity assessments. It involves identifying live hosts, open ports, running services, and potential vulnerabilities within a network. The goal is to discover entry points and map the network layout for further security analysis.

🔍 Objectives of Network Scanning
Identify active devices (hosts) on the network

Detect open and filtered ports

Discover services running on those ports

Determine versions of software and services

Detect vulnerabilities and misconfigurations

Assess firewall and intrusion detection system behavior

🧪 Common Network Scanning Techniques
Technique	Description
Ping Scan (-sn)	Checks if hosts are alive
Port Scan (-sS, -sT)	Identifies open TCP ports
UDP Scan (-sU)	Scans for open UDP ports
Service Detection (-sV)	Determines services on open ports
OS Fingerprinting (-O)	Detects operating system of the target
Vulnerability Scan (--script vuln)	Uses scripts to find known vulnerabilities

🛡️ Stealth and Bypass Techniques
ACK Scan (-sA): Checks firewall rules

FIN/NULL/XMAS Scans (-sF, -sN, -sX): Stealthy scans to bypass filters

Fragmented Packets (-f): Evades packet inspection

Decoy Scans (-D): Obscures the true source of the scan

🧰 Tools Used
Nmap – primary tool for scanning

Zenmap – GUI for Nmap

Netdiscover – passive discovery on LAN

Wireshark – packet capture and analysis
