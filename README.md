# CyberPatriot-Round-1-Linux-Mint-21
This project documents my participation in Round 1 of the CyberPatriot National Youth Cyber Defense Competition using **Linux Mint 21** on October 24, 2026.

The competition simulated an IT administration scenario in which participants were responsible for securing computer systems, managing user accounts, protecting sensitive information, and removing unauthorized or non-work-related content.

I collaborated with a four-person team, with each team member assigned a separate system image. Our team worked across Windows 11, Windows Server, **Linux Mint 21**, and Cisco Packet Tracer environments.

This repository focuses on the Linux Mint 21 environment and documents the system administration, security-hardening, and vulnerability research tasks I worked on during the competition.

## Competition Information

- **Competition:** CyberPatriot National Youth Cyber Defense Competition
- **Round:** Round 1
- **Date:** October 24, 2026
- **Operating System:** Linux Mint 21
- **Team Size:** 4 participants
- **Environment:** Competition-provided virtual machine

## Scenario and Objectives

The competition presented a simulated IT administrator scenario. The objective was to ensure that computer systems, user accounts, and stored information were properly secured and appropriate for a professional workplace.

Key objectives included:

- Investigating forensic questions
- Identifying and removing unauthorized user accounts.
- Reviewing user accounts and administrative privileges.
- Strengthening password security and account policies.
- Removing non-work-related files and unnecessary software.
- Configuring firewall protections.
- Investigating security vulnerabilities and updating system packages.

## Security Tasks Performed

### 1. Forensic Investigation
- Answered forensic questions using information provided in the competition scenario.
- Searched through the system to locate specific files and information.

### 2. User Account and Access Management
- Reviewed existing local user accounts.
- Evaluated account passwords and password security.
- Identified accounts that did not belong on the system.
- Reviewed administrative privileges and removed unauthorized users.
- Modified file permissions to support appropriate access restrictions.

### 3. Password Security
- Reviewed and strengthened password policies.
- Used *sudo chpasswd* to change the password of multiple users at once.

### 4. Firewall Configuration
- Configured the Uncomplicated Firewall (UFW).
- Established firewall rules to help restrict unauthorized network access.

### 5. Software and Package Management
- Identified and removed unnecessary or non-work-related software.
- Updated package information using APT.
- Applied available package upgrades.

### 6. Vulnerability Research
- Researched CVE-2026-109618 and CVE-2026-109619.
- Consulted the CISA Known Exploited Vulnerabilities (KEV) Catalog.
- Investigated related package references in Debian changelogs using `zgrep`.

## Tools Used
- Linux Terminal
- Users and Groups Program
- Uncomplicated Firewall (UFW)

## Skills Demonstrated

- Linux system administration
- User account and access management
- File permission management
- Password security configuration
- Firewall configuration
- Software and package management
- Forensic investigation
- Vulnerability research
- Technical problem-solving
- Team collaboration

## Competition Environment Limitations

The original competition virtual machine is no longer accessible following the conclusion of the competition. This repository serves as the documentation of the tasks, tools, and technical experience used during the competition.

## Reflection

This experience provided practical exposure to Linux system administration and cybersecurity in a simulated professional IT environment. It strengthened my understanding of user account security, access permissions, firewall configuration, package management, and vulnerability research while developing my ability to investigate unfamiliar systems and work collaboratively under competition constraints.
