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
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/Naeshon/post-install-config/assets/153772720/0e3607ee-a10a-4859-9f41-9282ea28af87)


<p>
1) After you've log into osTicket, make your way to the Admin Panel (you'll know you're in the admin panel if there is an option to click 'Agent Panel' in the top right-hand corner), then click onto the 'Agents' tab. From there, click the 'Roles' tab, from here you can create multiple new roles and manage their permissions.
</p>
<br />


![image](https://github.com/Naeshon/post-install-config/assets/153772720/c8d01ca6-ca7b-4d08-a29f-0aa637a1e9a0)



<p>
2) Once you've created all the roles necessary for the ticketing system, you can move onto configuring the departments. To do that, click the 'Departments' tab next to Roles, from here you can add new departments such as System Administrators.
</p>
<br />


![image](https://github.com/Naeshon/post-install-config/assets/153772720/d1b67981-0301-4922-99e3-d58ed27913ec)


3) Now that we've added new departments, we may configure teams for certain projects which may take agents from different departments & put them in a team together to finish the project. Click the 'Teams' tab, then 'Add New Team' to create a Level II Support team.



![image](https://github.com/Naeshon/post-install-config/assets/153772720/2a90344a-818e-4b48-9af9-4fdd700ba153)


4) Now we must allow any and all users to be able to create tickets. Go to Admin Panel->Settings->User Settings & make sure to uncheck the box that says 'Require registration and login to create tickets'



![image](https://github.com/Naeshon/post-install-config/assets/153772720/4724e45d-8cea-46ad-a729-45a5add5c740)



<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
