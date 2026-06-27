# Rainbow Table Generation & Cracking Lab

## Overview
This lab demonstrates how rainbow tables are generated, sorted, and used to crack weak password hashes.

## Objectives
- Generate rainbow tables using `rtgen`
- Sort tables using `rtsort`
- Crack MD5 hashes using `rcrack`
- Compare cracking speed with and without salts

## Tools Used
- RainbowCrack Suite (rtgen, rtsort, rcrack)
- MD5 hashing utilities

## Steps Performed
- Generated MD5 rainbow tables
- Sorted tables for faster lookup
- Attempted cracking sample hashes
- Observed limitations when salts are present

## What I Learned
- How rainbow tables drastically speed up cracking
- Why modern systems use salted hashing
- Why MD5 is insecure for password storage
