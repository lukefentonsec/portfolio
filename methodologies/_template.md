# Methodology: [Title]

## Purpose
Explain the goal of this methodology.  
Examples:
- to provide a repeatable process for threat modelling  
- to standardise enumeration steps  
- to ensure consistent incident response triage  
- to guide vendor engagement and escalation  

Keep this section high‑level and outcome‑focused.

---

## Scope
Define where this methodology applies.

Examples:
- cloud workloads  
- identity and access management  
- application security reviews  
- incident response workflows  
- vendor‑managed platforms  
- internal investigations  

---

## High‑Level Workflow
A quick overview of the major phases.

Example structure:
1. Preparation  
2. Discovery  
3. Analysis  
4. Validation  
5. Reporting  
6. Remediation  
7. Review & improvement  

This gives the reader a mental map before diving into detail.

---

## Detailed Process

Break down each phase with clear, actionable steps.

### **1. Preparation**
- gather context  
- identify stakeholders  
- confirm scope and constraints  
- collect relevant logs, configs, or architecture diagrams  
- define success criteria  

### **2. Discovery**
- enumerate assets, roles, permissions, or components  
- identify trust boundaries  
- gather telemetry (Sentinel, Defender, Purview, Nessus)  
- validate assumptions  
- form initial hypotheses  

### **3. Analysis**
- correlate signals  
- identify misconfigurations, vulnerabilities, or design flaws  
- map attacker paths or failure points  
- assess likelihood and impact  
- document evidence  

### **4. Validation**
- reproduce findings where appropriate  
- confirm behaviour with logs, configs, or vendor documentation  
- cross‑check with other tools or data sources  
- ensure accuracy before escalation  

### **5. Reporting**
- summarise findings  
- provide clear risk statements  
- include evidence and supporting artefacts  
- recommend remediation options  
- tailor communication to technical and non‑technical audiences  

### **6. Remediation**
- coordinate with internal teams or vendors  
- apply configuration changes or fixes  
- validate that remediation is effective  
- update monitoring or detection rules  

### **7. Review & Improvement**
- identify blind spots  
- update documentation  
- refine the methodology  
- capture lessons learned  
- feed improvements into future work  

---

## Common Pitfalls
List typical mistakes or failure points relevant to this methodology.

Examples:
- relying on assumptions instead of evidence  
- incomplete enumeration  
- missing identity or role mappings  
- failing to validate vendor behaviour  
- unclear communication or escalation paths  

---

## References & Notes
Include:
- vendor documentation  
- internal standards  
- CREST guidance  
- relevant frameworks (STRIDE, PASTA, MITRE ATT&CK, NIST)  
- links to related case studies or assets  

This section keeps the methodology grounded and traceable.
