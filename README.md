<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
This home lab was put together to test and practice my knowledge of Active Directory by establishing a server, adding/removing users to a network, and setting up DHCP to allow for individual IP addresses. 
<br />
<br />
This lab was completed by following the tutorial posted by Josh Madakor: https://youtu.be/MHsI8hJmggI?list=PLqBeiU46hx1H--SNfTrohTOWeqkK-M2Y0  
<br />



<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b><a href="https://www.virtualbox.org/wiki/Downloads">Oracle Virtual Box</a></b>
- <b><a href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022"> Server 2022 ISO</a></b>
- <b><a href="https://www.microsoft.com/en-us/software-download/windows10">Windows 10 ISO</a></b>
- <b><a href="https://github.com/joshmadakor1/AD_PS">Account Creation Script</a></b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server 2022</b>


<h2>Program walk-through:</h2>

<p align="center">
Download Virtualbox: <br/>
<img src="https://imgur.com/KUlvdTx.png" height="80%" width="80%" alt="Virtual Box Download"/>
<br />
<br />
Download Windows 10 ISO:  <br/>
<img src="https://imgur.com/cT0P0Ek.png" height="80%" width="80%" alt="Windows 10 ISO"/>
<br />
<br />
Download Windows 2022 Server: <br/>
<img src="https://imgur.com/5bQFbDZ.png" height="80%" width="80%" alt="Windows Server Download"/>
<br />
<br />
Create Virtual Machines:  <br/>
<img src="https://i.imgur.com/PKMMNHx.png" height="80%" width="80%" alt="Create Virtual Machines"/>
<br />
<br />
<p2 align=center> At this point, I followed the steps for creating the server's fundamental aspects, including allocating memory[50GB] and RAM [4GB]. I bumped up the cores [4] for a smoother experience and enabled bidirectional for both "Drag'n'Drop" and "Shared Clipboard."</p2>
<br />
<br />
<p3 align=center><b>Networking:</b> Ensured that the server could connect to the Internet by setting 'Adapter 1' to NAT and 'Adapter 2' to the Internal Network</p3>
<br />
<br />
Install Guest Additions:  <br/>
<img src="https://imgur.com/0wXQMkT.png" height="80%" width="80%" alt="Install Guest Additions"/>
<br />
<br />
Set-Up IP Addressing:  <br/>
<img src="https://imgur.com/tGiJX8E.png" width="80%" alt="Set-Up IP Addressing"/>
<br />
<br />
Install Active Directory Domain Services:  <br/>
<img src="" height="80%" width="80%" alt="Install ADDS"/>
<br />
<br />
Post Deployment Configurations:  <br/>
<img src="" height="80%" width="80%" alt="Post Deployment Config"/>
<br />
<br />
Dedicated Domain Admin Account:  <br/>
<img src="" height="80%" width="80%" alt="Dedicated Admin Account"/>
<br />
<br />
Create an Organizational Unit:  <br/>
<img src="" height="80%" width="80%" alt="Organizational Unit"/>
<br />
<br />
Create a New User:  <br/>
<img src="" height="80%" width="80%" alt="Create a New User"/>
<br />
<br />
Making a Domain Admin:  <br/>
<img src="" height="80%" width="80%" alt="Domain Admin"/>
<br />
<br />
Routing & Remote Access:  <br/>
<img src="" height="80%" width="80%" alt="Routing/Remote Access"/>
<br />
<br />
Install NAT:  <br/>
<img src="" height="80%" width="80%" alt="Install NAT"/>
<br />
<br />
Setting up DHCP:  <br/>
<img src="" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Add IP address for a router (DHCP):  <br/>
<img src="" height="80%" width="80%" alt="Router IP"/>
<br />
<br />
Powershell code for adding users:  <br/>
<img src="" height="80%" width="80%" alt="Adding Users"/>
<br />
<br />
Adding Windows Client to Server:  <br/>
<img src="" height="80%" width="80%" alt="Adding Windows Client"/>
<br />
<br />
</p>
<br />
<br />
<h2 align=center>Conclusion</h2>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
