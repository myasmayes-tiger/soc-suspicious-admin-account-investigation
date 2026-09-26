# SOC Suspicious Administrator Account Investigation

## Project Overview

This project simulates a Security Operations Center investigation of suspicious local account creation and privilege escalation activity on a Windows system.

The investigation used Windows Security event logs to identify when a new account was created, which account performed the action, and when the new account was added to the local Administrators group.

## Environment

- macOS host
- UTM virtualization
- Windows 11 Pro ARM64
- Windows Event Viewer
- Windows Security logs
- Local Security Policy
- Computer Management

## Skills Practiced

- Windows Security log analysis
- Event ID 4720 analysis
- Event ID 4732 analysis
- Account creation monitoring
- Privilege escalation investigation
- Timeline analysis
- Security group monitoring
- SOC documentation

## Investigation

[View Incident #002 — Suspicious Local Administrator Account](incident-002-suspicious-admin-account.md)
