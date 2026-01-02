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

 <blockquote class="imgur-embed-pub" lang="en" data-id="a/4GWMpaK" data-context="false" ><a href="//imgur.com/a/4GWMpaK"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

<img width="1169" height="688" alt="Topology" src="https://github.com/user-attachments/assets/ced4b73b-6f9e-48bf-bdff-cd6cdb4ce76f" />

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
