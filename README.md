Post-Installation Configuration
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

- Creating admins
- Assigning tickets to agents 
- Creating tickets/Closing tickets
- Giving access to agents 
  

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/7qWrIQd.jpg"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Once I logged into osTicket as an admin, I configured the settings for the role of 'supreme admin' to be able to assign tickets to other agents
</p>
<br />

<p>
<img src="https://i.imgur.com/sZf1cXo.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Next, I created a new department named 'Systems Administrators' for the agents who have admin access to assign roles, attend to high level SLA's etc. 
</p>
<br />

<p>
<img src="https://i.imgur.com/U6ivJBV.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/tXbRe7A.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<p>
  Then, I created an agent under the name 'Jane Doe' as a member of the support team who the tickets will be assigned to giving them 'supreme admin' access also allowing them to assign, open and close tickets. 
</p>

<p>
<img src="https://i.imgur.com/tGf8lbw.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<p>
  Within the Agent panel, I created a user who will have an issue that needs troubleshooting or information from a member of the support team. 
</p>

<p>
<img src="https://i.imgur.com/OXZf4FH.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<p>
  Back in the Admin Panel, I created Service Level Agreements' (SLA's) which determine the severity of each ticket in order of priority - SEV-A being highest where issues need to be resolved within an hour and support is open on a 24hr basis. SEV-C is the lowest priority and support tickets for this level can be resolved in 8 hours or more with support available from monday-friday 8am-5pm
</p>

<p>
<img src="https://i.imgur.com/zbC04nC.jpg"height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<p>
  Finally, In the Admin Panel, I created help topics or troubleshooting issues that the users may have which will be assigned to an agent in the support department. 
</p>
