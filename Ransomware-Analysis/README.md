# Ransomware Analysis Lab

## Overview
This lab analyzes WannaCry ransomware sample files in a safe environment. No malware was executed — only static analysis was performed.

## Objectives
- Inspect WannaCry sample files
- Identify MD5 and SHA‑256 hashes
- Review ZIP payload structure
- Understand ransomware kill chain behavior

## Tools Used
- Kali Linux
- Hashing tools (md5sum, sha256sum)
- unzip / file analysis utilities

## Steps Performed
- Extracted ransomware sample ZIP
- Calculated file hashes
- Identified suspicious executables and DLLs
- Studied ransomware behavior from public reports

## What I Learned
- How ransomware packages are structured
- How hashing verifies malware integrity
- Why backups, segmentation, and patching are critical defenses
