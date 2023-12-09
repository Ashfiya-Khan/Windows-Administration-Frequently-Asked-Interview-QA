# Windows-Administration-Frequently-Asked-Interview-QA

> Windows Administration Questions & Answers - Your Cheet Sheet for Windows Admin Interview

## Prepared & maintained by [Ashfiya Khan](https://www.linkedin.com/in/ashfiya-khan/) who is working in same domain and have collected these QA over a period of time to crack the interviews of Top companies.

## About me

Hi, I am [**Ashfiya Khan**](https://www.linkedin.com/in/ashfiya-khan/), Experienced Windows Administrator adept at ensuring server reliability, security, and performance. Skilled in troubleshooting and collaborating for effective IT infrastructure management.
 
You can connect with me on:

- [LinkedIn](https://www.linkedin.com/in/ashfiya-khan/)
- [GitHub](https://github.com/Ashfiya-Khan)

## Contents - Windows Administration Interview Questions

* Basic Windows Administration Questions
* Intermediate Windows Administration Questions
* Advanced Windows Administration Questions
* Troubleshooting and Security Questions
* PowerShell and Scripting Questions
* Networking and Security Questions
* Windows Server Roles and Features Questions

Basic Windows Administration Questions:
- Windows Registry
- Accessing Task Manager
- Device Manager
- MSCONFIG Utility
- Command Prompt
- Local vs. Domain User Account
- Event Viewer
- Enabling Remote Desktop
- Active Directory
- Group Policy

Intermediate Windows Administration Questions:
- Troubleshooting a Slow Computer
- Windows Update
- NTFS vs. FAT32
- Scheduling Tasks
- System Configuration
- Windows Firewall
- Managing Services
- User Account Control (UAC)
- Creating User Account in AD
- DHCP in Windows Networking

Advanced Windows Administration Questions:
- Group Policy Objects (GPOs)
- Configuring Domain Controller
- FSMO Roles in Active Directory
- Windows Deployment Services (WDS)
- Back up and Restore Active Directory
- Hyper-V
- Remote Desktop Services (RDS)
- DNS Configuration
- PowerShell
- Network Load Balancing (NLB)

Troubleshooting and Security Questions:
- Troubleshooting a Non-Booting Windows
- BitLocker
- Windows Defender
- Resetting a Forgotten Password
- Recovering Deleted Files
- Network Connectivity Issues
- User Rights Assignment
- Securing Windows Server
- Windows Security Center

PowerShell and Scripting Questions:
- PowerShell Script vs. cmd Script
- Writing PowerShell Scripts
- PowerShell Remoting
- Listing Running Processes Remotely
- Desired State Configuration (DSC)
- Querying Active Directory with PowerShell
- Restarting a Windows Service with PowerShell
- PowerShell Modules
- Managing Hyper-V with PowerShell
- PowerShell Remoting vs. SSH

Networking and Security Questions:
- Configuring Static IP Address
- Network Address Translation (NAT)
- VLAN Configuration
- Configuring VPN Connection
- Firewall Configuration

## Basic Windows Administration Questions:
### Windows Registry

* **What is the Windows Registry?**
    - The Windows Registry is a centralized database that stores configuration settings and options on Microsoft Windows operating systems.
    -  It serves as a centralized repository for information about the system, hardware, installed software, user preferences, and other settings.
    -  The Registry is organized into a tree-like structure, similar to a file system, with keys and subkeys representing different aspects of the system and its components.
    -  Users can access the Registry through the Registry Editor (regedit.exe), a built-in Windows tool that allows them to view and edit the Registry.

### Accessing Task Manager
* **How do you access the Windows Task Manager?**
    - Press Ctrl + Shift + Esc or Ctrl + Alt + Del and select Task Manager.
      
### Device Manager
* **Explain the purpose of the Device Manager.**
    - Device Manager is a tool to manage hardware devices installed on a Windows computer, update device drivers, and troubleshoot issues.

### MSCONFIG Utility
* **What is the purpose of the MSCONFIG utility?**
    - MSCONFIG is a system configuration utility used to manage system startup, services, and boot options.

### Command Prompt
* **How do you open a command prompt in Windows?**
    - You can open the Command Prompt by typing "cmd" in the Run dialog (Win + R).

### Local vs. Domain User Account
* **Explain the difference between a local user account and a domain user account.**
    - A local user account is created and managed on a specific computer, while a domain user account is managed centrally on a Windows Server domain controller.

### Event Viewer 
* **What is the purpose of the Event Viewer in Windows?**
    - The Event Viewer is a tool that allows you to view and analyze system events, logs, and error messages.

### Enabling Remote Desktop 
* **How do you enable Remote Desktop on a Windows computer?**
    - Go to System Properties > Remote tab > enable "Allow remote connections to this computer."

### Active Directory  
* **What is Active Directory?**
    - Active Directory is a directory service used to manage resources in a Windows network, including users, computers and printers.

### Group Policy
* **Explain the purpose of Group Policy in Windows.**
    - Group Policy is used to manage and configure the security settings of computers and users in an Active Directory environment.

## Intermediate Windows Administration Questions:
### Troubleshooting a Slow Computer
* **How do you troubleshoot a slow Windows computer?**
    - Check for malware, review startup programs, check disk space, and run performance monitoring tools.

### Windows Update
* **Explain the purpose of Windows Update.**
    - Windows Update is a service by Microsoft that provides updates for the Windows operating system and its installed components.

### NTFS vs. FAT32
* **What is the difference between NTFS and FAT32 file systems?**
    - NTFS supports larger file sizes, file-level security, and journaling, while FAT32 is an older file system with limitations on file size and lacks advanced features.

### Scheduling Tasks
* **How do you schedule a task in Windows Task Scheduler?**
    - Open Task Scheduler, create a new task, set triggers and actions, and configure additional settings as needed.

### System Configuration
* **Explain the purpose of the System Configuration (msconfig) utility.**
    - System Configuration is used to manage system startup, services, and boot options for troubleshooting and optimization.

### Windows Firewall
* **What is the purpose of the Windows Firewall?**
    - The Windows Firewall is a security feature that monitors and controls incoming and outgoing network traffic based on predetermined security rules.

### Managing Services
* **How do you manage services in Windows?**
    - Use the Services.msc console to view, start, stop, and configure Windows services.

### User Account Control (UAC)
* **Explain the concept of User Account Control (UAC) in Windows.**
    - UAC is a security feature that helps prevent unauthorized changes to your computer by prompting for permission or an administrator password.

### Creating User Account in AD
* **How do you create a user account in Active Directory?**
    - Use Active Directory Users and Computers (ADUC) to create a new user account, specifying username, password, and other attributes.

### DHCP in Windows Networking
* **What is DHCP, and how is it used in Windows networking?**
    - DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses and network configuration to devices on a network.
 
## Advanced Windows Administration Questions:
### Group Policy Objects (GPOs)
* **Explain the purpose of Group Policy Objects (GPOs) in Active Directory.**
    - GPOs are used to apply specific settings and configurations to groups of users or computers in an Active Directory environment.

### Configuring Domain Controller
* **How do you configure a Windows Server as a domain controller?**
    - Use the Active Directory Domain Services Installation Wizard on a Windows Server, promote it to a domain controller, and configure AD settings.

### FSMO Roles in Active Directory
* **What are FSMO roles in Active Directory, and why are they important?**
    - FSMO (Flexible Single Master Operation) roles are critical roles in Active Directory for tasks like schema updates, domain naming, and infrastructure master.
    - These roles are essential for the proper functioning and maintenance of Active Directory. If any of these roles were to fail or become unavailable, certain operations within the Active Directory infrastructure might be affected.

### Windows Deployment Services (WDS)
* **Explain the purpose of the Windows Deployment Services (WDS).**
    - WDS is used for deploying Windows operating systems remotely through the network using the Preboot Execution Environment (PXE).

### Back up and Restore Active Directory
* **How do you back up and restore Active Directory in Windows Server?**
    - Use tools like NTDSUTIL or Windows Server Backup to perform system state backups for Active Directory recovery.

### Hyper-V
* **What is Hyper-V, and how is it used in Windows Server environments?**
    - Hyper-V is a virtualization platform in Windows Server, allowing the creation and management of virtual machines.

### Remote Desktop Services (RDS)
* **Explain the purpose of Remote Desktop Services (RDS) in Windows Server.**
    - RDS allows multiple users to access Windows applications or a full desktop remotely.

### DNS Configuration
* **How do you configure and manage DNS in a Windows Server environment?**
    - Use the DNS Manager console to create and manage DNS zones, records, and settings.

### PowerShell
* **What is Windows PowerShell, and how is it used in Windows Administration?**
    - PowerShell is a scripting language and shell for automating administrative tasks. It can be used for managing Windows servers and services.

### Network Load Balancing (NLB)
* **Explain the steps to configure Network Load Balancing (NLB) on Windows Server.**
    - Install the NLB feature, configure cluster parameters, add hosts, and set up load balancing rules.

## Troubleshooting and Security Questions:
### Troubleshooting a Non-Booting Windows
* **How do you troubleshoot a Windows server that won't boot?**
    - Use the Windows Recovery Environment, check for hardware issues, and repair the Master Boot Record (MBR) or Boot Configuration Data (BCD).
      
### BitLocker
* **What is BitLocker, and how does it enhance Windows security?**
    - BitLocker is a disk encryption program that enhances data security by encrypting the entire disk or specific volumes.

### Windows Defender
* **Explain the purpose of Windows Defender in Windows 10.**
    - Windows Defender is an antivirus and antimalware program built into Windows 10, providing real-time protection against threats.

### Resetting a Forgotten Password
* **How do you reset a forgotten Windows password?**
    - Use password reset tools, boot from a password reset disk, or access Safe Mode to change the password.

### Recovering Deleted Files
* **What steps do you take to recover a deleted file in Windows?**
    - Check the Recycle Bin, use File History or a backup, or use third-party recovery tools.

### Network Connectivity Issues
* **How do you investigate and resolve network connectivity issues in Windows?**
    - Use command-line tools like ipconfig, ping, and tracert to diagnose and troubleshoot network issues.

### User Rights Assignment
* **Explain the concept of User Rights Assignment in Windows security.**
    - User Rights Assignment defines what actions users or groups are allowed to perform on a computer, such as logging on locally or shutting down the system.

### Securing Windows Server
* **How do you secure a Windows Server against common security threats?**
    - Apply security patches, use strong passwords, implement firewalls, configure proper permissions, and use security auditing.

### Windows Security Center
* **Explain the purpose of the Windows Security Center.**
    - Windows Security Center provides a central hub for monitoring and managing security settings, including antivirus, firewall, and system updates.

## PowerShell and Scripting Questions:
### PowerShell Script vs. cmd Script
* **What is the purpose of a PowerShell script, and how is it different from cmd scripts?**
    - PowerShell scripts leverage the PowerShell scripting language, which is more powerful and versatile than traditional cmd scripts.

### Writing PowerShell Scripts
* **How do you write a PowerShell script to automate a repetitive task?**
    - Use PowerShell cmdlets, variables, loops, and conditionals to automate tasks. Save the script with a .ps1 extension.

### PowerShell Remoting
* **Explain the concept of PowerShell remoting.**
    - PowerShell remoting allows executing PowerShell commands on remote computers, enabling remote management.

### Listing Running Processes Remotely
* **How can you list all running processes on a remote computer using PowerShell?**
    - Use the Get-Process cmdlet with the -ComputerName parameter.

### Desired State Configuration (DSC)
* **What is DSC (Desired State Configuration) in PowerShell, and how does it work?**
    - DSC is a management platform in PowerShell that enables the deployment and management of configuration settings.

### Querying Active Directory with PowerShell
* **How do you use PowerShell to query Active Directory information?**
    - Use cmdlets like Get-ADUser, Get-ADComputer, and Get-ADGroup to query and manage Active Directory objects.

### Restarting a Windows Service with PowerShell
* **How can you restart a Windows service using PowerShell?**
    - Use the Restart-Service cmdlet followed by the service name (Restart-Service -Name "ServiceName")

### PowerShell Modules
* **What is the purpose of PowerShell modules, and how do you use them?**
    - PowerShell modules are collections of reusable scripts and functions. You can use the Import-Module cmdlet to load modules.

### Managing Hyper-V with PowerShell
* **How do you use PowerShell to create and manage virtual machines in Hyper-V?**
    - Use cmdlets like New-VM, Start-VM, and Stop-VM to create and manage Hyper-V virtual machines.

### PowerShell Remoting vs. SSH
* **Explain the difference between PowerShell Remoting and SSH.**
    - PowerShell Remoting is specific to Windows and relies on WinRM, while SSH is a cross-platform protocol used for remote access and management.

## Networking and Security Questions:
### Configuring Static IP Address
* **How do you configure a static IP address on a Windows computer?**
    - Go to Network and Sharing Center > Change adapter settings > right-click on the network adapter > Properties > Internet Protocol Version 4 (TCP/IPv4) > Properties.

### Network Address Translation (NAT)
* **Explain the purpose of NAT (Network Address Translation) in Windows networking.**
    - NAT allows multiple devices on a local network to share a single public IP address when accessing the internet.

### VLAN Configuration
* **What is a VLAN, and how do you configure it on a Windows Server?**
    - A VLAN (Virtual LAN) is a network that is logically segmented. On Windows Server, use the Hyper-V Manager or PowerShell to configure VLANs for virtual machines.

### Configuring VPN Connection
* **How do you configure a VPN connection on a Windows computer?**
    - Go to Settings > Network & Internet > VPN > Add a VPN connection. Enter the necessary details such as server address and authentication information.

### Firewall Configuration
* **Explain the purpose of a firewall, and how do you configure it in Windows?**
    - A firewall controls incoming and outgoing network traffic. In Windows, use the Windows Defender Firewall or third-party firewall software to configure rules.
      
### Found this project useful :heart:

* Support by clicking the :star: button on the upper right of this page. :v:

You can connect with me on:
- [LinkedIn](https://www.linkedin.com/in/ashfiya-khan/)
