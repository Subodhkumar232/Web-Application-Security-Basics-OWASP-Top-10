# OWASP Top 10 Practical Awareness Report

Prepared By: Subodh Kumar

Date: 21 June 2026

## Project Title

Web Application Security Basics (OWASP Top 10 – Practical Awareness)

## Objective

The objective of this task was to understand common web application vulnerabilities listed in the OWASP Top 10 and learn how these vulnerabilities can be prevented through secure coding practices.

---

## Introduction

Web applications are widely used across industries and are frequent targets of cyber attacks. OWASP Top 10 is a standard awareness document that identifies the most critical security risks affecting web applications.

This project was completed using OWASP Juice Shop, a safe demonstration platform designed to teach web application security concepts.

---

## Vulnerability 1: SQL Injection

### Description

SQL Injection occurs when attackers insert malicious SQL statements into application inputs that interact with a database.

### How It Occurs

* Unsanitized user input
* Dynamic database queries
* Lack of parameterized statements

### Risks

* Data theft
* Unauthorized access
* Database manipulation

### Prevention

* Prepared statements
* Parameterized queries
* Input validation

---

## Vulnerability 2: Cross-Site Scripting (XSS)

### Description

Cross-Site Scripting allows attackers to inject malicious scripts into web pages viewed by other users.

### How It Occurs

* Improper input validation
* Untrusted user-generated content
* Lack of output encoding

### Risks

* Session hijacking
* Credential theft
* Malicious redirects

### Prevention

* Output encoding
* Input sanitization
* Content Security Policy (CSP)

---

## Vulnerability 3: Broken Authentication

### Description

Broken Authentication occurs when authentication and session management controls are not properly implemented.

### How It Occurs

* Weak passwords
* Poor session handling
* Missing multi-factor authentication

### Risks

* Account compromise
* Unauthorized access
* Identity theft

### Prevention

* Strong password policies
* Multi-factor authentication
* Secure session management

---

## Screenshots Collected

1. OWASP Juice Shop Homepage
2. Login Page (Authentication Awareness)
3. Search Functionality (XSS Awareness)
4. OWASP Juice Shop Challenges Dashboard

---

## Challenges Faced

* The OWASP Juice Shop website was occasionally unavailable and displayed loading errors during the task.
* Some pages took multiple refresh attempts before loading correctly.
* Understanding the differences between various OWASP vulnerabilities required additional research.
* Learning appropriate mitigation techniques for each vulnerability.

---

## Conclusion

This project provided practical awareness of common web application security risks described in the OWASP Top 10. By studying SQL Injection, Cross-Site Scripting, and Broken Authentication, a better understanding of web security principles and secure development practices was achieved. The task highlighted the importance of proper input validation, secure authentication mechanisms, and secure coding standards in modern web applications.
