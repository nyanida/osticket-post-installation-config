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

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Department
- Configute Teams
- Configure Agent
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>
<p>
<img src="https://i.imgur.com/tEGn7y5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> Select 'Admin Panel' at the top </p>

<p>
<img src="https://i.imgur.com/5FvLuj3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/M9Aj8SX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Click 'Add New Role' button</p>
<p>
<img src="https://i.imgur.com/Tkywu0Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Name new role 'Supreme Admin'</p>
<p>
Configure Roles
Admin Panel > Agents > Roles
Supreme Admin

</p>
<br />

<p>
<img src="https://i.imgur.com/csH8bkA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets
Admin Panel > Settings > User Settings
Registration Required: Require registration and login to create tickets (Make sure 'require registration and login to create tickets' is unchecked)

</p>
<br />

<p>
<img src="https://i.imgur.com/9aJXt3M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/1FRu2b2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Create new agent named "Jane Doe"</p>
<p>
<img src="https://i.imgur.com/B3jg9z0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Create a password</p>

<p>Repeat process to create an agent named "John Doe"</p>
<p>
Configure Agents (workers)
Admin Panel > Agents > Add New
Jane
John

</p>
<br />

<p>
<img src="https://i.imgur.com/UEfPWDL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/6vFeQW3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Xv0Z0re.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)
Agent Panel > Users > Add New
Karen
Ken

</p>
<br />

<p>
<img src="https://i.imgur.com/zCDfs4R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ceXtLTq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/FqV2zbx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)

</p>
<br />

<p>
<img src="https://i.imgur.com/YMK3nix.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/HaTBfdU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

<br />


