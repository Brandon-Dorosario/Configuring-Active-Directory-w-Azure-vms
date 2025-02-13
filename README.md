<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This project outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Create vitual network and virtual machine on Azure
- Step 2 - Install active directory & Create admin user 
- Step 3 - Setup remote desktop for non-admin users
- Step 4 - Create users with powershell script 
- Step 5 - Configure Group Policy to Lockout the account after 5 attempts
- Step 6 - Enable , Disable accounts & monitor logs on domain controller 

<h2>Deployment and Configuration Steps</h2>

<p>
  
![dc-1vnetdns](https://github.com/user-attachments/assets/0328dd1a-67cb-43b2-a3a2-7db2cb37102d)

</p>
<p>
DC-1 Vnet configured.
</p>
<br />

<p>
  
![downloadingactivedirectory](https://github.com/user-attachments/assets/9ed3c4c3-4830-4762-a508-3a39c0062f23)

</p>
<p>
Active Directory install.
</p>
<br />

<p>
  
![orginisationalunitEMPLOYEES](https://github.com/user-attachments/assets/6d8cc4ce-6d5e-49a7-a4de-dd38e1ef1705)

</p>
<p>
Org Unit created.
</p>
<br />

<p>
  
![memberofadminsjanedoe](https://github.com/user-attachments/assets/dbdfa928-ac3f-4321-8292-d4b7ddcedd40)

</p>
<p>
Admin account created. 
</p>
<br />

</p>

![remoteaccesspermissions](https://github.com/user-attachments/assets/59ecee88-5e8e-4762-9bce-1aa2d4c647b0)

</p>
<p>
Remote access permissions. 
</p>
<br />

</p>

![USERACCOUNTSCREATEDAD](https://github.com/user-attachments/assets/346810d5-1945-4d8e-8c64-4a8dbc9e83aa)

</p>
<p>
User accounts created.
</p>
<br />

</p>

![ADaccountlockoutsettings](https://github.com/user-attachments/assets/a079bebf-0ec3-4f99-a99c-22b0d9842ea2)

</p>
<p>
User account lockout settings.
</p>
<br />

</p>

![eventvwr](https://github.com/user-attachments/assets/c4b99746-fa56-4835-be3c-a7aebc26576e)

</p>
<p>
Account log activity.
</p>
<br />

</p>


