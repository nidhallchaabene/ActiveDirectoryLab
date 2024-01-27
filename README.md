<h1>Active Directory Home Lab</h1>



<h2>Description</h2>
This project utilizes Oracle VirtualBox to create a realistic testing environment for Active Directory scenarios. It includes domain controllers, and a custom Powershell script that generates unique usernames, and automates user addition to the Active Directory.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Virtual Box</b>
- <b>Server 2019</b>

<h2>Architecture</h2>
<img src="https://imgur.com/FqcB1hX.png" height="80%" width="80%" alt="Architecutre"/>


<h2>Program Walkthrough:</h2>

<p align="center">
Installing The AD: <br/>
<img src="https://imgur.com/3ZXAjt9.png" height="80%" width="80%" alt="AD steps"/>
<br />
<br />
Configuring The Domain:  <br/>
<img src="https://imgur.com/OKYinZq.png" height="80%" width="80%" alt="AD steps"/>
<br />
<br />
Installing The DHCP: <br/>
<img src="https://imgur.com/PkGuJOZ.png" height="80%" width="80%" alt="AD steps"/>
<br />
<br />
Configuring The DHCP Pool:  <br/>
<img src="https://imgur.com/ZQ9Lg7s.png" height="80%" width="80%" alt="AD steps"/>
<br />
<br />
Creating Users With Powershell (may take some time):  <br/>
<img src="https://imgur.com/jzwdnhg.png" height="80%" width="80%" alt="AD steps"/>
<br />
<br />
Client1 (Windows 10 VM) is Part Of The Domain:  <br/>
<img src="https://imgur.com/CLPUcbR.png" height="80%" width="80%" alt="AD steps"/>
<br />
<br />
Client1 Successfully Pinging The Domain Controller And The Internet:  <br/>
<img src="https://imgur.com/yRPWhjC.png" height="80%" width="80%" alt="AD steps"/>
<br />
<br />
Successful User Login:  <br/>
<img src="https://imgur.com/6DJuSbh.png" height="80%" width="80%" alt="AD steps"/>
</p>
