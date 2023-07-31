# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4


<h2>Installation Steps</h2>

![item 1](https://github.com/DGajar/osticket-prereqs/assets/140901911/e500a7ce-8027-4197-be74-11ab4a38e992)



<p>
![item 1](https://github.com/DGajar/osticket-prereqs/assets/140901911/e500a7ce-8027-4197-be74-11ab4a38e992)
</p>
<p>
When I was setting up the osTicket system you needed to create a virtual machine in Azure along with a resource group. After creating the virtual machine you must download the installation files in the c drive in order to start the osTicket system.
</p>
<br />

![item 2](https://github.com/DGajar/osticket-prereqs/assets/140901911/dc59f914-94a8-4ab4-bc12-a44b17463951)
</p>
<p>
Once everything is downloaded, you must create a profile on osTicket as an admin in order to assign roles to team members. Before we log in we must make sure that our php_imap.dll, php_intl.dll, and php_opcache are clicked as “enable” in PHP extensions, this is to improve features in osTicket.
</p>
<br />

<p>

![item 3](https://github.com/DGajar/osticket-prereqs/assets/140901911/1fa8a4b9-9822-4930-a61e-24f7434d738f)

</p>
<p>
After logging in, I assigned roles such as Supreme Admin to have access to all tickets and tasks, who can help alleviate workload in each department by assigning roles to team members  who can work on different tech issues. 
<br />

</p>
<p>
  
</p>
<p>


<p>
<p>

![item 4](https://github.com/DGajar/osticket-prereqs/assets/140901911/1e54e2f0-df28-4cfd-b18f-904c94a0b348)

Following the SLA plan, we implemented this system to prioritize tech issues from critical to less severe.  For example, if the office has had a “Business Critical Outage” this means their systems are down and 
needs to be up asap. This would be considered at (SEV-A) for critical. Another example for our SLA system, if an employee needs a password reset that would be considered a (SEV-C) for less severe. Each issue for 
help desk administrators allows them to prioritize which category of SLA needs to work on first before the ticket closes.
</p>
<br />

  


