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
![eth 04 1](https://github.com/user-attachments/assets/0b3bc881-2df3-4c6d-a504-136d39401a11)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![WhatsApp Image 2024-10-22 at 21 40 18_0f8271a1](https://github.com/user-attachments/assets/5ead06d8-f87d-435b-a3aa-0bb82317a82f)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



![eth 04 3](https://github.com/user-attachments/assets/2f46fead-e1ef-406c-984e-f41465c2f0fd)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![WhatsApp Image 2024-10-22 at 22 49 44_67e01c00](https://github.com/user-attachments/assets/73b6b708-2746-4413-b3e4-b560adf1c6a4)


Invoke the wireshark and examine the various menus  and controls of the tool:
![eth 04 5](https://github.com/user-attachments/assets/372b2374-01cc-406d-b6bb-4f551a88afa2)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
