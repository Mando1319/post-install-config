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

<p>
<img src="https://i.imgur.com/HrZCwEp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I started by logging into osTicket and then making my way to the Admin Panel -> Agents -> Roles, then I created a new role by the name supreme admin to allow an agent to have full control of everything. Next, I clicked on the department's tab and created a new department under the name SysAdmins.
</p>
<br />

<p>
<img src="https://i.imgur.com/EfYdoAL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After I was done configuring with departments I clicked on Teams and added a new team under the name of Online Banking. Moreover, I clicked on settings as I remained on the admin panel, then clicked on user and unchecked Registration Required:	Require registration and login to create tickets. After I was still on the admin panel, I clicked on agents and then added new agents, Jane (Dept: SysAdmins) and John (Dept: Support) who were the workers. Lastly, I added two users who were acting as the customers Karen and Ken under the agent panel.

</p>
<br />

<p>
<img src="https://i.imgur.com/w9gQfC1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
I moved on to configuring the SLA, so I clicked on Admin Panel -> Manage -> SLA. I added three new SLAs, 
Sev-A (Grace Period: 1 hour, Schedule: 24/7),
Sev-B (Grace Period: 4 hours, Schedule: 24/7),
Sev-C (Grace Period: 8 hours, Business Hours),
then after I made my way into help topics, and added five of them.
Business Critical Outage, Personal Computer Issues, Equipment Requests, Password Reset, and Other.

<p>

</p>
<br />
