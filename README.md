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
- Configure Agents(workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (When users create a ticket)

<h2>Configuration Steps</h2>

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

<p>

<img width="600" alt="Configure Roles - Image 1 " src="https://github.com/user-attachments/assets/e0ad981a-56f9-4dfc-94e6-7daa40c493fa" />
<img width="604" alt="Image 1 Part 2" src="https://github.com/user-attachments/assets/a9b39dd1-cec3-4bfb-b810-af9590431542" />

</p>
<p>
- In osTicket you configure roles for grouping permissions.

</p>


https://github.com/user-attachments/assets/5c125661-aa44-40b9-ad4e-bf89f3aee146



- Admin Panel -> Agents -> Roles > Add new role , for this example (Supreme Admin)
<br />

<p>
<img width="400" alt="Add a Department" src="https://github.com/user-attachments/assets/bf82a8c1-2a9a-4869-8056-1c9329f6fe33" />
</p>
<p>
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins vs Networking
- Admin Panel > Agents > Departments > Choose Departments, for this example (SysAdmins)
<br />

<p>
<img width="500" alt="Add New Team" src="https://github.com/user-attachments/assets/7a1b2d42-abed-499e-bdc6-0abc84a78c40" />
<img width="509" alt="Allow everyone to create tickets" src="https://github.com/user-attachments/assets/c5f7b6e1-860c-485f-86ad-b3a13816be9c" />

</p>
<p>
- Configure Teams 
</p> - Admin Panel > Agents > Teams (Pull Agents from different departments) > for this example (Online Banking)
</p> - You can also allow anyone to create tickets
</p> - Admin Panel > Settings > User Settings (UNCHECK: unregistered users can create tickets)
<br />
<p>
<img width="500" alt="Add Agents" src="https://github.com/user-attachments/assets/e3f442e6-2413-4d76-962d-e5f43d336890" />

https://github.com/user-attachments/assets/aa5a3671-489a-4eb6-9497-d6e433dcfde3

</p>

* Configure Agents (workers)
* Admin Panel > Agents > Add new
* Jane (Dept: SysAdmins)
* John (Dept: Support)
<br />

<p>
<img width="500" alt="Adding USers" src="https://github.com/user-attachments/assets/1ef82ae9-a6ed-40c8-bb94-d0f416764bd4" />
<img width="400" alt="Add User PArt 2" src="https://github.com/user-attachments/assets/9e034ce5-85f4-4bf9-99b0-a7708ada945b" />

</p>

* Configure Users (customers)
* Agent Panel > Users > Add New
* Karen
<br />

<p>
<img width="500" alt="Add SLA " src="https://github.com/user-attachments/assets/0ebd92fa-6b74-404f-936a-d2bc510f44c5" />
<img width="500" alt="Sev A " src="https://github.com/user-attachments/assets/c7e25f87-d94b-4a0f-a875-a61557a0d073" />
<img width="500" alt="Sev B" src="https://github.com/user-attachments/assets/6ee093e1-d646-41f8-8135-2b67967b4b37" />
<img width="500" alt="Sev C" src="https://github.com/user-attachments/assets/cfb09144-5fe7-4106-9d32-f9abc59afcfe" />

</p>

* Configure SLA 
* Admin Panel > Manage > SLA 
* Sev-A
* Sev-B
* Sev-C 
<br />

<p>
<img width="500" alt="Add NEw Help Topic" src="https://github.com/user-attachments/assets/e58c588e-5cd0-46de-8dff-98e0402b8bb8" />
<img width="500" alt="Help Topic PArt 2" src="https://github.com/user-attachments/assets/2c5265ad-68ed-4922-8387-c50eb2a9be50" />
<img width="500" alt="Help Topic Part 2 1" src="https://github.com/user-attachments/assets/7c7b91c5-8398-4cb6-9ab7-5062dff9e1bb" />


</p>

* Configure Help Topics (For when users create a ticket)
* Admin Panel > Manage > Help Topics
* Business Critical Outage
* Personal Computer Issues
* Equipment Request
* Password Reset
* Other 
