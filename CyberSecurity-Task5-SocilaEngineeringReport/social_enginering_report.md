# Social Engineering Attacks

## Report for Oasis Infobyte Security Analyst Internship
**Task 5 – Social Engineering Attacks Report**

---

## 1. Introduction

Social engineering is the psychological manipulation of people into performing actions or divulging confidential information. Unlike technical hacking, social engineering exploits human psychology rather than system vulnerabilities.

**Why Social Engineering is Effective:**
- Humans are the weakest link in security
- People naturally want to be helpful
- Emotions like fear and urgency can override logic
- Many people are unaware of such threats

**Statistics:**
- 98% of cyberattacks involve some form of social engineering
- Over 90% of data breaches start with a phishing email
- Social engineering attacks cost businesses billions of dollars annually

---

## 2. Phishing

### What is Phishing?

Phishing is a type of social engineering attack where attackers send fraudulent communications (usually emails) that appear to come from a legitimate source. The goal is to steal sensitive data like credit card numbers, login credentials, or to install malware.

### Types of Phishing

| Type | Description | Example |
|------|-------------|---------|
| **Spear Phishing** | Targeted attacks on specific individuals | CEO gets fake email from "board member" |
| **Whaling** | Attacks targeting senior executives | "FBI" email demanding financial info from CEO |
| **Vishing** | Voice phishing via phone calls | Caller pretending to be from "bank security" |
| **Smishing** | SMS phishing via text messages | Text with fake "shipping confirmation" link |

### How It Works

1. **Research** – Attackers gather information about the target
2. **Create** – A convincing fake message is crafted
3. **Send** – The message is sent via email, SMS, or call
4. **Harvest** – Victims are tricked into providing credentials
5. **Exploit** – Stolen information is used for fraud

### Real-World Case Study

**2011 RSA SecurID Attack** – Attackers sent a spear-phishing email with an Excel attachment to four employees at RSA Security. Two employees opened the attachment, which exploited a Flash vulnerability and installed malware. This allowed attackers to steal information about RSA's SecurID two-factor authentication tokens, which were used to protect many government and military systems.

### Prevention Recommendations

| # | Recommendation | Description |
|---|----------------|-------------|
| 1 | **Security Awareness Training** | Teach employees to identify phishing |
| 2 | **Multi-Factor Authentication** | Even if passwords are stolen, accounts remain secure |
| 3 | **Email Filtering** | Block suspicious emails before they reach users |
| 4 | **Verify Requests** | Confirm sensitive requests via a different channel |

---

## 3. Pretexting

### What is Pretexting?

Pretexting is creating a fabricated scenario (the "pretext") to manipulate a victim into providing information. The attacker establishes trust by impersonating someone the victim would normally trust.

### How an Attacker Builds a False Scenario

1. **Research** – Gather information about the target and organization
2. **Impersonation** – Pretend to be someone legitimate (IT support, bank, police)
3. **Create Urgency** – Make the victim feel they must act immediately
4. **Extract Information** – Ask for sensitive information under the guise of "helping"

### Real-World Case Study

**The Hacker Who Helped the FBI** – In 2002, a hacker named Adrian Lamo gained access to The New York Times' internal network using pretexting. He called the IT helpdesk pretending to be a journalist who had forgotten his password. By acting confused and in need of help, the helpdesk reset the password for him, giving him full access.

### Prevention Measures

| # | Measure | Description |
|---|---------|-------------|
| 1 | **Verify Identity** | Always verify the identity of the person requesting information |
| 2 | **Limit Information** | Never disclose sensitive information over the phone |
| 3 | **Use Callbacks** | Hang up and call the organization back on a known number |

---

## 4. Baiting

### What is Baiting?

Baiting is a social engineering attack that uses the promise of something desirable (like a free movie download, a good deal, or an infected USB drive) to manipulate a victim into taking a specific action.

### Types of Baiting

| Type | Description | Example |
|------|-------------|---------|
| **Physical Baiting** | Using physical devices | Infected USB drives dropped in a parking lot |
| **Digital Baiting** | Online temptations | "Free antivirus" fake download links |

### Real-World Case Study

**The USB Key Drop** – In 2011, security researchers conducted a test by dropping 200 USB drives in a parking lot. Out of 200 drives, 68 were picked up and inserted into computers. Of those, 56% of users clicked on files on the drives. In real attacks, these USB drives can install backdoors that give attackers full access to corporate networks.

### Prevention Measures

| # | Measure | Description |
|---|---------|-------------|
| 1 | **Security Policy** | Ban the use of untrusted USB drives in the organization |
| 2 | **Disable USB Ports** | Physically block USB ports or restrict them to approved devices |
| 3 | **Employee Education** | Warn employees about the risks of using unknown devices |

---

## 5. Quid Pro Quo

### What is Quid Pro Quo?

"Quid pro quo" means "something for something." In social engineering, the attacker offers a service or benefit in exchange for information.

### How It Works

1. **Approach** – The attacker contacts the victim offering something of value
2. **Build Trust** – The attacker acts helpful and legitimate
3. **Exchange** – The victim provides information in exchange for the "service"
4. **Exploit** – The information is used for malicious purposes

### Prevention

| # | Prevention | Description |
|---|------------|-------------|
| 1 | **Be Suspicious** | Be wary of unsolicited offers or requests for information |
| 2 | **Verify** | Always verify the identity of anyone requesting sensitive information |
| 3 | **Report** | Report suspicious attempts to the security team |

---

## 6. Comparison Table

| Attack Type | Primary Target | Psychological Lever | Best Countermeasure |
|-------------|----------------|---------------------|---------------------|
| **Phishing** | General public, Employees | Fear, Urgency | Security awareness training |
| **Pretexting** | Employees, IT staff | Trust, Authority | Identity verification, Callbacks |
| **Baiting** | Everyone | Greed, Curiosity | Security policies, USB restrictions |
| **Quid Pro Quo** | IT staff | Professionalism | Verify all requests |

---

## 7. Organizational Recommendations

### 5-Point Employee Security Awareness Training Checklist

| # | Point | Description |
|---|-------|-------------|
| 1 | **Identify Phishing** | Train employees to spot suspicious emails, links, and attachments |
| 2 | **Report Immediately** | Establish a clear process for reporting suspected attacks |
| 3 | **Verify Requests** | Always confirm sensitive requests through a known channel |
| 4 | **Use Trusted Channels** | Never share sensitive info unless you initiated the contact |
| 5 | **Think Before Clicking** | Always think before clicking links or opening attachments |

---

## 8. Conclusion

Social engineering is one of the most effective and dangerous attack vectors because it targets human psychology rather than technology. The best defense is awareness, education, and a security culture that encourages vigilance.

**Key Takeaways:**
- Social engineering attacks are increasing
- Human factors remain the weakest link in security
- Training and awareness are the most effective defenses
- Organizations must implement a multi-layered security approach

---

## 9. References

| # | Source | Link |
|---|--------|------|
| 1 | **CISA** | https://www.cisa.gov/ |
| 2 | **SANS Institute** | https://www.sans.org/ |
| 3 | **Dark Reading** | https://www.darkreading.com/ |
| 4 | **Krebs on Security** | https://krebsonsecurity.com/ |

---

**Report End**
