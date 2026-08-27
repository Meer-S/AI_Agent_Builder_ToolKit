# Security Policy

## 🛡️ Supported Versions
We actively maintain and patch the following versions of **AI_Agent_Builder_Toolkit**:

| Version | Supported |
|---------|-----------|
| main    | ✅ |
| dev     | ✅ |
| old branches | ❌ |

---

## 🔐 Reporting a Vulnerability
If you discover a security vulnerability, please follow these steps:

1. **Do not open a public issue.**
2. Email the maintainers directly at: **security@yourdomain.com**
3. Include:
   - Description of the vulnerability
   - Steps to reproduce
   - Impact assessment (data exposure, denial of service, etc.)
   - Suggested mitigation (if available)

We will acknowledge receipt within **72 hours**.

---

## 🧩 Patching Workflow
1. **Triage**  
   - Validate the vulnerability against **MITRE ATT&CK / ATLAS** techniques.  
   - Assign severity (Critical, High, Medium, Low).  

2. **Fix Development**  
   - Create a secure patch branch.  
   - Apply mitigations aligned with **OWASP Top 10** and **LLM Top 10**.  
   - Run regression and security tests.  

3. **Review & Validation**  
   - Peer review by maintainers.  
   - Verify against **Anti-Hallucination Rules** (no speculative fixes).  
   - Ensure compliance with **5 Pillars of Secure AI Apps**:
     - Threat Modeling  
     - Prompt Protection  
     - Data Privacy  
     - Model Integrity  
     - Human Oversight  

4. **Release**  
   - Merge into `main`.  
   - Publish release notes with CVE ID (if applicable).  
   - Notify reporters privately before public disclosure.  

---

## 📖 Responsible Disclosure
We follow **responsible disclosure practices**:
- Vulnerabilities are disclosed **only after a patch is available**.  
- Public advisories will include:
  - CVE ID (if assigned)  
  - Impact summary  
  - Mitigation steps  
- Contributors must not share exploit details until official release.  

---

## 🛡️ Security Validation Checklist
Before merging any patch:
- ✅ No hallucinated or speculative fixes.  
- ✅ All changes traceable to verified vulnerability reports.  
- ✅ Compliance with MITRE ATT&CK / ATLAS mapping.  
- ✅ OWASP Top 10 and LLM Top 10 risks addressed.  
- ✅ Logs and monitoring updated for detection.  

---

## 📚 References
- [MITRE ATT&CK](https://attack.mitre.org/)  
- [MITRE ATLAS](https://atlas.mitre.org/)  
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)  
- [OWASP LLM Top 10](https://owasp.org/www-project-llm-top-10/)  
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)  

---

## 🏁 Final Note
Security is a **shared responsibility**. By following this policy, contributors help ensure that **AI_Agent_Builder_Toolkit** remains secure, resilient, and trustworthy for real-time AI agent development.
