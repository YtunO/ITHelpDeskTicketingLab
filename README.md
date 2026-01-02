# ITHelpDeskTicketingLab
Simulated IT help desk lab demonstrating password reset and account lockout resolution using Active Directory and Jira Service Management.

# Active Directory Password Reset & Ticketing Lab

## Overview
This project demonstrates a simulated IT help desk workflow using Active Directory and Jira Service Management. It focuses on resolving password reset and account lockout requests submitted through a service portal.

## Technologies Used
- Windows Server 2019
- Windows 10
- Active Directory Domain Services
- Jira Service Management
- PowerShell
- Oracle VirtualBox

## Lab Architecture
- Domain Controller (Windows Server 2019)
- Client workstation (Windows 10)
- Jira Service Management portal for ticket intake

## Workflow
1. User becomes locked out after multiple failed login attempts.
<img src="https://i.imgur.com/Ez8bWiD.png" width="600">

3. User submits a password reset request through Jira Service Management.
4. IT reviews and assigns the ticket.
5. Account is unlocked and password reset in Active Directory.
6. User logs in successfully on a domain-joined client.
7. Ticket is documented and resolved.

## Key Skills Demonstrated
- Active Directory user management
- Password reset and account unlock
- IT ticketing and incident management
- Identity and Access Management (IAM)
- Troubleshooting and documentation
- PowerShell automation

## Notes
All users, domains, and data in this project are fictional and used for learning purposes.
