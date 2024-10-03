<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo">
</p>

<h1>osTicket - Post-Installation Configuration</h1>

<p>This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- PHP 7.3.8
- MySQL 5.5.62
- HeidiSQL
- osTicket v1.15.8

<h2>Operating Systems Used</h2>

- Windows 10 (22H2)

<h2>List of Prerequisites</h2>

<ul>
  <li><strong>Azure Virtual Machine:</strong> A Windows 10 VM with 4 vCPUs created in Microsoft Azure.</li>
  <li><strong>Remote Desktop Connection (RDP):</strong> Ability to connect to the VM using Remote Desktop.</li>
  <li><strong>Internet Information Services (IIS):</strong> IIS installed and configured on the Windows 10 VM to serve web applications.</li>
  <li><strong>PHP and PHP Manager:</strong> PHP installed and configured with PHP Manager on IIS to support osTicket.</li>
  <li><strong>MySQL Database:</strong> MySQL installed to store osTicket data.</li>
  <li><strong>osTicket Installation:</strong> osTicket installed and functioning on the server.</li>
</ul>

<h2>Post-Installation Configuration Steps</h2>


<p align="center">
  <img src="https://github.com/user-attachments/assets/e4092fe7-69cf-4fc2-bbd3-56ceac67d6aa" height="80%" width="80%" alt="Roles Configuration Image"/>
</p>
<p><strong>Step 1: Admin/Analyst Login</strong>: Access the osTicket Admin Panel by navigating to <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a>.


<p align="center">
  <img src="https://github.com/user-attachments/assets/98b81533-49c6-4485-9749-4b27b055fde8" height="80%" width="80%" alt="Roles Configuration Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/19d15661-9674-4607-8f84-7e7c9f53ff6b" height="80%" width="80%" alt="Roles Configuration Image"/>
</p>
<p><strong>Step 2: Configure Roles</strong>: In the Admin Panel, navigate to <strong>Agents -> Roles</strong>. Create and configure roles for grouping permissions. For example, you can create a role called "Supreme Admin" to have full control over the helpdesk system.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a7a95f18-4dc9-403c-9f36-9e9a116d261b" height="80%" width="80%" alt="Departments Configuration Image"/>
</p>
<p><strong>Step 3: Configure Departments</strong>: In the Admin Panel, go to <strong>Agents -> Departments</strong> and create departments such as "SysAdmins", "Networking", or "Help Desk" to manage ticket visibility and agent assignment within the system.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/26ebc883-a71a-480f-8a0e-b2a4b780bf43" height="80%" width="80%" alt="Teams Configuration Image"/>
</p>
<p><strong>Step 4: Configure Teams</strong>: In the Admin Panel, go to <strong>Agents -> Teams</strong>. You can pull agents from different departments and assign them to specific teams. For instance, you might create an "Online Banking" team consisting of agents from both the "Support" and "SysAdmins" departments.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0abf4fc1-d89b-485b-afd4-321f31cd458f" height="80%" width="80%" alt="User Settings Image"/>
</p>
<p><strong>Step 5: Configure User Settings</strong>: In the Admin Panel, navigate to <strong>Settings -> User Settings</strong>. If you want to require registration and login for users to create tickets, uncheck the option for "Allow anyone to create tickets". This forces users to register before submitting tickets.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ce41ebb2-699f-4e7a-bbe9-acbd11487bfd" height="80%" width="80%" alt="Agents Configuration Image"/>
</p>
<p><strong>Step 6: Configure Agents</strong>: In the Admin Panel, go to <strong>Agents -> Add New</strong> to add workers who will handle the tickets. For instance, you can create agents like "Jane" assigned to the "SysAdmins" department and "John" assigned to the "Support" department.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/54534046-bc10-4f61-92ae-3e4d5affe598" height="80%" width="80%" alt="Users Configuration Image"/>
</p>
<p><strong>Step 7: Configure Users</strong>: In the Agent Panel, navigate to <strong>Users -> Add New</strong>. Add customers who will submit tickets, such as "Karen" and "Ken". This helps you manage and track customer inquiries.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/929a4022-5260-46b5-ade8-f3ec6798c850" height="80%" width="80%" alt="SLA Configuration Image"/>
</p>
<p><strong>Step 8: Configure SLA Plans</strong>: In the Admin Panel, go to <strong>Manage -> SLA</strong> and create service level agreements (SLAs) for different severity levels. For example, create SLAs such as "Sev-A" with a 1-hour grace period and 24/7 availability, "Sev-B" with a 4-hour grace period, and "Sev-C" with an 8-hour grace period limited to business hours.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0fd3e42d-8a2a-4d6b-9305-b0d38622f5f9" height="80%" width="80%" alt="Help Topics Configuration Image"/>
</p>
<p><strong>Step 9: Configure Help Topics</strong>: In the Admin Panel, go to <strong>Manage -> Help Topics</strong>. Define topics that users can select when creating tickets, such as "Business Critical Outage", "Personal Computer Issues", "Equipment Request", "Password Reset", and "Other". This helps categorize and streamline ticket handling.</p>

<p><strong>End Result</strong>: Congratulations! You have successfully configured the post-installation settings for osTicket. Your helpdesk is now ready to handle tickets, manage users, and provide excellent support.</p>
