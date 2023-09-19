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

![Screenshot 2023-09-19 153844](https://github.com/sakthivel005/ARP-Attack-and-Network-Sniffing/assets/120550359/10a63e36-c6af-43dc-a612-c5cc6fe851c9)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2023-09-19 153901](https://github.com/sakthivel005/ARP-Attack-and-Network-Sniffing/assets/120550359/3662f883-6bc7-4338-a412-306ad05ee688)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![Screenshot 2023-09-19 153916](https://github.com/sakthivel005/ARP-Attack-and-Network-Sniffing/assets/120550359/e62f19be-afd3-4f78-85d0-5ccf462b46db)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2023-09-19 153933](https://github.com/sakthivel005/ARP-Attack-and-Network-Sniffing/assets/120550359/ca948d9d-0cc9-4b8e-9930-f82593951905)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
