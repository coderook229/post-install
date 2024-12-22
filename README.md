# post-install

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
Log into osTicket as an admin with the admin credentials you made at http://localhost/osTicket/scp/login.php 
</p>
<p>
  
![Screenshot 2024-12-19 213915](https://github.com/user-attachments/assets/c6c7ec63-64c7-40e8-90a8-3463e70ab60b)
</p>
<br />

<p>
Configure Roles (for grouping permissions). Go to the Admin panel of osTicket(Agent Panel will be in the top right). Click on Agents and then Roles.
Click Add New Role
  
![Screenshot 2024-12-21 154846](https://github.com/user-attachments/assets/6e495120-0f4d-4091-803d-6215662f8e06)
</p>
<p>
  Name the role, I used the name Supreme Admin and on the Permissions tab select all the permissions, on all tabs, example
  
  ![Screenshot 2024-12-21 155544](https://github.com/user-attachments/assets/67f8c2b5-8cfa-4a2d-b5d8-3cdb7a4e9337)
  
  ![Screenshot 2024-12-21 155645](https://github.com/user-attachments/assets/cd90a234-f442-41f7-901d-b585e2d5809a)
</p>

<p>
Configure Departments. Go to Agents and then Departments. Click on Add New Department

  ![Screenshot 2024-12-21 211422](https://github.com/user-attachments/assets/edc14dbd-4a1c-44fa-8c4c-ab86351c198d)
</p>
  <p>
    Choose a Top-Level Department and name it.
  
  ![Screenshot 2024-12-21 160657](https://github.com/user-attachments/assets/084a8b38-1ae4-4175-914d-c2464cd6f6dd)
</p>
<br />

<p>
Configure Teams(Pull Agents from different Departments). Click on Agents and then Teams. Click Add New Team on the right.
  
  ![Screenshot 2024-12-21 161552](https://github.com/user-attachments/assets/106027c9-1994-44ed-bd8b-6cd4a76b4222)

  Click Create Team
</p>
<br />

<p>Allow anyone to create tickets. From the Admin Panel, go to Settings then User Settings (UNCHECK: unregistered users can create tickets)
  
  ![Screenshot 2024-12-21 162601](https://github.com/user-attachments/assets/52a57bf1-ac13-4709-b5db-906ec5f6bb96)

  Make sure to save changes
</p>
<p> 
Configure Agents (workers). From the Admin Panel, Go to Agents and then Add New
  
  ![Screenshot 2024-12-21 223611](https://github.com/user-attachments/assets/92daa1d4-6119-480a-b06f-4c4b515ca347)
  <br />
Jane (Dept: SysAdmins)
John (Dept: Support)

Click the Access tab and add department and role

![Screenshot 2024-12-21 224346](https://github.com/user-attachments/assets/067bd0e4-801e-4301-bb22-631eac238e1e)


Click Set Password and uncheck Send the agent a password reset email
Make a password and uncheck Require password change at next login click Update

https://github.com/user-attachments/assets/deea2aec-65a2-4d7e-aa4b-882a399afe56

</p>
<p>
  Configure Users (customers). Click on Agent Panel(Admin Panel will be in the top right). Click on Users then Add New

https://github.com/user-attachments/assets/94e8dac5-0cb6-4c8d-b6db-54a985cf5a0f


</p>
