# Linux Update Script
## Overview

Make updating debian linux systems easier with a single command that updates and cleans old system files as well as leftover configuration files!

This script is for people like me, too many times I have input the same 5 update commands daily.
 
 ## Features
 - Updates package list | Prints complete text
 - Installs available package updates from list | Prints complete text
 - Updates available snap packages | Prints complete text
 - Updates local & system flatpaks | Prints complete text
 - Cleans old packages and configurations | Prints complete text
 - Cleans old system packages | It will not clean important system files | Prints complete text
 - Prints "Script Complete" when finished
 - SHA256SUM verification to ensure security for privileged commands

 Each stage of the script is displayed green in the terminal to help view any changes made during the process.

## Usage
```bash
chmod +x update.sh
```
```bash
sha256sum update.sh > update.sh.sha256
```
```bash
./update.sh
```
## NOTE:
- Debian Distro Required ( Ubuntu, Debian, Kali, etc. )
- Script Requires Sudo Privileges
- SHA256SUM Verification Added

The SHA256SUM command to create the verification file is provided ( sha256sum update.sh > update.sh.sha256 ). If local changes are made to the script ( update.sh ) you must update the SHA256SUM for script verification, otherwise the user would need to comment the verification block located at the top of the script to prevent error ( Not Recommended ).
