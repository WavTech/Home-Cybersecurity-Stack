# Building a Comprehensive Home Cybersecurity Stack

## Why I Built This Stack
I designed my home cybersecurity stack to create a secure, private, and efficient digital environment. My goal was to protect against **malware, phishing, unauthorized tracking, and data loss**, while ensuring **end-to-end encryption** for sensitive information.

This stack integrates **endpoint protection, privacy tools, network security, and secure web browsing** to minimize attack surfaces and enhance data protection.

---

## Components of My Cybersecurity Stack

### Endpoint Protection
1. **Malwarebytes Premium**: Real-time malware, ransomware, and phishing protection. Complements Windows Defender without causing conflicts.
2. **Windows Defender**: Baseline antivirus and firewall providing a solid security foundation.

### Privacy & Data Encryption
1. **ProtonVPN (with Cloudflare DNS)**: Encrypts internet traffic while ensuring fast and privacy-focused DNS resolution.
2. **ProtonMail**: End-to-end encrypted email for secure communications.
3. **ProtonDrive**: Secure cloud backup with encryption for storing sensitive files.

### Network Monitoring & Traffic Control
1. **GlassWire**: Monitors network activity, detects suspicious behavior, and provides real-time alerts for unknown devices.

### Secure Web Browsing
In Chrome, I use the following security extensions:
- **LastPass**: Secure password manager for generating and storing unique credentials.
- **uBlock Origin**: Blocks ads, trackers, and malicious scripts.
- **HTTPS Everywhere**: Enforces encrypted connections on supported websites.
- **Privacy Badger**: Blocks trackers based on behavioral detection.
- **Location Hider**: Conceals IP-based location for added privacy.

---

## My Setup & Workflow

### Step 1: System & Software Configuration
- Enabled and configured Windows Defender as a baseline security measure.
- Installed Malwarebytes Premium for **advanced malware and phishing protection**.
- Set up ProtonVPN on all devices and configured it with **Cloudflare DNS**.

### Step 2: Securing My Network
- **Enabled WPA3 encryption** on my router.
- Updated router firmware to the latest version.
- Configured **Cloudflare DNS** to improve security for non-VPN traffic.
- Used **GlassWire** to monitor unknown devices and network anomalies.

### Step 3: Privacy Implementation
- Migrated sensitive files to **ProtonDrive** for encrypted backups.
- Installed **privacy extensions** (LastPass, uBlock Origin, HTTPS Everywhere, Privacy Badger).
- Configured all browser extensions for **optimal protection** without conflicts.

### Step 4: Security Testing & Optimization
- Tested VPN for **DNS/IP leaks** to ensure full privacy.
- Verified tracker blocking effectiveness using **EFF’s Cover Your Tracks**.
- Conducted penetration tests using **ShieldsUP! and Nmap**.

### Step 5: Ongoing Maintenance & Updates
- **Weekly**: Software updates, review GlassWire network activity.
- **Monthly**: Audit stored passwords in LastPass, check ProtonDrive backups, re-test VPN leaks.

---

## Results & Benefits
- **Enhanced Privacy**: Encrypted browsing and communications with **ProtonVPN, ProtonMail, and security extensions**.
- **Improved Security**: Real-time **malware protection and network monitoring** reduce threats.
- **Data Safety**: Sensitive files are securely backed up to **ProtonDrive**.
- **Efficiency**: The entire stack runs **without slowing down system performance**.

---

## Future Plans
- **Implement IoT monitoring** to detect vulnerabilities in smart home devices.
- **Set up Pi-hole** for network-wide ad and tracker blocking.
- **Explore additional encryption layers**, such as **YubiKey and hardware-based authentication**.

---

## Project Repository Structure
```
Home-Cybersecurity-Stack/
│── README.md
│── vpn-config/
│── router-hardening.md
│── security-tools.md
│── browser-security.md
```

---

## Connect With Me
**LinkedIn:** [linkedin.com/in/cameron-v-624773317/](https://www.linkedin.com/in/cameron-v-624773317/)  
**GitHub Portfolio:** [github.com/WavTech](https://github.com/WavTech)

---

This cybersecurity stack is an ongoing project. Suggestions, contributions, and feedback are welcome.
