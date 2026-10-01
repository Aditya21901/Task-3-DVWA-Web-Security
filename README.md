# Task-3-DVWA-Web-Security
Task 3: Practical web application security testing using DVWA, covering SQL Injection, XSS, CSRF, and File Inclusion (LFI/RFI).
# Task 3 — Web Application Security Testing Using DVWA

## Overview

This project documents practical web application security testing performed using **Damn Vulnerable Web Application (DVWA)** in a controlled local lab environment.

## Objective

To understand and demonstrate common web application vulnerabilities and learn their security impact and mitigation techniques.

## Vulnerabilities Tested

### 1. SQL Injection

Tested SQL injection vulnerabilities through the DVWA SQL Injection module.

**Impact:** Unauthorized database queries and potential data disclosure.

### 2. Cross-Site Scripting (XSS)

Tested reflected and stored XSS using controlled payloads.

**Impact:** Execution of attacker-controlled scripts in a user's browser.

### 3. Cross-Site Request Forgery (CSRF)

Tested whether sensitive actions could be triggered without proper request validation.

**Impact:** Unintended actions performed using an authenticated user's session.

### 4. File Inclusion — LFI/RFI

Studied local and remote file inclusion vulnerabilities using the DVWA File Inclusion module.

**Impact:** Unauthorized file access or inclusion when insecure configurations are present.

## Lab Environment

* Kali Linux
* Apache Web Server
* MariaDB
* DVWA
* Firefox Browser

## Security Level

Testing was performed in the controlled DVWA laboratory environment, primarily using the **Low** security level to understand vulnerable behavior.

## Screenshots

Screenshots demonstrating the individual tests are available in the `screenshots/` directory.

## Learning Outcomes

* Understanding common web application vulnerabilities
* Practicing vulnerability identification in a legal lab environment
* Understanding the importance of input validation
* Learning basic web application security controls
* Documenting security testing results

## Disclaimer

This project was performed only against a deliberately vulnerable application in a controlled local laboratory environment. The techniques should not be used against systems without authorization.

## Conclusion

The DVWA exercises provided practical experience with common web application vulnerabilities and demonstrated why secure input handling, authentication controls, request validation, and secure configuration are important.
