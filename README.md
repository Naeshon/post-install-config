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
5) To configure Agents we must go to Admin Panel -> Agents -> Add New. Once you've made it to this page, you can create however many Agents as needed. Make sure to set the access permissions for each Agent & assign them a department.


![image](https://github.com/Naeshon/post-install-config/assets/153772720/2402d883-47bc-42b5-a5ea-ae16230438b0)

</p>
<br />


6) Next, we have to configure some new users. Users are essentially the people whom recieve the support (the people that create the tickets). For this step, go to Agent Panel -> Users -> Add New. Make as many Users as you may need.


![image](https://github.com/Naeshon/post-install-config/assets/153772720/3a3b767b-775c-4516-bfc2-d463ea2291e2)



7) Moving on, we must now configure the SLA (Service Level Agreements) which is basically a priority list for every ticket. For example, if your workplace's website was having an outage where customers can shop, this would be a high-priority issue to fix because it is actively costing the business money, therefore it would recieve the highest priority SLA. To configure the SLA's go to Admin Panel -> Manage -> SLA. In this example, Sev-A is the highest priority SLA with a 24/7 schedule and a one-hour grace period, meaning a Sev-A ticket would need to be tended to within an hour no matter what day of the week it is. Sev-B would be something like a 24/7 schedule with a 4-hour grace period. 



![image](https://github.com/Naeshon/post-install-config/assets/153772720/53698466-2dbb-4d19-a309-034ad1a9e1f9)

![image](https://github.com/Naeshon/post-install-config/assets/153772720/5a3bbb3d-44f6-49fd-aded-46d9a6f4a048)


8) After adding our SLA's go to Admin Panel -> Manage -> Help Topics to configure help topics. From here, create multiple Help Topics for Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset.



![image](https://github.com/Naeshon/post-install-config/assets/153772720/f0d76c4b-ee50-4b7d-905d-b5ea6dcac692)




9) Just like that you've configured your entire osTicket Ticketing System in your Windows Virtual Machine! Congratulations!


