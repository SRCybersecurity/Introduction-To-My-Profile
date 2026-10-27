# Hi, I'm Rathwa Sejal 👋

### Aspiring Cybersecurity Professional | SOC Analyst | Security Engineer

I'm building practical cybersecurity skills through hands-on labs, security investigations, automation, and documented projects.

My goal is to understand how security threats occur, how to detect and investigate them, and how to strengthen systems using industry-standard security practices.

---

## 🛡️ Core Skills

- **Security Operations:** SIEM, alert triage, log analysis, threat detection, incident investigation, phishing analysis, and incident response fundamentals.
- **Security Tools:** Splunk, Wireshark, Nmap, Nessus, OpenVAS, Burp Suite, OWASP ZAP, VirusTotal, and MXToolbox.
- **Operating Systems:** Linux (Ubuntu, Kali Linux), Windows administration, file permissions, firewall configuration, and Linux security hardening.
- **Networking:** TCP/IP, OSI model, DNS, DHCP, HTTP/HTTPS, SSH, VPNs, packet capture, and network traffic analysis.
- **Threat Intelligence:** Indicators of Compromise (IOCs), security event investigation, basic malware analysis, and threat intelligence fundamentals.
- **Scripting & Version Control:** Bash, Python, Git, and GitHub.
- **Frameworks & Standards:** MITRE ATT&CK, OWASP Top 10, CIS Benchmarks, CVE/NVD, and Zero Trust fundamentals.

---

## 🔬 Featured Projects

### 1. Linux Hardening & Compliance Toolkit

A security assessment project designed to identify Linux system misconfigurations and support security hardening.

**Key Features**
- Audit system configurations and file permissions.
- Review SSH settings and firewall configurations.
- Identify potential security weaknesses.
- Assess configurations against relevant CIS Benchmark recommendations.
- Generate reports with findings and remediation guidance.

**Technologies:** Bash, Python, Linux, CIS Benchmarks

**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/Python-Automation-Tools/blob/Linux_Auditing_Tool/Linux%20Hardening%20%26%20Compliance%20Toolkit.md)

### 2. Phishing Email Investigation Lab

A documented investigation of a sanitized training email, focusing on suspicious indicators, sender authentication, and recommended security actions.

**Key Activities**
- Examine email headers and sender authentication results.
- Identify suspicious URLs, sender details, and other indicators.
- Analyze evidence and document investigation findings.
- Recommend mitigation and remediation steps.

**Skills:** Email Security, Threat Analysis, IOC Identification, Incident Reporting

**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/Analysing-Phishing-Emails)

### 3. Network Traffic Analysis with WireShark
A hands-on network traffic analysis project focused on capturing live network packets, identifying communication protocols, and inspecting data exchanged between devices using **Wireshark**. This project demonstrates practical skills in packet analysis, protocol identification, and network troubleshooting.

**Key Activities**
- Captured and analyzed live network traffic using Wireshark.
- Identified and examined protocols such as DNS, TCP, HTTP, TLS, and ICMP.
- Inspected packet details, including source and destination IP addresses, port numbers, protocols, and timestamps.
- Analyzed communication between devices to understand network behavior.
- Documented findings using packet capture evidence and screenshots.

 **Skills:** Network Traffic Analysis, Wireshark, Protocol Analysis, Packet Inspection, Network Troubleshooting, TCP/IP Networking

**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/Network-Traffic-Analysis-with-Wireshark)

### 4. Vulnerability Scanning
A hands-on security assessment project focused on identifying web application vulnerabilities, evaluating SSL/TLS configurations, reviewing HTTP security headers, and analyzing exposed network services using free security assessment tools.

**Key Activities**
- Perform an active web application scan using OWASP ZAP to identify potential vulnerabilities and assess associated risks.
- Analyze SSL/TLS configurations using SSL Server Test to evaluate certificate validity and server security settings.
- Scan the target domain using SecurityHeaders.com to identify missing or misconfigured HTTP security headers.
- Use Nmap to discover open ports and identify services running on the target system.
- Evaluate the security implications of exposed services and recommend reducing the attack surface by closing unnecessary ports and securing required services.
- Review security header assessment results, including the capped A grade, and identify improvements needed to achieve an A+ rating.
- Recommend remediation measures for missing Content-Security-Policy (CSP), X-Frame-Options, and X-Content-Type-Options headers.
- Document recommended security improvements, including HTTPS enforcement, HSTS configuration, and CSP policy review.
- Compare tool-generated findings with a manually prepared assessment report and document the results.

**Skills:** Vulnerability Assessment, Security Remediation, Web Application Security, SSL/TLS Analysis, HTTP Security Headers, Network Scanning, Attack Surface Analysis, Risk Assessment, Security Reporting

**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/Vulnerability_Scan)

### 5. Local Network Port Scanning and Exposure Analysis
A hands-on network security project focused on discovering devices on a local network, identifying open ports and running services, and analyzing potential security risks using Nmap and Wireshark.

**Key Activities**
- Install and verify Nmap on Kali Linux using package management commands.
- Identify the local IP address and determine the network range to scan.
- Perform TCP SYN scans using `nmap -sS` to identify open ports on authorized local network devices.
- Discover active hosts using `nmap -sn` and scan hosts while skipping host discovery with `nmap -Pn`.
- Record discovered IP addresses, open ports, and associated network services.
- Capture and analyze network packets using Wireshark with filters such as `tcp`, `udp`, `dns`, `http`, `ssh`, and `tcp.port == 80`.
- Research common ports and services, including FTP (21), SSH (22), Telnet (23), DNS (53), HTTP (80), HTTPS (443), and NTP (123).
- Evaluate potential security risks associated with unnecessary, misconfigured, or vulnerable services.
- Recommend security improvements, including closing unused ports and restricting access to sensitive services.

**Skills:** Network Reconnaissance, Port Scanning, Host Discovery, Network Traffic Analysis, Service Enumeration, Network Security, Risk Assessment, Security Hardening
**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/Network-Scanning)

### 6. Firewall Configuration and Traffic Filtering
A hands-on firewall configuration lab focused on creating, testing, and managing firewall rules in Linux and Windows to control network traffic and prevent unauthorized access.

**Key Activities**
- Configure and enable UFW (Uncomplicated Firewall) on Linux.
- Inspect existing firewall rules and block inbound traffic on TCP port 23 (Telnet).
- Test firewall rules using Telnet and Netcat (`nc`).
- Configure Windows Defender Firewall to block inbound traffic on port 23.
- Create optional rules to allow SSH traffic on port 22.
- Remove test rules and restore the original firewall configuration.
- Document firewall configurations and test results using screenshots.

**Skills:** Firewall Configuration, Network Security, Traffic Filtering, Linux Administration, Windows Security, Network Troubleshooting, Access Control

**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/Configure-and-Test-Firewall-Rules)

### 7. Setup and Test VPN(Proton)
A hands-on VPN setup and testing project focused on establishing a secure VPN connection, verifying IP address changes, and understanding how VPNs protect online privacy and secure internet communication.

**Key Activities**
- Choose and install Proton VPN (Free Plan) on a supported operating system.
- Create an account, log in, and connect to an available VPN server.
- Verify IP address changes before and after establishing the VPN connection.
- Test internet connectivity by browsing websites while connected to the VPN.
- Compare IP addresses and browsing performance before and after disconnecting the VPN.
- Explore VPN security features, including encryption, DNS leak protection, and the kill switch.
- Document VPN setup steps, connection status, and testing results using screenshots.
- Evaluate the benefits and limitations of using a free VPN service.

**Skills:** VPN Configuration, Network Security, Online Privacy, IP Address Verification, Encrypted Communication, DNS Leak Protection, Network Troubleshooting

**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/Setup-and-Test-VPN)

### 8. Practice with NMAP tool.
A hands-on network scanning project using Nmap (Network Mapper) to discover open ports, identify running services, detect operating systems, and perform basic vulnerability checks on authorized target systems.

**Key Activities**
- Perform single-host and multiple-host scans to identify active hosts and open ports.
- Scan specific ports, including 22 (SSH), 80 (HTTP), and 443 (HTTPS).
- Scan a range of IP addresses to discover hosts and exposed network services.
- Perform aggressive scanning using the `-A` option to gather OS, service, and additional host information.
- Conduct UDP port scanning using the `-sU` option.
- Detect operating systems using the `-O` option.
- Identify service versions using the `-sV` option.
- Run vulnerability-related NSE scripts using `--script vulners` to check for known vulnerabilities in detected services.
- Compare TCP and UDP scanning techniques and understand their differences.
- Analyze scan results to identify potential security risks and recommend remediation steps.

**Skills:** Network Scanning, Port Enumeration, Service Detection, OS Fingerprinting, Vulnerability Assessment, Network Reconnaissance, Network Security, Security Reporting

**Repository:** [GitHub Repository](https://github.com/SRCybersecurity/NMAP_Practicals)

---

## 🏆 Certifications & Training

- **LetsDefend:** Splunk Engineer Badge
- **IBM:** Fundamentals of Network and Database Security
- **IBM:** Incident Response and Management

---

## 🧪 Hands-On Cybersecurity Practice

### LetsDefend

- Practiced investigating SIEM alerts involving brute-force attempts, malware, phishing, suspicious PowerShell activity, privilege escalation, and lateral movement.
- Worked through alert triage, IOC analysis, log correlation, incident documentation, and escalation workflows.

**Platform:** [LetsDefend](https://letsdefend.io/user/RS7777)

### TryHackMe

- Completed 130+ practical labs covering Windows Event Logs, Splunk, Active Directory, Kerberos, PowerShell logging, Linux privilege escalation, SOC investigations, and network traffic analysis.
- Achieved a **Top 2% platform ranking**, demonstrating consistent engagement with hands-on cybersecurity challenges.

**Profile:** [TryHackMe](https://tryhackme.com/p/RS77?utm_campaign=social_share&utm_medium=social&utm_content=profile&cardVersion=3674feb1b0f7&utm_source=copy&sharerId=699bd74649e8f7530e9ac1bf)

### picoCTF

- Practiced Capture The Flag (CTF) challenges in web exploitation, cryptography, reverse engineering, binary exploitation, and digital forensics.

**Platform:** [picoCTF](https://play.picoctf.org/users/Airysairyy_1122)

---

## 📚 Currently Learning

- Developing Security monitoring and SIEM investigation lab (ON GOING)
- Incident response and threat hunting lab (ON GOING)
- Linux and Windows security
- Network traffic analysis
- Security automation with Bash and Python

---

## 🤝 Let's Connect

- **GitHub:** [Explore my projects](https://github.com/SRCybersecurity)
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/sejalrathwacybersecurityL)
- **TryHackMe:** [View my profile](https://tryhackme.com/p/RS77)

---

> All security testing is performed in authorized environments. I aim to document findings accurately, explain remediation clearly, and make my projects reproducible.

⭐ Thanks for visiting my profile!
