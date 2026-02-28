# Devon Booker

Cloud security engineer building and securing Microsoft 365 + Azure environments.

Security Analyst at Arctic Wolf Networks, working enterprise SOC operations while building production-grade cloud infrastructure from scratch. Finishing B.S. Cybersecurity at WGU (Sep 2026).

My focus is the intersection of identity security, cloud infrastructure, and automation - the three areas that determine whether an organization gets breached or doesn't.

---

## Active Projects

### [The Fortress](https://github.com/devonbookerrr/the-fortress)
A production-grade M365 + Azure + Linux environment built from scratch and maintained as a living portfolio. Hub-and-spoke VNet topology with Azure Firewall. Entra ID with Conditional Access policy sets deployed via Graph API and PIM eligible-only role configuration. Ubuntu Server 24.04 hardened to CIS Level 2. MySQL backend tracking every architectural decision, configuration state, and compliance finding. Every cert I study and every technique I learn gets applied here first.

### [M365 Security Assessment Engine](https://github.com/devonbookerrr/assessment-engine)
PowerShell collectors query Entra ID tenants via Graph API and Exchange Online Management across five security domains: identity, privileged access, authentication, Exchange, and device compliance. A Python scoring engine evaluates each control, calculates a 0-100 score, and writes findings to MySQL with MITRE ATT&CK, CIS, and NIST mappings. Jinja2 report generator produces actionable Markdown remediation reports. The Assessment Engine evaluates The Fortress environment.

### [The Watchtower](https://github.com/devonbookerrr/the-watchtower)
Azure Sentinel detection lab monitoring The Fortress. Twelve custom analytic rules in YAML format mapped to MITRE ATT&CK - identity detections (impossible travel, MFA fatigue, privilege escalation outside PIM, CA policy modification) and Linux detections (SSH brute force, cron persistence, sudo escalation, new local user, AIDE integrity failure). KQL saved functions for reusable detection logic. Logic App playbooks for automated response: disable compromised accounts, revoke sessions, and notify SOC via Teams. The Watchtower monitors what The Fortress builds.

---

## Stack

```
Identity        Microsoft Entra ID  |  Conditional Access  |  PIM  |  Graph API  |  Zero Trust
Infrastructure  Azure VNets  |  NSGs  |  Key Vault  |  Azure Policy  |  Log Analytics  |  Bicep
Platform        Exchange Online  |  Intune  |  Defender for Office 365  |  DLP  |  SharePoint
Automation      PowerShell (Graph SDK, Az module, ExchangeOnlineManagement)
                Python (Azure SDK, FastAPI, Jinja2, mysql-connector)
                Bash  |  MySQL 8.0  |  KQL
OS              Ubuntu Server 24.04  |  Rocky Linux
Security        SIEM  |  Detection Engineering  |  MITRE ATT&CK  |  NIST  |  CIS Benchmarks
```

---

## Certifications

CompTIA Security+ &nbsp;|&nbsp; CompTIA Network+ &nbsp;|&nbsp; CompTIA A+ &nbsp;|&nbsp; BTL1

---

## Background

3+ years in cybersecurity across help desk, systems administration, and SOC roles. Led EDR deployment across 4,000+ endpoints and NIST SP 800-171 audits. Built 25+ custom SIEM detection rules with MITRE ATT&CK mapping. Currently working enterprise triage at Arctic Wolf while building toward cloud security engineering roles.

---

[LinkedIn](https://linkedin.com/in/devonbookerr) &nbsp;|&nbsp; San Antonio, TX
