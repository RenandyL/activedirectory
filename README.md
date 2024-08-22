<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Log in to Azure, create a virtual machine
- Install Active Directory within the VM

<h2>Deployment and Configuration Steps</h2>

<p>
Active Directory in VM.
</p>
<p>
<img src="https://github.com/user-attachments/assets/e0deff2e-3169-482f-a69d-239c71a3a943" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Create an Organizational Unit (OU) called “_EMPLOYEES” and “_ADMINS”.
</p>
<p>
<img src="https://github.com/user-attachments/assets/ebd5c2fa-767a-4f01-9e1d-b0295e4011c3" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Add a user to a group.
</p>
<p>
<img src="https://github.com/user-attachments/assets/4641604b-4f13-488a-9c68-05ce979ef14f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Create new users using PowerShell script.
</p>
<p>
<img src="https://github.com/user-attachments/assets/e17d5697-82e5-4751-97a2-bd7661c41b92" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/c7b376e4-12a6-454f-a01e-45c8b70c375a" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<br />
