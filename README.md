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

![Screenshot 2025-03-19 161021](https://github.com/user-attachments/assets/948fee18-dd46-4102-ad24-811fd26ff538)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:



 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![435557894-f1f4f7dd-ab9b-45e9-8d2d-da131d6143a0](https://github.com/user-attachments/assets/448d0280-5fe5-4ad6-bc78-0e97fa0f7074)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


Invoke the wireshark and examine the various menus  and controls of the tool:

![435558001-ad9d4e40-61ab-4c66-be20-ed352703d9d1](https://github.com/user-attachments/assets/e3ea09da-c012-4c69-bfce-b36fadd2f08e)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
