# FUTURE_CS-01
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

Vulnerability report-
(https://github.com/vaishnaviwasule17/FUTURE_CS-01/blob/9944bab1c43ff47eee4972490ed69302b0e66ba9/Vulnerability%20report.pdf)


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
Email phishing analysis report-
(https://github.com/vaishnaviwasule17/FUTURE_CS-01/blob/9d4cd89ed58f9e4fcf35a1d291f7676d85862d25/Project%20Report.pdf)

# API Security Assessment Project

## Overview

This project demonstrates a security-focused review of a public demo API using a security consultant methodology. The objective was to analyze API design, authentication mechanisms, access controls, response data, and common security risks without attempting to exploit or disrupt any system.

The assessment was conducted against a publicly available test API intended for development and educational purposes. The project focuses on identifying potential weaknesses, evaluating business impact, classifying risk severity, and recommending practical remediation measures.

## Objectives

* Review publicly available API documentation.
* Test API endpoints using Postman or Insomnia.
* Examine authentication and authorization mechanisms.
* Analyze request and response headers.
* Review API response data for potential information exposure.
* Identify common API security risks.
* Classify findings based on risk severity.
* Provide remediation recommendations.
* Document findings in a professional security assessment format.

## Scope

The assessment was limited to publicly documented endpoints and non-intrusive testing techniques. No attempts were made to bypass security controls, gain unauthorized access, exploit vulnerabilities, or impact service availability.

## Methodology

### 1. Documentation Review

* Reviewed API documentation.
* Identified available endpoints and supported HTTP methods.
* Examined authentication requirements and API usage guidelines.

### 2. Endpoint Testing

* Performed requests using Postman/Insomnia.
* Observed request headers, response headers, status codes, and response bodies.
* Verified expected API behavior.

### 3. Security Assessment

Evaluated the API against common security categories:

* Authentication
* Authorization and Access Control
* Data Exposure
* Input Validation
* Error Handling
* Transport Security
* Rate Limiting
* API Inventory and Documentation

### 4. Risk Analysis

Each finding was assigned a severity level:

* Critical
* High
* Medium
* Low
* Informational

Severity ratings considered both technical impact and business risk.

## Key Findings

Examples of security observations include:

* Missing or weak authentication controls.
* Lack of authorization checks.
* Potential excessive data exposure.
* Absence of rate limiting mechanisms.
* Broad CORS configurations.
* Information disclosure through API responses or errors.

## Remediation Approach

For each identified issue, practical recommendations were provided, including:

* Implementing strong authentication.
* Enforcing role-based access controls.
* Applying least-privilege principles.
* Restricting unnecessary data exposure.
* Enabling rate limiting and abuse prevention.
* Improving monitoring and logging.
* Strengthening API security governance.

## Tools Used

* Postman
* Insomnia
* REST APIs
* HTTP Request/Response Analysis
* OWASP API Security Top 10 Reference

## Skills Demonstrated

* API Security Assessment
* Security Risk Analysis
* Technical Documentation
* Vulnerability Classification
* Business Impact Evaluation
* Security Reporting
* REST API Testing
* Secure Design Review

