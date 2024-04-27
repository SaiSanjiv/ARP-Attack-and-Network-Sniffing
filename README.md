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
![Screenshot 2024-04-16 033946](https://github.com/MARXINLIJO/ARP-Attack-and-Network-Sniffing/assets/145742540/eb8cd1ba-962c-4038-ba0b-03f7a6b21b15)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/MARXINLIJO/ARP-Attack-and-Network-Sniffing/assets/145742540/6824bccd-37c9-4bda-aa57-de47f1eab2aa)
 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/MARXINLIJO/ARP-Attack-and-Network-Sniffing/assets/145742540/7f8d5306-232d-4185-9ca4-533cc12dae5a)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/MARXINLIJO/ARP-Attack-and-Network-Sniffing/assets/145742540/22e44d3a-917b-437b-8d35-49906ff22afd)
Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/MARXINLIJO/ARP-Attack-and-Network-Sniffing/assets/145742540/18aeda40-de44-465b-88a2-68c8aa8d32af)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
