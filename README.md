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
![image](https://github.com/user-attachments/assets/902bcc97-2918-465c-8a51-1097feb9c9b0)


It displays the following menu and select 2 for Website Attack Vectors: 
![image](https://github.com/user-attachments/assets/0c2db713-ec1c-4805-af15-bec724c12332)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/d6d1bd40-378d-4279-a3fb-d7e20ee9803d)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 
![image](https://github.com/user-attachments/assets/5d783d46-ae7a-4edd-87cc-20d3ed23b137)


It shows the following screen in which the ip address of the attacker need to be given which is the default value: 
![image](https://github.com/user-attachments/assets/78fff169-108c-4534-b512-978b72317527)


It shows the following screen in which the option Google can be selected 
![image](https://github.com/user-attachments/assets/e8cb0533-919f-4cb7-87aa-64a1f1b51503)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 
![image](https://github.com/user-attachments/assets/e0f6c430-1527-4f9b-a40d-be2070205bb1)


In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/63842432-fe52-4534-817f-a0a533af3961)


SET logs the information regarding the Google credentials: 
![image](https://github.com/user-attachments/assets/6b62b56b-9112-41e2-ac91-63c9e15d7d1b)


SET logs the information in the xml file under /root/.set directory: 
![image](https://github.com/user-attachments/assets/80a7a0cf-66e6-41e5-92a9-42786dc3d083)







## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
