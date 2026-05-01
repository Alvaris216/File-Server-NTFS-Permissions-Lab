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
<img width="1023" height="763" alt="AD File Server NTFS Permissions pt1" src="https://github.com/user-attachments/assets/16a43f38-813d-4dfd-9a25-7db7dce77381" />

<img width="1025" height="724" alt="AD File Server NTFS Permissions pt2 Setting Permission" src="https://github.com/user-attachments/assets/4d0f706a-e228-449c-a17f-1bdc57ab7f33" />

<img width="1019" height="729" alt="AD File Server NTFS Permissions pt3 Giving permissions to the Administrator" src="https://github.com/user-attachments/assets/6e09dc1a-df74-455f-8fac-88eb659b73fe" />

<img width="1016" height="768" alt="AD File Server NTFS Permissions pt4 assigning IT Folder permissions" src="https://github.com/user-attachments/assets/bcfa85e4-c21f-4d51-8103-c6bbb1f7e6c6" />

<img width="1022" height="766" alt="AD File Server NTFS Permissions pt5 Permissions for Sales" src="https://github.com/user-attachments/assets/100cf7a0-718c-4fb2-b1df-479834bd5353" />



