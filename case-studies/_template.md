# Case Study: [Title]

## Summary
A concise overview of the issue, context, and outcome.  
For example: an access control failure, misconfiguration, or vendor‑related issue affecting authentication or privileged access.

---

## Context
- System or platform involved (e.g., PAM solution, identity provider, access gateway)
- Business impact or operational dependency
- Relevant teams or vendors (e.g., internal IT, security partners, Delinea support)
- Tools used during investigation (Sentinel, Defender, Purview, Nessus, vendor logs)

---

## Discovery
Explain how the issue was first identified.

Examples:
- user reports of failed access or unexpected access
- anomalies in authentication logs
- alerts from SIEM/EDR
- vendor platform behaviour not matching expected configuration
- permission drift or role inconsistencies

Include:
- initial indicators  
- hypotheses formed  
- early triage steps  

---

## Technical Analysis
Deep‑dive into the mechanics of the issue.

Examples:
- misconfigured roles or policies
- incorrect mapping between identity provider and vendor platform
- API or integration behaviour not aligning with documentation
- audit logs showing unexpected privilege inheritance
- vendor platform artefacts (session logs, access logs, configuration exports)

Use code blocks for payloads, commands, or artefacts:
