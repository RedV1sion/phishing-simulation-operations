# Phishing Reporting Guide

## Enterprise Security Awareness Program
## Suspicious Email Reporting Procedures

---

# Overview

This guide provides employees with procedures for identifying and reporting suspicious emails, phishing attempts, credential harvesting attacks, and other malicious communications within the enterprise environment.

Prompt reporting helps reduce organizational risk and allows the Security Operations Team to rapidly investigate and contain phishing-related threats.

---

# Environment Overview

| Item | Details |
|---|---|
| Email Platform | Microsoft 365 |
| Security Awareness Platform | KnowBe4 |
| SIEM Platform | Microsoft Sentinel |
| Identity Platform | Microsoft Entra ID |
| Environment Type | Enterprise Hybrid Workforce |

---

# What Is Phishing?

Phishing is a social engineering attack where attackers attempt to trick users into:

- Revealing passwords or MFA codes
- Clicking malicious links
- Opening malware attachments
- Sending sensitive information
- Approving fraudulent payments
- Installing malicious software

Attackers often impersonate:

- Microsoft 365
- Internal IT departments
- Human Resources
- Executives
- Vendors
- Financial institutions

---

# Common Phishing Indicators

Employees should be cautious of emails containing:

| Indicator | Example |
|---|---|
| Urgent requests | "Immediate action required" |
| Credential requests | Password or MFA verification |
| Suspicious links | Misspelled or unusual URLs |
| Unexpected attachments | ZIP, HTML, or executable files |
| Financial requests | Invoice or wire transfer requests |
| Security alerts | Fake account compromise notices |
| External impersonation | Fake Microsoft or vendor branding |

---

# High-Risk Phishing Themes

Common phishing attack themes include:

- Password expiration notices
- MFA reset notifications
- Security breach alerts
- Payroll updates
- Vendor payment requests
- Invoice scams
- Package delivery notifications
- HR policy updates

---

# Examples of Suspicious Emails

## Example 1 — Credential Harvesting

```text
Subject: Your Microsoft 365 Password Will Expire Today
```

Potential risks:
- Fake login page
- Credential theft
- MFA phishing

---

## Example 2 — Financial Scam

```text
Subject: URGENT: Outstanding Invoice Requires Payment
```

Potential risks:
- Business Email Compromise (BEC)
- Fraudulent payment requests
- Vendor impersonation

---

## Example 3 — Security Alert Scam

```text
Subject: Suspicious Login Activity Detected
```

Potential risks:
- Fear-based phishing
- Fake security notifications
- Credential harvesting

---

# How To Report Suspicious Emails

Employees should immediately report suspicious emails using one of the following methods:

---

# Method 1 — Outlook Phishing Report Button

1. Open the suspicious email
2. Click the phishing reporting button in Outlook
3. Submit the report
4. Do not interact with links or attachments

---

# Method 2 — Forward to Security Team

Forward suspicious emails to:

```text
security@company-example.com
```

Include:
- Original email
- Screenshots if applicable
- Description of interaction (if any)

---

# Method 3 — Contact IT / Security Operations

If immediate assistance is needed:

- Contact the IT Help Desk
- Call the Security Operations Team
- Open a security incident ticket

---

# What Employees Should NOT Do

Do NOT:

- Enter credentials into suspicious websites
- Approve unexpected MFA prompts
- Open suspicious attachments
- Reply to suspicious senders
- Delete suspicious emails before reporting
- Forward phishing emails to coworkers

---

# If You Clicked a Suspicious Link

If you clicked a suspicious link:

1. Disconnect from suspicious websites immediately
2. Report the incident to Security Operations
3. Change your password immediately
4. Notify IT if credentials were submitted
5. Monitor for suspicious account activity

---

# If You Entered Credentials

If credentials were entered into a suspicious website:

1. Change your password immediately
2. Contact the Security Operations Team
3. Re-register MFA if instructed
4. Review account activity
5. Follow all containment instructions from IT

---

# Phishing Reporting Workflow

```text
User Receives Suspicious Email
            ↓
User Reports Email
            ↓
Security Operations Performs Triage
            ↓
Threat Indicators Identified
            ↓
Containment Actions Initiated
            ↓
Affected Users Notified
            ↓
Remediation & Awareness Training Assigned
```

---

# Security Operations Response Activities

The Security Operations Team may perform:

- Email header analysis
- IOC identification
- Malicious domain blocking
- Microsoft 365 investigation
- Endpoint analysis
- Credential compromise review
- User remediation assignment

---

# Common Security Team Actions

| Action | Purpose |
|---|---|
| Password reset | Prevent unauthorized access |
| MFA session revocation | Block active attacker sessions |
| Email removal | Remove phishing emails organization-wide |
| IOC blocking | Prevent future attacks |
| Endpoint investigation | Identify malware or compromise |

---

# Importance of Reporting

Rapid phishing reporting helps:

- Reduce credential compromise risk
- Prevent malware infections
- Improve organizational visibility
- Protect sensitive organizational data
- Improve enterprise security posture

---

# Reporting Metrics Tracked

The organization tracks:

- User reporting rate
- Reporting response time
- Phishing click rate
- Credential submission rate
- Repeat offender trends
- Department-specific phishing trends

---

# Security Best Practices

Employees are encouraged to:

- Verify sender legitimacy
- Hover over links before clicking
- Use MFA whenever possible
- Report suspicious emails immediately
- Contact IT if unsure
- Avoid urgency-driven decisions

---

# Operational Challenges Addressed

The phishing reporting process addresses:

- Hybrid workforce phishing exposure
- Microsoft 365 phishing attacks
- Credential harvesting threats
- Business Email Compromise (BEC)
- Social engineering attacks
- Remote workforce security risks

---

# Technologies Referenced

- Microsoft 365
- Microsoft Entra ID
- Microsoft Sentinel
- KnowBe4
- MFA Security
- Security Awareness Training

---

# Conclusion

Prompt phishing reporting is a critical component of enterprise cybersecurity operations and helps reduce organizational phishing risk through rapid investigation, containment, and remediation.

This guide supports realistic enterprise phishing reporting and security awareness practices commonly used within modern enterprise environments.

---

# Disclaimer

This project is a simulated enterprise phishing reporting and security awareness guide created for cybersecurity learning, portfolio demonstration, and security operations practice.

No real employee data or organizational information were used.
