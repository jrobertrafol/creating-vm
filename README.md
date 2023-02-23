<p align="center">
<img src="https://i.imgur.com/x499UNB.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating a Virtual Machine (Azure)</h1>
This tutorial outlines the creation of a single virtual machine using Microsoft Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine)



<h2>Operating Systems Used </h2>


- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- First, you need to create an Azure Tenant and Subscription.
- Step 2, create a Resource Group in Azure.
- Step 3, creat a Virtual Network and a Subnet, while creating your virtual machine.
- Finally, create a Virtual Machine.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/NZ9MpFW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First you need to create a free Azure subscription. You'll need a credit card for this but dont worry, It's free. Go to google and type in, "free Azure account". Then, choose start with $200 Azure credit and follow the instruction. This should give you $200 in credit for 30 days.

</p>
<br />

<p>
<img src="https://i.imgur.com/86YMBxP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next, once you are in, you can look up "Resource Group" in the search bar at the top or click the Resource Group icon. Click create, type the name of your Resource group, choose your region, click Review + create at the bottom left, then click create.
</p>
<br />

<p>
<img src="https://i.imgur.com/nz9DdRG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the third step, in order to create a Virtual Network and a Subnet, you need to create a Virtual Machine first. So, go back to the main Azure page, type in Virtual Machine on the search bar then, click create and choose Azure Virtual Machine. Select the same Resource Group, name the Virtual Machine as you desire, pick the same region and for operating system choose Windows 10 Pro. Then scroll down for more options.
</p>
<br />
<img src="https://i.imgur.com/ff6rXzV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, select the size of your virtual cpu (vcpus, at least 2 vcpus with 16GB memory), create a username and a password and make sure to write it down so you won't forget, check the box at the bottom left to confirm then click Next to Disks.
</p>
<br />
<img src="https://i.imgur.com/WcYpJAB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Keep everything as is for Disks section then, click Next to Networking.
</p>
<br />
<img src="https://i.imgur.com/boTfSpA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Networking, It should have automatically created a Virtual Network, default Subnet and an IP Address, so choose the given options then, click Review + create at the bottom left corner.
</p>
<br />
<img src="https://i.imgur.com/hd7WCSV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, once the validation passed, click create to create the Virtual Machine.
</p>
<br />
<img src="https://i.imgur.com/qkZW6Lw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Deployment is complete, click Go To Resources or type in Resource Group on the search bar to view the Virtual Machine. CONGRATULATIONS! You now have created your first Virtual Machine in Azure!
</p>
<br />
