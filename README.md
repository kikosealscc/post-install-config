# Post-Install-Config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=4kEQtECcO-U)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11 Pro </b> (23H2)

<h2>Post-Install Configuration Objectives</h2>

 
![image](https://github.com/user-attachments/assets/abc9f2da-e4be-4441-b03f-768d7cb4e279)




Email Setup: Configure email addresses for incoming tickets. Go to the Admin Panel > Emails to set up SMTP/IMAP for outgoing/incoming emails

Departments and Teams: Create departments and assign teams to handle specific ticket categories. Navigate to Admin Panel > Agents > Departments


<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/user-attachments/assets/6bd1f0c3-80d4-4b93-b614-2d8fc9c35e9d)

</p>
<p>

User Roles and Permissions: Set up user roles and permissions in Admin Panel > Agents > Roles. Assign users to roles to define access levels

Ticket Workflows: Configure ticket priorities, SLA plans, and custom workflows in Admin Panel > Manage > Help Topics


<br />

<p>

![image](https://github.com/user-attachments/assets/0ee9897a-4a69-4445-b3f6-e50e6712576a)



</p>
<p>

Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets) > Registration Required: Require registration and login to create tickets


</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/f9ebf2ce-5ab5-46cb-bc4d-5b2e9b633d74)


</p>
<p>

Configure Help Topics: Admin Panel > Manage > Help Topics > Business Critical Outage > Personal Computer Issues > Equipment Request > Password Reset


</p>
<br />
