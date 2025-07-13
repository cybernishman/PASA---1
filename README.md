# PASA---1
No-code security alert system built with Microsoft Power Automate Desktop. Monitors logs, alerts users, and responds to threats.
# No-Code Security Event Detection & Response using Power Automate Desktop

## Saturday Afternoon Project 🚀

This project demonstrates how to use Microsoft Power Automate Desktop (PAD) to automate basic security event detection, alerting, and response—all without writing code.

### Features
- Monitors a log file for failed login attempts
- Displays an on-screen alert
- Logs incidents to an alert log file
- (Optional) Locks the workstation if a suspicious event is detected

### How to Recreate This Flow in Power Automate Desktop

1. **Read text from file:** Reads the security_log.txt contents.
2. **Split text:** Splits by new line, output as TextList.
3. **For each:** Iterates over TextList.
4. **If:** Checks if CurrentItem contains "LOGIN_FAILED".
    - If true:
        - Display message: Alert popup.
        - Append line to text: Add to Result.
        - Write text to file: Log alert in alert_log.txt.
        - Run application: Lock workstation (optional).


### Real-World Use Cases
- Small business or home PC security automation
- Hands-on learning for IT/cybersecurity beginners
- Lightweight SOC for SMBs

### Files Included
- Project Report (PDF)
- Screenshots of the PAD flow
- Sample log file

> Power Automate Desktop doesn’t support native export/import for local flows. This repo is fully documented so anyone can rebuild it!

---
*Built as a hands-on weekend project. Connect with me on [LinkedIn](YOUR-LINKEDIN-PROFILE](https://www.linkedin.com/in/manish-pulluru-918507196/)) for questions or feedback!*

