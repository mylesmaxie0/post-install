<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This guide details the post-installation setup process for the open-source help desk ticketing system, osTicket.<br />

<h2>Environments and Technologies Utilized</h2>

- Microsoft Azure: Virtual Machines/Compute
- Remote Desktop: For remote management and access
- Internet Information Services (IIS): Web server configuration and hosting

  <h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

  <h2>Post-Install Configuration Objectives</h2>

<ul>
  <li>Configure Roles</li>
  <li>Configure Departments</li>
  <li>Configure Teams</li>
  <li>Configure Agents</li>
  <li>Configure Users</li>
  <li>Configure SLA</li>
  <li>Configure Help Topics</li>
</ul>

<h2>Configuration Steps</h2>

<h3 align="center">Configuring Roles</h3>
<br />
<p>
To access and configure roles in osTicket, navigate to:

Admin Panel → Agents → Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://i.imgur.com/SXpTf20.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://i.imgur.com/9fBmrZj.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/1sDBsuZ.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/2SVt7rt.png" height="75%" width="100%" alt="Even More Permissions"/>
  <img src="https://i.imgur.com/vJl5MPw.png" height="75%" width="100%" alt="Sys Admin Success"/>
</p>
<br />
<br />
<h3 align="center">Configuring Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://i.imgur.com/83gWQsO.png" height="75%" width="100%" alt="System Administrators"/>
  <img src="https://i.imgur.com/oGLXmQv.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configuring Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Level II Support:
</p>
<p>
  <img src="https://i.imgur.com/BnPrcDH.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://i.imgur.com/QsJjOuM.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configuring Help Desk Agents </h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://i.imgur.com/ujpOdKM.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://i.imgur.com/NcCP0v9.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/aKTJ01A.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configuring Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>
  <img src="https://i.imgur.com/vbPd3uK.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Karen User.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/6AAF3Ju.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/izcD74X.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/xKzdp7w.png" height="75%" width="100%" alt="sev three"/>
</p>
<br />
<br />
<h3 align="center">Configuring Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://i.imgur.com/Xdhp63v.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://i.imgur.com/3Y7k2o1.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://i.imgur.com/Z0eIGea.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://i.imgur.com/ndOdtTZ.png" height="75%" width="100%" alt="password reset"/>
</p>
<br />
<br />
<h3 align="center"> Next steps are here: https://github.com/mylesmaxie0/ticket-simulation</h3>

