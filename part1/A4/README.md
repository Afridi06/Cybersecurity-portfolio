# A4: Discover a Vulnerable Website

## Overview
This activity explores a vulnerable website example to understand common web security issues and how attackers can exploit them.

## Vulnerability Identified: SQL Injection

### Description
- SQL Injection is a vulnerability where an attacker can manipulate a website's database query
- It occurs when user input is not properly validated or sanitized
- Attackers can insert malicious SQL code into input fields such as login forms


## Example Scenario

- A login form asks for username and password
- Instead of entering normal input an attacker enters SQL code such as:

' OR '1'='1

- This can trick the system into granting access without valid credentials


## Impact of the Vulnerability

- Unauthorized access to user accounts
- Exposure of sensitive data such as usernames and passwords
- Potential modification or deletion of database information

Security Concept: Input Validation and Database Security

Evidence:
(To be added later)


## Why This Happens

- Lack of input validation
- Poor coding practices
- Direct use of user input in database queries

## Prevention Methods

### 1. Input Validation
- Ensure all user inputs are properly checked

### 2. Use of Prepared Statements
- Prevents execution of malicious SQL code

### 3. Parameterized Queries
- Separates user input from SQL commands

### 4. Web Application Firewalls
- Detects and blocks malicious requests


## Reflection
This activity shows how simple vulnerabilities like SQL Injection can lead to serious security breaches. Proper coding practices and validation are essential to prevent such attacks.

## Conclusion
Understanding web vulnerabilities helps developers build secure systems and protect user data from cyber attacks.
