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
![exp4_1](https://github.com/user-attachments/assets/cf43df2d-4ec6-440d-becc-47a3e924306f)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![exp4_2](https://github.com/user-attachments/assets/0ed948ef-4a2f-42fa-bb8a-d363291815b2)


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![exp4_3](https://github.com/user-attachments/assets/4d6c4fce-3682-4753-93bc-e84be9015365)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![exp4_4](https://github.com/user-attachments/assets/8a60ee3e-8de6-437f-b6df-2ec338dbf7c7)



Invoke the wireshark and examine the various menus  and controls of the tool:
![exp4_5](https://github.com/user-attachments/assets/0429591a-00bd-41b3-9a40-39031468a612)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
