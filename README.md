<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Login to osTicket Admin Panel
- config Roles
- Config Departments
- Config Teams
- Config SLA

<h2>Configuration Steps</h2>

<p> Login to the osTicket Admin Panel. The image  Below displays the tickets for admin/helpdesk User Interface  that will Show the tickets that are created by the End Users    

  
![Annotation 2024-09-09 175600](https://github.com/user-attachments/assets/6a4fadf3-09c4-4503-a74a-217c21be4bf3)


</p> 
<p>
 .
</h>Roles
<br /> Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access. An unlimited number of roles can be created and assigned to Agents with access to various departments.
Admin Panel>Agents> Roles
Supreme Admin


![Annotation 2024-09-09 204500](https://github.com/user-attachments/assets/c22bd1ee-4143-4cc1-8ba0-5d6ffc2dc4c9)

Now we can enable the permissions for this role and as the "Supreme Admin" we've enabled every possible permission available.

![Annotation 2024-09-09 204004](https://github.com/user-attachments/assets/59db7f45-c64e-482d-ac0a-c626a0d04e7a)

</p> Departments
<p>
Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.
Admin Panel > Agents > Departments
SysAdmins
Leave the remaining fields set as default .
</p>


![Annotation 2024-09-09 204609](https://github.com/user-attachments/assets/948035ed-c6b0-4055-a74f-e863d9998d96)

Agents
<p> Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
Admin Panel > Agents > Add New
Jane
John

![Annotation 2024-09-09 210431](https://github.com/user-attachments/assets/9a6bc2a1-3238-4b06-81ae-983c716f03dc)


</p>!









![Annotation 2024-09-09 204744](https://github.com/user-attachments/assets/a0365291-f1f4-485c-bcf3-3735429baebd)


<p>

  
  
  






</p> End Users Creation Users can log in to create a ticket or check on their ticket status as well.
Agent Panel > Users > Add New

1.Karen

2.Ken
<br />




![Annotation 2024-09-10 172416 User](https://github.com/user-attachments/assets/d9f9dff7-8ded-4f0d-8f7a-e1e7a7fe2545)






![Annotation 2024-09-10 172329 User](https://github.com/user-attachments/assets/119d13c1-83e2-4e35-8d5b-878c74edaf58)





SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed. Admin Panel > Manage > SLA

-.Sev-A (1 hour, 24/7)

-.Sev-B (4 hours, 24/7)

-.Sev-C (8 hours, business hours)






![Annotation 2024-09-09 183545](https://github.com/user-attachments/assets/c93140df-3d77-46bf-8251-0dde4a25685f)





Help Topics will help streamline your end-user’s help desk experience to ensure proper assignment and prompt response to the ticket. Create as many Help Topics as needed and can even nest Help Topics within each other for further breakdown (For example, Human Resources and Human Resources/Payroll.)

Admin Panel > Manage > Help Topics

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset



![Annotation 2024-09-09 183522](https://github.com/user-attachments/assets/14346d4c-b507-499e-a8f9-5e63fd789602)






