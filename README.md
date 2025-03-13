
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
<img src="https://imgur.com/doiaJAE.png" height="80%" width="80%" 

</p>
<p>
Configure Roles (for grouping permissions) 
Let's start by finding the Admin Panel -> then Agents -> and under Roles
You will need to create a role called Supreme Admin
Go to Add New Role -> Name is Supreme Admin -> Permissions -> enable everything on all 3 tabs -> click Add Role 


</p>
<br />



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure the Departments (Ticket Visibility)
  Go to the admin panel, then agents -> Departments, and look for SysAdmin
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams
  It's Admin Panel -> Then agents -> Teams
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
  Find the Admin Panel -> Agents -> then add new. Now create the agents you need for your organization 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users
  Go to the Agent Panel -> Then Users -> Add New
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
