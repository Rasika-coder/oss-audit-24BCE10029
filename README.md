Open Source Audit Project

Student Information

- Name: Rasika Jain
- Registration Number: 24BCE10029
- Course: Open Source Software
- Chosen Software: Python



Project Overview

This project is an audit of Python as an open-source software. The objective is to understand its origin, licensing model, working in a Linux environment, and its role in the open-source ecosystem.

The project also includes five shell scripts that demonstrate basic Linux command-line operations and automation using Bash scripting.



System Requirements

To run this project, the following environment is required:

- Linux Operating System (Ubuntu/Kali/any distribution)
- Bash Shell
- Installed tools:
  - python3
  - grep
  - awk
  - coreutils



Setup Instructions

Follow the steps below to set up and run the project:

Step 1: Clone the Repository

git clone https://github.com/Rasika-coder/oss-audit-24BCE10029
cd oss-audit-24BCE10029

Step 2: Provide Execute Permission

chmod +x *.sh

Step 3: Verify Environment

python3 --version



How to Run the Scripts

Run each script using the terminal:

./script1_system_identity.sh
./script2_package_inspector.sh
./script3_disk_auditor.sh
./script4_log_analyzer.sh /var/log/syslog error
./script5_manifesto_generator.sh

---

Script Description

Script 1: System Identity Report

Displays system details such as kernel version, logged-in user, uptime, and date/time.

Script 2: FOSS Package Inspector

Checks whether Python is installed and displays package-related information.

Script 3: Disk and Permission Auditor

Analyzes important system directories and shows their disk usage and permissions.

Script 4: Log File Analyzer

Reads a log file and counts how many times a keyword (like "error") appears.

Script 5: Open Source Manifesto Generator

Takes user input and generates a personalized open-source philosophy statement.



Execution Notes

- All scripts are executed using the command line interface
- No graphical interface is required
- Scripts are tested on a Linux system
- Ensure correct file path is given while running Script 4



Submission Details

GitHub Repository Link:
https://github.com/Rasika-coder/oss-audit-24BCE10029
