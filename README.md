# Security-Onion-Lab

## Objective
  
This lab emphasizes the practical application of security monitoring techniques such as log collection, network traffic analysis, and intrusion detection. I was able to gain more hands-on experience with simulating real-world cyberattacks and defending against them within the setup using a KALI Linux machine to simulate attacks against a Windows User. By the end of the lab I felt even more comfortable configuring key tools to detect, analyze, and respond to security events.
 <br>
 <br>
## Skills Learned

* Designed and configured a home lab using virtualization technologies (Virtualbox, VMware), gaining practical hands-on experience

* Deployed and secured various operating systems (Windows, Linux) and servers, enhancing technical skills

* Used Windows Server Manager to create certificates and perform necessary tasks to set up a domain controller 

* Collected and analyzed network traffic logs from Security Onion in Splunk, practicing correlating alerts with specific incidents and threat patterns 
 <br>
 <br>
 
## Tools Used

* KALI Linux
 
*  pfSense

* Security Onion 

 * Splunk Universal Forwarder
  
  * Ubuntu

  * vmware
   
* Windows Client/Server

<br>
<br>
<br>
<br>

# Lab Setup 

<img width="637" alt="pfsenseserv" src="https://github.com/user-attachments/assets/efd9727b-7788-459b-b10d-2c5249048eae" />


A. pfSense Firewall - Used for routing and NAT, can be accessed via LAN interface to create rules

<img width="637" alt="so-server" src="https://github.com/user-attachments/assets/6ea30548-8e59-49d5-a481-889296f1e1c8" />

B. Security Onion IDS - Configured management/monitor interfaces during setup. Enabled DHCP

<img width="637" alt="pfsense" src="https://github.com/user-attachments/assets/77afddc9-be93-42d7-bcbd-7244c6aad566" />

C. pfSense WebConfigurator - Accessed via LAN interface on KALI Linux machine, displays router and DNS configurations(Google). Rules have been created 

*Screenshot includes full VMware lab setup including target machine

<img width="637" alt="server" src="https://github.com/user-attachments/assets/548e4394-fdec-4499-91bb-e5ba0a63b0ca" />

D. Windows Server - Configured server to use Active Directory Domain & Certificate Services. Promoted to domain controller, created multiple user accounts, and configured pfSense as the default gateway for the DC.

*Disabled firewall

E.<img width="637" alt="splunkerr" src="https://github.com/user-attachments/assets/03a3c51e-a07d-454f-b174-e0a8de3106ec" />



F. <img width="637" alt="splunklog" src="https://github.com/user-attachments/assets/eacbc396-711b-4ef3-a347-80e331fb3a2a" />


### Key:




D. 

E.

F.
  
  
