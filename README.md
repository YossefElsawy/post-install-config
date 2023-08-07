<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- [osTicket Documentation](https://docs.osticket.com/en/latest/index.html)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- This section of the lab assumes you have created a virtual machine and went through the installation setup in Section 1 linked here: 

<h2>Configuration Steps</h2>

<p>
  
</p>

- ### [Section 3: Post Installation Configuration](https://www.loom.com/share/426e9de50a50411fafc5f3013b5dcdb4?sid=07ff685a-ce1a-4518-bb0e-0e940a3157ef)
<p>
Now we will go over creating the environment within osTicket.

First, we will create our roles
Admin Panel > Agents > Roles 
Set the appropriate roles for this person.
In my project I went ahead and named the role: Supreme Admin and gave all responsibilities
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will create Departments
Admin Panel > Agents > Departments 
Create the department which is of need for your organization
In this lab I created the role: System Administrators
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we created Teams
Admin Panel > Agent > Teams 
Depending on your organization each team will need to be defined
In this lab I created the team: Level II Support
</p>
<br />

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we created Agents:
Admin Panel > Agents > Add New
First Name: John -- Last Name: Cena -- Email Address: john.cena@osTicket.com -- Username: john.cena -- 
Click "Set Password" and then uncheck "Send the agent a password reset email". Create a password for this user. Uncheck "Require password change at next login". Make sure to click "Set"
Note: Another Agent was created and shown in the lab.
</p>
<br />

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we created Users:
Agent Panel > Users > Add New
First Name: Seth -- Last Name: Rollins -- Email Address: seth.rollins@osTicket.com -- 
Note: Another User was created and shown in the lab.
</p>
<br />

<p>
Next we created SLA's (Service Level Agreement):
Admin Panel > Manage > SLA
I created three levels of SLA
SLA-A > Grace Period: 1 hour > Schedule: 24/7
SLA-B > Grace Period: 4 hours > Schedule: 24/7
SLA-C > Grace Period: 8 hours > Schedule: Monday - Friday 8am - 5pm with U.S. Holidays
</p>
<br />

<br />

<p>
Next we created Help Topics
Admin Panel > Manage > Help Topics
  The examples used were:
  Business Critical Outage
  Personal Computer Issues
  Equipment Request
  Password Reset
</p>
<br />

<hr>
<h1><p align=center>All Done</p></h1

<h2><p align=center>Next Demonstration:<br><a href="https://github.com/YossefElsawy/ticket-lifecycle">Ticket Lifecycle Examples</a></p></h2>
