# HTB Starting Point: Meow
 
**Type:** Machine / Network Connectivity  
**Status:** In Progress ⏳

## Objective
Establish a VPN connection to the HTB network and identify open ports on the target machine to verify connectivity.

## Tools Used
* OpenVPN (HTB connection)
* Ping (ICMP testing)
* Telnet / Nmap (Service enumeration)

## Key Learnings

Discovered open Telnet port (23) using Nmap version scanning (-sV).
Exploited misconfigured Telnet service by logging in with default root account and a blank password to achieve total system compromise.
