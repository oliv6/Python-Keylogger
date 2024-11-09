# Python Keylogger & Web Phishing Project

## Project Overview
This mini-project is a three-member team's work, aiming to explores two spyware techniques for ethical hacking education: a Python keylogger and a phishing setup using BeEF. This report demonstrates how easily these methods can compromise sensitive information.

### Introduction
This project highlights the risks of spyware, showing how keystrokes and login credentials can be collected from target systems within a controlled ethical hacking environment.

### Setup and Tools
- **Virtual Machine**: Ubuntu 20.04 on VirtualBox
- **Python**: Keylogger script using `pynput` for keystroke logging and SMTP for log email delivery.
- **BeEF**: Hosted on a Linux server for phishing, capturing credentials on a fake login page.

### Scripts Overview
1. **Keylogger Script**: Logs keystrokes with timestamps, saving locally and emailing logs periodically.
2. **Email Sender**: Uses SMTP to send keystroke logs to an email.
3. **BeEF Phishing**: Deploys a fake login page to capture credentials.

### Results
- **Keylogger**: Successfully logs and emails keystrokes.
- **Phishing**: Captures credentials when the target clicks on the phishing link.

### Security Precautions
To protect against similar attacks, users should:
- Use reputable antivirus software with anti-spyware features.
- Avoid unknown links and attachments.
- Keep systems updated.

---

> **Disclaimer**: For educational use only. Unauthorized use of spyware is illegal. Always conduct testing in a permitted environment.
