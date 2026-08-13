# -networkwalks-B082-Week1-Cybersecurity-Lab-Setup
<h2 align="center">1st Project in Network Walks Internship Program - Cybersecurity Lab Setup </h2>
*******************************************************************************************************************************************************
<h3 align="center">
  🔐 Project 1 — Set Up Personal Cybersecurity Lab for Learning Purposes with VirtualBox
  </h3>
*******************************************************************************************************************************************************
# <strong> 🎯 Introduction </strong>
This is the 1st project of the internship program. We need to build our own cybersecurity labs in VirtualBox. The labs is seperate into few OS and version, Window 7
Window 11, Android, Linux and more. The reason of setup a virtual cybersecurity lab is to ensure the user able to perform penetration testing activities in a controlled and legal environment.

To allow each machine able to communicate to each other and use as targets, they will be configure in a same network and using same gateway.

# <strong> 🎯 Objectives </strong>
- Download & install Virtualbox on laptop
- Configure the network settings on your Virtualbox (VLAN 10.0.0.0/24)
- Download & import Kali Linux Virtual Machine in your Virtualbox
- Setup the IP configuration of Kali Linux (NATNetwork IP:10.0.0.2/24 DNS:8.8.8.8 Default Gateway: 10.0.0.1 )
- Take snapshot of the VM (For future recovery purpose)
- Download & Install Windows 11/10/7/Android9x (As victims)


# <strong> 🖥️ User Setup </strong>
- Host: ASUS TUF GAMING A16
- OS: Window 11
- Core: 2 slots
- RAM: 16 RAM
- Application: Oracle VirtualBox
- Guest OS: Linux
- Network Setting: NAT Network
- VLAN: 10.0.0.0/24
- Guest IP: 10.0.0.2/24
- Default Gateway: 10.0.0.1/24
- DNS: 8.8.8.8


  # <strong> 📁 Downloaded Files </strong>
- VirtualBox: [https://virtualbox.org/wiki/Downloads]
- Kali Linux: https://kali.org/get-kali
- Windows iso: https://www.microsoft.com/en-us/software-download/windows11
- Andriod Studio: https://developer.android.com/studio


# <strong> Step of the Project </strong>
First step- Download VirtualBox, Linux image iso, Window 11 image iso, Android image iso
Second step- Installed VirtualBox
Third step- Setup VirtualBox (Network -> NAT Network -> IPV4 prefix= 10.0.0.0/24 enabled DHCP)
Forth step- Build virtual machine (Machine -> New -> Choose preffer model and os -> Set base memory= 20GB, CPU= 2 Disk size= 40GB Network= NAT Network)
Fifth step- Setup network for each machine * Kali (Edit connection -> Wired connection 1 ->
