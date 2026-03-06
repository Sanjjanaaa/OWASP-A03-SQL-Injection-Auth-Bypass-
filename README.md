📌 Project Title


 SQL-INJECTION-AUTHENTICATION-BYPASS


 
📖 Overview
This project demonstrates a manual SQL Injection vulnerability in a login authentication mechanism, resulting in authentication bypass.

The testing was conducted in an authorized lab environment using manual request manipulation.

Mapped to:
OWASP Top 10 – A03: Injection



🛠 Tools Used

Burp Suite (Proxy – Manual Interception)

Browser Developer Tools




🔍 Vulnerability Details

Type: SQL Injection (Boolean-Based)

Location: Login Authentication Form

Impact: Unauthorized Access

Severity: High




🧪 Methodology

Intercepted login POST request using Burp Proxy.

Identified authentication parameters (username & password).

Injected boolean-based SQL payload.

Observed authentication bypass.

Confirmed backend query manipulation.




💥 Impact

Authentication Bypass

Potential privilege escalation

Database exposure risk

Unauthorized session creation




🛡 Remediation

Use parameterized queries

Implement prepared statements

Apply server-side input validation

Avoid detailed SQL error messages

Deploy WAF




📸 Proof of Concept

Screenshots available in /screenshots directory.

⚖️ Ethical Disclaimer

This project was conducted in an authorized testing environment for educational and defensive security purposes only.
