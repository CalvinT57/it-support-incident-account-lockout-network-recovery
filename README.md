# IT Support Incident: Account Lockout & Network Recovery

## Overview
This project simulates a real-world IT support incident involving a user account lockout combined with a secondary network connectivity issue. The objective was to identify root causes, restore user access, and verify full system functionality using proper troubleshooting methodology.

## Environment
- Host OS: macOS
- Guest OS: Windows 11 (Virtual Machine)
- User Accounts: Administrator, jdoe
- Tools Used:
  - Computer Management
  - Local Security Policy
  - Windows Settings
  - Event Viewer

## Incident Summary
A standard user (jdoe) was unable to log in due to repeated failed authentication attempts. During investigation, a secondary issue was identified where the system’s network adapter was disabled, preventing network access after login.

## Root Cause
The primary issue was an account lockout triggered by multiple failed login attempts. A secondary issue was identified where the network adapter was disabled, which would have prevented network access even after successful authentication.

## Resolution
The account lockout condition was cleared using administrative privileges. After authentication was restored, the network adapter was re-enabled to resolve the connectivity issue.

## Verification
The user was able to successfully log in after the account lockout was cleared. Network connectivity was verified by accessing external websites from the user account, confirming full service restoration.

## Ticket Summary
- **User Impact:** User could not log in and had no network access
- **Priority:** High
- **Primary Cause:** Account lockout
- **Secondary Cause:** Network adapter disabled
- **Resolution:** Account unlocked and network adapter re-enabled
- **Status:** Closed – Resolved

## Evidence (Screenshots)
Screenshots supporting each phase of the incident are located in the `screenshots/` directory and include:
- Account lockout confirmation
- Root cause identification
- Network adapter disabled
- Account unlock
- Network adapter re-enabled
- User login verification
- Network connectivity restoration

## Skills Demonstrated
- IT Support troubleshooting
- User account management
- Account lockout remediation
- Network troubleshooting
- Root cause analysis
- Incident documentation
- User verification and incident closure
