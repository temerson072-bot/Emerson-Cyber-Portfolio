# Trojan Lab 🐉🔒

## Overview
This controlled, educational lab demonstrates creating, hosting, and observing a Trojan‑style test artifact in an isolated environment for defensive learning. All artifacts are sanitized and non‑actionable.

## Objectives 🎯
- Observe how a test artifact is generated and hosted in a lab VM.  
- Capture console and server indicators without establishing real sessions.  
- Record user‑facing OS/browser warnings and human factors.  
- Identify high‑value detection signals defenders can use.

## Tools Used 🧰
- Kali Linux (isolated lab VM)  
- Metasploit Framework (for simulation/observation only)  
- Local web server (for hosting demonstration artifact)  
- Browser/OS dialogs (to capture user warnings)

## High‑level Steps Performed (non‑actionable) 📝
- Generated a sanitized test artifact inside an isolated VM and recorded console output.  
- Hosted the artifact on a local web directory and captured the directory index screenshot.  
- Launched a handler in the lab to observe listener/server messages (no sessions created).  
- Accessed the hosted file from a test client to capture the unsigned‑executable warning dialog.  
- Redacted all sensitive values and exported only sanitized screenshots for documentation.

## Key Observations 🔍
- Console output shows server/listener status and file creation events even when no session is established.  
- Directory listings can expose hosted filenames and make artifacts discoverable.  
- Unsigned executables trigger OS warnings that help protect users but depend on user behavior.  
- Even failed exploits produce network and file artifacts useful for detection and forensics.

## Detection Signals to Monitor 🚨
- New or unexpected HTTP servers or listeners on unusual ports.  
- Creation of executable files in web‑accessible directories.  
- Unusual SMB/file‑share activity or new anonymous shares.  
- Repeated serve/download attempts followed by suspicious process creation.  
- EDR/AV alerts for unsigned binaries or anomalous process chains.

## Defensive Recommendations 🛡️
- **Endpoint protection:** Tune EDR/AV to detect unsigned executables and suspicious process behavior.  
- **Network controls:** Restrict hosting of executables on general web servers; alert on new HTTP servers.  
- **User protection:** Enforce application whitelisting and train users to decline unsigned binaries.  
- **Logging & correlation:** Centralize web/host/EDR logs and create correlation rules for file creation + listener start + outbound callbacks.  
- **Containment:** Isolate affected hosts and preserve sanitized evidence; follow an IR playbook.

## What I Learned / Takeaway ✅
- Artifacts around hosting and handlers are often as valuable as a successful session for detection.  
- Human factors (security dialogs) matter but must be backed by technical controls.  
- Sanitized documentation of these artifacts demonstrates defensive thinking and safe lab practices.

## Safety Note ⚠️
This README intentionally omits commands, payloads, and reproduction steps. No runnable payloads or step‑by‑step attack instructions are included. All screenshots and artifacts are redacted and non‑actionable.
