# 🛡️ Interactive Nessus Vulnerability Dashboard

An interactive, responsive, and modern security dashboard built to visualize, filter, and analyze vulnerability scan results from **Nessus Essentials**. This project was developed as a core deliverable for an advanced cybersecurity audit, focusing on the evaluation of the **Linux Metasploitable 3** environment.

🌍 **Live Production Link:** [👉 Explore the Live Dashboard](https://manuelcruz21.github.io/nessus_dashboard/)  
💻 **Source Code Repository:** [📁 GitHub Repository](https://github.com/ManuelCruz21/nessus_dashboard)

---

## 🎯 Project Overview & Scope

The objective of this project is to bridge the gap between complex raw scanner outputs and executive-level security visualization. By analyzing and contrasting two distinct scanning methodologies, this dashboard provides a complete security posture assessment:

1. **Unauthenticated Scan (External Attacker Perspective):** Simulates a black-box attack originating outside the network perimeter, targeting exposed services and remote exploits.
2. **Authenticated Scan (Internal/Post-Compromise Perspective):** Executes deep local audits on operating system binaries, packages, and internal configurations to expose privilege escalation paths.

---

## 🚀 Key Features

* **Dual-Perspective Analytics:** Instantly toggle or compare data from authenticated and unauthenticated scans.
* **Smart Risk Triage:** Highlighted visibility for **Critical** and **High** vulnerabilities requiring immediate remediation.
* **Advanced Exploit Tracking:** Cross-references vulnerabilities that possess public exploit payloads in elite frameworks like **Metasploit** and **CANVAS**.
* **Vulnerability Intersection:** Built-in logic to display common vulnerabilities across both scan profiles.
* **100% Responsive Engine:** Mobile-optimized interface utilizing advanced CSS media queries for fluid on-the-field triage.
* **Interactive Architecture:** Zero-dependency vanilla frontend ensuring high performance and fast lookup.

---

## 📋 Monitored High-Impact Vulnerabilities

The dashboard provides a deep drill-down into critical infrastructure vulnerabilities found in the target system, including:

| Plugin ID | Vulnerability Name | Severity | CVSS | Main Threat Vector | Exploit Available |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **46882** | UnrealIRCd Backdoor Detection | Critical | **10.0** | Unauthenticated Remote Code Execution | Metasploit, CANVAS |
| **146799** | Linux Sudo Privilege Escalation (Baron Samedit) | High | **7.8** | Local Privilege Escalation to Root | Metasploit, CANVAS |

---

## 🛠️ Built With

* **HTML5** - Semantic structure for clean data mapping.
* **CSS3** - Custom design framework leveraging CSS variables, Flexbox matrix wrapping, and responsive media queries.
* **JavaScript (ES6+)** - Dynamic tab management, dataset intersections, and live UI parsing.

---

## 🔧 Remediation Strategy

Beyond listing threats, the project incorporates a **Remediation Plan** aligned with best practices in defensive security:
* **Perimeter Hardening:** Guidance on immediate firewall containment and port isolation (e.g., port 6697).
* **Defense in Depth:** Mitigation of internal privilege elevation risks by updating legacy operating system binary trees (e.g., `sudo` upgrades).
* **Lifecycle Management:** Addressing End-of-Life (SEoL) software stacks to reduce multi-vector risk inheritance.

---

## 👤 Author

* **Manuel Cruz**
* **Project Date:** June 7, 2026
* **Target Environment:** Linux Metasploitable 3 (Host: 192.168.56.115)