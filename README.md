<p align="center">
<img src="https://i.imgur.com/ANEJma8.jpg"  height="50%" width="50%" alt="VPN Logo"/>
</p>

<h1>VPN Setup and Usage</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Virtual Private Network
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<p>
In this tutorial I will be showing you how a VPN works. VPNs can be used to securely link to networks together from one location to another, being able to send condesne and exncrypted data to each other. You can use a VPN to connect to resources at your work from your own home.<br />

Okay now that we know what a VPN is we can start by checking our current IP Address using a Virtual machine, we can use our own device but for the purpose of this tutorial I will be using a VM for privacy reasons. Go over to this link I have provided below and you should see your IPv4 Address as well as the City, Region and Country that you are located.
https://whatismyipaddress.com/
</p>

<p>
<img src="https://i.imgur.com/6XvYu98.png" height="40%" width="40%" alt="Current IP Address"/>
</p>

<p>
Lets check a website such as Amazon, as we can compare this website to Amazon on the browser using a VPN later in this tutorial.
</p>

<p>
<img src="https://i.imgur.com/JnpP9Mm.png" height="40%" width="40%" alt="Amazon in current region"/>
</p>

<p>
Next lets start using a VPN, I will be using Proton VPN in this example. Link for Proton VPN:
Simply create an account and download Proton VPN to begin the next step. Once installed, login to Proton VPN and connect to a VPN server in another country. For this example I will connect to Japan, to do so simply hover over the country and select "connect".
</p>

<p>
<img src="https://i.imgur.com/lGOaxzp.png" height="40%" width="40%" alt="VPN connected to Netherlands"/>
</p>

<p>
After connecting to the VPN server in another country, restart your browser and go back to https://whatismyipaddress.com/ to see your new IP Address, Country, City and Region.
</p>

<p>
<img src="https://i.imgur.com/WdKfY5d.png" height="40%" width="40%" alt="New IP Address and region"/>
</p>

<p>
While still connected to the VPN server, we can browse to websites such as Google, Disney and/or Amazon to see the diffrence in the sites compared to our own location without the use of a VPN. For example the language or URL may change. 
</p>

<p>
<img src="https://i.imgur.com/NNI7Gx9.png" height="40%" width="40%" alt="Amazon in another region with the use of a vpn"/>
</p>
