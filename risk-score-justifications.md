# Northstar Digital Ltd — Inherent Risk Score Justifications

**Assessment type:** Fictional desktop GRC exercise. These scores are illustrative hypotheses, not measured frequencies or verified findings.

## How to read this document

Likelihood and impact use the 1–5 scale in `risk-methodology.md`. The scores below reproduce `risk-register.csv` and explain the assumptions that would need to be validated. This document does not assign residual risk.

## RISK-001 — Employee account compromise could expose customer records

**Likelihood: 4/5 | Impact: 5/5 | Inherent risk: 20/25 (Critical)**

**Why likelihood 4:** Assumed weak authentication and excessive permissions make account misuse a credible high-exposure scenario. 4 is a provisional judgement, not a measured frequency.

**Why impact 5:** Customer records could be disclosed at scale, causing serious customer harm, investigation costs, business disruption and potentially regulatory consequences. Severe impact is assumed because of the sensitivity and reach of the data.

**What evidence would improve confidence:** Sign-in logs, identity settings, incident history and permission reviews.

## RISK-002 — Theft of an employee laptop could expose confidential customer documents

**Likelihood: 4/5 | Impact: 4/5 | Inherent risk: 16/25 (High)**

**Why likelihood 4:** Regular travel with laptops exposes them to theft or loss; 4 assumes frequent exposure but is not supported by incident history.

**Why impact 4:** Unencrypted local customer documents could be accessible to a thief, causing substantial confidentiality, financial and reputational consequences.

**What evidence would improve confidence:** Asset inventories, control reports, incident history, system configurations and owner interviews.

## RISK-003 — Compromised Microsoft 365 account could expose company emails and documents

**Likelihood: 4/5 | Impact: 4/5 | Inherent risk: 16/25 (High)**

**Why likelihood 4:** Cloud accounts are regularly exposed to attempted compromise, and the scenario assumes weak authentication and insufficient monitoring; 4 remains provisional.

**Why impact 4:** An attacker might access business email and company documents, disrupt work, and expose confidential information.

**What evidence would improve confidence:** Sign-in logs, identity settings, incident history and permission reviews.

## RISK-004 — Ransomware infection could encrypt employee devices and disrupt operations

**Likelihood: 4/5 | Impact: 5/5 | Inherent risk: 20/25 (Critical)**

**Why likelihood 4:** The scenario assumes some unpatched devices and inadequate endpoint protections, increasing the chance of successful malicious code execution.

**Why impact 5:** A disruptive ransomware incident could affect multiple employees, interrupt services and trigger expensive response and recovery activities.

**What evidence would improve confidence:** Asset inventories, control reports, incident history, system configurations and owner interviews.

## RISK-005 — Unauthorised access could expose confidential employee records

**Likelihood: 3/5 | Impact: 4/5 | Inherent risk: 12/25 (High)**

**Why likelihood 3:** Excessive permissions are assumed, but exploitation is less certain than the scenarios scored 4; a moderate 3 is used provisionally.

**Why impact 4:** Exposure of employee records could harm staff, trigger investigation or legal obligations, and cause significant reputational damage.

**What evidence would improve confidence:** Asset inventories, control reports, incident history, system configurations and owner interviews.

## RISK-006 — Employees could disclose confidential information through unapproved generative AI tools

**Likelihood: 4/5 | Impact: 4/5 | Inherent risk: 16/25 (High)**

**Why likelihood 4:** Employees are assumed to use unapproved AI tools without a data-handling policy, creating frequent opportunities for inadvertent disclosure.

**Why impact 4:** Confidential information shared externally could cause contractual, privacy and reputational consequences, potentially across multiple records.

**What evidence would improve confidence:** Asset inventories, control reports, incident history, system configurations and owner interviews.

## RISK-007 — Attackers could compromise the company website through exploitable software weaknesses

**Likelihood: 3/5 | Impact: 4/5 | Inherent risk: 12/25 (High)**

**Why likelihood 3:** Outdated components and limited security testing are assumed, making compromise possible but not established.

**Why impact 4:** Website downtime or manipulation could disrupt enquiries, damage reputation and require remediation expenditure.

**What evidence would improve confidence:** Asset inventories, control reports, incident history, system configurations and owner interviews.

## RISK-008 — Backups could fail during recovery from a cybersecurity incident

**Likelihood: 3/5 | Impact: 5/5 | Inherent risk: 15/25 (High)**

**Why likelihood 3:** Insufficient restore testing is assumed. It is possible, not proven, that restoration would fail when needed.

**Why impact 5:** If backups cannot be restored during a significant incident, prolonged interruption and permanent data loss could have severe business consequences.

**What evidence would improve confidence:** Asset inventories, control reports, incident history, system configurations and owner interviews.

## RISK-009 — Excessive access privileges could enable unauthorised changes or data exposure

**Likelihood: 4/5 | Impact: 4/5 | Inherent risk: 16/25 (High)**

**Why likelihood 4:** The scenario assumes excessive privileged permissions and missing reviews, raising opportunities for misuse or account-compromise escalation.

**Why impact 4:** Privileged misuse could enable major unauthorised changes, broader system access and data exposure.

**What evidence would improve confidence:** Sign-in logs, identity settings, incident history and permission reviews.

## RISK-010 — Phishing could lead to business email compromise and fraudulent payments

**Likelihood: 4/5 | Impact: 4/5 | Inherent risk: 16/25 (High)**

**Why likelihood 4:** The scenario assumes inadequate email security and awareness, while email-based fraud attempts are plausible. Frequency is not measured.

**Why impact 4:** Business email compromise could cause substantial fraudulent payments and confidential-information exposure.

**What evidence would improve confidence:** Sign-in logs, identity settings, incident history and permission reviews.

## Quality and limitations

- Validate scoring against real control implementation, threat exposure, incident history and business impact criteria before using for an actual organisation.
- The high-risk concentration is driven by choosing scenarios with serious possible consequences; this is not a representative estimate of a real SME risk distribution.
- Reassess controls and residual risk only after obtaining reliable evidence of implementation and effectiveness.
- Management would normally agree risk appetite, treatment priorities and ownership.
