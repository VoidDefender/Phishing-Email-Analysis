# Header Analysis Summary (From MxToolbox)

###Key Findings:

## Spoofed "From" Address

From: PayPal Support support@paypal-secure123.com

Not a real PayPal domain.

Created to trick users with a lookalike name.



## Fake Return-Path

Return-Path: hacker@malicious-site.ru

Clearly malicious and unrelated to PayPal.

A strong indicator of spoofing or email redirection.



## Suspicious Source IP

Received From: unknown123.com (185.244.25.88)

Not a PayPal mail server.

May be from a blacklisted VPS host.



## SPF Failure

Received-SPF: Fail (does not match PayPal’s domain)

Shows the sending server is not authorized to send mail on behalf of PayPal.

Used to prevent domain spoofing—this failed.



## Missing DKIM Signature

DKIM-Signature: None

DKIM helps verify if the message was altered.

Missing DKIM means it’s not a verified sender.


---

## Conclusion:

MxToolbox reveals that this email is not coming from a legitimate PayPal source:

It fails SPF, has no DKIM, and spoofs the sender address.

The email came from a suspicious IP with a fake domain.


These are technical proofs confirming that this email is phishing
