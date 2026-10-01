# Cybersecurity Internship Reports

Four weekly deliverables from my cybersecurity internship: threat modeling, incident response, penetration testing and a full security audit. Each task was carried out as a **simulation in an isolated virtual lab** on a fictional company, *NorthStar Retail*, and documented as a 20+ page Word report with diagrams, charts, tables and real-world case studies.

> **Safety and ethics:** All testing was done on virtual machines I own, on a host-only network with no internet route. No real systems, real malware or real personal data were involved. Do not use any technique described here against systems you do not own or have written permission to test.

## Repository structure

| Folder | Task | Report |
|---|---|---|
| [`week-1-threat-modeling-vulnerability-assessment`](./week-1-threat-modeling-vulnerability-assessment) | Virtual Threat Modeling and Vulnerability Assessment | [DOCX](./week-1-threat-modeling-vulnerability-assessment/Week1_Threat_Modeling_and_Vulnerability_Assessment.docx) |
| [`week-2-incident-response-simulation`](./week-2-incident-response-simulation) | Virtual Security Incident Response Simulation | [DOCX](./week-2-incident-response-simulation/Week2_Incident_Response_Simulation.docx) |
| [`week-3-penetration-testing-simulation`](./week-3-penetration-testing-simulation) | Virtual Security Control Testing and Penetration Simulation | [DOCX](./week-3-penetration-testing-simulation/Week3_Penetration_Testing_Simulation.docx) |
| [`week-4-security-audit-strategic-recommendations`](./week-4-security-audit-strategic-recommendations) | Comprehensive Security Audit and Strategic Recommendations | [DOCX](./week-4-security-audit-strategic-recommendations/Week4_Security_Audit_and_Strategic_Recommendations.docx) |
| [`submission-descriptions`](./submission-descriptions) | 200+ word descriptions used in the submission forms | [descriptions.md](./submission-descriptions/descriptions.md) |

Each week folder contains the report (`.docx`), a `figures/` folder with every diagram and chart as PNG, and its own `README.md` summary.

## Summary of each week

### Week 1 - Threat Modeling and Vulnerability Assessment
- Defined network zones, assets, data flows and trust boundaries
- Modeled 27 threats with **STRIDE**; applied **PASTA** and an attack tree
- Scanned with Nmap, OWASP ZAP and testssl.sh; validated manually
- 13 findings (3 Critical, 6 High, 3 Medium, 1 Low), risk heat map, 90-day remediation roadmap

### Week 2 - Incident Response Simulation
- Simulated phishing-to-ransomware scenario with benign emulation tools
- IoCs, Cyber Kill Chain and MITRE ATT&CK mapping
- Response plan based on **NIST SP 800-61** and **SANS PICERL**, with roles, severity matrix and playbooks
- Post-incident analysis: root cause, MTTD/MTTC/MTTE/MTTR, gap analysis, lessons learned

### Week 3 - Penetration Testing Simulation
- **PTES** and **OWASP WSTG** methodology; 108 planned test cases across network, application and access control
- 14 validated findings with estimated CVSS, OWASP/CWE mapping and remediation
- Seven-step exploitation chain, detection measurement and retest results

### Week 4 - Security Audit and Strategic Recommendations
- Audit against **ISO/IEC 27001:2022**, **NIST CSF 2.0** and **CIS Controls v8**
- 19 findings, 47 risk scenarios, gap analysis, KPI dashboard
- Immediate action plan and 24-month strategic roadmap with cost versus risk-reduction model

## Frameworks and standards used
STRIDE, PASTA, NIST SP 800-30, NIST SP 800-61, NIST SP 800-115, NIST CSF 2.0, MITRE ATT&CK, Cyber Kill Chain, SANS PICERL, PTES, OWASP Top 10 and WSTG, CVSS v3.1, ISO/IEC 27001:2022, ISO/IEC 27035, ISO 19011, CIS Controls v8 and CIS Benchmarks.

## Tools (lab only)
Nmap, OWASP ZAP, Burp Suite Community, Nikto, Gobuster, testssl.sh, Wireshark, Metasploit Framework, Wazuh, pfSense, VirtualBox, Kali Linux; intentionally vulnerable targets such as OWASP Juice Shop, DVWA and Metasploitable 2.

## Note on the scenario
NorthStar Retail, its IP addresses and its statistics are a **simulated scenario** created for learning. Illustrative output panels are labelled as such in the reports.

## Author
**Anjali** - GitHub: [@anjal-iiii](https://github.com/anjal-iiii)

## License
Educational use. Reports are shared for learning and portfolio purposes.
