# PENETRATION-TESTING-TOOLKIT
A TOOLKIT WITH MULTIPLE  MODULES (E.G., PORT SCANNER,  BRUTE-FORCER) FOR PENETRATION  TESTING.<br>
 COMPANY: CODTECH IT SOLUTIONS <br>
 NAME : SHURAIM SHAKEEL BHAT<br>
 INTERN  ID : CT08TPH<br>
 DOMAIN : CYBER SECURITY AND ETHICAL HACKING<br>
 DURATION : 4 WEEKS<br>
 MENTOR : NEELA SANTOSH<br>
 # Penetration Testing Toolkit

## Overview
The **Penetration Testing Toolkit** is a Python-based modular security testing tool designed for ethical hacking and cybersecurity professionals. It includes multiple modules such as a **port scanner** and a **brute-force attack tool** to help identify vulnerabilities in network security and authentication mechanisms.

## Features
- **Port Scanner**: Scans specified ports on a target host to identify open services.
- **Brute Force Login**: Attempts to crack web-based authentication using a username and a list of potential passwords.
- **Password Generator**: Creates possible password combinations using custom character sets and lengths.
- **Modular Structure**: Easily extendable with new penetration testing features.
- **Simple CLI Interface**: Easy-to-use command-line interface for quick security assessments.

## Installation
### Prerequisites
- Python 3.x must be installed.
- Required Python libraries:
  ```bash
  pip install requests
  ```

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/penetration-testing-toolkit.git
   cd penetration-testing-toolkit
   ```
2. Run the script:
   ```bash
   python penetration_testing_toolkit.py
   ```

## Usage
### 1. Port Scanning
To scan for open ports on a target:
```plaintext
Penetration Testing Toolkit
1. Port Scanner
2. Brute Force Login
Select a module (1/2): 1
Enter target IP or domain: example.com
Enter ports to scan (comma-separated): 22,80,443
```
#### Example Output:
```plaintext
[OPEN] Port 22 is open on example.com
[OPEN] Port 80 is open on example.com
[OPEN] Port 443 is open on example.com
```

### 2. Brute Force Login
To attempt a brute-force attack on a login page:
```plaintext
Penetration Testing Toolkit
1. Port Scanner
2. Brute Force Login
Select a module (1/2): 2
Enter login URL: https://example.com/login
Enter username: admin
Enter password list (comma-separated): password123, admin123, qwerty
```
#### Example Output:
```plaintext
[SUCCESS] Password found: admin123
```

## Customization
- Modify `brute_force_login()` to include headers and tokens if required by the target website.
- Add more modules like **Directory Bruteforcing**, **Subdomain Enumeration**, or **SQL Injection Detection**.

## Legal Disclaimer
This tool is intended for ethical hacking and security testing **with permission**. Unauthorized use may violate legal and ethical guidelines.




