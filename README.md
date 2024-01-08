# Active Directory Dynamics
<h2>Description</h2>

-This project underscores my proficiency in Active Directory management. I went through the meticulous setup of VirtualBox, Windows Server 2019, and linked clones, seamlessly integrating Windows 10 clients. Crafted a bespoke Active Directory template for over 1000 user accounts, I delved into the intricacies of the domain, configuring settings, server names, TCP/IP settings, and optimizing remote desktop functionalities on Windows Server 2019.


-In steering this tech project, I extended beyond basic configurations - implementing Group Policy Objects (GPO) within Active Directory, prioritizing not only functionality but also creating a streamlined and efficient organizational structure. This project exemplifies my holistic approach to system management.

-Harnessing the power of PowerShell scripting, I employed an efficient strategy to add over 1000 users to Active Directory. This not only significantly saved time but also greatly enhanced operational efficiency, exemplifying my commitment to leveraging technology for streamlined and effective processes.


</b>
<h2>Languages and Utilities Used</h2>

- <b>Oracle VM VirtualBox</b> 
- <b>Powershell</b>

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b> (Enterprise Evaluation)

<h2>Simplified Program walk-through:</h2>

<p align="center">
Install Windows Server 2019: <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/59d1097b-5c0a-4529-8f00-daa45e50099a" height="50%" width="50%"/>
<br />
<br />
Add AD DS and promote server to DC:  <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/5549e4ec-776b-4a56-bb5e-cc555e42dabf" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Create new user and admin: <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/e45884bf-10e0-44e9-bea6-1b04901ca8e7" height="50%" width="50%" alt="ADD"/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/5c5ccd38-c9fb-410f-aad8-3e5ef76ff034" height="50%" width="50%" alt="ADD"/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/2e773026-1e9d-4236-89f9-460691b2733f" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Install Windows 10 on another machine, configure DC and Windows 10 machine to be in the same network :  <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/ce1e16e9-1b57-401c-8361-5fdb65445d6a" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Configure the DNS on Windows 10 machine to the DC which will be the DNS provider:  <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/1ad6b4a8-9839-4e63-8817-f691d92f5aef" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Add Windows 10 to ActiveDirectoryDynamics.com domain:  <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/e840bcb6-58cb-471d-842b-abd38e90eb77" height="50%" width="50%" alt="ADD"/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/30be1e11-bd6e-4bef-8f4c-130a7f15d57a" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Verify on the DC's server manager:  <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/0b5c58db-a56f-4fe0-9e07-e1c21d267b60" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Simplify adding 1000+ users to directory using PowerShell scripting:  <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/81ccdf71-abf5-4d5b-87d3-4ac24b420a8c" height="50%" width="50%" alt="ADD"/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/4e33d2dd-9729-40aa-9b2e-a2e2945881e1" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Execute PowerShell script:  <br/>
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/1fd36a37-1469-443d-b95b-83df1456e85e" height="50%" width="50%" alt="ADD"/>
<br />
<br />
Verify using Active Directory Users and Computers:
<img src="https://github.com/PaviKotees/ActiveDirectoryLab/assets/154454339/29293edb-a0bd-4de1-9be7-cf0198578619" height="50%" width="50%" alt="ADD"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
