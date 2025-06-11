<p align="center"> <img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%" alt="osTicket logo"/> </p> 
<h1>osTicket - Post-Installation Setup Guide</h1> This walkthrough covers the essential configurations required after installing the open-source help desk system, osTicket.<br /> 
<h2>Tools and Platforms Used</h2>

<ul>
<li>Microsoft Azure (Virtual Machines/Compute)</li>

<li>Remote Desktop Protocol (RDP)</li>

<li>Internet Information Services (IIS) </li>
</ul>

<h2>Operating System</h2>

<li>Windows 10 (Version 21H2)</li>

<h2>Post-Installation Setup Goals</h2>
<ul>
<li>Define Roles</li>

<li>Set Up Departments</li>

<li>Create Teams</li>

<li>Add Agents</li>

<li>Register Users</li>

<li>Configure SLA Policies</li>

<li>Set Up Help Topics</li>
</ul>


<h2>Step-by-Step Configuration</h2>

<h3 align="center">Defining Roles</h3>
<br />
<p>Navigate to: Admin Panel → Agents → Roles.</p>
<p>Example: Supreme Admin Role</p>
<p>
  <img src="https://github.com/user-attachments/assets/df8ea725-f2da-48c7-9382-a14afbf578b1" alt="Role Definitions" />
  <img src="https://github.com/user-attachments/assets/6ca26bde-cc2d-4dc5-aece-8a007970a1ce" alt="Permissions" />
  <img src="https://github.com/user-attachments/assets/bdaf86d7-746f-470d-b0b9-e4d7fc358e1e" alt="More Permissions" />
  <img src="https://github.com/user-attachments/assets/c4010bd0-2c1d-40eb-b348-02cc9d46edae" alt="Additional Permissions" />
</p>

<h3 align="center">Setting Up Departments</h3>
<br />
<p>Navigate to: Admin Panel → Agents → Departments.</p>
<p>Example: System Administrators Department</p>
<p>
  <img src="https://i.imgur.com/83gWQsO.png" alt="Department Settings" />
  <img src="https://i.imgur.com/oGLXmQv.png" alt="Department Details" />
</p>

<h3 align="center">Creating Teams</h3>
<br />
<p>Navigate to: Admin Panel → Agents → Teams.</p>
<p>Example: Level II Support</p>
<p>
  <img src="https://i.imgur.com/BnPrcDH.png" alt="Team Setup" />
</p>

<h3 align="center">Enable Ticket Creation for All Users</h3>
<br />
<p>Navigate to: Admin Panel → Settings → User Settings.</p>
<p>Uncheck the box labeled "Require registration and login to create tickets":</p>
<p>
  <img src="https://i.imgur.com/QsJjOuM.png" alt="Allow Ticket Submission Without Login" />
</p>

<h3 align="center">Adding Agents (Staff Members)</h3>
<br />
<p>Navigate to: Admin Panel → Agents → Add New.</p>
<p>Agent Example: John Doe</p>
<p>
  <img src="https://i.imgur.com/NcCP0v9.png" alt="John Doe Profile" />
  <img src="https://i.imgur.com/aKTJ01A.png" alt="John Doe Permissions" />
</p>

<h3 align="center">Registering Users (End Customers)</h3>
<br />
<p>Navigate to: Admin Panel → Users → Add New.</p>
<p>User Example: Ken User</p>
<p>
  <img src="https://i.imgur.com/vbPd3uK.png" alt="User Registration" />
</p>
<p>Repeat similar steps to create: Laura User</p>

<h3 align="center">Setting Up SLA Plans</h3>
<br />
<p>Navigate to: Admin Panel → Manage → SLA.</p>
<p>Sample SLA Policies:</p>
<ul>
  <li>Sev-A (1 hour response, 24/7 coverage)</li>
  <li>Sev-B (4 hours response, 24/7 coverage)</li>
  <li>Sev-C (8 hours response, business hours only)</li>
</ul>
<p>
  <img src="https://i.imgur.com/6AAF3Ju.png" alt="SLA Level A" />
  <img src="https://i.imgur.com/izcD74X.png" alt="SLA Level B" />
  <img src="https://i.imgur.com/xKzdp7w.png" alt="SLA Level C" />
</p>

<h3 align="center">Creating Help Topics</h3>
<br />
<p>Navigate to: Admin Panel → Manage → Help Topics.</p>
<p>Example Help Topics:</p>
<ul>
  <li>Business Critical Outage</li>
  <li>Personal Computer Issues</li>
  <li>Equipment Request</li>
  <li>Password Reset</li>
</ul>
<p>
  <img src="https://i.imgur.com/Xdhp63v.png" alt="Help Topic 1" />
  <img src="https://i.imgur.com/3Y7k2o1.png" alt="Help Topic 2" />
  <img src="https://i.imgur.com/Z0eIGea.png" alt="Help Topic 3" />
  <img src="https://i.imgur.com/ndOdtTZ.png" alt="Help Topic 4" />
</p>

<br />
<p>
  Your osTicket instance is now fully configured. This guide is meant to assist you in setting up a functioning support system. Continued practice in triaging and resolving support tickets is strongly recommended.
</p>
<p>
  Ticket handling is a vital skill for help desk technicians, who act as the front line of support between an organization and its customers when resolving product or service issues.
</p>

