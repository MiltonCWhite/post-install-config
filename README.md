<p align="center"> <img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%" alt="osTicket logo"/> </p> <h1>osTicket - Post-Installation Setup Guide</h1> This walkthrough covers the essential configurations required after installing the open-source help desk system, osTicket.<br /> <!-- <h2>Video Demonstration</h2> - ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) --> <h2>Tools and Platforms Used</h2>
Microsoft Azure (Virtual Machines/Compute)

Remote Desktop Protocol (RDP)

Internet Information Services (IIS)

<h2>Operating System</h2>
Windows 10 (Version 21H2)

<h2>Post-Installation Setup Goals</h2>
Define Roles

Set Up Departments

Create Teams

Add Agents

Register Users

Configure SLA Policies

Set Up Help Topics

<h2>Step-by-Step Configuration</h2> <h3 align="center">Defining Roles</h3> <br /> <p> Navigate to: Admin Panel → Agents → Roles. </p> <p> Example: Supreme Admin Role </p> <p> <img src="https://i.imgur.com/SXpTf20.png" alt="Role Definitions"/> <img src="https://i.imgur.com/9fBmrZj.png" alt="Permissions"/> <img src="https://i.imgur.com/1sDBsuZ.png" alt="More Permissions"/> <img src="https://i.imgur.com/2SVt7rt.png" alt="Additional Permissions"/> <img src="https://i.imgur.com/vJl5MPw.png" alt="Sys Admin Setup Complete"/> </p> <h3 align="center">Setting Up Departments</h3> <br /> <p> Navigate to: Admin Panel → Agents → Departments. </p> <p> Example: System Administrators Department </p> <p> <img src="https://i.imgur.com/83gWQsO.png" alt="Department Settings"/> <img src="https://i.imgur.com/oGLXmQv.png" alt="Department Details"/> </p> <h3 align="center">Creating Teams</h3> <br /> <p> Navigate to: Admin Panel → Agents → Teams. </p> <p> Example: Level II Support </p> <p> <img src="https://i.imgur.com/BnPrcDH.png" alt="Team Setup"/> </p> <h3 align="center">Enable Ticket Creation for All Users</h3> <br /> <p> Navigate to: Admin Panel → Settings → User Settings. </p> <p> Uncheck the box labeled "Require registration and login to create tickets": </p> <p> <img src="https://i.imgur.com/QsJjOuM.png" alt="Allow Ticket Submission Without Login"/> </p> <h3 align="center">Adding Agents (Staff Members)</h3> <br /> <p> Navigate to: Admin Panel → Agents → Add New. </p> <p> Agent Example: Jane Doe </p> <p> <img src="https://i.imgur.com/ujpOdKM.png" alt="Jane Doe Agent Setup"/> </p> <p> Agent Example: John Doe </p> <p> <img src="https://i.imgur.com/NcCP0v9.png" alt="John Doe Profile"/> <img src="https://i.imgur.com/aKTJ01A.png" alt="John Doe Permissions"/> </p> <h3 align="center">Registering Users (End Customers)</h3> <br /> <p> Navigate to: Admin Panel → Users → Add New. </p> <p> User Example: Ken User </p> <p> <img src="https://i.imgur.com/vbPd3uK.png" alt="User Registration"/> </p> <p> Repeat similar steps to create: Karen User </p> <h3 align="center">Setting Up SLA Plans</h3> <br /> <p> Navigate to: Admin Panel → Manage → SLA. </p> <p> Sample SLA Policies: </p> <ul> <li>Sev-A (1 hour response, 24/7 coverage)</li> <li>Sev-B (4 hours response, 24/7 coverage)</li> <li>Sev-C (8 hours response, business hours only)</li> </ul> <p> <img src="https://i.imgur.com/6AAF3Ju.png" alt="SLA Level A"/> <img src="https://i.imgur.com/izcD74X.png" alt="SLA Level B"/> <img src="https://i.imgur.com/xKzdp7w.png" alt="SLA Level C"/> </p> <h3 align="center">Creating Help Topics</h3> <br /> <p> Navigate to: Admin Panel → Manage → Help Topics. </p> <p> Example Help Topics: </p> <ul> <li>Business Critical Outage</li> <li>Personal Computer Issues</li> <li>Equipment Request</li> <li>Password Reset</li> </ul> <p> <img src="https://i.imgur.com/Xdhp63v.png" alt="Help Topic 1"/> <img src="https://i.imgur.com/3Y7k2o1.png" alt="Help Topic 2"/> <img src="https://i.imgur.com/Z0eIGea.png" alt="Help Topic 3"/> <img src="https://i.imgur.com/ndOdtTZ.png" alt="Help Topic 4"/> </p> <br /> <p> Your osTicket instance is now fully configured. This guide is meant to assist you in setting up a functioning support system. Continued practice in triaging and resolving support tickets is strongly recommended. </p> <p> Ticket handling is a vital skill for help desk technicians, who act as the front line of support between an organization and its customers when resolving product or service issues. </p>
