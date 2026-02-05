# IT Portfolio

This repository contains my hands-on IT labs and mini projects. The goal is to build practical Windows and networking skills, document what I did, and keep a clear record of troubleshooting and outcomes.

## What you will find here
- Windows Server labs (AD DS, DNS, DHCP)
- Windows client configuration and domain joining
- Basic networking (IP addressing, subnets, routing, name resolution)
- Troubleshooting notes and fixes
- Screenshots and short write-ups for evidence

## Projects

### 1) Windows Server Home Lab: AD DS, DNS, DHCP
**Goal:** Build a small domain environment and connect two Windows 11 clients to it.

**Stack:**
- VirtualBox
- Windows Server 2025 (DC01)
- Windows 11 clients (WIN11-CL1, WIN11-CL2)

**What I implemented:**
- Promoted DC01 to a Domain Controller (new forest)
- Configured DNS for the domain
- Created a DHCP scope and issued leases to both clients
- Joined both Windows 11 clients to the domain
- Verified DHCP and DNS from clients using `ipconfig /all` and `nslookup`

**Evidence:**
- Server Manager role status (AD DS, DNS, DHCP)
- ADUC showing both client computer objects
- Client outputs proving DHCP and DNS configuration

Folder: `projects/windows-server-homelab-ad-dns-dhcp/`

## Repo structure
- `projects/` individual projects with their own README
- `screenshots/` images used in documentation (kept inside each project where possible)
- `notes/` general notes and troubleshooting snippets

## Roadmap (next labs)
- OUs, users, groups, and permissions design
- Group Policy basics (password policy, mapped drive, desktop restrictions)
- File share with NTFS and share permissions
- Optional: IIS basics or WSUS overview

## Contact
If you would like to connect, you can find me on LinkedIn.
