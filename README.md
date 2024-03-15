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

After creating your virtual machine (VM), you can find it by searching "Virtual Machines" in the search bar or by clicking "Virtual Machines" under the "Azure Services" tab. Once you find your VM, click on its name to access the overview page, where you can see the public and private IP addresses. Remember to write down or copy the public IP address as needed later.

For Windows users, click the Start menu and type "remote desktop." On the screen that appears, paste or type in the public IP address and enter the username and password you used when creating the VM. If you receive a warning message stating that the VM is unsafe, ignore it and click "yes," as it is entirely safe. Once you have done this correctly, your virtual machine will start loading on your screen. Type in your username and password when prompted, and you're all set!

Mac users can download Microsoft Remote Desktop for free from the App Store. After installing the app, open it and click on the "+" sign. Select "Add PC" and enter the IP address under "PC NAME". Under "USER ACCOUNT," type in your VM's username and password, and click save. This will create your virtual PC within the app with the IP address as the name. Click on the PC, and your VM should load on your Mac.

To delete your VM, go back to your Azure portal and access the resource group. Delete the resource group and the NetworkWatcherRG folders created.
