# Voiletemoon AD Automation Lab

A hands-on Active Directory-compatible lab for learning domain
administration, identity management, DNS, Kerberos, and eventually
PowerShell-based user provisioning and deprovisioning.

## Project Goal

Built a small fictional company environment for:

- Active Directory administration
- User and group management
- Organizational Units (OUs)
- Domain-joined Windows clients
- PowerShell automation
- User onboarding and offboarding
- Auditing and logging

## Company

**Voiletemoon Clothing Co.**

Domain:

`voiletemoon.local`

## Current Lab Architecture

```text
MacBook
   |
   └── VirtualBox
        |
        ├── DC01
        |    ├── Ubuntu Linux
        |    ├── Samba AD
        |    ├── DNS
        |    ├── LDAP
        |    └── Kerberos
        |
        └── CLIENT01
             └── Windows 11
