# Common Network Security Threats

## Report for Oasis Infobyte Security Analyst Internship
**Task 4 – Network Security Threats Report**

---

## 1. Introduction

Network security threats are malicious activities designed to compromise the confidentiality, integrity, and availability of network resources. In today's interconnected world, understanding these threats is crucial for protecting sensitive data and maintaining business operations.

This report covers four major network security threats: DDoS Attacks, Man-in-the-Middle (MITM) Attacks, IP Spoofing, and DNS Poisoning.

---

## 2. DDoS (Distributed Denial of Service) Attacks

### What is a DDoS Attack?

A Distributed Denial of Service (DDoS) attack occurs when multiple compromised systems (often part of a botnet) flood a target server or network with massive amounts of traffic, rendering it unavailable to legitimate users.

### How It Works

1. **Compromise** – Attackers infect devices to create a botnet
2. **Command** – The botnet receives instructions to attack a target
3. **Flood** – All infected devices send overwhelming traffic to the target
4. **Crash** – The target becomes overwhelmed and stops responding

### Real-World Example

The **2016 Dyn DNS Attack** was a massive DDoS attack that took down major websites including Twitter, Netflix, Reddit, and Spotify. The attack used the Mirai botnet, which infected IoT devices like cameras and routers.

### Impact

| Impact | Description |
|--------|-------------|
| **Financial Loss** | Businesses lose revenue when services are down |
| **Reputation Damage** | Customers lose trust in services |
| **Operational Disruption** | Employees cannot access internal systems |
| **Recovery Costs** | Expensive to mitigate and restore services |

### Mitigation Strategies

| # | Strategy | Description |
|---|----------|-------------|
| 1 | **Traffic Filtering** | Use DDoS protection services (Cloudflare, AWS Shield) |
| 2 | **Rate Limiting** | Limit the number of requests a user can make |
| 3 | **Web Application Firewall (WAF)** | Block malicious traffic patterns |

---

## 3. Man-in-the-Middle (MITM) Attacks

### What is a MITM Attack?

A Man-in-the-Middle attack occurs when an attacker intercepts communication between two parties and relays messages without either party knowing the conversation is compromised.

### How It Works

1. **Interception** – The attacker intercepts the communication channel
2. **Eavesdropping** – The attacker listens to or captures the traffic
3. **Relaying** – The attacker may modify messages before passing them on
4. **Impersonation** – The attacker pretends to be both parties

### Real-World Example

**Public Wi-Fi Sniffing** – In 2015, attackers set up fake free Wi-Fi hotspots at airports and cafes. Users connected to these fake networks, and the attackers captured their login credentials for email, banking, and social media.

### Impact

| Impact | Description |
|--------|-------------|
| **Data Theft** | Passwords, credit card numbers, and personal data |
| **Identity Theft** | Stealing personal information to impersonate victims |
| **Financial Fraud** | Unauthorized transactions |
| **Data Manipulation** | Changing messages or transactions |

### Mitigation Strategies

| # | Strategy | Description |
|---|----------|-------------|
| 1 | **Use HTTPS** | Encrypt all website communication |
| 2 | **Avoid Public Wi-Fi** | Use VPN on unsecured networks |
| 3 | **Implement Certificate Pinning** | Prevent forged SSL certificates |

---

## 4. IP Spoofing

### What is IP Spoofing?

IP spoofing is the creation of Internet Protocol (IP) packets with a forged source IP address. The attacker masks the true source of packets to hide their identity.

### How It Works

1. **Forgery** – The attacker creates packets with a false source IP
2. **Send** – Packets are sent to the target
3. **Response** – Responses go to the spoofed (fake) IP address
4. **Exploitation** – Used for DoS attacks and session hijacking

### Real-World Example

**The 2000 Yahoo! Attack** – Attackers used IP spoofing in a massive DDoS attack against Yahoo! The spoofed IP addresses made it difficult to trace the real attackers.

### Impact

| Impact | Description |
|--------|-------------|
| **Network Overload** | Floods networks with fake traffic |
| **Security Bypass** | Bypasses IP-based authentication |
| **Tracing Difficulty** | Makes it hard to find real attackers |

### Mitigation Strategies

| # | Strategy | Description |
|---|----------|-------------|
| 1 | **Ingress Filtering** | Block packets with invalid source IPs |
| 2 | **Egress Filtering** | Prevent internal networks from sending spoofed packets |
| 3 | **TCP SYN Cookies** | Protect against SYN floods |

---

## 5. DNS Poisoning (DNS Spoofing)

### What is DNS Poisoning?

DNS poisoning occurs when an attacker corrupts the Domain Name System (DNS) cache, redirecting users from legitimate websites to malicious ones without their knowledge.

### How It Works

1. **Exploit** – The attacker finds a vulnerability in a DNS server
2. **Inject** – Malicious DNS entries are inserted into the cache
3. **Redirect** – Users trying to visit a legitimate site are sent to a fake site
4. **Harvest** – The fake site steals credentials or installs malware

### Real-World Example

**The Brazil Bank Redirect** – In 2010, attackers used DNS poisoning to redirect Brazilian bank customers to fake banking websites. The fake sites captured login credentials, resulting in millions of dollars in theft.

### Impact

| Impact | Description |
|--------|-------------|
| **Credential Theft** | Users give passwords to fake sites |
| **Malware Installation** | Fake sites can install malicious software |
| **Financial Fraud** | Stolen credentials used for financial theft |
| **Reputation Damage** | Companies lose customer trust |

### Mitigation Strategies

| # | Strategy | Description |
|---|----------|-------------|
| 1 | **DNSSEC** | Digitally sign DNS data to verify authenticity |
| 2 | **Monitor DNS Traffic** | Detect unusual DNS requests |
| 3 | **Secure DNS Servers** | Keep DNS servers updated and patched |

---

## 6. Comparison Table

| Threat | Attack Vector | Primary Target | Difficulty | Mitigation Ease |
|--------|---------------|----------------|------------|-----------------|
| **DDoS** | Network/Server | Websites, ISPs | Medium | Medium |
| **MITM** | Network | Users, Communications | Medium | Easy |
| **IP Spoofing** | Network | Networks, Servers | High | Medium |
| **DNS Poisoning** | DNS Infrastructure | DNS Servers | High | Medium |

---

## 7. Conclusion

### Key Takeaways

| # | Takeaway |
|---|----------|
| 1 | Network security threats are constantly evolving and require proactive defense |
| 2 | A multi-layered security approach is essential for protection |
| 3 | Regular monitoring and timely patching are critical for maintaining security |

### For Network Administrators

- Implement **defense in depth** – multiple layers of security
- Regularly **train employees** about security threats
- Establish an **incident response plan**
- Keep systems **updated and patched**
- Use **strong authentication** for all network access

---

## 8. References

| # | Source | Link |
|---|--------|------|
| 1 | **NIST** | https://www.nist.gov/ |
| 2 | **CISA** | https://www.cisa.gov/ |
| 3 | **MITRE ATT&CK** | https://attack.mitre.org/ |
| 4 | **SANS Institute** | https://www.sans.org/ |
| 5 | **Krebs on Security** | https://krebsonsecurity.com/ |

---

**Report End**
