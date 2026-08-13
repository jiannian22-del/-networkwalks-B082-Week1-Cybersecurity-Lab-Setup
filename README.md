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
<p><b><i>First step</i></b></p>- Download VirtualBox, Linux image iso, Window 11 image iso, Android image iso <br>
<p><b><i>Second step</i></b></p>- Installed VirtualBox<br>
<p><b><i>Third step</i></b></p>- Setup VirtualBox (Network -> NAT Network -> IPV4 prefix= 10.0.0.0/24 enabled DHCP)<br>
<p><b><i>Forth step</i></b></p>- Build virtual machine (Machine -> New -> Choose preffer model and os -> Set base memory= 20GB, CPU= 2 Disk size= 40GB Network= NAT Network) <br>
<p><b><i>Fifth step</i></b></p>- Setup network for each machine * Kali (Edit connection -> Wired connection 1 -> IPv4 setting -> Address= 10.0.0.2 Netmask= 24 Gateway= 10.0.0.1 DNS Server= 8.8.8.8 -> Terminal -> Disconnect/connect the network)
*Window (Network and Internet setting -> change DHCP to static -> Address= 10.0.0.11 mask= 255.255.255.0 Gateway= 10.0.0.1 DNS Server= 8.8.8.8)
*Android (Setting -> Network Detail -> Edit -> Address= 10.0.0.11 mask= 255.255.255.0 Gateway= 10.0.0.1 DNS Server= 8.8.8.8)
<img width="1397" height="944" alt="change ip kali" src="https://github.com/user-attachments/assets/3f542676-5642-43ee-83f4-b5ade71e8d85" />
<img width="1041" height="886" alt="change ip 11" src="https://github.com/user-attachments/assets/a4184af4-cf48-4599-b100-3b172642c135" />
<img width="1030" height="865" alt="change ip android" src="https://github.com/user-attachments/assets/8630b271-1d01-4b35-8f7c-7312e657fa0c" />
<br><br>


