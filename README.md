<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
In this lab, this is going to walk through how to create an Active Directory home lab Enviroment using Oracle Virtual Box. Configuring and running this lab will definitely help develop your understanding of how active directory and windows networking works, so highly recommend running through it a couple of times, ask questions where things are unclear, and eventually try to build it on your own without watching tutorials.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Server 2019</b>
<h2>Program walk-through:</h2>

<p align="center">
INSTALLING ACTIVE DIRECTORY: <br/>
<img src="https://imgur.com/c4YyZLA.png" height="80%" width="80%" alt="Active Directory Steps"/>
 <br />
WHEN BOOTING UP YOUR SERVER, THIS SHOULD BE THE FIRST THING THAT POPS UP.
<br />
<br />
STEP 2: <br />
<img src="https://imgur.com/Fv6lAVh.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
GO TO THE TOP RIGHT CORNER AND CLICK ON "MANAGE" THEN CLICK ON "ADD ROLES AND FEATURES"
<br />
<br />
STEP 3: <br />
<img src="https://imgur.com/C1pViCS.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
CLICK ON "ROLE-BASED OR FEATURE-BASED INSTALLATION" THEN CLICK "NEXT"
<br />
<br />
STEP 4: <br />
<img src="https://imgur.com/GHbrubc.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
CLICK ON "SELECT A SERVER FROM THE SERVER POOL". MAKE SURE ITS THE RIGHT SERVER LISTED. THEN CLICK "NEXT"
<br />
<br />
STEP 5: <br />
<img src="https://imgur.com/VzsAXlG.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
CLICK ON THE "ACTIVE DIRECTORY DOMAIN SERVICES"
<br />
<br />
STEP 6: <br />
<img src="https://imgur.com/Ijglvt7.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
CLICK ON "ADD FEATURES" THEN CLICK "NEXT"
<br />
<br />
STEP 7: <br />
<img src="https://imgur.com/VVtIIQe.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
CLICK "NEXT"
<br />
<br />
STEP 8: <br />
<img src="https://imgur.com/oXY9TUm.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
CLICK "NEXT"
<br />
<br />
STEP 9: <br />
<img src="https://imgur.com/XI0cNGJ.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
MAKE SURE YOU CLICK TO "RESTART THE SERVER" TO SAVE THE SETTINGS PROPERLY. A PROMPT WILL ASK YES OR NO. CLICK "YES" THEN CLICK "INSTALL". THIS WILL TAKE A FEW MOMENTS.
<br />
<br />
STEP 10: <br />
<img src="https://imgur.com/tMNRFrN.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
ONCE YOU ARE DONE WITH ALL OF THE INSTALLATION, LOCATE THE FLAG ON THE TOP RIGHT CORNER. THIS IS WHERE YOU START YOUR DOMAIN CONTROLLER INSTALLATION.
<br />
<br />
INSTALLING DOMAIN CONTROLLER: <br />
<img src="https://imgur.com/KjSfOwL.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
TO MAKE A NEW DOMAIN, CLICK "ADD NEW FOREST" THEN MAKE A NAME FOR IT FOLLOWED BY .COM
<br />
<br />
STEP 2: <br />
<img src="https://imgur.com/wdHxJgh.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
CLICK ON "PROMOTE THIS SERVER TO A DOMAIN CONTROLLER".
<br />
<br />
STEP 3: <br />
<img src="https://imgur.com/bNq3irG.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
MAKE SURE YOUR FUNCTIONAL LEVEL IS THE SERVER OPERATING SYSTEM YOU ARE ON. THEN IF NOT CHECKED, CLICK "DNS SERVER" AND MAKE A PASSWORD TO DRSM (DIRECTORY SERVICES RESTORE MODE) 
<br />
<br />
STEP 4: <br />
<img src="https://imgur.com/WJvBenQ.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
MAKE SURE THE "CREATE DNS DELEGATION" IS NOT CHECKED TO MAKE SURE YOU DO NOT CREATE A WEBSITE ON ACCIDENT.
<br />
<br />
STEP 5: <br />
<img src="https://imgur.com/uUu0KM8.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
WAIT A FEW MOMENTS AND IT SHOULD GENERATE YOUR DOMAIN NAME. CLICK "NEXT" TO PROCEED.
<br />
<br />
STEP 6: <br />
<img src="https://imgur.com/iYQ4ncO.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
KEEP EVERYTHING DEFAULT AND CLICK "NEXT".
<br />
<br />
STEP 7: <br />
<img src="https://imgur.com/A5bsmmw.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
THIS IS A REVIEW OF EVERYTHING THAT WAS PUT ON YOUR SERVICES. CLICK ON "VIEW SCRIPT" AND SAVE IT FOR A TEMPLATE AS THE ADDS TO RUN.
<br />
<br />
STEP 8: <br />
<img src="https://imgur.com/29vIXEZ.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
ENSURE ALL PREREQUISITES CHECKS HAVE PASSED AND CLICK "INSTALL". YOUR SERVER WILL NOW RESTART.
<br />
<br />
STEP 9: <br />
<img src="https://imgur.com/MQsrMFM.png" height="80%" width="80%" alt="Domain Services Steps"/>
<br />
THIS IS YOUR DOMAIN NAME AS THE ADMIN NOW.
