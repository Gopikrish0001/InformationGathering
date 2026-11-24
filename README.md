## InformationGathering
## Information Gathering Techiques

## REGNO :212223043001
## NAME  :GOPIKRISHNAN M

## To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="958" height="539" alt="Screenshot 2026-10-30 135704" src="https://github.com/user-attachments/assets/14cc133c-c5d8-425f-8b10-b6f56dd1fd48" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="1920" height="891" alt="VirtualBox_Parrot Security 6 0_30_10_2026_14_12_24" src="https://github.com/user-attachments/assets/3c23837c-9c19-455b-926e-bf686ed6a102" />


## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="946" height="506" alt="Screenshot 2026-10-30 140217" src="https://github.com/user-attachments/assets/f926bfa1-b852-4ebe-bdeb-bd8dda8da3ae" />


## History of the website:
## output
https://web.archive.org/
<img width="959" height="539" alt="Screenshot 2026-10-30 140846" src="https://github.com/user-attachments/assets/c18115f3-2329-44bd-ac5b-1c63584c150a" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="1920" height="891" alt="VirtualBox_Parrot Security 6 0_31_10_2026_08_51_44" src="https://github.com/user-attachments/assets/8ce257ff-244f-4cd6-a9e4-b394ed00c79b" />


## nmap:
###output
<img width="1920" height="891" alt="VirtualBox_Parrot Security 6 0_31_10_2026_08_55_12" src="https://github.com/user-attachments/assets/dc9c5b48-8dd1-4374-971a-91c5c7f3ba1e" />


## Whatweb
### output
<img width="532" height="135" alt="Screenshot 2026-11-05 081243" src="https://github.com/user-attachments/assets/98507e54-7f82-4db3-b984-862dc23c799d" />


## httprint
### output
<img width="1920" height="891" alt="VirtualBox_Parrot Security 6 0_04_11_2026_12_51_26" src="https://github.com/user-attachments/assets/6d404379-cad7-493c-a2bd-8d0ef111fa9c" />

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="390" height="65" alt="Screenshot 2026-11-05 084049" src="https://github.com/user-attachments/assets/941b5d21-9c80-4bf2-8b88-0b565bc9f065" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="387" height="50" alt="Screenshot 2026-11-05 084108" src="https://github.com/user-attachments/assets/e9622a08-407c-49aa-a92f-e5efea6cb1df" />


## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="440" height="53" alt="Screenshot 2026-11-05 084120" src="https://github.com/user-attachments/assets/344fc4bf-ea3c-4aad-bc5c-a4a33977476f" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully

