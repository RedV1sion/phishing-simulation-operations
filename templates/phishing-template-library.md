# Phishing Template Library

## Enterprise Phishing Campaign Operations  
## KnowBe4 Phishing Simulation Template Catalog

---

# Overview

This document contains a categorized phishing template library used for enterprise phishing simulation campaigns.

The template library supports:

- Phishing simulation planning
- Campaign theme selection
- User risk testing
- Department-specific phishing scenarios
- Security awareness program development
- Remediation-focused phishing exercises

All templates are intended for authorized security awareness training and phishing simulation purposes only.

---

# Environment Overview

| Item | Details |
|---|---|
| Platform | KnowBe4 |
| Email Environment | Microsoft 365 |
| Identity Platform | Microsoft Entra ID |
| User Base | 120+ Users |
| Campaign Type | Security Awareness & Phishing Simulation |
| Use Case | Authorized Internal Training |

---

# Template Classification

Templates are categorized by:

- Attack theme
- Difficulty level
- Target audience
- Primary risk behavior tested
- Recommended campaign frequency

---

# Difficulty Levels

| Level | Description |
|---|---|
| Low | Obvious phishing indicators included |
| Medium | Realistic enterprise phishing message |
| High | Strong branding, urgency, and social engineering |
| Advanced | Targeted scenario with minimal obvious indicators |

---

# Template Categories

| Category | Description |
|---|---|
| Credential Harvesting | Simulates fake login portals and password reset requests |
| IT Notification | Simulates internal IT/security alerts |
| HR Social Engineering | Simulates HR policy, payroll, and benefits messages |
| Financial Scam / BEC | Simulates invoice, payment, and executive fraud attempts |
| Data Breach Alert | Simulates security breach and account compromise warnings |
| Vendor Impersonation | Simulates third-party vendor communication |
| QR Code Phishing | Simulates mobile-based phishing attacks |
| Awareness Reinforcement | Lower-risk templates used for education and reinforcement |

---

# Template Catalog

| Template ID | Template Name | Category | Difficulty | Target Audience | Primary Risk Tested |
|---|---|---|---|---|---|
| PT-001 | Microsoft 365 Password Expiration Alert | Credential Harvesting | Medium | All Users | Credential submission |
| PT-002 | MFA Reset Required | IT Notification | High | Remote Users / All Users | MFA phishing susceptibility |
| PT-003 | Suspicious Login Activity Alert | Data Breach Alert | High | All Users | Urgency-based response |
| PT-004 | Updated PTO Policy Acknowledgment | HR Social Engineering | Medium | All Users | Internal department trust |
| PT-005 | Payroll Direct Deposit Update | HR Social Engineering | High | HR / Finance / All Users | Sensitive information disclosure |
| PT-006 | Urgent Invoice Payment Review | Financial Scam / BEC | High | Finance / Admin Staff | Financial fraud susceptibility |
| PT-007 | Vendor Document Shared With You | Vendor Impersonation | Medium | Admin / Finance | Link click behavior |
| PT-008 | Account Storage Limit Warning | IT Notification | Medium | All Users | Microsoft-themed phishing |
| PT-009 | Data Breach Notification | Data Breach Alert | High | All Users | Fear-based phishing |
| PT-010 | QR Code Security Verification | QR Code Phishing | Advanced | Mobile Users | QR phishing interaction |
| PT-011 | LinkedIn Connection Request | Social Engineering | Medium | All Users | Brand impersonation |
| PT-012 | Package Delivery Failure Notice | Consumer Scam | Low | All Users | Suspicious link recognition |

---

# Credential Harvesting Templates

## PT-001 — Microsoft 365 Password Expiration Alert

| Field | Value |
|---|---|
| Category | Credential Harvesting |
| Difficulty | Medium |
| Target Audience | All Users |
| Landing Page | Simulated Microsoft 365 Login |
| Primary Risk Tested | Credential submission |

### Scenario

Employees receive a simulated Microsoft 365 password expiration notice requiring immediate login verification.

### Subject Example

```text
[Action Required] Your Microsoft 365 Password Will Expire Today
```

### Learning Objective

Teach users to verify Microsoft login pages, inspect URLs, and avoid entering credentials into suspicious portals.

---

## PT-002 — MFA Reset Required

| Field | Value |
|---|---|
| Category | IT Notification |
| Difficulty | High |
| Target Audience | Remote Users / All Users |
| Landing Page | Simulated MFA Verification Portal |
| Primary Risk Tested | MFA phishing susceptibility |

### Scenario

Employees receive a fake MFA reset notification claiming their account requires security verification.

### Subject Example

```text
Microsoft 365 MFA Reset Required Due to Suspicious Login Activity
```

### Learning Objective

Teach users to avoid approving unexpected MFA requests and verify security notifications.

---

# HR Social Engineering Templates

## PT-004 — Updated PTO Policy Acknowledgment

| Field | Value |
|---|---|
| Category | HR Social Engineering |
| Difficulty | Medium |
| Target Audience | All Users |
| Landing Page | Simulated Employee Portal |
| Primary Risk Tested | Internal department trust |

### Scenario

Employees receive a fake HR policy update requiring acknowledgment.

### Subject Example

```text
Updated PTO & Remote Work Policy – Employee Acknowledgment Required
```

### Learning Objective

Teach users to validate HR communications and avoid clicking suspicious employee portal links.

---

## PT-005 — Payroll Direct Deposit Update

| Field | Value |
|---|---|
| Category | HR Social Engineering |
| Difficulty | High |
| Target Audience | HR / Finance / All Users |
| Landing Page | Simulated Payroll Portal |
| Primary Risk Tested | Sensitive information disclosure |

### Scenario

Employees receive a simulated payroll message requesting direct deposit verification.

### Subject Example

```text
Action Required: Confirm Your Direct Deposit Information
```

### Learning Objective

Teach users to verify payroll-related requests through approved channels.

---

# Financial Scam / BEC Templates

## PT-006 — Urgent Invoice Payment Review

| Field | Value |
|---|---|
| Category | Financial Scam / BEC |
| Difficulty | High |
| Target Audience | Finance / Administrative Staff |
| Landing Page | Simulated Vendor Payment Portal |
| Primary Risk Tested | Financial fraud susceptibility |

### Scenario

Finance and administrative staff receive a simulated urgent invoice payment request from a vendor.

### Subject Example

```text
URGENT: Outstanding Invoice Requires Immediate Payment Review
```

### Learning Objective

Teach users to validate invoice requests, vendor identities, and payment changes before taking action.

---

# Data Breach Alert Templates

## PT-003 — Suspicious Login Activity Alert

| Field | Value |
|---|---|
| Category | Data Breach Alert |
| Difficulty | High |
| Target Audience | All Users |
| Landing Page | Simulated Security Verification Portal |
| Primary Risk Tested | Urgency-based response |

### Scenario

Employees receive a simulated account compromise alert requiring immediate password verification.

### Subject Example

```text
[Security Alert] Suspicious Login Activity Detected
```

### Learning Objective

Teach users not to react quickly to fear-based security alerts without verifying legitimacy.

---

## PT-009 — Data Breach Notification

| Field | Value |
|---|---|
| Category | Data Breach Alert |
| Difficulty | High |
| Target Audience | All Users |
| Landing Page | Simulated Security Portal |
| Primary Risk Tested | Fear-based phishing |

### Scenario

Employees receive a fake breach notification requiring immediate account verification.

### Subject Example

```text
Immediate Password Reset Required Following Security Incident
```

### Learning Objective

Teach users to verify security breach communications through trusted internal channels.

---

# Vendor Impersonation Templates

## PT-007 — Vendor Document Shared With You

| Field | Value |
|---|---|
| Category | Vendor Impersonation |
| Difficulty | Medium |
| Target Audience | Administrative / Finance |
| Landing Page | Simulated File Sharing Portal |
| Primary Risk Tested | Link click behavior |

### Scenario

Employees receive a fake vendor document-sharing notification.

### Subject Example

```text
Vendor Document Shared With You for Review
```

### Learning Objective

Teach users to verify vendor communications before opening shared documents or links.

---

# QR Code Phishing Templates

## PT-010 — QR Code Security Verification

| Field | Value |
|---|---|
| Category | QR Code Phishing |
| Difficulty | Advanced |
| Target Audience | Mobile Users / Remote Users |
| Landing Page | Simulated Mobile Login Portal |
| Primary Risk Tested | QR phishing interaction |

### Scenario

Employees receive an email asking them to scan a QR code to complete security verification.

### Subject Example

```text
Scan Required: Complete Mobile Security Verification
```

### Learning Objective

Teach users that QR codes can be used for phishing and should be verified before scanning.

---

# Template Selection Matrix

| Campaign Goal | Recommended Template |
|---|---|
| Test credential harvesting risk | PT-001, PT-002 |
| Test MFA phishing awareness | PT-002 |
| Test HR social engineering | PT-004, PT-005 |
| Test financial fraud risk | PT-006 |
| Test urgency/fear response | PT-003, PT-009 |
| Test vendor impersonation | PT-007 |
| Test mobile phishing awareness | PT-010 |

---

# Recommended Campaign Frequency

| Template Type | Recommended Frequency |
|---|---|
| Credential Harvesting | Monthly |
| IT Notification | Monthly |
| HR Social Engineering | Quarterly |
| Financial Scam / BEC | Quarterly |
| Data Breach Alert | Quarterly |
| Vendor Impersonation | Quarterly |
| QR Code Phishing | Semi-Annually |

---

# Risk-Based Targeting Guidance

| User Group | Recommended Template Types |
|---|---|
| Finance | BEC, invoice scams, vendor impersonation |
| HR | HR social engineering, payroll scams |
| Remote Users | MFA reset, QR phishing, Microsoft login phishing |
| Administrative Staff | Credential harvesting, vendor document scams |
| Executives | BEC, executive impersonation, data breach alerts |
| New Employees | Low-to-medium difficulty awareness templates |

---

# Template Review Process

Before a phishing template is used in a campaign, it should be reviewed for:

- Campaign objective alignment
- Appropriate difficulty level
- Relevance to current threat trends
- Safe and ethical simulation design
- Correct landing page configuration
- Remediation training mapping

---

# Operational Notes

Templates should avoid collecting real credentials or sensitive information.

Credential harvesting simulations must only capture training indicators such as:

- Click activity
- Simulated credential submission
- Reporting behavior
- Training completion status

---

# Metrics Associated With Templates

Each template may be evaluated using:

- Email open rate
- Link click rate
- Credential submission rate
- Attachment open rate
- QR scan rate
- User reporting rate
- Repeat offender trends
- Department risk trends

---

# Technologies Used

- KnowBe4
- Microsoft 365
- Microsoft Entra ID
- Security Awareness Training
- Phishing Simulations
- Campaign Management
- User Risk Analysis

---

# Disclaimer

This project is a simulated enterprise phishing template library created for cybersecurity learning, portfolio demonstration, and security awareness operations practice.

No real employee credentials, sensitive organizational data, or unauthorized phishing activity are involved.
