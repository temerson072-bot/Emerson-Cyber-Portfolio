# Credential Harvesting Lab

## Overview
This lab demonstrates how attackers clone legitimate websites and capture user credentials through malicious POST requests. The goal is to understand how credential harvesting works and how to defend against it.

## Objectives
- Clone a real login page using SET (Social Engineering Toolkit)
- Host the cloned page locally
- Capture submitted usernames and passwords
- Analyze harvested credential logs

## Tools Used
- Kali Linux
- Social Engineering Toolkit (SET)
- Apache2 Web Server
- Browser Developer Tools

## Steps Performed
- Used SET to clone a target login page
- Configured Apache to host the cloned phishing page
- Captured POST request data containing credentials
- Reviewed logs to understand attacker visibility

## What I Learned
- How phishing pages are created and deployed
- How credentials are captured through POST requests
- Why HTTPS, MFA, and user awareness are critical defenses
