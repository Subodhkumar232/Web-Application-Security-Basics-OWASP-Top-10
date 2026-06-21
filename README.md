# Web Application Security Basics (OWASP Top 10)

## Overview

This project focuses on understanding common web application vulnerabilities based on the OWASP Top 10. The task was completed using OWASP Juice Shop, a safe and intentionally vulnerable web application designed for security awareness and learning.

## Objectives

* Understand the OWASP Top 10 security risks.
* Learn how common vulnerabilities occur.
* Study prevention techniques.
* Gain practical awareness through safe demo environments.

## Tools Used

* OWASP Juice Shop
* Web Browser
* GitHub

## Vulnerabilities Studied

### 1. SQL Injection

#### How It Occurs

SQL Injection occurs when user input is inserted into database queries without proper validation or sanitization.

#### Risks

* Unauthorized database access
* Data leakage
* Modification of records

#### Prevention

* Parameterized queries
* Prepared statements
* Input validation

---

### 2. Cross-Site Scripting (XSS)

#### How It Occurs

XSS occurs when user input is displayed on a web page without proper sanitization, allowing malicious scripts to execute.

#### Risks

* Session hijacking
* Cookie theft
* Unauthorized actions

#### Prevention

* Output encoding
* Input validation
* Content Security Policy (CSP)

---

### 3. Broken Authentication

#### How It Occurs

Authentication mechanisms are improperly implemented, allowing attackers to gain unauthorized access.

#### Risks

* Account takeover
* Unauthorized access
* Identity theft

#### Prevention

* Strong password policies
* Multi-factor authentication (MFA)
* Secure session management

## Screenshots Included

1. OWASP Juice Shop Homepage
2. Login Page (Authentication Awareness)
3. Search Functionality (XSS Awareness)
4. OWASP Juice Shop Challenges Dashboard

## Learning Outcomes

* Understanding of OWASP Top 10 vulnerabilities
* Awareness of secure coding practices
* Recognition of common web security risks
* Knowledge of mitigation techniques

## Disclaimer

This project was conducted for educational purposes only. No exploitation activities were performed. Only safe and authorized demo environments were used.
