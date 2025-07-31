<p align="center">
<img width="334" height="132" alt="image" src="https://github.com/user-attachments/assets/94c2eeb7-f589-4c0f-b2f8-cdf29cf6233b" />

</p>
<h1>Project Summary</h1>
This tutorial outlines the prerequisites and step-by-step tutorial on creating a virtual machine using the Azure Portal.<br />

<h2>Azure - Prerequisites </h2>

- An active Microsoft Azure account

- Basic understanding of navigating in Azure

<h2>Languages Used</h2>

- None required for the portal method

<h2>Environments Used</h2>

- <a href="https://portal.azure.com">Microsoft Azure Cloud Platform </a>

- Windows 10

<h2>Technologies Used</h2>

- Azure Virtual Machines

- Windows Server





<h1>Step 1: Sign in to Azure Portal</h1>
<p>  
<img width="958" height="449" alt="image" src="https://github.com/user-attachments/assets/5f660b2f-0076-429c-9e0b-962cf265f1e8" />
</p>
<p>
  
- Go to https://portal.azure.com
- Sign in using your Microsoft account

<h1>Step 2: Search Virtual Machine</h1>
<p>  
<img width="802" height="213" alt="image" src="https://github.com/user-attachments/assets/49971de8-4f8b-4efc-b435-e2a79fce8ac4" />

</p>
<p>

- Double click Virtual Machines under Services


<h1>Step 3: Click Create>Virtual Machine</h1>
<p>  
<img width="957" height="476" alt="image" src="https://github.com/user-attachments/assets/6040ce2b-28a8-471b-a874-340ef9b80dea" 
 />

</p>
<p>
  
- This opens up the VM (virtual machine) creation wizard, where we'll select the OS, size, and region

<h1>Step 4: Fill in Virtual Machine Configurations</h1>
<p>  
<img width="959" height="472" alt="image" src="https://github.com/user-attachments/assets/6b5677d8-c84b-40de-9311-ffddb2af60dc" />


</p>
<p>
<h3>A.</h3>
  
  - Click Create new
  
  - Name your Resource group
  
  - Click OK

</p>
<p>
<img width="639" height="281" alt="image" src="https://github.com/user-attachments/assets/116546d0-e4c9-4676-82b2-f5a52ffbba69" /></p>

<h3>B.</h3>

- Name your VM (virtual machine)
</p>
<p>
<img width="768" height="276" alt="image" src="https://github.com/user-attachments/assets/f493da08-cd13-478c-9c06-1ce323c0ba3e" />

  - Select your Region (choose the region closest to you)
</p>
<p><img width="803" height="384" alt="image" src="https://github.com/user-attachments/assets/bee6cdd5-7d4b-4cb9-9ae9-da47fdb4f072" />
</p>

<h3>C.</h3>

- The following may be left as default: Availability options, Zone options, Availability zone, and Security type
</p>
<p><img width="730" height="295" alt="image" src="https://github.com/user-attachments/assets/c23ebe99-0440-4872-85bd-edda2d7a22f4" />
</p>

<h3>D.</h3>

- Change Image Type by clicking the downward arrow

- Select Windows 10 Pro version 22H2 - x64 Gen2
</p>
<p><img width="706" height="287" alt="image" src="https://github.com/user-attachments/assets/c84287d7-efe9-4930-94cf-342bed0d3dbd" />

- Leave the following as default
</P>
<img width="959" height="169" alt="image" src="https://github.com/user-attachments/assets/93dba2e2-3bf3-4702-9138-7d19fed8c6f3" />

<h3>E.</h3>

- Change Size by clicking the downward arrow

- Select Standard_B2ms - 2 vcpus (pricing is $0.04-0.06 per hour covered by the $200 credit provided to new customers account in the 30 day trial)
</p>
<p><img width="767" height="356" alt="image" src="https://github.com/user-attachments/assets/d85f3c51-87f4-4e64-b394-4ba9c4f1162b" />
</p>
<h3>F.</h3>

- Create Username
- Create Password
  <h3>PICK A STRONG USERNAME AND SECURE PASSWORD (KEEP NOTE)</h3>
  </p>
  <p><img width="959" height="136" alt="image" src="https://github.com/user-attachments/assets/b6d73166-12bf-44be-977e-f6529ce58055" />
</p>

<h1>Step 5: Create Virtual Machine</h1>

<h3>A.</h3>

- Keep Public inbound ports and Select inbound ports as default
- Check Licensing box
- Click Review + create

</p>
<p><img width="656" height="374" alt="image" src="https://github.com/user-attachments/assets/e717262b-2b28-4315-94bf-6a5c36d813ca" />
</p>

<h3>B.</h3>

- After getting confirmation that validation has passed, click Create

   </p>
  <p><img width="775" height="454" alt="image" src="https://github.com/user-attachments/assets/0d47cc12-c2ba-482e-b86c-d68cadee85d6" />
</p>

- Please note the "deployment progress" may take anywhere from 2-4 minutes
</p>
<p><img width="956" height="324" alt="image" src="https://github.com/user-attachments/assets/be3d8348-a77a-436e-b2ad-b38c029eb94b" />
</p>

<h3>C.</h3>

- Once deplyment is complete, select Go to resource
   
</p>
<p><img width="959" height="472" alt="image" src="https://github.com/user-attachments/assets/3f3ca672-dfeb-406b-bd16-778489030919"
</p>

- This will take you straight to your VM
- Here you will be able to get your private IP address to start your RDP connection
</p>
<p><img width="959" height="473" alt="image" src="https://github.com/user-attachments/assets/26f8535a-ff97-4a39-9f09-a4d6a1a9a450" />
</p>

<h3> Make sure to stop your VM when not in use to perserve the credits provided to you, that can be done by hitting stop and waiting on confirmation it has stopped</h3>
</p>
<p><img width="959" height="212" alt="image" src="https://github.com/user-attachments/assets/8eb78c0a-b52f-41eb-b389-193bd104ace1" />
</p>
