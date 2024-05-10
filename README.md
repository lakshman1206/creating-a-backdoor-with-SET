# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/5fdc1e61-6d95-4a1a-9e72-678577e87a61)
It displays the following menu and select 2 for Website Attack Vectors: 
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/b34757c2-e60c-40aa-89b9-ea6a55991abe)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected: 
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/bb4f30d0-5af3-49df-a207-de1876bb4fc9)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/099c624a-def8-41e6-acd1-fceec629fc9d)
It shows the following screen in which the ip address of the attacker need to be given which is the default value: 
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/eb43848d-48da-4825-8939-88224381045f)
It shows the following screen in which the option Google can be selected:
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/407c5462-96f1-46b0-901a-96154b5e3def)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/118ae795-b6ed-4b6e-900c-19249ab07c83)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/c6224195-8f1b-4a71-95fd-a067f9f7f8f8)
SET logs the information regarding the Google credentials: 
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/ff8972c0-efde-4994-ac28-3ec1e5f94cbe)
SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/Udhayasankaran04/creating-a-backdoor-with-SET/assets/119393933/2f2c004d-6fcc-4718-a3a3-010600688df2)
## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is examined successfully
