<h1>Giving Security Groups Permission To Access Shared Folders (HR and Personal Folders)</h1>


<h2>Description</h2>
<p>In this scenario, I'd like to connect these two security groups (HR and PERSONAL) to both shared folders that I've recently created. This will allow John and others in the HR department to access the shared folders. This is secure since only those assigned to those security groups will have access to the shared folders.</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1: <br/>
<img src="https://i.imgur.com/KYAvaUA.png" height="70%" width="70%"/> </p>


<p align="center">The first step is to open File Explorer on the Server device. As you can see, I have located the folders. I then move on to the next phase.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/QuU4m4w.png" height="40%" width="40%"/> </p>


<p align="center">Here, I right-click on the HR folder to view its settings. I then select the "PROPERTIES" tab to access further settings.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/w8viOMo.png" height="40%" width="40%"/> </p>


<p align="center">This is the "PROPERTIES" section of the HR folder, and from here I move on to the "security" sections to remove specific permissions. I then click the "Advanced" button to access further security settings.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 4: <br/>
<img src="https://i.imgur.com/dcwBGAB.png" height="70%" width="70%"/> </p>


<p align="center">From here, I can link the security group (HR) to this folder. This allows members of that group to view the HR folder. To add it, I click the "Add" button and then go to the next step.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/D9gdxYY.png" height="70%" width="70%"/> </p>


<p align="center">From here, I select the option "SELECT A PRINCIPAL". In this scenario, I need to link the HR security group and add the Helpdesk account to this folder so that he can manage the shared folder as well.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/I6PKqnR.png" height="90%" width="90%"/> </p>


<p align="center">As you can see, I looked up both the helpdesk account and the HR security group. I then add them by clicking "OK". I then move on to the next phase.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/E99Fd3r.png" height="70%" width="70%"/> </p>


<p align="center">As you can see, the Helpdesk account and HR security group have been linked within the HR folder. They don't have complete control, but they can still contribute and make changes to the folder.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 5: <br/>
<img src="https://i.imgur.com/QjsVZSJ.png" height="40%" width="40%"/> </p>


<p align="center">Now that I've accessed the "SHARING" section of the HR folder, I want to adjust the permission level for the HR security group. To do so, I click the "SHARE" option and go to the next step.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/FUxG6ck.png" height="70%" width="70%"/> </p>


<p align="center">From here, I provide "READ/WRITE" permission to the HR security group. This will allow users in the HR security group to contribute and modify the HR folder.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 6: <br/>
<img src="https://i.imgur.com/aYfRaA1.png" height="90%" width="90%"/> </p>


<p align="center">Now I'm on John's PC, and I need to map the HR and PERSONAL folders on his account. To do so, I first open File Explorer.  I then right-click "THIS PC" to access other settings, and then select the option "MAP NETWORK DRIVE".</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/bxbSqnp.png" height="70%" width="70%"/> </p>


<p align="center">I then type the precise location of the shared folder in the "FOLDER" section. I leave all of the other settings as default and then click "Finish" to map the folder to John's account.</p>



<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/NE5kJtL.png" height="70%" width="70%"/> </p>


<p align="center">I also add the location of John's "PERSONAL" folder to map it. I then click "FINISH" to finish the mapping procedure.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/ymW03fG.png" height="70%" width="70%"/> </p>


<p align="center">As you can see, the HR and PERSONAL folders have been successfully mapped to John's account. Now, whenever he signs in to his account, these folders will be available. He can now add and remove files from these folders, and everyone in his security group can do the same.</p>





<a href="https://www.example.com">
  <button>NEXT</button>
</a>
