

![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/1d10087c-82b1-437a-a347-e8eefba67d70)




<h1>Analyzing Network Traffic and Implementing Network Security Groups</h1>

<h2>Project Summary</h2>
This project involves the creation of two virtual machines and the utilization of Wireshark to examine various network traffic. Additionally, Network Security Groups will be accessed via Azure to allow or block ICMP traffic. Completion of this project aims to give the user a better understanding of ports, network protocols, remote desktop protocol, command line use, and a basic proficiency of a network analyzer tool, such as Wireshark.
<h2>Platforms and Technologies Used</h2>

- Microsoft Azure (Virtual Machine Deployment)
- Powershell (Communication with the Operating System)
- Wireshark (Network Traffic Analyzer Tool)
- SSH (Accessing Linux Terminal)
  - TCP Port 22
- DNS (Website Traffic Information)
  - TCP and UDP Port 53
- DHCP (IP Address Allocation)
  - TCP Ports 67 and 68
- RDP (Remotely Accessing Virtual Machines)
  - TCP Port 3389

<h2>Operating Systems Used </h2>

- Windows 10 Pro
- Linux (Ubuntu Server 20.04)

<h2>Project Installation Steps</h2>

- Step 1 (Create a Resource Group within Microsoft Azure)
![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/36006b36-ffd9-41f5-9f41-7f04ae2ce17e)

- Step 2 (Create an Azure Virtual Machine running a Windows 10 Pro Image) - within the Resource Group that was created
  - Ensure that 2 Virtual CPU's are selected for each VM
  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/baef5b4a-f3ed-40d2-90d6-fcd570da6d1c)

- Step 3 (Repeat the same process and create a Virtual Machine with an Ubuntu Server Image)
  - Make sure that both Virtual Machines are on the same Virtual Network   
![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/f4cd71bc-35c3-4753-a4c2-0860fadf57f2)

- Step 4 (Utilizing RDP on Windows, Remote into Virtual Machine 1 (Windows Pro) - by typing in the IP Address
  - If using a Mac computer, go to the app store and download the Microsoft Remote Desktop application
  - You will be prompted with a login screen - use the credentials you provided during the virtual machine creation process
![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/9bea59e4-e387-42fc-90d8-9752cb7841e2)

- Step 5 (Once you are booted into the Virtual Machine, proceed to download Wireshark
  - Type in "Download Wireshark" on a Google Search
    ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/0fb98c1c-7feb-4465-8ba6-9e4914726d40)

- Step 6 (Once you are finished downloading Wireshark, boot up Wireshark by searchin for the program towards the bottom left corner of the screen)

   ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/4929ebc0-2736-48f7-bec3-81b7cb40ae7a)

- Step 7 (Once you are in Wireshark, be sure to select Ethernet)
  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/f4463c38-3339-439e-9e2c-1ce43ee360a5)

- Step 8 (You will begin to see multiple streams of network traffic be displayed)
  - Above the network traffic, where it says "Apply a Display Filter" in the white box, type in whatever traffic you would like to be displayed
  - Have fun analyzing network traffic!
  - ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/bd4a5ea6-9da4-4706-8a86-364312b0e281)

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
