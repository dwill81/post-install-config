<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Setup </h1>
This tutorial outlines the post-installation setup of osTicket. This setup includes creating agents, users, departments, teams, and roles. Different types of SLA's will be configured as well that outlines the ranges in severity of the tickets we will be creating.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (version 21H2)

<h2>Good Things to Know</h2>

 - Click on specific positions for a better understanding!
 	- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
	- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
	- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html) 
	- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
	- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
	- [Service Level Agreement(SLA)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)
	
   
<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments & Teams
- Allow Users to Create Tickets
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

Log into the OsTicket browser and make sure you are on the "admin panel" (note if it shows "agent panel" up top then you are currently in the admin panel and vice versa) reference picture # 1. Click agents --> roles --> add new role --> create a "super admin" whom can do every task and has all permissions/access. This process will need to be repeated to perform the next two steps which are: configuring the departments & teams (create a "System Administrators department" & "Level II Support team"). Please reference screenshots below.
<p>
<img width="773" alt="image" src="https://user-images.githubusercontent.com/122701786/212603603-0b82b63e-262f-473a-8a8b-0d3d1fb510b3.png">
<img width="737" alt="image" src="https://user-images.githubusercontent.com/122701786/212603909-f371e414-ab81-4639-b6d9-6905fb50bf43.png">
<img width="743" alt="image" src="https://user-images.githubusercontent.com/122701786/212604063-a6320303-0471-4287-8d50-af03249a8dc0.png">
</p>
<p>

</p>
<br />
<p> 5. Allow anyone to create tickets: Make sure "Registration Required" section remains unchecked.
Admin Panel -> Settings -> User Settings

</p>
<br />

<p>
<img width="733" alt="image" src="https://user-images.githubusercontent.com/122701786/212606372-eb0fb5f0-ecfb-4197-a0a2-9af1551513dd.png">
</p>                                                                                                
                                                                                               
                                                                                               
<p>
6. Configure Agents (workers):
Admin Panel -> Agents -> Add New

</p>
<br />

<p>
<img width="737" alt="image" src="https://user-images.githubusercontent.com/122701786/212607114-440767d1-bf7b-48e5-aef6-c9e5c45f1d8d.png">
</p>
<p>
7. Configure Users (customers):
Agent Panel -> Users -> Add New

</p>
<br />

<img width="736" alt="image" src="https://user-images.githubusercontent.com/122701786/212607989-b0d90cdb-ac37-401c-b872-a77440fd1339.png">

<p>
8. Configure SLA:
Admin Panel -> Manage -> SLA

</p>
<br />

<img width="741" alt="image" src="https://user-images.githubusercontent.com/122701786/212609354-8e1fe608-2d47-41bf-b150-8ac25ba28cb4.png">

<p>
9. Configure Help Topics:
Admin Panel -> Manage -> Help Topics

</p>
<br />

<p>
10. Congratulations! Now you have learned how to create both users, departments, and tickets on osTicket.
</p>
<br />
