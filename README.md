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

- Item 1
  Creating example accounts as an Administrator
- Item 2
  Seeing an End Users perspective
- Item 3
  Configuring SLA, Help Topics
  

<h2>Configuration Steps</h2>

<p>

![Admin panel](https://github.com/Onstarva/post-install-config/assets/166679644/97359367-9d54-4910-94e0-a329967e0076)
![Admin agent roles](https://github.com/Onstarva/post-install-config/assets/166679644/9aa0c8ec-4c25-4bad-a60c-cd75e0582727)
![Allowing anon tickets](https://github.com/Onstarva/post-install-config/assets/166679644/8036d5d5-6b71-4b9a-9e05-dcd475d3896b)

</p>
<p>
To create and configue accounts roles. Login into osTicket's admin login. After that Click the Agents tab-> Roles-> Add New Role. Name the Role you wish to add and notes if you like. Adjust the permissions you want for that said role and click add role. Next you want to adjust the Department for the role buy clicking the departments tab. Click Add New Department. Do note you will need to comeback here once you configure the SLAs. Name the department and fill out the information you would like filled, emails, managers, SLA priority, things of that nature. Once you finished filling the information click create Dept. Next you will need to assign teams to each department. Click Teams tab and create a name or level to the team and click Create team once your done. Next you can allow anonymous tickets to be made, by going to Settings-> Users-> and uncheck Require registration and login to create tickets for End Users. Next you'll want to create Agents to answer tickets. Go to Agents tab, Add new agents and fill out the person information, assign departments, roles, username, status, and a Password they can reset later. Then hit create.   
<br />

<p>

![User Example](https://github.com/Onstarva/post-install-config/assets/166679644/fea67b8e-cb8f-482a-a34b-6302b02739ec)

</p>
<p>
For example purposes, to create an Users for tickets later for agents. Switch to Agent panel-> Users-> Add User. Fill out the information and hit Add User.
</p>
<br />

<p>

![Adding SLAs](https://github.com/Onstarva/post-install-config/assets/166679644/40965ad2-72c0-456b-9fa5-ff195180120a)

![SLAs created](https://github.com/Onstarva/post-install-config/assets/166679644/b10c2239-857e-4163-ade7-ec92e075bf1b)

![Help Topics](https://github.com/Onstarva/post-install-config/assets/166679644/f9f2067e-7c7a-47fe-a71a-cc9fad46fb38)


</p>
<p>
To configure SLAs you will need to be in Admin panel-> Manage-> SLA. Add New SLA Plan. From here you can adjust SLAs, along with there schedule and notes. Once your done, click Add Plan. Adding as many SLAs as you see fit for any situation. Next to Configure help topics, go to Admin Panel-> Manage-> Help Topics. Click Add Help Topic, from here you can create Topics along with there levels of severity.
</p>
<br />
