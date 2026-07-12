# Task 1: Basic Network Scanning with Nmap

## Project Overview is project demonstrates basic network scanning using Nmap on a local machine as part of the Oasis Infobyte Security Analyst internship.

## Tools Used
- *Nmap* – Network Mapper for port scanning and service detection
- *Kali Linux* – Operating system with pre-installed security tools

## Why Network Scanning Matters
- Identifies open ports and running services
- Detects potential security vulnerabilities
- Helps understand your attack surface
- Essential for network security audits

## Ethical Guidelines
- Only scan systems you own or have explicit permission to scan
- Unauthorized scanning is illegal in most jurisdictions
- This scan was performed ONLY on localhost (127.0.0.1)

## Scan Commands Used

### Basic Port Scan
```
nmap localhost```

## Service Version Detection:
- nmap -sV localhost
## OS Detection:
- nmap -O localhost

## Scan Results
- Open Ports Found:
```
Port	Service	Version
22/tcp	SSH	OpenSSH 7.9p1
80/tcp	HTTP	Apache 2.4.59
3306/tcp	MySQL	MariaDB 10.11.7
````
# OS Detection:
- Linux (detected via TCP/IP fingerprinting)

# Security Analysis
- See **nmap_scan_analysis.txt** for detailed port-by-port security analysis.

# Screenshots
```https://Screenshot_2026-07-12_10_45_13.png```

# Learning Outcomes
- Understanding of Nmap and its capabilities
- Knowledge of common open ports and their services
- Awareness of network security fundamentals
- Importance of ethical scanning practices

# References
- Nmap Official Documentation
- OWASP Network Security Testing Guide
- NIST Guide to Network Scanning
