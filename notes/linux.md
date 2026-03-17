\# Linux Basics for Cybersecurity



\## Overview

Linux is one of the most widely used operating systems in cybersecurity, server administration, networking, and penetration testing. Many security tools and enterprise servers run on Linux-based systems.



This document contains basic Linux commands and concepts useful for security operations and system administration.



\---



\## Common Linux Commands



\### pwd

Displays the current working directory.



```bash

pwd

```



\---



\### ls

Lists files and directories.



```bash

ls

ls -la

```



\---



\### cd

Changes the current directory.



```bash

cd Documents

cd ..

```



\---



\### mkdir

Creates a new directory.



```bash

mkdir test-folder

```



\---



\### touch

Creates a new file.



```bash

touch notes.txt

```



\---



\### cp

Copies files and directories.



```bash

cp file.txt backup.txt

```



\---



\### mv

Moves or renames files.



```bash

mv old.txt new.txt

```



\---



\### rm

Removes files or directories.



```bash

rm file.txt

rm -r foldername

```



\---



\### chmod

Changes file permissions.



```bash

chmod 755 script.sh

```



Permission values:

\- 7 = read + write + execute

\- 5 = read + execute

\- 4 = read only



\---



\### sudo

Runs commands with elevated privileges.



```bash

sudo apt update

```



\---



\### grep

Searches for specific text patterns inside files.



```bash

grep "admin" users.txt

```



Useful for log analysis and searching configuration files.



\---



\### ps

Displays currently running processes.



```bash

ps aux

```



\---



\### netstat

Displays network connections and listening ports.



```bash

netstat -an

```



\---



\## Linux in Cybersecurity



Linux is commonly used for:

\- Penetration testing

\- Network analysis

\- SIEM servers

\- Security monitoring

\- Vulnerability assessment

\- Malware analysis



Popular cybersecurity distributions:

\- Kali Linux

\- Parrot OS

\- BlackArch



\---



\## Important Security Concepts



\### File Permissions

Linux uses permission-based access control to restrict file access.



Example:

```bash

\-rwxr-xr-x

```



\---



\### Root User

The root account has full administrative privileges on the system.



\---



\### SSH

Secure Shell (SSH) is used for secure remote access.



```bash

ssh user@ip-address

```



\---



\## Conclusion



Understanding Linux basics is essential for cybersecurity professionals because many enterprise systems, security tools, and cloud environments rely heavily on Linux.

