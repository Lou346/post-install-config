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
- configure Roles
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


<p> Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
Admin Panel -> Agents -> Add New
Jane
John

![Annotation 2024-09-09 210431](https://github.com/user-attachments/assets/9a6bc2a1-3238-4b06-81ae-983c716f03dc)


</p>
<p>

  
  
  
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
