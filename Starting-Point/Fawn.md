# HTB Starting Point: Fawn

**Type:** Machine / Network Enumeration  
**Status:** Completed ✅

## Objective
Enumerate the target to identify open ports, specifically looking for misconfigured FTP (File Transfer Protocol) services, and successfully connect to retrieve the flag.

## Tools Used
* Ping (ICMP testing)
* Nmap (Service and version enumeration)
* FTP Client (File transfer and exploitation)

## Key Learnings
* Enumerated open port 21 using Nmap version scanning (`-sV`).
* Discovered and exploited an Anonymous FTP misconfiguration, allowing login without valid credentials.
* Successfully navigated the remote file system and exfiltrated the target data using command-line FTP commands (`ls`, `get`).
