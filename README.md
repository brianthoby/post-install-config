<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket and its components

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

-	set up roles & permissions
- Create departments & teams
- Add and configure agents & users
- Establish Help Topics & SLA (Service Level Agreements) policies

<h2>Configuration Steps</h2>
<img width="1920" height="1039" alt="1" src="https://github.com/user-attachments/assets/a8d0115f-6c2a-40a4-a084-69811245c223" />



- These 2 pages displayed is the general end user's ticket submission page and on the right is for actual help desk agents to manage, create, and/or resolve tickets
- osTicket provides two main interfaces:
  - User Panel: Where customers (end-users) submit and track tickets.
  - Agent/Admin Panel: Where help desk staff manage tickets and system settings.
- Admins control system-wide settings, while agents primarily resolve tickets.

**ROLES**
<img width="961" height="359" alt="4" src="https://github.com/user-attachments/assets/1ed90f84-cbc5-48ee-9f8f-35064efa3cf2" />
<img width="960" height="884" alt="5" src="https://github.com/user-attachments/assets/285ee89a-4f22-4cf3-8219-20dae593257a" />



- Roles define what agents are allowed to do within osTicket, assigns levels of access, roles is meant to group permissions
- Default access types include: View, Limited, Expanded, and Full.
- You can also create custom roles with granular permissions.
- Default and custome roles can be toggled on/off without deleting.

**DEPARTMENTS**

<img width="961" height="359" alt="4" src="https://github.com/user-attachments/assets/1772de5d-8d71-4726-bf31-ea76a74e3ce9" />
<img width="960" height="884" alt="5" src="https://github.com/user-attachments/assets/41335d87-e6f1-441b-81c3-a9fc43ce18b8" />


- Departments can be located under agents as well but in its own tab
- Departments are used to organize tickets based on business divisions.
- You can restrict ticket visibility per department, helping define data access boundaries.
- Example: IT Support, HR Helpdesk, Billing — each with its own ticket queue.

**TEAMS**
<img width="961" height="328" alt="6" src="https://github.com/user-attachments/assets/02473f7a-f33e-4d54-b446-7310e5dc3c72" />
<img width="962" height="708" alt="7" src="https://github.com/user-attachments/assets/3185d023-c7ce-47ea-9dd3-9b77bbd90d1a" />


- Teams is another tab within agents
- Teams allow you to build cross-functional groups of agents.
- Typically used when different departments need to collaborate.
- Can be set up to manage specific ticket types or complex request

**AGENT CONFIGURATION**
<img width="959" height="714" alt="8" src="https://github.com/user-attachments/assets/fe92c10e-e8f4-4498-b4ab-cf09c2c4949e" />


- User settings is where mass adjustments are made and/or dictate how users interact with osTicket

<img width="968" height="798" alt="9" src="https://github.com/user-attachments/assets/b2a4ec3b-9448-4e77-b084-8852c9e047ce" />
<img width="962" height="563" alt="10" src="https://github.com/user-attachments/assets/c9e9bbe5-f769-4857-baee-fef96b3e9743" />
<img width="963" height="534" alt="11" src="https://github.com/user-attachments/assets/af63ba2d-1b30-4148-84d7-94fa13e18624" />
<img width="966" height="459" alt="12" src="https://github.com/user-attachments/assets/059bc833-d4e5-45f7-814f-4f293ab9df11" />


- Adding users is under the agents tab of agents
- Here is where user information is filled to be created, granted access, permissions, and assigned a team
- personal and generic info is stored to create pr adjust accounts
- Allows you to build a controlled agent environment with proper scope of access.

**USER MANAGEMENT**
<img width="957" height="347" alt="13" src="https://github.com/user-attachments/assets/f32212b6-394a-4187-945e-f610968c2011" />


- going into the agent panel, a look from a help desk agents perspective is displayed in the image above
- Users can be created from their users tab by clicking "add user", or when submitting a ticket
**SLA**
<img width="961" height="325" alt="14" src="https://github.com/user-attachments/assets/371bee63-9451-4a65-8fca-0206f369e46b" />
<img width="964" height="694" alt="15" src="https://github.com/user-attachments/assets/2a69253b-c65d-4e1c-afa4-55c0c439aeaa" />


- SLA's or Service Level Agreements identify what the expected levels of service are (performance, responsibilities, and consequences)
- Defining response and resolution expectations, multiple SLA plans can be created and different SLA's can be applied to different help topics or departments

**HELP TOPICS**
<img width="963" height="666" alt="16" src="https://github.com/user-attachments/assets/31df8af0-eff7-4e2c-9f54-d9773a4352e1" />


- Help Topics let users categorize their issue when submitting a ticket.
- Example topics: "Password Reset," "Network Issue," "Equipment Request."
- Helps with automatic routing and setting expectations from the start.
- Used to get users to the right person

**DONE**

*This configuration ensures osTicket is not just installed, but optimized for real-world use.*
- You now have:
  - A structured team system
  - Clear responsibilities
  - Helpdesk logic mapped to real business needs
This setup simulates a production-ready environment reflecting modern IT support workflows.

Continue to **[Ticket Lifecycle](https://github.com/brianthoby/ticket-lifecycle)**
