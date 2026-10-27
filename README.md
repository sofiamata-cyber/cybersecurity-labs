# cybersecurity-labs
Hands-on cybersecurity labs, Linux networking, virtualization and ethical hacking practice.

# Week 1 — Kali Linux Lab Setup

**Program:** Cybersecurity & Ethical Hacking Internship  
**Academy:** NETWORKWALKS  
**Instructor:** Waqas Karim (CCIE)

## Project Overview

This project documents the setup and configuration of a Kali Linux virtual machine using Oracle VirtualBox.

## Objectives

- Install and configure Kali Linux.
- Configure NAT networking and IPv4 addressing.
- Troubleshoot network connectivity.
- Verify internet connectivity and DNS resolution.
- Configure shared clipboard and bidirectional drag-and-drop.
- Create a virtual machine snapshot.

## Commands Used

```bash
ip -4 addr show eth0
ping -c 4 8.8.8.8
ping -c 4 google.com
```

## Results

- Successful ICMP connectivity to 8.8.8.8.
- Successful DNS resolution and connectivity to google.com.
- 0% packet loss during both ping tests.
- Successful file transfer between Windows and Kali Linux.

## Skills Practiced

Linux Administration | Virtualization | IPv4 Networking | Network Troubleshooting | DNS | ICMP

## Network Connectivity Evidence

![Kali Linux connectivity tests](network-connectivity.png)
