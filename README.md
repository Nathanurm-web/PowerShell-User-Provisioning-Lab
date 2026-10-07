# PowerShell User Provisioning Lab

## Overview

This project demonstrates basic Windows administration using PowerShell. I created local users and security groups, assigned users to groups, and generated a CSV report for auditing and documentation purposes.

## Tasks Completed

- Created local user accounts
- Created department security groups
- Added users to groups
- Verified user and group creation
- Exported user data to CSV

## Technologies Used

- Windows 11
- PowerShell
- Local User & Group Management

## Key Commands

### Create Users

```powershell
New-LocalUser
```

### Create Groups

```powershell
New-LocalGroup
```

### Add Users to Groups

```powershell
Add-LocalGroupMember
```

### Export User Report

```powershell
Get-LocalUser |
Select-Object Name, Enabled |
Export-Csv C:\users-report.csv -NoTypeInformation
```

## Skills Demonstrated

- PowerShell Scripting
- User Provisioning
- Group Administration
- Access Control
- Windows System Administration
- Reporting & Documentation
