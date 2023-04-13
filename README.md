<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. Check out my prerequisites and installation to install and setup osTicket if you did not do so already.<br />

<h2>Video Demonstration</h2>

<!-- - ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

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
- Configure Tickets Permissions
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics


<h2>Configuration Steps</h2>

<p>
<img width="1148" alt="Screen Shot 2023-04-13 at 8 15 00 AM" src="https://user-images.githubusercontent.com/88648101/231755246-71cdbf27-8670-4cec-8a69-b876699b8c9e.png">
</p>
<p>
If you followed my previous post on how to install and setup os Ticket. On Login you should be met we this page. One thing to know is in osTicket there is an Admin panel, and Agent panel. On initial login you will be on Agent panel, and you can tell this because you can see Admin panel on top of the page. You can switch to Admin Panel and vice versa my clicking on it. In this tutorial we will do mocks as an Admin, that is set up roles, and asign tickets. We wil also do examples as an agent that is do tasks assigned to us. 
</p>
<br />

<h3>Configuring Roles</h3>
<p>Admin Panel -> Agents -> Roles</p>
<p>
<img width="1095" alt="Screen Shot 2023-04-13 at 8 30 41 AM" src="https://user-images.githubusercontent.com/88648101/231758904-938200cb-0390-4bb7-911a-cffe19e667a3.png">
<img width="1055" alt="Screen Shot 2023-04-13 at 8 34 25 AM" src="https://user-images.githubusercontent.com/88648101/231759837-ce7afe77-8155-4112-966f-4032177295e1.png">
<img width="1077" alt="Screen Shot 2023-04-13 at 8 36 23 AM" src="https://user-images.githubusercontent.com/88648101/231760513-95eb3ec5-b69b-47db-8fc8-e5171b07ed86.png">
<img width="1108" alt="Screen Shot 2023-04-13 at 8 36 44 AM" src="https://user-images.githubusercontent.com/88648101/231760644-a783469c-7631-4e49-a471-52cbfeb6ac67.png">
<img width="1084" alt="Screen Shot 2023-04-13 at 8 36 52 AM" src="https://user-images.githubusercontent.com/88648101/231760662-a1f2d527-3d0e-4749-aaeb-cf5e65152f3f.png"><img width="1056" alt="Screen Shot 2023-04-13 at 8 40 18 AM" src="https://user-images.githubusercontent.com/88648101/231761272-35eca4af-de4d-4b67-8180-cab2043e677d.png">
</p>
<p>
Navigate to Roles and create an Admin called Highest Admin. Assign them all the previledges. 
</p>
<br />

<h3>Configuring Departments</h3>
<p>Admin Panel -> Agents -> Departments</p>
<p>
<img width="1056" alt="Screen Shot 2023-04-13 at 8 49 02 AM" src="https://user-images.githubusercontent.com/88648101/231763560-0a7c080a-6177-4d2c-a56c-7c92c527f9ed.png">
<img width="1139" alt="Screen Shot 2023-04-13 at 8 52 53 AM" src="https://user-images.githubusercontent.com/88648101/231764925-51b25752-6e2f-4618-b971-e4859666df00.png">
<img width="1098" alt="Screen Shot 2023-04-13 at 8 56 14 AM" src="https://user-images.githubusercontent.com/88648101/231765425-9f09428a-7dfc-4c87-a4cb-131d87ef3777.png">
</p>
<p>
Navigate to Departments, add new Departments and call it System Administrators.
</p>
<br />

<h3>Configuring Teams</h3>
<p>Admin Panel -> Agents -> Teams</p>
<p>
<img width="1065" alt="Screen Shot 2023-04-13 at 9 20 18 AM" src="https://user-images.githubusercontent.com/88648101/231772726-bbc55563-6fab-4171-a79a-b97fbec25143.png">
<img width="1058" alt="Screen Shot 2023-04-13 at 9 22 02 AM" src="https://user-images.githubusercontent.com/88648101/231772795-658bbd26-5811-4211-b821-f89c61af4e82.png">
<img width="1044" alt="Screen Shot 2023-04-13 at 9 22 15 AM" src="https://user-images.githubusercontent.com/88648101/231772840-839165cd-a00f-4433-858b-0eb9d7d19dab.png">

</p>
<p>
Navigate to Teams, add new Team and call it A-Team. Add yourself as a memeber.
</p>
<br />

<h3>Configuring Tickets</h3>
<p>Admin Panel -> Settings -> Users - Authentication Settings</p>
<p>
<img width="1040" alt="Screen Shot 2023-04-13 at 9 33 56 AM" src="https://user-images.githubusercontent.com/88648101/231775408-174e98b5-8a5a-4183-90a9-adb8666c3689.png">
</p>
<p>
Navigate to Users Setting, Make sure "Require registration and login to create tickets" is unchecked. This is to allow everyone the priviledge to create tickets.
</p>
<br />

<h3>Configuring Agents</h3>
<p>Admin Panel -> Agents -> Add New</p>
<p>
<img width="1166" alt="Screen Shot 2023-04-13 at 11 36 55 AM" src="https://user-images.githubusercontent.com/88648101/231811692-69719cce-7d3a-48d6-9c31-457f50ab054e.png">
<img width="926" alt="Screen Shot 2023-04-13 at 11 43 40 AM" src="https://user-images.githubusercontent.com/88648101/231814750-dafb1935-deea-43c8-9f0a-70355dc20f0b.png">
<img width="722" alt="Screen Shot 2023-04-13 at 11 40 29 AM" src="https://user-images.githubusercontent.com/88648101/231814792-177daccc-b8d7-4c22-9387-931062a1c540.png">
<img width="1013" alt="Screen Shot 2023-04-13 at 11 45 13 AM" src="https://user-images.githubusercontent.com/88648101/231814825-60b13c05-9cf7-410c-b0c4-959c001cd38b.png">
<img width="1035" alt="Screen Shot 2023-04-13 at 11 48 40 AM" src="https://user-images.githubusercontent.com/88648101/231814987-cf9af747-6e70-4bc6-b5f4-a1b6b5b18669.png">

</p>
<p>
Navigate to Agents and , add new Agents; Jane Doe, and John Doe.
</p>
<br />


