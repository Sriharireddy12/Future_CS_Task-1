# Future_CS_Task-1
Future Intern 
Web Application Security Testing – Task 1

This project is part of my Future Interns – Cyber Security Internship (Track Code: CS).
Task 1 focuses on identifying common vulnerabilities in a web application and understanding how these attacks work in real scenarios.

🚀 Task Overview

The goal of this task is to test a sample web application and find security issues like:

SQL Injection (SQLi)

Cross-Site Scripting (XSS)

Cross-Site Request Forgery (CSRF)

Authentication weaknesses

Insecure configurations

This helps in understanding the basics of web application security and penetration testing.

🔧 Tools Used

WebGoat – Vulnerable web application for practice

OWASP ZAP – For scanning, intercepting, and testing traffic

Web Browser (Proxy Configured) – To route traffic through ZAP

🛠 Features / Key Points

Identified SQLi, XSS, and CSRF vulnerabilities

Used ZAP to analyze insecure requests and input fields

Tested login bypass and script injection

Learned how web attacks are performed

Practiced hands-on exploitation in WebGoat

Documented mitigation techniques for each vulnerability

📌 Steps Performed

Set up WebGoat and OWASP ZAP

Configured browser proxy

Tested SQL Injection using ' OR '1'='1 payload

Triggered XSS using <script>alert('XSS')</script>

Explored CSRF attacks

Scanned vulnerabilities using ZAP

Recorded findings and fixes

🛡 Mitigation Summary

SQL Injection: Use prepared statements

XSS: Apply input validation & output encoding

CSRF: Use tokens & SameSite cookies
