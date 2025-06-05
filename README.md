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

- Item 1: Roles
- Item 2: Departments
- Item 3: Teams
- Item 4 Agents(workers) and Users(customers)
- Item 5: SLAs and Help topics

 Items 1-5 Should be in the osTickets site. 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/XrcYXDl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The roles are the accessiblity that an agent of osTicket will have at their position of the job. One person can have all access/supreme admin that kind of poeple can have all the permission like creating a ticket on behalf of the user. Instead the view only people can just view the ticket. In order to locate it you want to go in the osticket ->admin pane -> agents-> roles. As you can see there is some options departments,agents and teams in the image above. Department section is for selecting the departments such as maintance, support or system administrators. The teams selection is for selection your new or old agents group. 
</p>
<br />

<p>
 
Admin Panel 

<img src="https://i.imgur.com/qU756gp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Agent Panel

 <img src="https://i.imgur.com/hfuOPXa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The agent's section will show you all your agents and their usernames aswell as the department they are in including yourself. The way you can locate is by going  to admin panel-> agents-> agents you can only see if you are on the admin panel but if you are on the agents panel you can see the user's ticket that has been issued. The way to get to the users selection is by going to agent panel -> user.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ii1XSfH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 The SLA (Service Level Agreements) it can tell what kind of ticket the priorty such as the sev-a has one hour that you work and have done but the others you will have more time to work. The SLAs can help you determine what kind of help topic is and how long you have to work on the help topics such as resetting password you have time to work on it. The way you can locate it is by going to Admin Panel-> Manage-> SLA.
</p>
<br />
