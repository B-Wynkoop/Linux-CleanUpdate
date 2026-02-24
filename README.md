# Linux Update & Clean Script
## Overview
Made for Linux Debian Distributions (OS-Ubuntu)
 
This script is for people like me, too many times I have input the same 5 update commands daily.
 
 ## Features
 - Updates package list | Prints complete text
 - Installs available package updates from list | Prints complete text
 - Updates available snap packages | Prints complete text
 - Cleans old packages and configurations | Prints complete text
 - Cleans old system packages | Prints complete text
 - Prints "Script Complete" when finished
 - SHA256SUM verification to ensure security for privileged commands

 Each stage of the script is displayed green in the terminal to help view any changes made during the process.

## Usage
```bash
chmod +x update.sh
./update.sh
```
## NOTE:
- Script Requires Sudo Privileges
- SHA256SUM Verification Added

The SHA256SUM file is provided ( update.sh.sha256 ). If changes are made to the script ( update.sh ) you must update the SHA256SUM for script verification, otherwise the user would need to comment the verification block located at the top of the script ( Although this is not recommended ).
