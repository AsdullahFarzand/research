# Security Tools and Frameworks Reference

**Repository:** AsdullahFarzand/research  
**Last Updated:** January 10, 2026  
**Document Version:** 1.0

---

## Overview

This document catalogs the security tools and frameworks referenced in the research papers within this repository. Tools are organized by category and include descriptions, use cases, and relevance to the research domains.

---

## Table of Contents

1. [SOC and Monitoring Tools](#soc-and-monitoring-tools)
2. [Penetration Testing Tools](#penetration-testing-tools)
3. [Vulnerability Assessment Tools](#vulnerability-assessment-tools)
4. [Machine Learning Frameworks](#machine-learning-frameworks)
5. [Threat Intelligence Platforms](#threat-intelligence-platforms)
6. [Security Frameworks and Standards](#security-frameworks-and-standards)

---

## 1. SOC and Monitoring Tools

### SIEM (Security Information and Event Management)

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Splunk** | Commercial | Enterprise SIEM with advanced analytics | Log aggregation, threat detection, compliance |
| **Elastic Security** | Open Source/Commercial | SIEM built on Elasticsearch | Scalable log analysis, threat hunting |
| **IBM QRadar** | Commercial | Enterprise SIEM with AI capabilities | Large enterprise security operations |
| **Microsoft Sentinel** | Cloud | Cloud-native SIEM on Azure | Cloud-first security operations |
| **Wazuh** | Open Source | Host-based intrusion detection and SIEM | SMB security monitoring |
| **OSSIM** | Open Source | Open-source SIEM by AlienVault | Entry-level security monitoring |

### SOAR (Security Orchestration, Automation and Response)

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Splunk SOAR** | Commercial | Enterprise SOAR platform | Incident response automation |
| **IBM Resilient** | Commercial | Incident response platform | Enterprise incident management |
| **Palo Alto XSOAR** | Commercial | Integrated SOAR solution | Security workflow automation |
| **TheHive** | Open Source | Scalable incident response platform | Case management, collaboration |
| **Shuffle** | Open Source | SOAR automation platform | Workflow automation |

### EDR/XDR (Endpoint/Extended Detection and Response)

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **CrowdStrike Falcon** | Commercial | Cloud-native endpoint protection | Enterprise endpoint security |
| **Microsoft Defender** | Commercial | Integrated security suite | Microsoft ecosystem security |
| **SentinelOne** | Commercial | AI-powered endpoint protection | Automated threat response |
| **Carbon Black** | Commercial | VMware endpoint security | Virtualized environment security |
| **Velociraptor** | Open Source | Digital forensics and IR | Endpoint investigation |

---

## 2. Penetration Testing Tools

### Reconnaissance

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Nmap** | Open Source | Network mapper and port scanner | Network discovery, port scanning |
| **Shodan** | Commercial | Internet-connected device search | External asset discovery |
| **Maltego** | Commercial | Visual link analysis | OSINT gathering |
| **Recon-ng** | Open Source | Web reconnaissance framework | Automated recon |
| **theHarvester** | Open Source | Email and subdomain harvesting | Target enumeration |

### Vulnerability Scanning

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Nessus** | Commercial | Comprehensive vulnerability scanner | Enterprise vulnerability assessment |
| **OpenVAS** | Open Source | Open-source vulnerability scanner | Network vulnerability scanning |
| **Nuclei** | Open Source | Fast vulnerability scanner | Template-based scanning |
| **Nikto** | Open Source | Web server scanner | Web vulnerability detection |

### Exploitation Frameworks

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Metasploit** | Open Source/Commercial | Comprehensive exploitation framework | Penetration testing, exploit development |
| **Cobalt Strike** | Commercial | Adversary simulation platform | Red team operations |
| **Burp Suite** | Commercial | Web application security testing | Web application testing |
| **SQLMap** | Open Source | Automated SQL injection tool | Database vulnerability testing |
| **Impacket** | Open Source | Network protocol manipulation | Windows exploitation |

### Web Application Testing

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **OWASP ZAP** | Open Source | Web application security scanner | Automated web testing |
| **Burp Suite** | Commercial | Web security testing platform | Professional web testing |
| **Wfuzz** | Open Source | Web application fuzzer | Input fuzzing |
| **Dirb/Gobuster** | Open Source | Directory enumeration | Content discovery |
| **Postman** | Commercial | API testing platform | API security testing |

### Password Attacks

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Hashcat** | Open Source | Advanced password recovery | Hash cracking |
| **John the Ripper** | Open Source | Password cracker | Password auditing |
| **Hydra** | Open Source | Network login cracker | Brute force attacks |
| **CrackMapExec** | Open Source | Network authentication attacks | Windows network testing |

---

## 3. Vulnerability Assessment Tools

### Application Security Testing

| Tool | Type | Category | Description |
|------|------|----------|-------------|
| **SonarQube** | Open Source/Commercial | SAST | Code quality and security analysis |
| **Checkmarx** | Commercial | SAST | Enterprise source code analysis |
| **Veracode** | Commercial | SAST/DAST | Application security platform |
| **Snyk** | Commercial | SCA | Open-source vulnerability management |
| **Semgrep** | Open Source | SAST | Lightweight static analysis |
| **Dependabot** | Free | SCA | Dependency vulnerability alerts |

### Infrastructure Scanning

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Qualys** | Commercial | Cloud-based vulnerability management | Enterprise vulnerability scanning |
| **Tenable Nessus** | Commercial | Comprehensive vulnerability scanner | Network and web vulnerability |
| **Rapid7 InsightVM** | Commercial | Vulnerability management platform | Risk-based prioritization |
| **OpenSCAP** | Open Source | Security compliance framework | Configuration compliance |

### Container Security

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **Trivy** | Open Source | Container vulnerability scanner | CI/CD integration |
| **Grype** | Open Source | Container image scanning | Container vulnerability detection |
| **Aqua Security** | Commercial | Container security platform | Enterprise container security |
| **Prisma Cloud** | Commercial | Cloud-native security | Multi-cloud container security |

---

## 4. Machine Learning Frameworks

### General ML Frameworks

| Framework | Type | Description | Security Applications |
|-----------|------|-------------|----------------------|
| **TensorFlow** | Open Source | Google's ML framework | Deep learning models |
| **PyTorch** | Open Source | Facebook's ML framework | Research and production ML |
| **Scikit-learn** | Open Source | Python ML library | Classification, anomaly detection |
| **XGBoost** | Open Source | Gradient boosting library | Threat classification |
| **LightGBM** | Open Source | Gradient boosting framework | High-performance classification |

### Security-Specific ML Tools

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **EMBER** | Open Source | Malware feature extraction | Malware classification |
| **Cuckoo Sandbox** | Open Source | Malware analysis sandbox | Behavioral analysis |
| **YARA** | Open Source | Pattern matching for malware | Malware identification |
| **Zeek (Bro)** | Open Source | Network analysis framework | Network traffic analysis |

### MLOps and Deployment

| Tool | Type | Description | Use Case |
|------|------|-------------|----------|
| **MLflow** | Open Source | ML lifecycle management | Model tracking and deployment |
| **Kubeflow** | Open Source | ML toolkit for Kubernetes | Scalable ML pipelines |
| **Amazon SageMaker** | Cloud | AWS ML platform | Cloud ML deployment |
| **Azure ML** | Cloud | Microsoft ML platform | Enterprise ML operations |

---

## 5. Threat Intelligence Platforms

### Commercial Platforms

| Platform | Type | Description | Capabilities |
|----------|------|-------------|--------------|
| **Recorded Future** | Commercial | AI-powered threat intelligence | Predictive analysis, risk scoring |
| **CrowdStrike Falcon X** | Commercial | Automated threat intelligence | IOC analysis, malware intelligence |
| **Mandiant Threat Intelligence** | Commercial | Strategic threat intelligence | APT tracking, campaign analysis |
| **IBM X-Force** | Commercial | Threat intelligence network | Vulnerability intelligence |

### Open Source Intelligence

| Platform | Type | Description | Capabilities |
|----------|------|-------------|--------------|
| **MISP** | Open Source | Threat intelligence sharing | IOC sharing, correlation |
| **OpenCTI** | Open Source | Cyber threat intelligence platform | Knowledge management |
| **AlienVault OTX** | Free | Open threat exchange | Community threat intelligence |
| **VirusTotal** | Free/Commercial | File and URL analysis | Malware detection |

### Threat Feeds

| Feed | Type | Content | Update Frequency |
|------|------|---------|------------------|
| **MITRE ATT&CK** | Free | Adversary TTPs | Regular |
| **Abuse.ch** | Free | Malware IOCs | Daily |
| **PhishTank** | Free | Phishing URLs | Continuous |
| **Spamhaus** | Free | IP reputation | Continuous |

---

## 6. Security Frameworks and Standards

### Risk and Compliance Frameworks

| Framework | Organization | Focus | Applicability |
|-----------|--------------|-------|---------------|
| **NIST CSF** | NIST | Cybersecurity risk management | All organizations |
| **ISO 27001** | ISO | Information security management | International standard |
| **CIS Controls** | CIS | Prioritized security controls | Practical implementation |
| **COBIT** | ISACA | IT governance | Enterprise IT |

### Security Testing Standards

| Standard | Organization | Focus | Use Case |
|----------|--------------|-------|----------|
| **OWASP Testing Guide** | OWASP | Web application testing | Application security |
| **PTES** | Industry | Penetration testing methodology | Penetration testing |
| **OSSTMM** | ISECOM | Security testing methodology | Comprehensive testing |
| **NIST SP 800-115** | NIST | Technical security testing | Government and enterprise |

### Threat Modeling

| Framework | Description | Application |
|-----------|-------------|-------------|
| **STRIDE** | Microsoft threat modeling | Application threats |
| **DREAD** | Risk rating system | Threat prioritization |
| **MITRE ATT&CK** | Adversary TTPs | Threat intelligence |
| **Kill Chain** | Attack stages | Incident analysis |
| **Diamond Model** | Intrusion analysis | Threat analysis |

### Vulnerability Standards

| Standard | Organization | Purpose |
|----------|--------------|---------|
| **CVE** | MITRE | Vulnerability identification |
| **CWE** | MITRE | Weakness classification |
| **CVSS** | FIRST | Vulnerability scoring |
| **CPE** | NIST | Product identification |

---

## Tool Selection Guidelines

### By Organization Size

| Size | Recommended Stack |
|------|-------------------|
| **Startup/SMB** | Wazuh, OWASP ZAP, Snyk, Velociraptor |
| **Mid-Enterprise** | Elastic Security, Qualys, Metasploit Pro |
| **Large Enterprise** | Splunk, CrowdStrike, Checkmarx, Recorded Future |

### By Security Maturity

| Level | Recommended Focus |
|-------|-------------------|
| **Basic** | Vulnerability scanning, basic monitoring |
| **Intermediate** | SIEM, EDR, regular penetration testing |
| **Advanced** | SOAR, threat hunting, custom ML models |
| **Expert** | Integrated XDR, automated red teaming |

---

## Document History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | January 10, 2026 | Initial tools catalog |

---

**Maintainer:** AsdullahFarzand  
**Repository:** AsdullahFarzand/research

---

*Tool recommendations are based on research papers in this repository and do not constitute endorsement.*
