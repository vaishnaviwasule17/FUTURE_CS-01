# FUTURE_CS-01
DVWA (Damn Vulnerable Web Application) – README
Website Tested

DVWA (Damn Vulnerable Web Application)

DVWA is a deliberately insecure PHP/MySQL web application designed for learning web application security, ethical hacking, and penetration testing techniques in a safe environment.

Application: Damn Vulnerable Web Application (DVWA)
Purpose: Security training and vulnerability assessment practice
Environment: Localhost/Lab setup only
Scope
In-Scope Areas

The assessment focused on identifying and demonstrating common web application vulnerabilities available within DVWA, including:

SQL Injection (SQLi)
Blind SQL Injection
Cross-Site Scripting (XSS)
Reflected XSS
Stored XSS
DOM-based XSS
Command Injection
File Inclusion (LFI/RFI)
File Upload Vulnerabilities
Cross-Site Request Forgery (CSRF)
Brute Force Authentication
Weak Session Management
Insecure CAPTCHA Implementation

Out-of-Scope Areas-

Denial-of-Service (DoS) attacks
Attacks against external systems
Network infrastructure testing
Third-party services
Production environments

Tools Used-

Web Application Testing-

Burp Suite
Intercepting requests
Modifying parameters
Replaying HTTP requests

Vulnerability Analysis-

OWASP ZAP
Spidering
Passive scanning
Security assessment

Browser Developer Tools-

Inspecting HTML, JavaScript, and network traffic
Analyzing cookies and session tokens

Database Testing-

SQLMap (for SQL Injection verification)

Command Line Utilities-

cURL
Wget

Password Testing-

Hydra (Brute-force testing)

Environment Setup-

XAMPP / WAMP / LAMP Stack
MySQL Database
PHP Runtime

Testing Methodology-

Information Gathering
Application Mapping
Authentication Testing
Input Validation Testing
Session Management Analysis
Vulnerability Exploitation
Verification and Documentation

##Vulnerability report
[View Vulnerability report]
()


Findings
1. Suspicious Sender Address

The sender domain:

security-alert@account-verification-support.com

appears generic and does not identify any legitimate company, bank, or service provider. Legitimate organizations typically send account-related notifications from their official corporate domains.

Indicator: Suspicious Domain

2. Use of Urgency and Fear

The email contains phrases such as:

"Your account has been temporarily locked."
"Verify your identity immediately."
"Failure to verify within 24 hours may result in permanent suspension."

These statements are designed to create panic and pressure the recipient into acting without verification.

Indicator: Social Engineering

3. Generic Greeting

The message begins with:

Dear Customer

Legitimate organizations generally address customers by name or account identifier.

Indicator: Generic Salutation

4. Verification Request

The email asks the recipient to click a verification link to restore account access.

Attackers commonly use such links to:

Steal credentials
Harvest personal information
Deliver malware

Indicator: Credential Harvesting Attempt

5. Lack of Organization Identification

The email never identifies:

The company name
The affected service
The account involved

This vagueness is common in mass phishing campaigns.

Indicator: Lack of Legitimate Business Context
##Project Report
[View Project Report]
(https://github.com/vaishnaviwasule17/FUTURE_CS-01/blob/9d4cd89ed58f9e4fcf35a1d291f7676d85862d25/Project%20Report.pdf)

