# Adewale Olalekan — Cybersecurity Portfolio

![Banner](https://github.com/adewaleolalekan/cybersecurity_portfolio/raw/main/logo.png)

[![Google Cybersecurity](https://img.shields.io/badge/Google-Cybersecurity_Certificate-4285F4?style=flat-square&logo=google&logoColor=white)](https://www.credly.com/badges/945c2a4a-d516-4244-85fb-be6c8f7820c0/public_url)
[![Microsoft Cybersecurity](https://img.shields.io/badge/Microsoft-Cybersecurity_Analyst-0078D4?style=flat-square&logo=microsoft&logoColor=white)](https://coursera.org/verify/professional-cert/AEXA8H2ZJ2BB)
[![ISC2 CC](https://img.shields.io/badge/ISC2-Certified_in_Cybersecurity-1A1A2E?style=flat-square&logo=isc2&logoColor=white)](https://www.isc2.org/certifications/cc)
[![Portfolio](https://img.shields.io/badge/Live_Portfolio-Visit_Site-00d4ff?style=flat-square&logo=github&logoColor=white)](https://adewaleolalekan.github.io/cybersecurity_portfolio/)
![Location](https://img.shields.io/badge/Location-Abuja,_Nigeria-green?style=flat-square)
![Open to Work](https://img.shields.io/badge/Status-Open_to_Remote_Roles-brightgreen?style=flat-square)

---

## About Me

I'm a certified cybersecurity professional focused on **defensive security** — detecting threats, investigating incidents, and building secure infrastructure. This portfolio documents hands-on projects covering the full range of a SOC analyst's work: from packet-level malware hunting to compliance audits, network design, and vulnerability assessment.

I hold three industry certifications (Google, Microsoft, ISC2) and am actively seeking **remote SOC Analyst, Security Analyst, or Junior Security Engineer** roles.

📍 Abuja, Nigeria (UTC+1) &nbsp;|&nbsp; ⚡ Available immediately &nbsp;|&nbsp; 🌐 Open to remote worldwide

**[View Live Portfolio →](https://adewaleolalekan.github.io/cybersecurity_portfolio/)** &nbsp;&nbsp; **[Connect on LinkedIn →](https://www.linkedin.com/in/adewale-olalekan-401455159/)**

---

## Skills & Tools

### Core Competencies
`Threat Detection & Incident Response` &nbsp; `Network Traffic Analysis` &nbsp; `Vulnerability Assessment` &nbsp; `Security Auditing & Compliance` &nbsp; `Risk Assessment` &nbsp; `Malware Traffic Analysis` &nbsp; `SIEM Operations` &nbsp; `Network Design & Segmentation`

### Tools
| Category | Tools |
|---|---|
| **Traffic Analysis** | Wireshark, tcpdump |
| **Vulnerability Scanning** | OWASP ZAP, OpenVAS, Nessus Essentials |
| **SIEM / Monitoring** | Microsoft Sentinel, Wazuh, Elastic Stack |
| **Networking** | Cisco Packet Tracer, VLANs, Firewall config, Inter-VLAN routing |
| **Threat Intelligence** | VirusTotal, URLhaus, MITRE ATT&CK Navigator |

### Frameworks
`NIST CSF` &nbsp; `MITRE ATT&CK` &nbsp; `GDPR` &nbsp; `ISO 27001` &nbsp; `PCI DSS` &nbsp; `RBAC`

---

## Projects

### 🔴 Malware Traffic Analysis *(Capstone)*
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/malware_traffic_analysis/)**

Full incident investigation of a live host compromise on a corporate network. Reconstructed a complete attack chain — from a fake "Google Authenticator" lure through fileless PowerShell execution to an active DynGate RAT C2 session — entirely from PCAP evidence.

- Identified typosquatted delivery domain (`authenticatoor[.]org`) via DNS traffic analysis
- Extracted malicious ZIP payload from cleartext HTTP stream using Wireshark's HTTP Object Export
- Traced fileless PowerShell dropper (`29842.ps1`) executed in memory via IEX download cradle
- Detected DynGate RAT beaconing to `185[.]188[.]32[.]26` with consistent 60-second heartbeat intervals
- Mapped all techniques to MITRE ATT&CK (T1566, T1105, T1059.001, T1027, T1219, T1573)
- Produced full IOC list in defanged format and executive-level recommendations

`Wireshark` `MITRE ATT&CK` `Incident Response` `Threat Hunting` `IOC Analysis`

---

### 🟠 Internal Security Audit
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/internal_security_audit/)**

End-to-end security audit of a fictional mid-sized organisation. Applied a structured audit methodology to assess controls across people, process, and technology — producing a findings report with risk-rated recommendations.

- Conducted scope definition, asset inventory, and threat modelling
- Assessed controls against NIST CSF and ISO 27001 requirements
- Identified critical gaps in access control, patch management, and data handling
- Delivered a prioritised remediation roadmap with risk ratings (Critical / High / Medium / Low)

`Security Auditing` `NIST CSF` `ISO 27001` `Risk Assessment` `Compliance`

---

### 🟠 Wireshark Traffic Analysis
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/wireshark_traffic_analysis/)**

Deep packet inspection exercise focused on identifying network anomalies, suspicious traffic patterns, and protocol misuse within a provided PCAP file.

- Applied targeted display filters to isolate protocol-specific traffic (DNS, HTTP, TCP, ARP)
- Identified anomalous traffic volumes and unusual external connection attempts
- Reconstructed data flows using TCP stream analysis
- Documented findings with annotated screenshots and filter references

`Wireshark` `Network Forensics` `Protocol Analysis` `Anomaly Detection`

---

### 🟡 OWASP ZAP Vulnerability Scan
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/zap_vulnerability_scan/)**

Web application vulnerability assessment using OWASP ZAP against a deliberately vulnerable target. Identified, classified, and documented findings with remediation guidance.

- Ran automated active and passive scans using OWASP ZAP
- Identified vulnerabilities including missing security headers, XSS vectors, and exposed sensitive paths
- Classified findings by OWASP Top 10 category and severity
- Produced a remediation report with developer-facing fix guidance

`OWASP ZAP` `Web App Security` `OWASP Top 10` `Vulnerability Assessment` `Penetration Testing Basics`

---

### 🟡 Secure Network Design
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/secure_network/)**

Designed and implemented a segmented, defence-in-depth network architecture using Cisco Packet Tracer. Focused on isolating trust zones and enforcing least-privilege traffic flows.

- Designed multi-zone network with DMZ, internal LAN, and management VLAN separation
- Configured firewall ACLs to enforce inter-zone traffic policies
- Applied the principle of least privilege to routing and access rules
- Documented topology, design rationale, and security decisions

`Network Security` `Cisco Packet Tracer` `Firewall Configuration` `Defence in Depth` `Network Design`

---

### 🟡 Inter-VLAN Routing
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/inter_vlan/)**

Configured inter-VLAN routing on a Layer 3 switch to segment a flat network into logical security zones while maintaining controlled connectivity between them.

- Designed VLAN scheme for department segmentation (HR, Finance, IT, Guest)
- Configured trunk ports and sub-interfaces for inter-VLAN communication
- Applied access control to restrict cross-VLAN traffic to necessary flows only
- Verified routing and segmentation through simulation testing

`VLANs` `Layer 3 Switching` `Network Segmentation` `Cisco Packet Tracer`

---

### 🟡 Simple Network Design
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/simple_network/)**

Foundational network design exercise covering core IP addressing, subnetting, and routing configuration for a small office environment.

- Designed IP addressing scheme with appropriate subnets per department
- Configured static and dynamic routing between network segments
- Verified end-to-end connectivity through Packet Tracer simulation

`Networking Fundamentals` `IP Addressing` `Subnetting` `Cisco Packet Tracer`

---

### 🟢 Role-Based Access Control (RBAC)
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/rbac/)**

Designed and documented an RBAC framework for a fictional organisation, mapping job roles to access permissions following the principle of least privilege.

- Defined role taxonomy across business units (Admin, Analyst, Manager, Guest)
- Mapped data assets and systems to access tiers
- Documented privilege escalation procedures and review cycles
- Applied RBAC principles aligned with NIST SP 800-53 AC controls

`Access Control` `IAM` `Least Privilege` `NIST` `Security Policy`

---

### 🟢 GDPR Compliance Checklist
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/gdpr_checklist/)**

Developed a practical GDPR compliance checklist for a fictional data-processing organisation, covering the key requirements of the regulation across six lawful bases.

- Assessed data collection, storage, retention, and transfer practices
- Documented gaps against GDPR Articles 5, 13, 17, 25, and 32
- Produced actionable remediation items for each identified gap
- Created a Data Subject Rights response procedure

`GDPR` `Data Privacy` `Compliance` `Risk Assessment` `Policy Development`

---

### 🟢 Equifax Data Breach — Case Study
**[View Project →](https://adewaleolalekan/cybersecurity_portfolio/tree/main/equifax_data_breach/)**

Analytical case study of the 2017 Equifax breach — one of the largest data breaches in history, exposing 147 million records — examining root causes, failure points, and lessons learned.

- Traced the attack vector (unpatched Apache Struts CVE-2017-5638) and exploitation timeline
- Analysed detection failures: the breach went undetected for 78 days
- Mapped control failures to NIST CSF functions (Identify, Protect, Detect, Respond, Recover)
- Documented 10 specific lessons applicable to enterprise security programmes

`Incident Analysis` `NIST CSF` `Vulnerability Management` `Case Study` `Root Cause Analysis`

---

### 🟢 Basic Risk Assessment
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/basic_risk_assessment/)**

Conducted a structured risk assessment for a fictional small business using a qualitative risk matrix, identifying assets, threats, vulnerabilities, and mitigation strategies.

- Identified and categorised key information assets by criticality
- Applied a 5×5 likelihood × impact risk matrix to score each risk
- Prioritised risks and mapped mitigation controls to each
- Produced an executive risk register suitable for board-level review

`Risk Assessment` `Risk Matrix` `Asset Management` `Security Controls` `GRC`

---

### 🟢 Ethical Concepts in Cybersecurity
**[View Project →](https://adewaleolalekan.github.io/cybersecurity_portfolio/ethical_concepts/)**

Written exploration of core ethical principles in cybersecurity practice — covering responsible disclosure, privacy, professional conduct, and the legal boundaries of security testing.

- Analysed ethical frameworks applied in security research and penetration testing
- Discussed the responsible disclosure lifecycle and CVE reporting
- Examined legal boundaries under the Computer Fraud and Abuse Act (CFAA) and equivalents
- Applied ethical reasoning to real-world security dilemmas

`Security Ethics` `Responsible Disclosure` `Professional Development` `Policy`

---

## Certifications

| Certification | Issuer | Verify |
|---|---|---|
| Cybersecurity Professional Certificate | Google | [Credly Badge](https://www.credly.com/badges/945c2a4a-d516-4244-85fb-be6c8f7820c0/public_url) |
| Cybersecurity Analyst Professional Certificate | Microsoft | [Coursera](https://coursera.org/verify/professional-cert/AEXA8H2ZJ2BB) |
| Certified in Cybersecurity (CC) | ISC2 | — |

---

## Currently Developing

- 🔵 **SIEM Lab** — Building a home SOC with Wazuh + Elastic Stack, ingesting Windows event logs and writing detection rules
- 🔵 **Cloud Security** — Azure security fundamentals and Microsoft Defender for Cloud configuration
- 🔵 **Python for Security** — Automating IOC lookups and log parsing with Python scripts

---

## Contact

I'm actively looking for **remote cybersecurity opportunities**. If you're hiring for SOC Analyst, Security Analyst, or similar roles, let's connect.

- 📧 **Email**: adewale.olalekan@gmail.com  
- 💼 **LinkedIn**: [linkedin.com/in/adewale-olalekan-401455159](https://www.linkedin.com/in/adewale-olalekan-401455159/)  
- 🌐 **Portfolio**: [adewaleolalekan.github.io/cybersecurity_portfolio](https://adewaleolalekan.github.io/cybersecurity_portfolio/)

---

*Continuously improving — new projects added regularly. Last updated: July 2025.*