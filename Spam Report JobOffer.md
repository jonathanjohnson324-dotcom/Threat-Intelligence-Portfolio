REPORT: 01 <br/>
DATE: Feb 20, 2026  <br/>
PRIORITY: Medium  <br/>
SENSITIVITY: Standard  <br/><br/><br/>

# Incident Report Phishing Email Impersonation

### 1. Intelligence Assessment
**Date:** February 17, 2026
**Threat Actor:** Steven Lucky (Impersonating Ciena Telecommunications)
**Vector:** Phishing Email
**Confidence Level:** High

**Summary:**
I assess with high confidence that this email is a phishing attempt designed to engage users through a third-party application (Microsoft Teams) to likely harvest personal information or credentials. The email impersonates a legitimate company but originates from a personal Gmail account.

---

### 2. Evidence (Delivery Stage)

> **Screenshot of Phishing Email:**
[Threat Intelligence Portfolio Email.pdf](https://github.com/user-attachments/files/25374791/Threat.Intelligence.Portfolio.Email.pdf)


---

### 3. Technical Indicators of Compromise (IOCs)

| Type | Value |
| :--- | :--- |
| **Sender Email** | `stevenlucky632@gmail.com` |
| **Subject** | "Job offer" |
| **Malicious URL** | `https://teams.live.com/l/invite/FBAlstrDxlluT-digY?v=g1` |
| **Impersonated Entity** | Ciena Telecommunications |

---

### 4. Technical Analysis
* **Filter Bypass:** The email originated from a legitimate Gmail server (`gmail.com` to `gmail.com`). Therefore, SPF, DKIM, and DMARC checks passed successfully. This highlights the limitation of relying solely on technical email filters for threats sent from personal email providers.
* **Social Engineering:** The message uses high-pressure language ("immediate hire position") and financial incentives ($35.50/hr) to compel the user to act quickly without verifying the legitimacy of the sender.

---

### 5. Recommendations
* **User Awareness:** Instruct users to immediately delete the email and **do not** interact with the link.
* **Verification:** Verify all job offers directly through the official company career portal, not via personal email outreach.
* **Technical Mitigation:** Block `stevenlucky632@gmail.com` at the organizational email gateway.

---

### Appendix
Full email headers are available upon request for forensic analysis.



