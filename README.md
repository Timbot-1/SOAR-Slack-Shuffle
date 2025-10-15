# SOAR-Slack-Shuffle
A VirtualBox laboratory that orchestrates an automated response to an external attacker.

MyDFIR Server 2022 Active Directory Installation/Attack response automation Project 2.0

https://www.youtube.com/watch?v=1nX6_Nlly-4&t=173s 

In this demonstration I will simulate an attack in which stolen valid credentials are used for successful login and configure servers to execute an automated response to the login. The SOC analyst will receive an instant warning of the intrusion and remotely disable the account via the Slack and Shuffle services. 

All hail MyDFIR for the guidance here, and for the best damn videos on YouTube! Steven, THANKS, you are an oasis of calm understanding and encouragement for so many. I have learned a lot from this one project; it is a really good introduction.  
https://www.youtube.com/@MyDFIR 
The MyDFIR project uses the VULTR cloud platform for installation and configuration of the virtual machines. I began this way, but after a while I was unable to access my project. Being a total amateur, I also found the Ubuntu/Splunk installation challenging. So, I decided to do it DFIRENTLY and completed the project using only Windows machines on VirtualBox. Hopefully this will be helpful to some. Please read on… 
<img width="1094" height="491" alt="image" src="https://github.com/user-attachments/assets/1e057194-ed9c-4f2b-b811-c3ce6cf049e6" />
1.0 Core Vbox server network components installation/configuration  

     also VirtualBox/Guest Additions installation   

1.1 Server promotion to AD/DC 

1.2 Test Machine Installation and AD/DC promotion (for DNS redundancy) 

1.2.1 Redundant DNS server installation (good but too much for my pc) 

1.3 Splunk Installation 

1.4 Attacker (Kali Linux) Installation 

2.0 Slack Alert Notification 

3.0 Trigger Shuffle Playbook 

3.1 E-mail notification to SOC analyst 

3.2 Disable User? 

3.2.1 Allow access 

3.2.2 Disable Account 

3.2.3 Disable Domain User in AD 

3.2.4 Account disabled in Slack	 

Please check in to see my progress!
