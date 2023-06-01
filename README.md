# VPN-Configuration-Setup
<p align="center">
<img src="https://i.imgur.com/7CwjoFq.jpg" alt="osTicket logo"/>
</p>

<h1>VPN setup and Usage </h1>
This tutorial outlines the prerequisites,installation, and usage of Proton VPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create Virtual Machine
- Sign up for Proton VPN
- Browse within the Virtual Machine with Proton VPN

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/hNpE81B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first step of this lab will be to create a Virtual Machine within Azure in another geographic location (try a different country). For example I am using Southeast Asia. The resource group will be created upon the VM being created.
</p>
<br />

<p>
<img src="https://i.imgur.com/eiL9vy2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
While the Virtual Machine is being created browse to https://whatismyipaddress.com/ and take note of this in a text file . After the Virtual Machine is created also browse to https://whatismyipaddress.com/ and take note of this in a text file as well.
</p>
<br />

<p>
<img src="https://i.imgur.com/xHTjhwV.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On your home computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
Back within your VM, download the Proton VPN client.
Login to the VPN and choose a VPN server in yet another country (such as Japan)
Browse to https://whatismyipaddress.com/  and take note of this in a text file
.
</p>
<br />
<p>
<img src="https://i.imgur.com/WgwAW6D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
