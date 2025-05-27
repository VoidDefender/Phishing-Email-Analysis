# Task 2 - Phishing Email Analysis | Cyber Security Internship

## Objective:

Analyze a suspicious email to identify phishing indicators such as spoofed addresses, fake URLs, malicious attachments, and failed authentication checks.

---

## Sample Email Overview:

**From:** PayPal Support <support@paypal-secure123.com>  
**To:** you@example.com  
**Subject:** Urgent: Account Suspended – Immediate Action Required  
**Attachment:** Account_Verification.html  
**Suspicious Link:** https://www.paypal.com.verify-login-user-check.com

---

## Email Header Analysis Summary:

**Tool Used:** MxToolbox Email Header Analyzer  
**Sender IP:** 185.244.25.88  
**Return-Path:** hacker@malicious-site.ru  
**SPF Check:** Fail  
**DKIM:** None  
**Relay Server:** unknown123.com  
**Blacklist Status:** IP blacklisted

---

## Phishing Indicators / Observations:

1. Spoofed email domain (paypal-secure123.com).
2. Suspicious and deceptive URL attempting to mimic PayPal.
3. Urgent tone and threat of account suspension.
4. Generic greeting (“Dear Customer”) instead of personalization.
5. Malicious HTML attachment named `Account_Verification.html`.
6. SPF authentication failed.
7. No DKIM signature found.
8. Source IP address listed on blacklist.

---

## Files Included:

- `Phishing-email-sample.md`: Raw phishing email sample.
- `Header-analysis.txt`: Output from email header analysis.
- `Phishing-analysis-report.md`: Detailed breakdown of phishing traits.
- `README.md`: Documentation.

---

## Learning Outcomes:

- Understood how to detect phishing through header analysis and content inspection.
- Learned how attackers spoof domains and disguise links.
- Used MxToolbox to inspect email metadata.
- Improved awareness of how malicious attachments are used in phishing campaigns.
