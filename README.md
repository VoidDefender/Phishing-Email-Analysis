# Task 2 - Phishing Email Analysis | Cyber Security Internship

## Files Included:

- phishing-email-sample.md: The sample phishing email used for analysis.
- Analysis/phishing-analysis-report.md: Detailed breakdown of phishing indicators.
- Analysis/summary.md: Brief summary of objectives and tool usage.
- MxToolbox/header-analysis.txt: Raw header analysis results from MxToolbox.
- README.md: Documentation and explanation of the analysis process.

---

## Objective:

Analyze a suspicious email to detect phishing characteristics and understand common techniques used by attackers. This helps build awareness of social engineering tactics and strengthens email threat detection skills.

---

## Tools Used:

- Email client or text viewer
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

---

## Sample Email Overview:

**Subject:** Urgent: Account Suspended – Immediate Action Required  
**From:** PayPal Support <support@paypal-secure123.com>  
**Attachment:** Account_Verification.html  
**Suspicious Link:** [https://www.paypal.com.verify-login-user-check.com](https://www.paypal.com.verify-login-user-check.com)

---

## Email Header Scan Summary:

- **Return-Path:** hacker@malicious-site.ru  
- **Sender IP:** 185.244.25.88 (Blacklisted)  
- **SPF Check:** Failed (does not match PayPal domain)  
- **DKIM:** None  
- **Relay:** unknown123.com  
- **SPF/DKIM Verdict:** Fail

---

## Phishing Indicators:

1. Spoofed email address using a fake PayPal domain.
2. Mismatched and suspicious link URL.
3. Use of urgency and threats (“Account suspended”, “Immediate Action Required”).
4. Suspicious attachment with potential malicious content.
5. No personalization — addressed as “Dear Customer”.
6. SPF and DKIM authentication failed.
7. Blacklisted source IP and domain.

---

## Security Insights:

- **Fake domains** are often used to mimic trusted organizations.
- **Urgency and fear tactics** are common methods used to trick users.
- **Attachments** in phishing emails often include malicious code or credential harvesting forms.
- **Email header analysis** is a critical skill in cybersecurity defense.

---

## Learning Outcomes:

- Learned how to identify phishing tactics in emails.
- Practiced using MxToolbox for analyzing email headers.
- Gained insight into how attackers structure phishing attempts.
- Understood the importance of domain verification (SPF/DKIM) in email authenticity.

---
