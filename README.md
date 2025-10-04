# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="878" height="381" alt="image" src="https://github.com/user-attachments/assets/b71d62b4-c51f-4301-a80e-109ac16adc24" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="1383" height="527" alt="image" src="https://github.com/user-attachments/assets/88f8bda1-de68-44d1-be64-941861574cae" />


 dsniff:

<img width="935" height="994" alt="image" src="https://github.com/user-attachments/assets/d7f26c82-cd9b-4090-bcaf-97b5cbaebbd7" />





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="756" height="748" alt="image" src="https://github.com/user-attachments/assets/601cf7e3-d5d5-48a6-bf40-a0fe18932d6b" />




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="948" height="1033" alt="image" src="https://github.com/user-attachments/assets/ad8063be-ba73-42ec-957b-0e88d698b98d" />



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
