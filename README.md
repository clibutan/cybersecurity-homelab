# cybersecurity-homelab
Hands-on cybersecurity homelab using Proxmox, Kali Linux, Linux Mint, Windows, and Splunk for networking, exploitation testing, and log analysis.

## Overview
This projects highlights and documents my personal cybersecurity homelab which was built with the intention on gaining hands-on experience with virtualization, networking, Linux systems, penetration testing concepts, and security monitoring.

The lab utilizes Proxmox to host multiple virtual machines in an isolated environment where I can safely configure systems, test security tools, troubleshoot networking issues, and analyze system activity.

## Lab Environment
- Proxmox VE
- Kali Linux
- Linux Mint
- Splunk
- Virtual Networking
- Windows/Linux Systems

## Network Setup
The Kali Linux and Linux Mint virtual machines were configured on the same isolated virtual network to allow communication between systems.

Example IP addresses:
- Kali Linux: 10.5.1.206
- Linux Mint: 10.5.1.189

## Security Testing
I used Kali Linux security tools to practice basic penetration testing techniques

Exercise Involved:
- Generating a test payload with msfvenom
- Hosting and transferring the payload within the lab
- Configuring a Metasploit listener
- Establishing a Meterpreter session between the two virtual machines

All security testing was performed against systems that I personally own and control within the isolated lab environment

## Security Monitoring
I had also experimented with Splunk to better understand centralized logging and security monitoring.

This included:
- Collecting system logs
- Reviewing events
- Searching log data
- Identifying activity occurring within the lab environment

## Troubleshooting
While building the lab, I had encountered issues. These would include:

- Virtual machine network activity
- Proxmox firewall configuration
- Linux Permissions
- Payload architecture compatibility
- IP addressing
- Service Configuiration

## Skills Demonstrated
- Linux Administration
- Virtualization
- Network Troubleshooting
- Cybersecurity Fundamentals
- Penetration Testing Concepts
- SIEM/Log Analysis
- Troubleshooting
- Documentation

## Disclaimer
This lab is intended strictly for educational purposes. All security testing was performed in a personal isolated environment against systems that I personally own and authorize for the sole purpose to test with. 
