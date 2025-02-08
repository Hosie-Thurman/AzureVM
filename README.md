
![Image](https://github.com/user-attachments/assets/607dfe26-e05d-426a-a304-8db67c453d71)
</p>

<h1> Windows 10 VIrtual Machine - Setup & Connection </h1>
This tutorial outlines the process of creating a Virtual Machine using Azure and connecting to it via Remote Desktop..<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (Windows & MacOS versions)

<h2>Installation Steps</h2>

<h3>Step 1: Creating a Virtual Machine for osTicket</h3>

-Sign into Azure

-Go to Create a resource → Select Virtual Machine.

![Image](https://github.com/user-attachments/assets/127c37ad-fc8f-4fe5-ac4d-ee49a4dde407)


<h3>Step 2: Virtual Machine Settings</h3>

-First create a new  Resource Group

-Now name the VM and select the Region
Keep in mind that the region determines the available vCPU sizes below
You may need to change the region to receive more options 

-Choose Windows 10 Pro as the Image

![Image](https://github.com/user-attachments/assets/adacf78e-2c35-4fc9-b5a2-a6b7608d4ac2)



<h3>Step 3: Virtual Machine Settings</h3>

-Choose a VM of 2 vCPUs or more 

-Remember that your region directly affects the available sizes 

-The admin account can have any Username and Password you like

![Image](https://github.com/user-attachments/assets/f7264070-12eb-4bf8-a915-bd8f3237d303)


<h3>Step 4: Virtual Machine Settings</h3>

-Check the box at the very bottom

-Then click “Review + Create” 

![Image](https://github.com/user-attachments/assets/d13df200-aea6-437e-a71e-f53168a5a7a2)


<h3>Step 5: Grabbing the IP</h3>

-Click the “Go to Resource” button
-Copy the Numbers in the Public IP address tab to the right

![Image](https://github.com/user-attachments/assets/72aabd13-0f9e-438f-a8e7-993d9e00f593)
![Image](https://github.com/user-attachments/assets/874285a6-23b0-4fe7-88e3-363f329a5435)


<h3>Step 6: Mac VM sign in</h3>

-Go to the App Store to download the Windows App
-Click the + icon in the top right - Click Add PC
-Paste the IP and then your Username and Password

![Image](https://github.com/user-attachments/assets/29890bbd-1ccc-428a-a435-a93b3539a35c)
![Image](https://github.com/user-attachments/assets/c373de36-4289-419e-a6d8-8e8018e19cda)

<h3>Step 7: Window VM sign in</h3>
-Click the Windows key
-Type Remote Desktop
-Paste the IP and the sign in using your Username and Password

![Image](https://github.com/user-attachments/assets/b9f5a010-2acf-4ab4-bc40-0d66ccec00d0)

🎉Congratulations! You have sucessfully Setup the VM and now ready to install osTicket!🎉

![Image](https://github.com/user-attachments/assets/318bb611-ae3c-4ed1-aca5-2cb998a440d2)

