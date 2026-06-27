# Password Hashing & Shadow File Analysis Lab

## Overview
This lab explores how Linux stores password hashes securely using `/etc/passwd` and `/etc/shadow`. It demonstrates hashing, salting, and password policy enforcement.

## Objectives
- Inspect password and shadow files
- Identify hashing algorithms (SHA‑512)
- Generate hashed passwords using `mkpasswd`
- Understand salts and password aging

## Tools Used
- Kali Linux / Ubuntu
- mkpasswd
- cat, grep, passwd, chage

## Steps Performed
- Viewed `/etc/passwd` and `/etc/shadow`
- Identified hash formats and salts
- Generated new password hashes
- Compared strong vs weak password hash behavior

## What I Learned
- Why passwords are never stored in plaintext
- How salts prevent rainbow table attacks
- How Linux enforces password aging and complexity

