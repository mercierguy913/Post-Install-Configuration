
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
 

</p>
<p>
Configure Roles (for grouping permissions) 
Let's start by finding the Admin Panel -> then Agents -> and under Roles
You will need to create a role called Supreme Admin
Go to Add New Role -> Name is Supreme Admin -> Permissions -> enable everything on all 3 tabs -> click Add Role 


</p>
<br />

![Screenshot 2025-03-12 222801](https://github.com/user-attachments/assets/d4245c80-4921-42d6-b68b-810012e2fa80)



<p>

</p>
<p>
Configure the Departments (Ticket Visibility)
  Go to the admin panel, then agents -> Departments, and then click on create SysAdmin
</p>
<br />

![Screenshot 2025-03-12 225624](https://github.com/user-attachments/assets/99822e3c-e945-4bbb-bd85-fc0967992508)


</p>
<p>
Configure Teams
  It's Admin Panel -> Then agents -> Teams
 Now, add the team members you need on there by clicking on Add New Team
</p>
<br />

![image](https://github.com/user-attachments/assets/b1e7f81a-74f2-486c-9223-72bfc8451208)


<p>

</p>
<p>
Configure Agents (workers)
  Find the Admin Panel -> Agents -> then Add New Agent. Now create the agents you need for your organization 
</p>
<br />

![image](https://github.com/user-attachments/assets/8b26aeb6-5c72-48c4-81ce-fcd3eb5ce232)


<p>

</p>
<p>
Configure Users
  Go to the Agent Panel -> Then Users -> Add New
</p>
<br />

![Screenshot 2025-03-13 214558](https://github.com/user-attachments/assets/8cd79705-4eef-4a86-aa72-a27c91f1abb7)


<p>

</p>
<p>
Configure SLA
  It's Admin Panel -> Manage -> SLA
  These are the different SLA's that there would be in a business, the different severity of need
  Sev-A (Grace Period: 1 hour, Schedule: 24/7)
  Sev-B (Grace Period: 4 hours, Schedule: 24/7)
  Sev-C (Grace Period: 8 hours, Business Hours)

</p>
<br />

![image](https://github.com/user-attachments/assets/12807629-ab9e-493f-9a74-d007bbd6daf2)


<p>

</p>
<p>
Configure Help Topics (when the user creates a ticket)
  Go to yes you guess it the Admin panel -> Manage -> Help Topics
  now make help topics for the users I recommend these as topics
  
  Business Critical Outage
  Personal Computer Issues
  Equipment Request
  Password Reset
  Other

  This would be the last step for this tutorial. congrats!
</p>
<br />

![image](https://github.com/user-attachments/assets/df471951-4dc1-4778-ba83-e74249956d04)

