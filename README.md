# Personal Data Breach Response Playbook & Tabletop Kit

**DPDP Act 2023 · DPDP Rules 2025 · CERT-In Directions · RBI · NIST SP 800-61r3 · ISO/IEC 27001:2022**

A complete, ready-to-use personal data breach response playbook for **Suvidha Finserv Ltd**, a fictional RBI-registered NBFC in Ahmedabad holding KYC and financial data on about 12 lakh customers.

One breach at an Indian financial company can start **three regulatory clocks at once**: CERT-In (6 hours), RBI (6 hours) and the Data Protection Board (72 hours). This playbook shows exactly who does what, and by when, so none of those deadlines are missed.

---

## The problem

- DPDP Rule 7 requires **every** personal data breach to be reported to the Data Protection Board and to each affected person, with **no risk threshold**.
- CERT-In requires cyber incidents to be reported within **6 hours** of noticing them.
- RBI-regulated entities must also report cyber incidents within **6 hours**.
- Penalties under the DPDP Act reach **₹250 crore** for weak security safeguards and **₹200 crore** for failing to notify.

Most organisations have a generic incident response plan, but not one that coordinates these parallel privacy and regulatory obligations.

## What I built

| Component | What it does |
| --- | --- |
| Regulatory timeline matrix | All obligations side by side: trigger, deadline, content, channel |
| Breach Response Team + RACI | Named roles and who is Responsible / Accountable / Consulted / Informed for 10 key decisions |
| Severity matrix | 4 levels based on business and customer harm, with escalation factors |
| Hour-by-hour workflow | T+0 to T+30 days, with owners for every step |
| Reportability decision tree | 5 checks run in the first hour (diagram below) |
| Notification templates | CERT-In report, DPDP Board initial intimation, 72-hour detailed report, customer notice |
| Evidence handling + breach register | Chain of custody rules and a worked register entry |
| Tabletop exercise kit | "The Open Bucket" scenario, 8 timed injects, facilitator guide, scoring sheet |
| Post-incident review + KPIs | Review agenda and 10 board-level metrics |
| Control mapping | Every section mapped to DPDP, ISO 27001:2022 Annex A and NIST CSF 2.0 |

## Reportability decision tree

![Reportability decision tree](images/reportability-decision-tree.png)

## Skills demonstrated

- **Privacy law:** DPDP Act 2023 and Rules 2025 (Rule 7 breach intimation), GDPR Articles 33–34
- **Indian cyber regulation:** CERT-In Directions (6-hour reporting, 180-day logs), RBI cyber incident reporting
- **Incident response:** NIST SP 800-61 Rev. 3 aligned to CSF 2.0, evidence handling, chain of custody
- **GRC:** RACI design, severity classification, control mapping to ISO/IEC 27001:2022, KPI design
- **Third-party risk:** processor notification clauses and vendor coordination during a breach
- **Exercise design:** tabletop scenario, injects and capability scoring

## Files

| File | Description |
| --- | --- |
| [`PLAYBOOK.md`](PLAYBOOK.md) | The full playbook and tabletop kit |
| [`images/reportability-decision-tree.png`](images/reportability-decision-tree.png) | Decision tree diagram |

## Disclaimer

Suvidha Finserv Ltd and every person, number and incident in this project are **fictional**. This is a portfolio project, not legal advice. Regulatory requirements reflect sources available in November 2026; phased DPDP commencement dates should be checked before real-world use.

---

**Author:** Khooshi Joshi · Data Privacy & GRC
MSc Digital Forensics & Information Security (NFSU) · ISO/IEC 27001
