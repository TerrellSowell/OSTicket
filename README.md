# Ticketing System (OsTicket)
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>

## Objective


OsTicket is an open source Helpdesk ticketing system. This OsTicket lab is aimed to establish a controlled environment for simulating an on-site helpdesk ticketing system duties. The primary focus was to gain a better understanding of all parts of the ticketing system as both a administrator and user of the ticketing system, by mimicing real-world scenarios. This hands-on experience was designed to deepen my understanding of helpdesk functionality.

## Skills
- Advanced understanding of ticket properties.
- Proficiency in analyzing and interpreting SLAs.
- Ability to generate and recognize Departments, Permissions, and Users.
- Development of critical thinking and problem-solving skills in IT Support.

### Environments and Tools Used

- Mircosoft Azure (Virtual Machines)
- Remote Desktop
- IIS (Internet Information Services)
- OsTicket
- Windows 10

## Steps
* **Step 1:Create a Windows 10 virtual machine(VM) in Azure**<p>
    - Create a resource group
    - Create a Windows 10 virtual machine
    - Copy and paste the virtual machine's public network address into the remote desktop application to access the VM

* **Step 2: Install OsTicket**<p>
    - Install Osticket on Windows 10 virtual machine 
![install OS](https://github.com/TerrellSowell/OsTicket/assets/161978506/55e6f335-3abe-4e17-b6a7-b39b8b6d248e)<p>

* **Step 3: Configure Roles on OsTicket**<p>
    - Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
    - In Admin Panel head to Agents tab then click Roles
    - Example shown in photos I created an "Supreme Admin" role and gave it specialized persmissions
![add roles ](https://github.com/TerrellSowell/OsTicket/assets/161978506/43f00909-fec0-4088-be92-08dc943ea7f4)
![add roles 2](https://github.com/TerrellSowell/OsTicket/assets/161978506/5eb57d00-cfb0-4ea5-8439-f66407b75d1a)<p>

* **Step 4: Configure Departments**<p>
    - Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.
    - In Admin Panel head to Agents tab then click Departments
    - Example shown in photos I created an "System Adminstrators" department
![add department SLA](https://github.com/TerrellSowell/OsTicket/assets/161978506/3f63bb51-052f-4fee-a53c-cd7bd921a361)
![add department 2](https://github.com/TerrellSowell/OsTicket/assets/161978506/b4bfc135-c8ec-4c4b-888e-a6678d9995a3)<p>

* **Step 5: Configure Teams**<p>
    - Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
    - In Admin Panel head to Agents tab then click Teams
    - Example shown in photos I created two tiers of teams: Level I Support, Level II Support
![add teams](https://github.com/TerrellSowell/OsTicket/assets/161978506/2f79e029-0b9d-48f2-b175-0dba7a0efab5)
![add teams 2](https://github.com/TerrellSowell/OsTicket/assets/161978506/ce94839f-24e9-41b6-bf8b-6de5336eb422)<p>

* **Step 6: Configure Agents (I.T. Specialist)** <p>
    - Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
    - In Admin Panel head to Agents and then click Add New
    - Example shown in photos I added "Lebron James" as an agent and gave him access to specific deaprtments for ticket access.
![add new agents 1](https://github.com/TerrellSowell/OsTicket/assets/161978506/1a203573-c8e5-4d6a-8598-c38376deefac)
![adding agent LB](https://github.com/TerrellSowell/OsTicket/assets/161978506/4dff397b-de05-4d45-b8fb-c39e8c4e63ee)
![giving access to LB](https://github.com/TerrellSowell/OsTicket/assets/161978506/17ba4240-1890-4e3c-9215-57238e2218e3)<p>

* **Step 6: Configure SLA**<p>
    - SLA Plans or Service Level Agreements. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.
    - In Admin Panel head to Manage and click SLA
    - Example shown in photo 
![SLA1](https://github.com/TerrellSowell/OsTicket/assets/161978506/1a4fa2e5-a5f7-4c7f-ae39-1ebc935d22fb)
![SLA2](https://github.com/TerrellSowell/OsTicket/assets/161978506/01b5c1b1-8ce1-4b2e-a1f2-a99c4f68e602)
![SLA 3](https://github.com/TerrellSowell/OsTicket/assets/161978506/f7ad885e-9e6c-4640-978d-631f4b59e278)



* **Step 7: Configure Users (Customers)** <p>
Users can create an account and log-in to create a ticket or check a ticket’s status. Users or ticket creators are associated with their email address as the unique identifier of each user. The User Directory, located on the Agent Panel, allows agents to search tickets by user as well as create Organizations to associate the user to. Agents can be configured as internal Account Managers for tickets created by users of an Organization.
    - In Agent Panel head to Users and click Add New
    - Example shown in photo 
![support ticket os](https://github.com/TerrellSowell/OsTicket/assets/161978506/e8ef1414-824c-4d99-862f-b7563b19cc85)


  





  
