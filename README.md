<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Microsoft Web Platform Installer (MWPI)

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)

<h2>List of Prerequisites</h2>

- Install/Enable IIS in Windows
- Install Web Platform Installer
- Open the Web platform installer after installation and add "MySQL 5.5". Also add all simple versions of "x86 PHP up until 7.3"
- Install "PHP Manager 1.5.0" for IIS 10, then finally Install Microsoft Visual C++ 2009 Redistributable Package
- Download then Install osTicket v1.15.8 unto your Computer
- Extract and copy the “upload” folder INTO c:\inetpub\wwwroot
- Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”
- Enable Extensions in IIS: Note that some extensions are not enabled
- Go back to IIS, sites -> Default -> osTicket. 
- Double-click PHP Manager, then click “Enable or disable an extension”
- Enable: php_imap.dll -> Enable: php_intl.dll -> Enable: php_opcache.dll
- Refresh the osTicket site in your browse, observe the changes
- Go to Files, and RENAME: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php TO: C:\inetpub\wwwroot\osTicket\include\ost-config.php
- Assign Permissions to "ost-config.php"    
- Disable inheritance -> Remove All 
New Permissions -> Everyone -> All
- Continue Setting up osTicket in the browser (then click Continue)
- Download and Install HeidiSQL -> Create a new session, root/Password1 -> Connect to the session -> Create a database called “osTicket”
- MySQL Database: osTicket ---> MySQL Username: root ---> MySQL Password: Password1
- Click “Install Now!” 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/PA7jUwY.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Go to Control Panels and under the "Programs" section your gonna click "Uninstall a Program".
</p>
<br />

<p>
<img src="https://i.imgur.com/QyDhJBP.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Next, your gonna click the option on the left of the screen "Turn windows features on or off".
</p>
<br />

<p>
<img src="https://i.imgur.com/hLMIj4M.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Install/Enable IIS in Windows.
</p>
<br />

<p>
<img src="https://i.imgur.com/kDVLKGj.png" height=60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Download and Install Web Platform Installer, then open app after installation.
</p>
<br />
                                                                                        <p>
<img src="https://i.imgur.com/iAmMsJM.png" height=40%" width="50%" <p float="left"> alt="Disk Sanitization Steps"/>
</p>
<p>
- Add "MySQL 5.5" to installation list. Along with all simple versions of PHP x86 up until 7.3 (IIS Express)
</p>
<br />

<p>
<img src="https://i.imgur.com/v0b0xRr.png" height=60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Add all simple versions of PHP x86 up until 7.3 (IIS Express).
</p>
<br />

 <p>
<img src="https://i.imgur.com/i7XLjaa.png"60%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Download and Install PHP Manager 1.5.0 for IIS, along with any other missing PHP x86 files.
</p>
<br />

 <p>
<img src="https://i.imgur.com/zSVvBRd.png"60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Install Microsoft Visual C++ 2008 Redistributable Package
</p>
<br />
                                                                                        
 <p>
<img src="https://i.imgur.com/INiW7OW.png"60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Install osTicket v1.15.8, then complete the configurations.

</p>
<br />                                                                                        
                                                                                      
