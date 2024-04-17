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

* **Step 3: Config Roles on OsTicket**<p>
    - Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
    - Admin Panel -> Agents -> Roles
![add roles ](https://github.com/TerrellSowell/OsTicket/assets/161978506/43f00909-fec0-4088-be92-08dc943ea7f4)
![add roles 2](https://github.com/TerrellSowell/OsTicket/assets/161978506/5eb57d00-cfb0-4ea5-8439-f66407b75d1a)



  
