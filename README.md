
<p align="center">
<img src="https://d1ka0itfguscri.cloudfront.net/r5Jl/2023/04/10/05/49/c0f6hdVaCoW/preview.jpg" alt="osTicket logo"/>
</p>

In this installation guide, I installed and configured Active Directory on a domain controller. I used Azure cloud to set up this environment. 

For this setup, we will create two virtual machines. One of these machines will act as the domain controller while the other will act as the client.


To begin creating a virtual machine in Azure Cloud, we will need to set up a subscription. 

Link:  https://portal.azure.com


Once you have your subscription created, you should see a screen look that looks similar to this or  you can navigate to  https://portal.azure.com/#home

<p align = center>
<img src="https://d1ka0itfguscri.cloudfront.net/r5Jl/2023/04/13/03/00/c0fIecVasXR/preview.jpg" alt=""/>
</p>
<br>
<br>

Next we will click on Resource Group Icon to name and create a resource group. I have given my resource group the name “Active-Directory-Lab” but you can name it whatever you like.

<br>
<br>

<p align = center>
<img src="https://d1ka0itfguscri.cloudfront.net/r5Jl/2023/04/13/03/03/c0fIeeVaslr/preview.jpg" alt=""/>
</p>


Once you follow through by clicking the various prompts to review and create your resource group, the deployment of your resource group should begin. Just remember to take note of the resource group region. It will be very important in optimizing networking capabilities. 


<p align = center>
  You can watch this video for further instructions: <a href="https://youtu.be/gneJ5mZnAO4?t=74">Click Here</a>
</p>
<p align = center>

  
  <br>
<br>
  
  
Now it’s time to create the two virtual machines. It is very important to put the virtual machines in the same resource group, same region, and in the same network.
<p align = center>
<img src="https://d1ka0itfguscri.cloudfront.net/r5Jl/2023/04/13/04/51/c0fIf7Vas0K/preview.jpg" alt=""/>
</p>

  
  
  <p align = center>
  You can watch this video for further instructions: <a href="https://youtu.be/gneJ5mZnAO4?t=109">Click Here</a>
</p>
<p align = center>
  
  There is much more to do once the virtual machines are created; however, instead of typing all the steps out I have created a detail video documenting the installation of active directory in the Azure Cloud, and using powershell to add multiple users to specific folder. 
    You can watch this video for further instructions: <a href="https://youtu.be/gneJ5mZnAO4">Click Here</a>
