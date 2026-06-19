# Active Directory Help Desk Lab

## Overview

This project simulates a small Windows Active Directory environment used for help desk and junior system administration practice. The lab includes a Windows Server domain controller, organizational units, user accounts, security groups, domain-joined client testing, password reset practice, and shared folder permission validation.

The goal of this lab was to practice common help desk and entry-level IT administration tasks in a realistic Windows domain environment.

## Lab Environment

- Windows Server domain controller
- Windows client workstation
- Active Directory Domain Services
- Active Directory Users and Computers
- Organizational Units
- Domain user accounts
- Security groups
- Shared folders and permissions

## Network / Domain Topology

![Active Directory Lab Topology](network-diagram/ad-lab-topology.png)

## Key Tasks Completed

- Installed and configured Active Directory Domain Services
- Promoted Windows Server to a domain controller
- Created organizational units for departments
- Created domain user accounts
- Created security groups for access control
- Added users to appropriate groups
- Joined a Windows client to the domain
- Tested domain user login
- Practiced password reset workflow
- Configured shared folder access using group-based permissions
- Validated access from a domain-joined workstation

## Active Directory Structure

Example structure used in the lab:

| OU / Department | Purpose |
|---|---|
| IT | Technical/admin users |
| HR | Human Resources users |
| Sales | Sales department users |
| Accounting | Accounting department users |
| Disabled Users | Deactivated account storage/testing |
| Security Groups | Group-based permission management |

## Validation Screenshots

### Domain Controller

![Domain Controller](screenshots/domain-controller.png)

### Organizational Unit Structure

![OU Structure](screenshots/ou-structure.png)

### Active Directory Users

![Active Directory Users](screenshots/active-directory-users.png)

### Group Membership

![Group Membership](screenshots/group-membership.png)

### Password Reset Practice

![Password Reset](screenshots/password-reset.png)

### Shared Folder Permissions

![Shared Folder Permissions](screenshots/shared-folder-permissions.png)

### Domain-Joined Client

![Domain Joined Client](screenshots/domain-joined-client.png)

### Successful Domain Login Test

![Login Test](screenshots/login-test.png)

## Configuration Notes

Additional notes are included in the `configs/` folder:

- `lab-summary.txt`
- `user-and-group-structure.txt`
- `permissions-notes.txt`

## Skills Demonstrated

- Active Directory Domain Services setup
- Domain controller configuration
- Organizational Unit management
- User account creation and administration
- Security group management
- Password reset workflow
- Domain join troubleshooting
- Shared folder and NTFS permission management
- Help desk-style account and access support
- Documentation of lab setup and validation evidence
