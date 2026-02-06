# Gmail BCC Alert – Data Leak Prevention

## Overview
Security-focused proof of concept designed to reduce accidental data leakage caused by sending emails with multiple visible recipients (To / Cc).

This project demonstrates how simple detection logic can prevent common human errors that lead to privacy and data protection incidents.

## Security Problem
Sending emails with multiple visible recipients is a frequent source of:
- Privacy violations
- Accidental data exposure
- Compliance issues (GDPR / internal policies)

The risk is caused by human error rather than technical exploitation.

## Solution
The tool detects scenarios where multiple recipients are included in visible fields and alerts the user before the email is sent, prompting safer alternatives such as BCC.

## Key Security Concepts
- Data leakage prevention
- Human error mitigation
- Client-side validation
- Secure-by-design user workflows

## Notes
This project was implemented using AI-assisted development.
The focus is on security logic, validation, and practical risk mitigation rather than full application development.
