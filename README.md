<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration

## This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.
### Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)

- Remote Desktop

- Internet Information Services (IIS)

## Operating Systems Used
 
-  Windows 10 (21H2)
 
### Post-Install Configuration Objectives
- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

### Configuration Steps

Configure Roles

Admin Panel -> Agents -> Roles.

Supreme Admin:

![ROLE](assets/Role1.png)

![ROLE](assets/role2.png)

![ROLE](assets/role3.png)

![ROLE](assets/role4.png)

![ROLE](assets/role5.png)





Configure Departments

Admin Panel -> Agents -> Departments.

System Administrators:

![ROLE](assets/dep1.png)

![ROLE](assets/dep2.png)



Configure Teams

Admin Panel -> Agents -> Teams.

Level II Support:

![ROLE](assets/team.png)



Allow anyone to create ticket

Admin Panel -> Settings -> User Settings.

Make sure "Require registration and login to create tickets" is not selected:

![ROLE](assets/settings.png)



Configure Agents (workers)

Admin Panel -> Agents -> Add New.

Jane Doe:

![ROLE](assets/jane.png)

John Doe:

![ROLE](assets/john.png)

![ROLE](assets/john2.png)

Configure Users (customers)

Admin Panel -> Users -> Add New.

Karen User:

![ROLE](assets/karen.png)

Repeat the same above for Karen User.



Configure SLA

Admin Panel -> Manage -> SLA.

Sev-A (1 hour, 24/7).

![ROLE](assets/seva.png)

Sev-B (4 hours, 24/7).

![ROLE](assets/sevb.png)

Sev-C (8 hours, business hours):

![ROLE](assets/sevc.png)




Configure Help Topics

Admin Panel -> Manage -> Help Topics.

Business Critical Outage.

![ROLE](assets/bus.png)

Personal Computer Issues.

![ROLE](assets/comp.png)

Equipment Request.

![ROLE](assets/equ.png)

Password Reset.

![ROLE](assets/pass.png)



And now we are done configure osTicket. I hope this tutorial helped. All that's left is to practice triaging and solving tickets.

This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
