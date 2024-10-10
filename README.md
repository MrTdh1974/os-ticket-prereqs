# os-ticket-prereqs
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



List Of Prerequisites 

![image](https://github.com/user-attachments/assets/7b976a77-2c3c-4ce2-bcf8-41a32fa83966)


Installation Overview

1. Create Virtual Machines
2. Turn Windows 10 OS into a web server
3. Install all Prerequisite Programs
4. Install osTicket and confirm that it is a website running on the web server
5. Enable features and assign all permissions to osTicket
6. Complete installation by registering email and mySQL database
7. Confirm osTicket can be reached by end users on LocalHost
8. Clean up of all files that pose a security risk


Installation 
1. Create Resource Group 
2. Create Windows 10 Virtual Machine W/2 CPUs
3. Allow Azure to create Virtual Network (Vnet)
4. Prepare Windows 10 OS by turnint it into a web server
   ![image](https://github.com/user-attachments/assets/41b95b5e-337c-4ef0-9eee-d920f934f742)

   -Install & Enable IIS (Internet Information Services) on the Windows computer, including application features the IIS Management Console

5. Install Prerequisite Programs
   -Install PHP Manager
   -Install Rewrite
   -Install PHP:
     




