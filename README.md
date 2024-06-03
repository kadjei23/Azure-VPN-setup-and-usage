<p align="center">
<img src="https://i.imgur.com/83eerhQ.png" alt="Connectivity Preview"/>
</p>

<h1>VPN setup and forwarding traffic through virtual machine as well as showing connectivity.</h1>
In this tutorial, we are going to be learning how to create a virtual machine within azure through windows and setting up a VPN with PROTONVPN.  <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- PROTONVPN
- whatismyipaddress.com
  
<h2>Operating Systems Used </h2>

- Windows 10 (22H2)

<h2>Creating a Virtual Machine in azure</h2>

- So for creating a VM through azure, you sign in into azure then click on the virtual machine icon(blue monitor screen icon) or go to search and type in virtual machine.
-  <img src="https://i.imgur.com/477I2LJ.png" alt="VM Azure showcase"/>
- After pressing Virtual machine you're then going to select create which then is going to bring you to a project detail screen. In this screen there are a couple things you have to fill in which are resource group, Virtual machine name, the region , availability options, security type, and image.
- <img src="https://i.imgur.com/MXsLEDZ.png" alt="Detailed Screen"/>
- For resource groups you can always create that first then have that VM inside the resource group. For this tutorial though we are going to let azure automatically create one for us. The virtual machine name is just a name you've assigned to the VM. The region indicates where the VM is going to be stationed but for this tutorial we're going to have it stationed somwehere that isn't america, in my case what was available to me was France. Lastly, you're going to select what type of image you want displayed after the VM connects for this tutorial we're going to use Windows 10.
- After filling those out you scroll down and fill out the size which basically determines a various amount of things from how many vms you want to have to how much power and storage each virtual computer can have. After completion we then have to come up with our username and password for our VM using the remote desktop feature on our own computer. Lastly we then hit review + create on the bottom right, it's going to take a couple of seconds to validate then we hit create to fully deploy our VM. <img src="https://i.imgur.com/hxUHk33.png" alt="Detailed Screen pt.2"/>
 - Once our VM is fully deployed and ready we now go ahead and connect our VM using the remot desktop feature on our computer. To do this we copy our Vm's public IP Address, search for our remote desktop connection and paste that IP Address in the tab.<img src="https://i.imgur.com/Vz69nXS.png" alt="IP Address"/>  <img src="https://i.imgur.com/ow2rfsD.png" alt="Remote desktop location"/>  <img src="https://i.imgur.com/RHu8iMM.png" alt="Remote desktop connection"/>
- Then connect to your VM by entering the username and password you created for yourslef. <img src="https://i.imgur.com/Y2syXt2.png" alt="Connect to VM"/> <img src="https://i.imgur.com/dzs7szx.png" alt="Connect to VM PT.2"/> <img src="https://i.imgur.com/blZSnmb.png" alt="Connect to VM PT.3"/> 
- We should now be connected to your Vm and be using whatever Operating system you chose at image via detailed screen. <img src="https://i.imgur.com/4OmlBXp.png" alt="Connect to VM PT.4"/>

 <h2>Creating and using our VPN through ProtonVPN</h2> 

- Now that we are connected and ready to go we are going to be using a public website called whatismyipaddress to determine our personal computers IP Address, our VM's IP Address as well as the IP Address of the other computer in another country that we will connect to through our VPN. These addresses should all be different because they should be in different locations. <img src="https://i.imgur.com/anNF2b1.png" alt="Connect to VM PT.4"/>  <img src="https://i.imgur.com/SrDVsdA.png"/>




 
<h2>Actions and Observations</h2>

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
