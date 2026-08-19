# Handheld Video Game Project
This project demonstrates the assembly of a handheld retro video game device which can play games such as Tetris.

<h2>Tools Used</h2>

- <b>Active Directory</b>
- <b>Microsoft Azure(Virtual Machines/Compute)</b>
- <b>Remote Desktop</b>
- <b>Powershell</b>


<h2>Deployment and Configuration Steps</h2>

- <b>Step 1- Create the client and domain controller virtual machines within Azure. Assign the client virtual machine the IP address of the domain controller as the DNS server.</b>
- <b>Step 2- Install Active Directory Domain Services on the domain controller virtual machine and promote it to domain controller.</b>
- <b>Step 3- Join the client virtual machine to the domain.</b>
- <b>Step 4- Allow remote desktop access to the client virtual machine.</b>
- <b>Step 5- Create 10,000 user accounts using a Powershell script and attempt to login with one of the accounts.</b>











