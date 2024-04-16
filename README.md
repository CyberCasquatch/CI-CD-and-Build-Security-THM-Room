<h1>CI/CD and Build Security - TryHackMe</h1>

 ###
<h2>Description</h2>
This project consists of practicing the following:
Explore what it takes to secure a DevOps pipeline and the builds it produces. Understanding the potential risks and consequences of insecure build processes. 
Explore common insecurities and how threat actors can exploit these to compromise not only the process, but also production systems.


<img src="Pipeline Lieutenant.PNG" height="60%" width="60%" alt="Badge"/>

~ This room took me a while to get through. If I got stuck, I headed to  https://www.youtube.com/@TylerRamsbey - He has two great videos to assist with the room. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Gitlab, Bash</b> 

<h2>Environments Used </h2>

- <b>Gitlab</b>
- <b>Kali Linux</b>

<h2>Room walk-through:</h2>

<p align="center">
Learning Objectives for this room:
 - Understand the significance of CI/CD and build system security within the DevSecOps pipeline.
 - Explore the potential risks and consequences associated with insecure CI/CD pipelines and build processes.
 - Gain awareness of the importance of integrating robust security measures into the build processes to ensure integrity with the deployment of applications.
 - Learn about the practical attacks that can happen against misconfigured CI/CD pipelines and build processes.  
<br/>
<img src="26 - that was the worst.PNG" height="80%" width="80%" alt="26"/>
<br />
<br />
As a note if you're completing this room - make sure to take notes at different intervals at credentials or syntax you may need  <br/>
<img src="" height="80%" width="80%" alt="Notes"/>
<br />
<br />
Gathering information: getting the CICD IP - we need this throughout the room <br/>
<img src="1 - get ip.PNG" height="80%" width="80%" alt="1"/>
<br />
<br />
Configure DNS <br/>
<img src="2 - configure dns.PNG" height="80%" width="80%" alt="2"/>
<br />
<br />
Make sure you can access the login page at Gitlab - this tells you if you are connected properly <br/>
<img src="3 - make sure you can access gitlab.PNG" height="80%" width="80%" alt="3"/>
<br />
<br />
Login to Mother and register your credentials (note these down, we use these later) <br/>
<img src="4 - log into mother.PNG" height="80%" width="80%" alt="4"/>
<br />
<br />
Sign into or register for Gitlab and create a fork of the project <br/>
<img src="5 - sign into or register gitlab and create fork of project.PNG" height="80%" width="80%" alt="5"/>
<br />
<br />
Follow the instructions to install, run, and register a runner <br/>
<img src="6 - follow instructions to install, run, and register runner.PNG" height="80%" width="80%" alt="6"/>
<br />
<br />
Make a change in the README file on the repo <br/>
<img src="7 - make change on repo.PNG" height="80%" width="80%" alt="7"/>
<br />
Once the pipeline is complete - open the web application to verify it's working <br/>
<img src="8 - once pipeline progress complete verify web applicaiton.PNG" height="80%" width="80%" alt="8"/>
<br />
<br />
Login with the credentials from the repo and grab the flag <br/>
<img src="9 - login to application and grab flag.PNG" height="80%" width="80%" alt="9"/>
<br />
<br />
Make sure Gitlab pip package is installed <br/>
<img src="10 - making sure Gitlab pip package installed.PNG" height="80%" width="80%" alt="10"/>
<br />
<br />
Grab your personal access token <br/>
<img src="11 - create personal access token.PNG" height="80%" width="80%" alt="11"/>
<br />
<br />
Add token to the python script we copied from the THM website <br/>
<img src="12 - add token to python script.PNG" height="80%" width="80%" alt="12"/>
<br />
<br />
Grep for "THM" within the Modile Application folder (unzipped)  <br/>
<img src="13 - grep for api key in mobile ap.PNG" height="80%" width="80%" alt="13"/>
<br />
<br />
Flag found <br/>
<img src="14 - flag found API.PNG" height="80%" width="80%" alt="14"/>
<br />
<br />
Create a shell script and set up a listener <br/>
<img src="15 - create shell script and setup listener.PNG" height="80%" width="80%" alt="15"/>
<br />
<br />
Replace info in the jenkins file <br/>
<img src="16 - replace info in the jenkinsfile.PNG" height="80%" width="80%" alt="16"/>
<br />
<br />
We can see a host unlocked <br/>
<img src="17 - new host noted.PNG" height="80%" width="80%" alt="17"/>
<br />
<br />
Just forked merge test <br/>
<img src="19 - Just forked merge test.PNG" height="80%" width="80%" alt="19"/>
<br />
<br />
After merger request created <br/>
<img src="18 - After Merge Request creation.PNG" height="80%" width="80%" alt="18"/>
<br />
<br />
Get the first flag by following mother orders (log into mother first, she will give you directions) <br/>
<img src="20- get the first flag by following mothers orders.PNG" height="80%" width="80%" alt="20"/>
<br />
<br />
First part of task 7 <br/>
<img src="21 - first part of task 7 metasploit.PNG" height="80%" width="80%" alt="21"/>
<br />
<br />
Once in the target machine - go back to mother and ask for directions to get the flag <br/>
<img src="22 - as the first flag_create folder and type Y to mother.PNG" height="80%" width="80%" alt="22"/>
<br />
<br />
Create public key for DEV and PROD (This is the start of heavily relying on the youtube videos for assistance / I got stuck here a lot trying to figure out how it works) <br/>
<img src="23 - create PUB key for DEV and PROD.PNG" height="80%" width="80%" alt="23"/>
<br />
<br />
Try the API Key <br/>
<img src="24 - trying API key.PNG" height="80%" width="80%" alt="24"/>
<br />
<br />
Deploy / Push the pipeline to get the secret in the file - this is the last flag. Congrats! <br/>
<img src="25 - Push pipeline and get secret.PNG" height="80%" width="80%" alt="25"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

