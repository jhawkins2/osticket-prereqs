<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Install Web Platform Installer
- Install MySQL and setup username and password
- Install C++ redistributable 
- Configue Permissions and install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/qjfEpnj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<img src="https://i.imgur.com/Ebunvpo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<p>
Before installing the prerequisites for osTicket, you want to enable Internet Information Services (IIS) with Computer Generated Imagery (CGI). Internet Information Services is a web server that allows the computer to host, deploy, and manage web applications. Because osTicket runs from a website, we need to configure Internet Information Services in on to run osTicket as a web application.
</p>
<br />

<p>
<img src="https://i.imgur.com/nBAIBlp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you want to install PHP Manager, Rewrite module, mySQL 5.5.62, PHP 7.3.8, and VC_redist.x86.exe. Once this is completed, you want to register PHP from within the Internet Information Services server and then restart the server.
</p>
<br />

<p>
<img src="https://i.imgur.com/oXvAtfa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you want to reload Internet Information Services by stopping the server and restarting the server. Now, you want to install osTicket v1.15.8. Once this is completed, you want to browse to the osTicket tab and select "Browse *.80". If this was completed successfully, the page above should appear.
</p>
<br />

<img src="https://i.imgur.com/QSVfCT9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Finally, you will install HeidiSQL and create a new session. After creating a new session, you will need to create a database called (osTicket). Once this database is created, you will need to connect to the session. Aftter you have successfully connected to the session, you should be able to login with the root credentials: Username: root     Password: Password1
