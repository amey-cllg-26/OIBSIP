# Common Network Security Threats
## Report for Oasis Infobyte Security Analyst Internship (Task 4)

### 1. Introduction

Network security threats are malicious activities designed to compromise the confidentiality, integrity, and availability of network resources. In today's interconnected world, understanding these threats is crucial for protecting sensitive data and maintaining business operations.

This report covers four major network security threats: DDoS Attacks, Man-in-the-Middle (MITM) Attacks, IP Spoofing, and DNS Poisoning.

### 2. DDoS (Distributed Denial of Service) Attacks

**What is a DDoS Attack?**
A Distributed Denial of Service (DDoS) attack occurs when multiple compromised systems (often part of a botnet) flood a target server or network with massive amounts of traffic, rendering it unavailable to legitimate users.

**How It Works:**
1.  **Compromise** – Attackers infect devices to create a botnet.
2.  **Command** – The botnet receives instructions to attack a target.
3.  **Flood** – All infected devices send overwhelming traffic to the target.
4.  **Crash** – The target becomes overwhelmed and stops responding.

**Real-World Example:**
The **2016 Dyn DNS Attack** was a massive DDoS attack that took down major websites including Twitter, Netflix, Reddit, and Spotify using the Mirai botnet.

**Mitigation Strategies:**
1.  Use DDoS protection services (e.g., Cloudflare, AWS Shield).
2.  Implement rate limiting to control user requests.
3.  Deploy a Web Application Firewall (WAF).

### 3. Man-in-the-Middle (MITM) Attacks

**What is a MITM Attack?**
A Man-in-the-Middle attack occurs when an attacker intercepts communication between two parties, eavesdrops, or relays messages without either party knowing the conversation is compromised.

**Real-World Example:**
Attackers set up fake free Wi-Fi hotspots at airports to capture login credentials, a practice known as "Public Wi-Fi Sniffing."

**Mitigation Strategies:**
1.  Always use HTTPS and verify website certificates.
2.  Avoid using public Wi-Fi without a VPN.
3.  Implement certificate pinning to prevent forged SSL certificates.

### 4. IP Spoofing

**What is IP Spoofing?**
IP spoofing is the creation of Internet Protocol (IP) packets with a forged source IP address to mask the true source of the packets.

**Mitigation Strategies:**
1.  Implement ingress filtering to block invalid source IPs.
2.  Use egress filtering to prevent internal spoofed packets from leaving the network.
3.  Utilize TCP SYN cookies to protect against SYN floods.

### 5. DNS Poisoning (DNS Spoofing)

**What is DNS Poisoning?**
DNS poisoning occurs when an attacker corrupts a DNS server's cache, redirecting users from legitimate websites to malicious ones without their knowledge.

**Mitigation Strategies:**
1.  Deploy DNSSEC to verify DNS data authenticity.
2.  Monitor DNS traffic for unusual patterns.
3.  Keep DNS servers updated and patched against known vulnerabilities.

### 6. Conclusion

Network security threats are constantly evolving and require a proactive, multi-layered defense strategy. Regular monitoring, timely patching, and employee training are essential for maintaining a robust security posture.

### 7. References

- NIST: https://www.nist.gov/
- CISA: https://www.cisa.gov/
- MITRE ATT&CK: https://attack.mitre.org/
- Krebs on Security: https://krebsonsecurity.com/
