Trojan Lab 🐉🔒
Overview

Controlled, educational lab demonstrating hosting and observing a Trojan‑style test artifact in an isolated environment. All artifacts are sanitized and non‑actionable.
Objectives 🎯

    Observe hosting and listener indicators

    Capture console and OS/browser warnings

    Identify detection signals for defenders

Key Observations 🔍

    Server/listener console output is visible even without sessions

    Directory listings can expose hosted filenames

    Unsigned executables trigger OS warnings but rely on user behavior

Detection Signals 🚨

    New HTTP servers or listeners on unusual ports

    Executable files appearing in web‑accessible directories

    Repeated download attempts followed by suspicious process creation

Defensive Recommendations 🛡️

    Tune EDR/AV for unsigned binaries and anomalous processes

    Restrict hosting of executables on general web servers

    Centralize logs and create correlation rules for file creation + listener start

