# InformationGathering
Information Gathering Techiques

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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

<img width="653" height="312" alt="image" src="https://github.com/user-attachments/assets/7a7c0ce3-a123-4daa-8cac-13a5fbde77d0" />

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="628" height="247" alt="image" src="https://github.com/user-attachments/assets/682013b5-fcfd-4298-8473-be0e4e6306f4" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="651" height="312" alt="image" src="https://github.com/user-attachments/assets/007e3314-1f7b-4ada-93d9-b56ddf8c866c" />


## History of the website:
## output

<img width="653" height="312" alt="image" src="https://github.com/user-attachments/assets/a67fd3e0-4674-4554-a9b8-32ec63a99e79" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="566" height="246" alt="image" src="https://github.com/user-attachments/assets/e63bfe59-3415-4d40-8476-a0df2f4094d4" />



## nmap:
###output
<img width="615" height="205" alt="image" src="https://github.com/user-attachments/assets/8bbf5a0e-3695-493c-941b-88b0bd99ed95" />



## Whatweb
### output
<img width="613" height="263" alt="image" src="https://github.com/user-attachments/assets/de42ecd6-0672-408d-ac01-85c0d3479133" />


## httprint
### output
<img width="612" height="172" alt="image" src="https://github.com/user-attachments/assets/12225b66-bd0a-4b7b-bc5a-173583e7d423" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="625" height="177" alt="image" src="https://github.com/user-attachments/assets/4a67875b-5820-437e-a4c0-34aa366083f3" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="612" height="223" alt="image" src="https://github.com/user-attachments/assets/abc2769c-76fb-43e4-b01d-0afed19859b0" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output

<img width="622" height="186" alt="image" src="https://github.com/user-attachments/assets/4ae71731-8283-4976-b8da-a6833e96a34b" />





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
