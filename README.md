# Sysadmin CloudOps(Azure) Lab
This is a 4 months roadmap designed (with the help of OpenAI) to build experience, skill, and familiarity necessary in the sysadmin and cloudops (Azure) environment. This roadmap is made under the premise that the user (in the original case, me) has the fundamentals of:
* Windows OS
* Basic Virtualization Concepts (Hyper-V, Containers)
* Basic Networking Concepts (IP & MAC address, subnetting, DNS, OSI model, basic routing, firewall and ports)
* Basic Cloud Computing Concepts (IaaS, PaaS, SaaS, Pricing Models)
* Azure Fundamentals (Availability Zones, Availability Sets, VNets, Redundancy, Blob Storage, File Share)

All exercises in this roadmap are cost-free, the only equipment required is a good laptop/desktop and a working internet.  
All exercises are self-guided, with the help of free internet resources like Microsoft Learn, Google, ChatGPT.  
⚠️⚠️⚠️ Exercises with Azure may incur costs if not setup correctly, proceed with caution. ⚠️⚠️⚠️

## Month 1 - Server and Networking (Local + Azure)
The first month is about Windows and Linux server fundamentals. We will navigate through Windows Server fundamentals (AD, DNS, DHCP, domain joining), Ubuntu Linux (users, groups, permissions, SSH, package management, Apache/Nginx), networking practice (IP addressing, subnetting, routing tables, firewall configuration, netstat, ipconfig, nslookup, tracert), Azure VNets (subnets, NSGs, peering).
### Week 1: Windows Server - AD, DNS, DHCP, domain join.
- Setup lab environment (VirtualBox or Hyper-V)
- Deploy VMs (Windows Server, Ubuntu server, Windows Client)
- Install Active Directory Domain Services on Windows Server, promote to Domain Controller.
- Explore Group Policy Objects and User management.
- Explore and deploy DNS Manager (Forward lookup zones, Name Resolution, A Record)
- Explore and deploy DHCP Server (Configure subnet, IP range)
- Document journey.
### Week 2: Linux Basics - Bash CLI, Users, Groups, Permissions, Domain join
- Practice CLI basics:
    - Navigation (ls, cd, pwd, cat, nano/vm)
    - File management (cp, mv, rm, mkdir)
    - Disk usage (df, du)
    - Process monitoring (ps aux, top, htop)
- Users, Groups and Permissions (adduser, groupadd, usermod, chmod)
- Package Management (apt update, apt upgrade, apt install)
- Networking (ip, ping, ssh, ufw)
- Mini Project
    - Host a website with Nginx/Apache.
- Document journey.
### Week 3: Networking Fundamentals (optional if you have studied basic concepts)
- IP Addressing & Subnets (IPv4 & IPv6, Subnet Masking, CIDR notation, Gateway, Broadcasting)
- Explore Routing (route print, tracert, ip route, static routing)
- Firewall & Networking ports (HTTP/HTTPS, TCP, UDP, SSH, RDP, LDAP, SMTP, POP3, IMAP)
- Connect the VMs deployed on Week 1.
- Document journey.
### Week 4: Azure Virtual Networking 
These exercises can be perfomed with Azure Cloud Shell (Free).
- Deploy a VNet in Azure, create a subnet.
- (Optional - May Incur Charges) Deploy 2 VMs in Azure, assign to different subnets and test ping.
- Create a Network Security Group, explore priority and port blocking.
- Deploy second VNet, test VNet peering.
- Explore DNS Servers settings.
- Explore service endpoints & private link.
- (Optional - May Incur Charges) Create a storage account and setup private endpoint connection to a VNet.
- Document journey.

## Month 2 - Automation & Hybrid Identity
The second month will cover task automation via scripting with Powershell, Linux Bash, and Azure (ARM/Bicep/CLI). Identity and Access Management will also be covered through tools like Entra ID, AD Connect, Intune, Conditional Access, MFA, etc.
### Week 5: Powershell Fundamentals
- Basic tools (Get-Help, Get-Command, Get-Service, Get-Process, Get-Package)
- Variables, logics & loops
    - Conditional logic (if, elseif, switch)
    - Loops (foreach, while)
    - Object functions (ForEach-Object, Select-Object, Where-Object, Compare-Object)
- Logging tools (Get-WinEvent, Get-EventLogs)
- Mini Projects
    - Write a script that checks if disk space is below certain threshold and sends a desktop notification. Schedule the task at log on through Task Scheduler.
    - Write a script that checks if Spooler service is running, start the service if not.
    - Write a script that logs system errors past a certain date.
- Document journey.
### Week 6: Linux Automation (Bash Scripting)

### Week 7: Azure Automation

### Week 8: Azure Identity & Hybrid Management


