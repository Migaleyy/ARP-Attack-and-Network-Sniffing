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
![image](https://github.com/Migaleyy/ARP-Attack-and-Network-Sniffing/assets/118262199/ee3971a9-27aa-416f-851b-6a0e6702743d)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Migaleyy/ARP-Attack-and-Network-Sniffing/assets/118262199/cfb40fd4-3d34-4f47-a26a-fd472e8640c3)


dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/Migaleyy/ARP-Attack-and-Network-Sniffing/assets/118262199/db33b457-86a5-428f-94f9-39c504aa7cf8)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Migaleyy/ARP-Attack-and-Network-Sniffing/assets/118262199/24ffb8fa-061e-48f3-9f51-78f7db435e5c)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Migaleyy/ARP-Attack-and-Network-Sniffing/assets/118262199/d09e0034-375e-43a6-96d6-9a936bf4e3e9)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
