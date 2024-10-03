<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo">
</p>

<h1>osTicket - Post-Installation Configuration</h1>

<p>This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.</p>


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
  <img src="https://github.com/user-attachments/assets/bfbeb953-2e5a-45a6-80a5-afae5d1ed071" height="80%" width="80%" alt="Departments Configuration Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/cdc62b6c-f5b1-4ede-952e-9803cf9bd62c" height="80%" width="80%" alt="Departments Configuration Image"/>
</p>
<p><strong>Step 3: Configure Departments</strong>: In the Admin Panel, go to <strong>Agents -> Departments</strong> and create departments such as "SysAdmins", "Networking", or "Help Desk" to manage ticket visibility and agent assignment within the system.</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/9d18a60e-1edd-44de-9d68-a9807f6f109d" height="80%" width="80%" alt="Teams Configuration Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/6e5dbf65-7b24-4fd3-86d9-9f456eb84616" height="80%" width="80%" alt="Teams Configuration Image"/>
</p>
<p><strong>Step 4: Configure Teams</strong>: In the Admin Panel, go to <strong>Agents -> Teams</strong>. You can pull agents from different departments and assign them to specific teams. For instance, you might create an "Online Banking" team consisting of agents from both the "Support" and "SysAdmins" departments.</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/0abafec6-eaab-434f-8639-614394275bac" height="80%" width="80%" alt="User Settings Image"/>
</p>
<p><strong>Step 5: Configure User Settings</strong>: In the Admin Panel, navigate to <strong>Settings -> User Settings</strong>. If you uncheck "Require registration and login to create tickets", anyone will be able to submit a ticket without creating an account. If this option is checked, users will need to register and log in to submit tickets.</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/af6b9d63-5123-44b8-b0c4-5b954d721f98" height="80%" width="80%" alt="Agents Configuration Image"/>
</p>
<p><strong>Step 6: Configure Agents</strong>: In the Admin Panel, go to <strong>Agents -> Add New</strong> to add workers who will handle the tickets. For instance, you can create agents like "David" assigned to the "SysAdmins" department and "Pablo" assigned to the "Support" department.</p>

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
