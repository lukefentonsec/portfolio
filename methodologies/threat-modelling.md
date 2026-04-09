# Methodology: Threat Modelling

## Purpose
To provide a structured, repeatable approach for identifying threats, misconfigurations, and design weaknesses across applications, identity flows, cloud workloads, and vendor-managed platforms. This methodology supports both proactive design reviews and reactive investigations.

---

## Scope
This methodology applies to:
- application security reviews  
- identity and access management flows  
- cloud and hybrid architectures  
- vendor-managed platforms (e.g., PAM, IDP, SaaS)  
- integration points and trust boundaries  
- internal systems undergoing change or remediation  

---

## High-Level Workflow
1. Preparation  
2. Discovery  
3. Analysis  
4. Validation  
5. Reporting  
6. Remediation  
7. Review & improvement  

---

## Detailed Process

### **1. Preparation**
- gather architecture diagrams, data flows, and system context  
- identify stakeholders (engineering, security, vendors)  
- confirm scope and constraints  
- identify assets, roles, and trust boundaries  
- define success criteria and risk appetite  

### **2. Discovery**
- enumerate components, identities, permissions, and integrations  
- identify entry points, data flows, and privilege boundaries  
- gather telemetry (Sentinel, Defender, Purview)  
- review vendor documentation and configuration baselines  
- form initial hypotheses about potential weaknesses  

### **3. Analysis**
Use structured frameworks such as **STRIDE**, **PASTA**, or hybrid modelling.

Evaluate:
- spoofing and authentication weaknesses  
- tampering or configuration drift  
- repudiation gaps (logging, audit trails)  
- information disclosure risks  
- privilege escalation paths  
- denial-of-service or operational impact  
- vendor platform behaviour vs expected design  

Map attacker paths using:
- logs  
- identity events  
- configuration exports  
- role/permission mappings  
- integration behaviour  

### **4. Validation**
- reproduce or simulate identified weaknesses  
- confirm behaviour with logs, configs, or vendor documentation  
- cross-check with Nessus or other scanning tools  
- validate assumptions with engineering or vendors  
- ensure findings are accurate before escalation  

### **5. Reporting**
- summarise threats and affected components  
- provide clear risk statements  
- include evidence, diagrams, and log excerpts  
- recommend remediation options  
- tailor communication for technical and non-technical audiences  

### **6. Remediation**
- coordinate with internal teams or vendors  
- apply configuration or architectural changes  
- validate that remediation is effective  
- update monitoring, detection rules, or governance controls  

### **7. Review & Improvement**
- identify blind spots or gaps in modelling  
- update documentation and diagrams  
- refine the methodology  
- capture lessons learned  
- feed improvements into future threat models  

---

## Common Pitfalls
- relying on assumptions instead of evidence  
- incomplete enumeration of identities or roles  
- missing trust boundaries or integration points  
- failing to validate vendor behaviour  
- unclear communication or escalation paths  
- modelling only “happy paths” and ignoring failure modes  

---

## References & Notes
- STRIDE  
- PASTA  
- MITRE ATT&CK  
- NIST 800-154  
- vendor documentation  
- internal architecture diagrams  
- related case studies (e.g., access control issues, vendor escalations)
