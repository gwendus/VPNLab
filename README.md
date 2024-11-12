<h1>VPN LAB</h1>

 <p align="center">
<br/>
<img src="https://i.imgur.com/2zGY3rs.png" height="60%" width="60%" alt="Intuition-building exercise"/>
<br />
<br />

<h2>Description</h2>
Project consists of observing IP addressing changes via a VPN on our personal and virtual machine. The utility affords us a layer of extra privacy, security, and bypasses geo-restrictions on content.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Remote Desktop</b>
- <b>ProtonVPN</b> 
- <b>whatismyIPaddress.com</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Program walk-through:</h2>

<p align="center">
1. Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE and take note of this in a text file: <br/>
<img src="https://i.imgur.com/SpnHZoJ.png" height="60%" width="60%" alt="Home computer IP (CENSORED)"/>
<br />
<br />
2. Create a resource group and windows 10 virtual machine in another geographic location (try another country):  <br/>
<img src="https://i.imgur.com/LbcqDsM.png" height="70%" width="70%" alt="Creating our resources"/>
<br />
<br />
3. Log in to the virtual machine with remote desktop. Browse to https://whatismyipaddress.com/ FROM WITHIN THE VIRTUAL MACHINE and take note of this in a text file : <br/>
<img src="https://i.imgur.com/eU3nSmc.pnga" height="70%" width="70%" alt="VM IP ADDRESS"/>
<br />
<br />
4. Sign up for Proton VPN and test the connection:  <br/>
<img src="https://i.imgur.com/cYIXEcK.png" height="70%" width="70%" alt="Sign up for Proton VPN"/>
<br />
<br />
5. Download proton client onto the virtual machine. Log in to the VPN client and choose a server in another country:  <br/>
<img src="https://i.imgur.com/01SKVek.png" height="70%" width="70%" alt="Connect to VPN in another country"/>
<br />
<br />
6. Browse to https://whatismyipaddress.com/ and take note of your IP address in a text file. Also, note that the site detected we were using a VPN!:  <br/>
<img src="https://i.imgur.com/hjcTETn.png" height="70%" width="70%" alt="IP address from VPN VM"/>
<br />
<br />
7. Observe the difference in IP addresses in our text file:  <br/>
<img src="https://i.imgur.com/ukFjtGR.png" height="40%" width="40%" alt="Different IP addresses"/>
<br />
<br />
8. Navigate to different sites and note the difference in language and address domain!:  <br/>
<img src="https://i.imgur.com/tQZWzIc.png" height="70%" width="70%" alt="disney japan"/>
<img src="https://i.imgur.com/cRkSknR.png" height="70%" width="70%" alt="amazon japan"/>
<br />
<br />
Do not forget to clean up your Azure resources and delete your resource group and virtual machine!
<br />
<br />
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
