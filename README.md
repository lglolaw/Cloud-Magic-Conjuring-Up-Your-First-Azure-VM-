# Cloud-Magic-Conjuring-Up-Your-First-Azure-VM-
<p align="center">

  
   ![image](https://github.com/user-attachments/assets/0cb487d0-d45a-4c26-bf9f-925cd55015ac)


  This project will guide you through creating a Windows or Linux virtual machine in Microsoft Azure. You'll learn how to set up, configure, and connect to a VM in the cloud.
</p>

<h1>VM - Prerequisites</h1>

-An Azure account (free trial available)

-Basic understanding of cloud computing concepts

-Web browser (Chrome, Edge, or Firefox recommended).<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- *Ubuntu Server 20.04/22.04 LTS* (free, beginner-friendly)
  
-  Windows Server 2022 Datacenter (free for Azure trial)


<h2> Step by Step Guide</h2>
1. Create or Sign In

Go to portal.azure.com


     ![image](https://github.com/user-attachments/assets/87277375-ce1a-4e69-a6e8-d0b2f92a9c83)


Log in with your account


    ![image](https://github.com/user-attachments/assets/f1ef591b-90b3-404f-9c65-f464c577e7d9)



2. Create VM

     ![image](https://github.com/user-attachments/assets/819d7f71-1629-4c36-8ca9-3444afde471e)


Click "Create a resource" > "Virtual Machine"

4. Basic Setup
Choose resource group (or create new)

Name your VM (e.g., "MyTestVM")

Select region near you

Choose OS (Windows/Linux)

Pick size (B1s for testing)

4. Admin Account
Set username (e.g., "azureuser")

Create password

5. Networking
Allow RDP (Windows) or SSH (Linux)



   ![image](https://github.com/user-attachments/assets/9297ed87-4bf3-49e8-9246-17088d05a691)


Keep other defaults

6. Review & Create
Click "Review + create"

Wait ~5 minutes for deployment

   ![image](https://github.com/user-attachments/assets/a4e28e6f-4ee7-45a2-a2a2-37af01870eec)


7. Connect
Windows: Download RDP file

Linux: Use SSH command

8. Clean Up
Delete resource group when done

💡 Tip: Always delete VMs when not using to avoid charges!


