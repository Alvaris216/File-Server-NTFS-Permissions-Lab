# File-Server-NTFS-Permissions-Lab
This project demonstrates hands-on experience with Active Directory File Server + NTFS Permissions.
# Windows File Server + NTFS Permissions Lab

## Overview
This project demonstrates the setup and configuration of a Windows Server 2022 file server with role-based access control using NTFS and shared folder permissions.

## Objectives
- Deploy a structured file share environment
- Configure NTFS permissions for security groups
- Simulate real-world department access (HR, IT, Sales)
- Test access control and troubleshoot permission issues

## Environment
- Windows Server 2022
- Windows 11 Client
- Active Directory Domain Services
- NTFS File System

## Folder Structure
C:\Shares
├── HR
├── IT
├── Sales
└── Public
## Security Model
- HR group → HR folder (Full Control)
- IT group → IT folder (Full Control)
- Sales group → Sales folder (Modify access)
- Domain Users → Public folder (Read access)

## Key Skills Demonstrated
- Windows Server administration
- Active Directory group management
- NTFS permissions (DACLs)
- Share permissions vs NTFS permissions
- Access troubleshooting

## Screenshots
