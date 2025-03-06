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
<img src="https://github.com/user-attachments/assets/91a3dd34-762a-4c62-af27-b2025b3e6638" height="80%" width="80%" />
</p>
<p>
Now, we are going to copy the contents of a script into a newly created PowerShell file to run that script.
</p>
<br />



<p>
<img src="https://github.com/user-attachments/assets/d8a9d7e3-d263-4bf6-bf26-ee4110a9dc22" height="80%" width="80%" />
</p>
<p>
Save the script on the desktop 
</p>
<br />



<p>
<img src="https://github.com/user-attachments/assets/f4bdc473-1a39-422a-b078-0f960a6085a6" height="80%" width="80%" />
</p>
<p>
Run the script.
</p>
<br />




<p>
<img src="https://github.com/user-attachments/assets/d857c30b-5d9f-446f-bc94-3241c8bc991b" height="80%" width="80%" />
</p>
<p>
We have just created 100 users.
</p>
<br />




<p>
<img src="https://github.com/user-attachments/assets/6985e12c-0fdf-4362-a4f0-f34cc46c1fc1" height="80%" width="80%" />
<img src="https://github.com/user-attachments/assets/aa9f711e-87d8-4e7f-90f0-480fc3f76fc0" height="80%" width="80%" />
</p>
<p>
Next, we're going to open Active Directory and observe the accounts in the appropriate organizational unit.
</p>
<br />




<p>
<img src="https://github.com/user-attachments/assets/81a3934a-bd8f-4beb-8798-b97d0ebc169f" height="80%" width="80%" />
<img src="https://github.com/user-attachments/assets/9d162c1e-613f-4f7a-b98b-05849de447bd" height="80%" width="80%" />
<img src="https://github.com/user-attachments/assets/bf9d90c2-2076-4817-9035-9f932b6e95ed" height="80%" width="80%" />
</p>
<p>
Finally, we'll log into the client PC with one of the newly created accounts.
</p>
<br />


































