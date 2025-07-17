<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
<p>This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.</p>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
  <li>osTicket and its components</li>
</ul>

<h2>Operating System</h2>
<ul>
  <li>Windows 10 (21H2)</li>
</ul>

<h2>Post-Install Configuration Objectives</h2>
<ul>
  <li>Set up roles and permissions</li>
  <li>Create departments and teams</li>
  <li>Add and configure agents and users</li>
  <li>Establish Help Topics and SLA (Service Level Agreement) policies</li>
</ul>

<h2>Configuration Steps</h2>

<img src="https://github.com/user-attachments/assets/a8d0115f-6c2a-40a4-a084-69811245c223" />

<ul>
  <li>osTicket offers two primary interfaces:</li>
  <ul>
    <li><strong>User Panel:</strong> where end-users submit and track support tickets.</li>
    <li><strong>Agent/Admin Panel:</strong> where staff resolve tickets and manage settings.</li>
  </ul>
  <li>Admins configure global settings while agents manage the ticket queue.</li>
</ul>

<h3>Roles</h3>
<img src="https://github.com/user-attachments/assets/1ed90f84-cbc5-48ee-9f8f-35064efa3cf2" />
<img src="https://github.com/user-attachments/assets/285ee89a-4f22-4cf3-8219-20dae593257a" />
<ul>
  <li>Roles determine what permissions agents have in the system.</li>
  <li>Permission levels include: View, Limited, Expanded, and Full.</li>
  <li>You can create custom roles with fine-tuned control.</li>
  <li>Roles can be enabled or disabled as needed.</li>
</ul>

<h3>Departments</h3>
<img src="https://github.com/user-attachments/assets/1772de5d-8d71-4726-bf31-ea76a74e3ce9" />
<img src="https://github.com/user-attachments/assets/41335d87-e6f1-441b-81c3-a9fc43ce18b8" />
<ul>
  <li>Departments categorize support by business unit or function.</li>
  <li>They help segment access and ticket visibility.</li>
  <li>Examples: HR, IT, Facilities, Billing.</li>
</ul>

<h3>Teams</h3>
<img src="https://github.com/user-attachments/assets/02473f7a-f33e-4d54-b446-7310e5dc3c72" />
<img src="https://github.com/user-attachments/assets/3185d023-c7ce-47ea-9dd3-9b77bbd90d1a" />
<ul>
  <li>Teams allow you to group agents across departments.</li>
  <li>Useful for managing complex workflows that require collaboration.</li>
  <li>Ideal for specialized ticket queues or project-based assignments.</li>
</ul>

<h3>Agent Configuration</h3>
<img src="https://github.com/user-attachments/assets/fe92c10e-e8f4-4498-b4ab-cf09c2c4949e" />
<img src="https://github.com/user-attachments/assets/b2a4ec3b-9448-4e77-b084-8852c9e047ce" />
<img src="https://github.com/user-attachments/assets/c9e9bbe5-f769-4857-baee-fef96b3e9743" />
<img src="https://github.com/user-attachments/assets/af63ba2d-1b30-4148-84d7-94fa13e18624" />
<img src="https://github.com/user-attachments/assets/059bc833-d4e5-45f7-814f-4f293ab9df11" />
<ul>
  <li>Create and manage agents under the <strong>Agents</strong> tab.</li>
  <li>Set contact info, assign teams, departments, and access roles.</li>
  <li>Tailor each agent's permissions to fit their responsibilities.</li>
</ul>

<h3>User Management</h3>
<img src="https://github.com/user-attachments/assets/f32212b6-394a-4187-945e-f610968c2011" />
<ul>
  <li>Users can be added manually or created when a ticket is submitted.</li>
  <li>Manage all users from the <strong>Users</strong> tab inside the admin panel.</li>
</ul>

<h3>SLA (Service Level Agreements)</h3>
<img src="https://github.com/user-attachments/assets/371bee63-9451-4a65-8fca-0206f369e46b" />
<img src="https://github.com/user-attachments/assets/2a69253b-c65d-4e1c-afa4-55c0c439aeaa" />
<ul>
  <li>SLAs define ticket response and resolution expectations.</li>
  <li>Apply different SLA plans to different departments or help topics.</li>
  <li>This helps you manage service quality and escalation procedures.</li>
</ul>

<h3>Help Topics</h3>
<img src="https://github.com/user-attachments/assets/31df8af0-eff7-4e2c-9f54-d9773a4352e1" />
<ul>
  <li>Help Topics let users choose what type of issue they’re reporting.</li>
  <li>Examples: “Login Issue”, “Printer Not Working”, “Request Equipment”.</li>
  <li>This improves routing and enables automation and filtering.</li>
</ul>

<h2>Done</h2>
<p>This completes the post-install configuration. Your osTicket instance is now fully set up and production-ready.</p>

<ul>
  <li>Roles, teams, and permissions are structured</li>
  <li>SLA policies and help topics are active</li>
  <li>Your support process reflects your business needs</li>
</ul>

<p>Continue to: <strong><a href="https://github.com/brianthoby/ticket-lifecycle">Ticket Lifecycle</a></strong></p>
