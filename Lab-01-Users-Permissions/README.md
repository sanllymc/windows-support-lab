# Lab 01 – Users and Permissions

## Scenario

A Windows user reports that they cannot access a folder and receives an "Access Denied" message.

## Objective

Create a controlled permissions problem, troubleshoot the issue, identify the root cause, apply the appropriate fix, and verify access.

## Environment

- Windows 11
- Local Windows user account
- Command Prompt
- PowerShell
- NTFS permissions
- `net user`
- `icacls`

---

## Step 1 – Create a Test User

A local Windows user named `LabUser` was created for testing.

### Command

```cmd
net user LabUser * /add
