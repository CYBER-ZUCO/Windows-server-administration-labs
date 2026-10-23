# Windows-server-administration-labs
My hands-on Windows Server Administration labs and collage projects, including the World tours network.

## WorldTours Server Administration Project

This project documents my hands-on experience with Windows server 2022 as part of my Networking and Cybersecurity course at college.

### Server Configuration
- Server name: WT-DC01
- Operating systems: Windows server 2022 standard
- Virtualisation software: Oracle VirtualBox
- RAM: 8 GB
- Hard Drive: 50 GB


### Network Configuration
- IP Address: 192.168.10.254
- Subnet mask: 255.255.255.0
- Default Gateway: 192.168.10.1
- Network Type: Internal network
- Virtual Network: WTswitch

 ### Practical Tasks Completed

- Installed Windows Server 2022
- configured the virtual machine in virtualbox
- Renamed the server to WT-DC01
- Configured a static IPV4 address
- Checked the network adapter settings
- restarted the server to apply changes
- Created a virtual machine snapshot

### What I Have Learned

I learned how to set up a Windows server using virtualBox.

I practised configuring static IP addresses, network settings and managing a virtual machine.

This helped me understand how servers are set up and managed in a business environment.

### Next Steps
- Installed Active Directory Domain Services
- Configure the WorldTours.lab domain
- Learn how to manage users and groups
- Continue developing my Windows Server skills



## 23 October 2026 - Active Directory Setup

### Installing Active Directory Domain Services
- Installed Active Directory Domain Services (AD DS) ON Windows Server 2022.
- Promoted WT-DC01 to a Domain Controller foe WorldTours.lab.
- Configured a new Active Directory forest called WorldTours.lab.
- Installed DNS as part of the Domain Controlled setup.
- Completed the prerequisite checks and restarted the server.
- Verified the domain using Active Directory Users and computers.

### Organisational Units
- Created an Employees OU.
- Created an IT OU.
- Enabled protection against accidental deletion.

### User Accounts
- Created John Smith with username jsmith.
- Created Sarah Wilson with username swilson.
- Configured employees passwords.
- Enabled the option to change password at next log in.

### Security Groups
- Created WorldTours_staff as a Global Security group.
- Created WorldTours_IT as a Global Security Group.
- Added John Smith to the WorldTours_staff.
- Added Sarah Wilson to WorldTours_IT.
- Verified group memberships using the Member of tab.

### Skills Learned
- Installing and configuring Active Directory Domain Services.
- Promoting a Windows Server to a Domain Controller.
- Managing Organisational Units and user accounts.
- Creating security groups and assigning users.
- Understanding basic domain administration.

### Next Steps
- learn how to configure Group Policy
- Practise managing user permissions.
- Explore password polices and account security.


   
  
