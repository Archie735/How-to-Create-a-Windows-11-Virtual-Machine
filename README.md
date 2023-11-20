
<p align="center">
<img src="https://cdn.mos.cms.futurecdn.net/t22B2B44iJ4WP9WXsuN2sS-650-80.png" alt="Windows 11 Pro"/>
</p>

<h1>How to create a Windows 11 Pro Virtual Machine using Microsoft Azure</h1>
In this tutorial, we will learn how to create a simple Windows 11 Pro Virtual Machine and log into it


<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Windows Remote Desktop Connection

<h2>Prequesite</h2>
* You must already have an Azure account prior


<h3>Step 1: Log in to <a href="www.portal.azure.com"> Microsoft Azure </a></h3>
<h3>Step 2: On the search bar search for "Virtual Machine" and click on it</h3>
<h3>Step 3: Click on "Create Azure Virtual Machine" </h3>
<h3>Step 4: Fill in the information below ↓ </h3>

    Subscription: Azure subscription 1
    Resource group: Create new "Seasons"
    Virtual machine name: Winterland
    Region: (US) East US
    Image: Windows 11 Pro, version 22H2 - x64 Gen 2
    Size: Standard_D4s_v3 - 4vcpus, 16 GiB memory
    Username: Winterwonderland
    Password: Winteriscoming2
    Confirm licensing


<img src=https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/5881d141-8d61-4c22-9307-3329f32fcd62 width="600" height="400" id="Step 1" alt="">

<img src=https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/d6cab8f7-4c06-4d92-8636-4110acddee6d width="600" height="400" id="Step 2" alt="">

* You can modify the resource group, virtual machine name, region, username, and password to your liking ;)
    
<h3>Step 5: Review + Create then Click on Create</h3>
Give it some time to create before heading on to the next step :)

<h3>Step 6: Connect to Windows 11 Virtual Machine</h3>
    
* On the virtual machine (Winterland) on the Overview tab, copy the Public IP address
* On the search bar search for Remote Desktop Connection and click it  
* Paste the Public IP address on the Computer bar
* Then click "Use a different account" and enter Username and Password for Winterland
* Click on Connect
* Click on Yes to continue

<img src=https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/b6de1969-bde0-4a6f-b576-5d3e69ecb4d7 width="auto" height="400" id="Step 6" alt="">

<img src=https://github.com/Archie735/How-to-Create-a-Windows-11-Virtual-Machine/assets/150314129/432ed440-37df-4db4-817a-b9174bc0b031 width="400" height="400" id="Step 6" alt="">



<h2>Horray!!!! You are now logged in!!!! 🥳</h2>
