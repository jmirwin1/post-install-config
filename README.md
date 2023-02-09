<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

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

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles
</p>
<p>
  Supreme Admin:
</p>
<p>
<img src="https://i.imgur.com/gcWYV4C.png" alt="Supreme Admin"/>
<img src="https://i.imgur.com/vqm74tD.png" alt="set Permissions"/>
<img src="https://i.imgur.com/izSTMHQ.png" alt="Success"/>
</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
<img src="https://i.imgur.com/Lpps6i7.png" alt="System Administrators"/>
<img src="https://i.imgur.com/pfPRaRw.png" alt="New Department"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Level II Support:
</p>
<p>
<img src="https://i.imgur.com/sKUjiMa.png" alt="Level II Support"/>
<img src="https://i.imgur.com/q6w5s1A.png" alt="New Team"/>  
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
Under Authentication Settings, make sure the check box with "Require registration and login to create tickets" is not selected
</p>
<p>
<img src="https://i.imgur.com/NEUSclh.png" alt="User Settings"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New
</p>
<p>
  Create Agent Jane Doe:
</p>
<img src="https://i.imgur.com/pSYrZEi.png" alt="Jane Doe"/>
<p>
  Create Agent John Doe:
</p>
<p>
<img src="https://i.imgur.com/n1PRiid.png" alt="John Doe"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
 Create and add Lab User Ken:
</p>
<img src="https://i.imgur.com/NeDHMoE.png" alt="Lab User Ken"/>
<p>
  Repeat the same steps above for Lab User Karen
<img src="https://i.imgur.com/lMBZirx.png" alt="Lab User Karen"/>
</p>
<br />
<br />
<h3 align="center">Configure Service Level Agreements</h3>
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
<img src="https://i.imgur.com/FBdTBx4.png" alt="Sev-A"/>
<img src="https://i.imgur.com/BTc0Hiu.png" alt="Sev-B"/>
<img src="https://i.imgur.com/ComSN68.png" alt="Sev-C"/>  
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  </p>
<br />
<br />
<p>
now we are done configure osTicket
</p>
<p>
