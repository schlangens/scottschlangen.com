---
title: "Resume"
description: "Scott Schlangen — Security Engineer resume"
aliases: ["cv", "resume"]
eyebrow: "Career"
subtitle: "Detection Engineering · Vulnerability Management · Incident Response · Security Automation"
sidebar:
  label: "Connect & work"
  groups:
    - title: "Contact"
      items:
        - label: "Email"
          href: "mailto:scott@scottschlangen.com"
          hint: "Mail"
        - label: "LinkedIn"
          href: "https://www.linkedin.com/in/scottschlangen/"
          hint: "Network"
        - label: "GitHub"
          href: "https://github.com/schlangens"
          hint: "Code"
        - label: "Scott's Lab"
          href: "https://scottslab.io/"
          hint: "Lab"
    - title: "Writing"
      items:
        - label: "Hacking with AI"
          href: "https://scottslab.io/posts/hacking-with-ai-security-engineers-guide"
          hint: "AI"
        - label: "Wazuh home-lab SIEM"
          href: "https://scottslab.io/posts/home-lab-siem-wazuh-custom-detection"
          hint: "SIEM"
        - label: "All Lab posts"
          href: "https://scottslab.io/posts"
          hint: "Archive"
    - title: "Tools"
      items:
        - label: "Scrambler"
          href: "https://scramble.scottslab.io"
          hint: "PII"
        - label: "WX Dashboard"
          href: "https://wx.scottslab.io"
          hint: "Weather"
        - label: "CyberChef"
          href: "https://chef.scottslab.io"
          hint: "Transform"
        - label: "EventID-Scraper"
          href: "https://github.com/schlangens/EventID-Scraper"
          hint: "Python"
    - title: "This site"
      items:
        - label: "About"
          href: "/about/"
          hint: "Story"
        - label: "Projects"
          href: "/tools/"
          hint: "Build"
        - label: "Now"
          href: "/now/"
          hint: "Focus"
---

Indianapolis, IN · Eastern Time

## Summary

Security engineer with eight years in cybersecurity, currently the incident response lead and vulnerability management owner for municipal government clients as an MSSP subject matter expert. Builds the tooling a security program actually runs on: a Python vulnerability-reporting framework that cut monthly analysis from hours to under 30 seconds, a Rapid7 detection exception that ended a 154-ticket false-positive flood without losing coverage, and a public GitHub of self-built security tooling. Owned a 25+ domain cybersecurity risk program end to end for a city of 100,000 residents, raising its posture score 6.7% in six months. Works across detection engineering, vulnerability management, incident response, IAM, and GRC — with current hands-on experience running AI-agent and MCP-based automation platforms and a Microsoft security certification track (SC-300 through SC-100) alongside CISSP.

## Core Competencies

**Detection Engineering & SIEM** — Rapid7 InsightIDR · Microsoft Sentinel · Microsoft Defender XDR · Wazuh · MITRE ATT&CK mapping · alert tuning · detection rule authoring

**Vulnerability Management** — Rapid7 InsightVM · Tenable Nessus · ConnectSecure · prioritization and remediation at 11,000+ finding scale

**Security Automation** — Python reporting frameworks · scripted ingestion across 40+ segments · dual-format reporting · infrastructure automation

**AI Agent & LLM Tooling** — AI coding agents · MCP-integrated automation · sandboxed execution · credential-scoped workflows

**Incident Response** — IR lead for confirmed intrusions, ATO, BEC, and vendor email compromise · forensic triage · executive and insurer coordination

**Identity & Access** — Microsoft Entra ID · Conditional Access · Active Directory · Duo MFA · Varonis · RBAC / least privilege

**Compliance & Risk (GRC)** — NIST CSF 2.0 · CIS Controls · HIPAA · PCI DSS · ISO 27001 · CJIS · Cynomi risk register · policy authoring

## Experience

### Resultant (MSSP) · Mar 2026 – Present · Remote

**Senior Security Engineer**

Security engineer for a city-county government serving 300,000+ residents across police, courts and utilities, plus incident response for other clients. Recognized at company all-hands three times in seven months and given a manager spot bonus for incident response.

- Led the response to an infostealer with confirmed data exfiltration at a city police department. Found a 15.6 MB upload in a 500,129-row firewall export, scoped it to one host and briefed leadership, then found a second infected workstation a managed detection vendor had closed without action.
- Built a PII email data loss prevention program in Microsoft Purview for about 1,000 users across three departments, with enforced hold-and-encrypt for county HR and approval-driven release automated in Azure Automation.
- Ran a four-stage Conditional Access program for 4,000 users, and found a baseline access policy trusted for ten months that had never applied to a single device.
- Checked 145 public hostnames the morning a critical PHP remote code execution flaw was disclosed and briefed leadership on 10 systems that will never be patched, 4 of them internet-facing.
- Reviewed vendors and AI tools before approval, including 8 gaps in an AI contact-center vendor's service agreement.
- Built a risk register as code mapped to NIST CSF 2.0, CIS Controls and COBIT 2019, guarded by 31 automated checks.
- Combined four years of CISA Cyber Hygiene scans into one trend, with findings down from 262 to 58.
- Authored security standard operating procedures for the company-wide runbook library.

Core skills include information security, security operations, incident response, data loss prevention, Microsoft Entra ID, Microsoft Purview, vulnerability management, risk management, NIST CSF, CJIS, Python and PowerShell.

<div class="company-header">
  <img src="/img/logos/carmel.png" alt="City of Carmel" class="company-logo">
  <h3>City of Carmel, Indiana · Sep 2025 – Mar 2026 · Carmel, IN</h3>
</div>

**System Administrator - Cybersecurity**

Ran the cybersecurity risk program for a city of 100,000+ residents across 25+ security policy domains. Owned identity and access governance, endpoint protection, vulnerability management and security monitoring across city systems.

- Raised the cybersecurity posture score 6.7% in six months, from 5.28 to 6.0, by completing 284 of 553 security tasks and closing 86% of critical-priority items.
- Triaged 11,777 vulnerability findings across 39 organizational risks and cut high-severity hosts by a third in three months, from 281 to 187. Advanced CJIS compliance to 59% and NIST CSF 2.0 to 55%.
- Built a Python reporting framework that ingests exports from 40+ network segments and maps findings to MITRE ATT&CK, cutting monthly vulnerability analysis from hours to under 30 seconds.
- Coordinated Dell iDRAC firmware upgrades on 17 of 18 hosts, SNMP hardening on 49 of 81 hosts and OpenSSH upgrades that cut affected hosts from 152 to 98.
- Cut the phish-prone rate from 25% to 1.8% across 861 users with 6 phishing simulations and 7 monthly KnowBe4 campaigns, ten times better than the 18.6% government benchmark.
- Assessed vulnerabilities across water treatment, wastewater, police, fire and emergency operations networks, and wrote a 9-section runbook and handoff package covering 40+ network segments.
- Led the Abnormal AI rollout across 1,051 mailboxes, which stopped 410 email attacks in 90 days and took business email compromise cases from 13 to 0.

Core skills include vulnerability management, risk management, security operations, identity and access management, security awareness, CJIS, NIST CSF 2.0, KnowBe4, Abnormal AI and Python.

<div class="company-header">
  <img src="/img/logos/quadrant.png" alt="Quadrant Information Security" class="company-logo">
  <h3>Quadrant Information Security · Jan 2024 – Sep 2025 · Remote</h3>
</div>

**Cyber Threat Analyst**

Monitored and analyzed security alerts across client environments using SIEM platforms, handling real-time threat detection, triage and escalation for managed security operations.

- Investigated malware, phishing, unauthorized access and anomalous network activity across diverse client environments.
- Developed and refined detection rules and correlation logic to reduce false positives and improve alert fidelity.
- Prioritized security events by risk and gave client security teams the threat context they needed to act.
- Contributed to incident response documentation and post-incident analysis.

Core skills include threat detection, SIEM operations, detection engineering and incident response.

## Projects & Public Work

Hands-on orchestration of AI coding agents and MCP-integrated automation platforms, including scheduled jobs, sandboxed execution, and credential-scoped automation. Public writing, tools, and repositories are linked in the sidebar.

## Certifications

**In progress:** CCSP · Microsoft SC-300 · SC-200 · SC-500 · SC-100

**Security:** CISSP · CompTIA CySA+ ce · CompTIA Security+ ce · CompTIA Security Analytics Professional (CSAP) · Blue Team Level 1 (BTL1) · Certified CyberDefender Level 2 (CCDL2) · Wazuh for Security Engineers · Ransomware Negotiation and Threat Intelligence

**Cloud & Infrastructure:** CompTIA Cloud+ ce · CompTIA Secure Cloud Professional (CSCP) · CompTIA Cloud Admin Professional (CCAP) · AWS Certified Cloud Practitioner · Microsoft Certified: Azure Fundamentals · Microsoft Certified: Security, Compliance, and Identity Fundamentals (SC-900) · CompTIA Network+ ce

**Platform & Program:** ConnectSecure Certified Administrator (CCA) · CompTIA Project+ ce

**Roadmap:** Databricks Certified Generative AI Engineer and Google Cloud AI/ML track through 2027.

## Affiliations

- **Indiana Civilian Cyber Corps (ICCC)**, Volunteer, Aug 2026 to present.
- **InfraGard Indiana**, membership application pending.
- **Cyber Leadership Institute**, Member, Nov 2026 to present.
- **National Society of Leadership and Success**, WGU chapter, induction in progress.

## Education

**Western Governors University**, B.S. Cybersecurity and Information Assurance, expected June 2027
