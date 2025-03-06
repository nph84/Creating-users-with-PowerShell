<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the process of creating multiple users in Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- Power Shell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup remote desktop for non-administrative users on client PC
- Create a lot of additional users and attempt to log into client PC with one of the users


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/7a6ae69d-91be-47a2-96db-192ac870feb3" height="80%" width="80%" />
</p>
<p>
First, we will log into the client PC as the administrator created in the last step.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/9ae9f14f-31d2-4634-a3ef-3d734a46ec90" height="80%" width="80%" />
<img src="https://github.com/user-attachments/assets/e53db424-c726-40e7-8ef4-ad7ff03029ed" height="80%" width="80%" />
<img src="https://github.com/user-attachments/assets/e1b965cc-3114-4869-9102-2e1dc789a1b8" height="80%" width="80%" />
<img src="https://github.com/user-attachments/assets/c5b9562a-2490-4bdd-ba13-21d9da826576" height="80%" width="80%" />
</p>
<p>
Navigate to remote desktop by right-clicking on the start button and clicking on "System" as we will be granting domain users access to remote desktop.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/68a87e7a-59d6-4120-aab5-17f54c50da06" height="80%" width="80%" />
</p>
<p>
All members of the domain now have access to the client PC via remote desktop.
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/882d2461-8e7b-4cf0-bf7d-400722a27377" height="80%" width="80%" />
</p>
<p>
Next, we will log into the domain PC as the previously created administrator and open PowerShell ISE as an administrator.
</p>
<br />



<p>
<img src="https://github.com/user-attachments/assets/882d2461-8e7b-4cf0-bf7d-400722a27377" height="80%" width="80%" />
</p>
<p>
Now, we are going to copy the contents of a script into a newly created PowerShell file to run that script.
</p>
<br />





















































