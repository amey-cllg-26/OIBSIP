# Task 2: Basic Firewall Configuration with UFW

## Project Overview
This project demonstrates basic firewall configuration using UFW (Uncomplicated Firewall) on Kali Linux as part of the Oasis Infobyte Security Analyst internship.

## Tools Used
- **UFW** – Uncomplicated Firewall for managing firewall rules
- **Kali Linux** – Operating system with pre-installed security tools

## What is a Firewall?
A firewall is a network security system that monitors and controls incoming/outgoing traffic based on predetermined rules.

## Firewall Rules Configured

### Allowed Rules:
| Service | Port | 	Reason 		|
|---------|------|----------------------|
| SSH	  | 22 	 | Secure remote access |
| HTTP 	  | 80   | Web traffic 		|
| HTTPS   | 443  | Secure web traffic 	|
|---------------------------------------|

### Denied Rules:
| Service | Port | 	Reason 		 |
|---------|------|-----------------------|
| FTP 	  | 21 	 | Insecure protocol 	 |
| Telnet  | 23 	 | Unencrypted, insecure |
|----------------------------------------|
## Commands Used

# Check status
ufw status

# Enable firewall
ufw enable

# Allow services
ufw allow ssh
ufw allow http
ufw allow https

# Deny services
ufw deny 21
ufw deny 23

# Check rules
ufw status numbered
ufw status verbose

## Screenshots
https://ufw_screenshot.png

## Learning Outcomes
- Understanding of firewall fundamentals
- Practical experience configuring UFW
- Knowledge of which ports are safe/unsafe
- Importance of firewall in network security

## References
- UFW Official Documentation
