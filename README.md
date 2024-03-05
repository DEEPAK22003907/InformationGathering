# InformationGathering
Information Gathering Techiques

### DEVELOPED BY: DEEPAK.S
### REGISTER NO.: 212222040032

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

### PEN TEST TOOLS CATEGORIES:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
## OUTPUT:
![Screenshot 2024-03-05 202321](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/f479c03f-63d6-44f4-a67f-8cf8572fbc10)
### FINDING IP ADDRESS:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```

![Screenshot 2024-03-05 202413](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/0ab74b04-33e2-40dc-8221-22beb7416929)
### FINDING HOSTING COMPANY :
get further detail by using ip2location.com website.
![Screenshot 2024-03-05 202455](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/904357b1-a0c8-4435-9340-48b640fd0241)
### HISTORY OF THE COMPANY (WEBSITE) :
![Screenshot 2024-03-05 202515](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/413662e8-71f5-4269-b81b-bdd6779ec5dd)
###  WEB SERVER FINGERPRINT :
### NETCAT:
```
nc 172.17.52.118 80
```
![Screenshot 2024-03-05 202542](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/21dbe5b1-07b1-4b74-ac80-d270b5e99a97)
###  NMAP :
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
![Screenshot 2024-03-05 203947](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/4e3c3b0d-ec79-46c9-bd22-1ac03c8bc676)

### WHATWEB :
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
![Screenshot 2024-03-05 202623](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/8b9ea6f3-48c5-4317-b2cb-563501e55ba8)
### httprint:InformationGathering:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
![Screenshot 2024-03-05 202644](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/1f064465-496e-4a94-80ac-42c44e6ac469)
### TRACING THE LOCATION:
### TCP TRACEROUTE
```
sudo traceroute -T www.saveetha.ac.in
```
![Screenshot 2024-03-05 204228](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/c36512bc-8ab2-4140-8940-ae6105646286)

## UDP TRACEROUTE
```
sudo traceroute -U www.saveetha.ac.in
```
![Screenshot 2024-03-05 204321](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/f36ff097-ac88-4ebb-b570-f5a4f0fe3b3c)
### ICMP TRACEROUTE
```
sudo traceroute  www.saveetha.ac.in
```
![Screenshot 2024-03-05 204409](https://github.com/DEEPAK22003907/InformationGathering/assets/119404520/3ddecb1d-11d0-4a7d-ad45-d1a63e7e623f)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
