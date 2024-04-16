<h1>CI/CD and Build Security - TryHackMe</h1>

 ###
<h2>Description</h2>
This project consists of practicing the following:
Explore what it takes to secure a DevOps pipeline and the builds it produces. Understanding the potential risks and consequences of insecure build processes. 
Explore common insecurities and how threat actors can exploit these to compromise not only the process, but also production systems.

<img src="PipelineLieutenant Badge" height="60%" width="60%" alt="SOC Analyst 1 Certificate"/>
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
<img src="26" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
As a note if you're completing this room - make sure to take notes at different intervals at credentials or syntax you may need  <br/>
<img src="00" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Gathering information: getting the CICD IP - we need this throughout the room <br/>
<img src="1" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Configure DNS <br/>
<img src="2" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Make sure you can access the login page at Gitlab - this tells you if you are connected properly <br/>
<img src="3" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Login to Mother and register your credentials (note these down, we use these later) <br/>
<img src="4" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Sign into or register for Gitlab and create a fork of the project <br/>
<img src="5" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Follow the instructions to install, run, and register a runner <br/>
<img src="6" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Make a change in the README file on the repo <br/>
<img src="7" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
Once the pipeline is complete - open the web application to verify it's working <br/>
<img src="8" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Login with the credentials from the repo and grab the flag <br/>
<img src="9" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Make sure Gitlab pip package is installed <br/>
<img src="10" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Grab your personal access token <br/>
<img src="11" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Add token to the python script we copied from the THM website <br/>
<img src="12" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Grep for "THM" within the Modile Application folder (unzipped)  <br/>
<img src="13" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Flag found <br/>
<img src="14" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Create a shell script and set up a listener <br/>
<img src="15" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Replace info in the jenkins file <br/>
<img src="16" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
We can see a host unlocked <br/>
<img src="17" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Just forked merge test <br/>
<img src="19" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
After merger request created <br/>
<img src="18" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Get the first flag by following mother orders (log into mother first, she will give you directions) <br/>
<img src="20" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
First part of task 7 <br/>
<img src="21" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Once in the target machine - go back to mother and ask for directions to get the flag <br/>
<img src="22" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Create public key for DEV and PROD (This is the start of heavily relying on the youtube videos for assistance / I got stuck here a lot trying to figure out how it works) <br/>
<img src="23" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Try the API Key <br/>
<img src="24" height="80%" width="80%" alt="DC and Client Walkthrough"/>
<br />
<br />
Deploy / Push the pipeline to get the secret in the file - this is the last flag. Congrats! <br/>
<img src="25" height="80%" width="80%" alt="DC and Client Walkthrough"/>
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

