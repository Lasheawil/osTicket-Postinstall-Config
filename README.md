<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure (Roles, Departments, and Teams)
- Allow anyone to create tickets
- Configure (Agents/Workers, and Users/Customers)
- Configure SLA
- Configure help topics 

<h2>Configuration Steps</h2>

<p align="center">
 <br/></b>
 I logged in as the admin, Configured roles to create a new <b>supreme admin role</b>, and applied all permissions.  Configured teams to be able to pull specefic teams to perform specefic tasks. Created different levels of support, such as, level 1 and level 2.
 <img src="https://github.com/Lasheawil/osTicket-Postinstall-Config/blob/main/osTicket%20Postinstall/permissions.png" height="80%" width="80%"/>
 <br/>
 Configured departments and created a systems administration department.
 <br/>
 <img src="https://github.com/Lasheawil/osTicket-Postinstall-Config/blob/main/osTicket%20Postinstall/sysadmin%20first.png" height="80%" width="80%"/>
 <br/>
 Allow anyone to create tickets. "Uncheck" <B>Require registration and login to create tickets</B> This will not require users to register in order to create tickets.
 <br/>
 <img src="https://github.com/Lasheawil/osTicket-Postinstall-Config/blob/main/osTicket%20Postinstall/user%20settings.png" height="80%" width="80%"/>

<p align="center">
I configured and created users karen and Ken; these individuals (workers) will create tickets.
 <img src="https://github.com/Lasheawil/osTicket-Postinstall-Config/blob/main/osTicket%20Postinstall/osUsers.png" height="80%" width="80%"/>
 <br/>

 <p align="center">
 Configured and added Jane and John with different permissions. They will respond to the tickets.
 <img src="https://github.com/Lasheawil/osTicket-Postinstall-Config/blob/main/osTicket%20Postinstall/users.png" height="80%" width="80%"/>
 <br/>

 <p align="center">
 As admin, I Configured SLA (Service Level Agreement). This gives a timeframe to complete tasks. Create 3 SLA's, Sev-A (1 hour, 24/7), Sev-B (8 hours, 24/7), and Sev-C (8 hours, business hours)
 <img src="https://github.com/Lasheawil/osTicket-Postinstall-Config/blob/main/osTicket%20Postinstall/SLA.png" height="80%" width="80%"/>
 <br/>
