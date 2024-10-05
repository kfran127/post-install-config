<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo">
</p>

<h1>osTicket - Post-Installation Configuration</h1>

<p>In this lab, I walk through the post-installation configuration of the open-source help desk ticketing system osTicket. This includes setting up roles, departments, agents, SLAs, and help topics to streamline ticket handling and improve support operations.</p>

<h2>Post-Installation Configuration Steps</h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e4092fe7-69cf-4fc2-bbd3-56ceac67d6aa" height="80%" width="80%" alt="Admin Login Image"/>
</p>

<p><strong>Step 1: Admin/Analyst Login</strong>: I started by accessing the osTicket Admin Panel at <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a> to configure the system.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/98b81533-49c6-4485-9749-4b27b055fde8" height="80%" width="80%" alt="Roles Configuration Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/19d15661-9674-4607-8f84-7e7c9f53ff6b" height="80%" width="80%" alt="Roles Configuration Image"/>
</p>

<p><strong>Step 2: Configure Roles</strong>: In the Admin Panel, I navigated to <strong>Agents -> Roles</strong> to create roles that define permissions for agents. I created roles such as "Supreme Admin," granting full control over the helpdesk system.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bfbeb953-2e5a-45a6-80a5-afae5d1ed071" height="80%" width="80%" alt="Departments Configuration Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/cdc62b6c-f5b1-4ede-952e-9803cf9bd62c" height="80%" width="80%" alt="Departments Configuration Image"/>
</p>

<p><strong>Step 3: Configure Departments</strong>: I then went to <strong>Agents -> Departments</strong> and set up departments like "SysAdmins", "Networking", and "Help Desk" to manage ticket visibility and agent assignments.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d18a60e-1edd-44de-9d68-a9807f6f109d" height="80%" width="80%" alt="Teams Configuration Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/6e5dbf65-7b24-4fd3-86d9-9f456eb84616" height="80%" width="80%" alt="Teams Configuration Image"/>
</p>

<p><strong>Step 4: Configure Teams</strong>: Next, I configured teams by navigating to <strong>Agents -> Teams</strong>. I created teams like "Online Banking," composed of agents from multiple departments (e.g., Support and SysAdmins), to address specific types of tickets.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0abafec6-eaab-434f-8639-614394275bac" height="80%" width="80%" alt="User Settings Image"/>
</p>

<p><strong>Step 5: Configure User Settings</strong>: In the Admin Panel, I adjusted user settings by going to <strong>Settings -> User Settings</strong>. By unchecking the option "Require registration and login to create tickets," I allowed unregistered users to submit tickets. Alternatively, this option can be checked to require users to register before submitting tickets.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/af6b9d63-5123-44b8-b0c4-5b954d721f98" height="80%" width="80%" alt="Agents Configuration Image"/>
</p>

<p><strong>Step 6: Configure Agents</strong>: I added agents by going to <strong>Agents -> Add New</strong>. For example, I added agents like "David" to the SysAdmins department and "Pablo" to the Support department to handle incoming tickets.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7c41daa4-77ae-49a1-a432-d352c4e83e46" height="80%" width="80%" alt="Users Configuration Image"/>
</p>

<p><strong>Step 7: Configure Users</strong>: I added end users, who will submit tickets, by navigating to <strong>Users -> Add New</strong>. For example, I added customers such as "Daisy" and "John" to track and manage their inquiries more efficiently.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/59363d84-1d5b-4948-a75a-a8a761c2e1f4" height="80%" width="80%" alt="SLA Configuration Image"/>
</p>

<p><strong>Step 8: Configure SLA Plans</strong>: In the Admin Panel, I set up service level agreements (SLAs) by going to <strong>Manage -> SLA</strong>. I configured SLAs like "Sev-A" with a 1-hour response time and 24/7 coverage, "Sev-B" with a 4-hour response time, and "Sev-C" with an 8-hour response time during business hours.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/efbfba86-15c0-49aa-a5a6-7aa4d044000f" height="80%" width="80%" alt="Help Topics Configuration Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/cb06efcd-165f-4652-a44f-f4e49e8a3195" height="80%" width="80%" alt="Help Topics Configuration Image"/>
</p>

<p><strong>Step 9: Configure Help Topics</strong>: To streamline ticket categorization, I created help topics in <strong>Manage -> Help Topics</strong>. Some of the help topics I set up included "Business Critical Outage," "Personal Computer Issues," "Equipment Request," "Password Reset," and "Other."</p>

<p><strong>End Result</strong>: Congratulations! I have successfully completed the post-installation configuration of osTicket. My helpdesk is now fully set up to manage tickets efficiently, handle users, and provide excellent support. These configurations help improve the organization and tracking of tickets, ultimately enhancing the overall support workflow.</p>
