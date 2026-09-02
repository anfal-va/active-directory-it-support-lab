# Active Directory & IT Support Home Lab

## Overview

I built this home lab to practice common L1 IT Support and Desktop Support tasks in a Windows domain environment.

Using Windows Server 2019 and a Windows 11 client in Oracle VirtualBox, I configured and tested Active Directory users, shared folder permissions, account management, and domain access.

## Lab Setup

- Oracle VirtualBox
- Windows Server 2019
- Windows 11
- Active Directory Domain Services
- Domain: `corp.local`

## What I Configured and Tested

- Created HR, IT, and Sales Organizational Units (OUs)
- Created and managed domain user accounts
- Joined a Windows 11 client to the domain
- Configured shared folders and NTFS permissions
- Tested authorized and unauthorized folder access
- Tested account lockout and account unlock
- Reset a user password and tested **User must change password at next logon**
- Created a new user account as a basic onboarding task

## Screenshots

### Lab Environment

![Oracle VirtualBox Lab Environment](Lab_Environment_1.png)

### Active Directory Structure

![Active Directory Structure](AD_Structure_1.png)

![HR Organizational Unit](AD_Structure_2.png)

![IT Organizational Unit](AD_Structure_3.png)

![Sales Organizational Unit](AD_Structure_4.png)

### Domain Join

![Windows 11 Domain Join](./Domain_Join_1.png)

### NTFS Permissions

![NTFS Permissions](NTFS_Permissions_1.png)

### File Access Testing

**1. John Smith logged in as a domain user**

![John Smith Domain Login](File_Access_Testing_1.png)

**2. Authorized access to the IT shared folder**

![Authorized IT Folder Access](File_Access_Testing_2.png)

**3. Unauthorized access to the HR shared folder**

![HR Folder Access Denied](File_Access_Testing_3.png)

### Account Lockout and Unlock

![Account Lockout](Account_Lockout_1.png)

![Account Unlock](Account_Lockout_2.png)

![Account Access Restored](Account_Lockout_3.png)

### Password Reset

![Password Reset in Active Directory](Password_Reset_1.png)

![User Forced to Change Password](Password_Reset_2.png)

### User Onboarding

![New User Account Creation](User_Onboarding_1.png)

![New User Account Configuration](User_Onboarding_2.png)

## Skills Practiced

- Active Directory user and OU management
- Windows domain joining
- NTFS permissions
- Shared folder access
- Basic access troubleshooting
- Account lockout and unlock
- Password resets
- Basic user onboarding
