# Configure-VM
This project is a step by step tutorial on creating a virtual machine using Azure

<h1>CREATING VIRTUAL MACHINE</h1>
<b>Creating Virtual Machines</b>

Creating Virtual Machines has never been easier! Follow these simple steps: 
1. Visit azure.microsoft.com and sign up for a subscription account. A free 30-day subscription is available and recommended for practice purposes.

2. Create a username and password to access your portal anytime by visiting portal.azure.com. 

3. In the search bar, type "resource groups" and click "create resource group." 

4. Type in the name of your resource group and select any region you'd like. Then, click "Review + Create" to quickly create a resource group! 

5. Go to the search bar and type "Virtual Machines." Click "Create" and select the first option, "Azure Virtual Machine." 

6. Name your Virtual Machine, select the same region as your resource group, choose your desired operating system, and select the desired size of your virtual CPU. 

7. Create a username and password under "Administrator account," check the box under "licensing," and finally, click "Review + Create." 

If done correctly, the validation check should pass. Click "create" to successfully establish a "Virtual Machine."

<h2>REMOTE ACCESS</h2>

-Now that you have created the VM (virtual machine) click in the search bar and search "Virtual Machines" (or click you can click virtual machines under the "Azure Services" tab) there you will see the name of the machine you created.

-Click the name of your vm and that will take you to an overview page displaying all the info about your vm. You will see a public ip address and a private ip address. You will need the public ip; copy or write it down!!!

-If you are a windows user; click the start menu and type in "remote desktop". In the screen; paste or type in the public ip address and enter the username and password you've created making the vm. If you get warning message saying that it isn't safe, disregard that and click yes, its totally safe. If done correctly, your virtual machine will open on your screen and start loading. Type in username and password when prompted, and welcome to your Virtual Machine!

-For Mac users, download "RD Cient" from the Apple store (its free).

-Open the app and click on the + sign. Select "Add PC". Enter ip adress under "PC NAME" and under "USER ACCOUNT" type in your vms username and password that you created and click save. This will create your virtual PC within the app with the IP adress as the name.

-Click on the PC and if done correctly; your vm should load on your Mac.

-To delete your vm, go back to your azure portal and go to resoure group. Delete the resource group and the NetworkWatcherRG folders created and your done. 

<H3> VIDEO EXAMPLE</H3>

<a href="https://www.youtube.com/watch?v=iaooNrDpEtM&t=11s"> Creating Virtual Machine In Azure</a>
