<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
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

- Create 2 VMs that are on the same domain with a created admin and employee. Also able to logged in remotely without the pretext "mydomain.com"
- Create folders "_EMPLOYEES & _ADMINS"
- Upload the script to add more created employees into Windows Powershell ISE as an administrator
- Able to log into "client-1" as a created employee

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/SQiJVCa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created 2 virtual machines that are able to ping each other and on the same domain
</p>
<br />

<p>
<img src="https://i.imgur.com/B4khuA9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Logged into DC-1 as created admin, Tony Stark, without having to use the pretext "mydomain.com"
</p>
<br />

<p>
<img src="https://i.imgur.com/ij5Icdi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once logged on ran Windows Powershell ISE as an administrator 
</p>
<br />
<p>
<img src="https://i.imgur.com/JT9FvZ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Uploaded the script to add more employees
</p>
<br />
<p>
<img src="https://i.imgur.com/18zjJLA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the ADUC, Active Directory Users and Computers, add "_EMPLOYEES & _ADMINS" folders. Inside the "_EMPLOYEES" folder is where the created users are upload and added to the domain
</p>
<br />
<p>
<img src="https://i.imgur.com/yw0wttk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/oEm5NvW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Logged into client-1 remotely as created user "qol.jap" 
</p>
<br />
