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
![1](https://github.com/user-attachments/assets/72d1fb42-795b-4e48-a3f4-e71573926292)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2](https://github.com/user-attachments/assets/57dd07ac-207e-4691-8e1a-3575f71f43ca)







In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/user-attachments/assets/fdccca21-f36d-4e27-b687-f4c653ff5680)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![4](https://github.com/user-attachments/assets/760e28d6-2a8e-47c3-bae5-3afd8e7cbafd)


Invoke the wireshark and examine the various menus  and controls of the tool:
## OUTPUT:
![5](https://github.com/user-attachments/assets/7b80d94d-c6e4-4aa8-b7ca-a18f665731ef)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
