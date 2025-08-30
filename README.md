# Ex-02 InformationGathering
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1050" height="950" alt="image" src="https://github.com/user-attachments/assets/1c7b3289-843f-4251-ad9a-0176134118e1" />


### Finding Hosting Company :
<img width="1694" height="840" alt="image" src="https://github.com/user-attachments/assets/7c5d91a9-abd9-49f9-80af-73ed2054a8a5" />


### History of the website :
<img width="1659" height="974" alt="image" src="https://github.com/user-attachments/assets/b6fde50c-2cfe-41be-b001-f1cf8fdfe8e7" />


### ping command :
<img width="702" height="540" alt="image" src="https://github.com/user-attachments/assets/1b76895c-9b5f-4396-a5a0-e4e8fd2309c6" />

### whois :
<img width="675" height="626" alt="image" src="https://github.com/user-attachments/assets/49ca4aa8-d790-4883-aa77-3b2d9ac3b004" />

### netcat :
<img width="700" height="92" alt="image" src="https://github.com/user-attachments/assets/bffc6bbe-fa0b-473f-9580-3a032cf53b20" />

### nmap :
<img width="738" height="278" alt="image" src="https://github.com/user-attachments/assets/86c45cd6-23aa-49cf-9769-cef2df3c0bfc" />

### whatweb :
<img width="1901" height="502" alt="image" src="https://github.com/user-attachments/assets/a267a2a2-2ee8-4ede-82f9-a89198362a64" />

### httprint :
<img width="551" height="142" alt="image" src="https://github.com/user-attachments/assets/f23e0688-1283-45e1-9862-23118e57ac26" />

### TCP traceroute :
<img width="773" height="95" alt="image" src="https://github.com/user-attachments/assets/67eb7ebc-3108-47f2-b1b2-8408e6d76553" />

### UDP traceroute :
<img width="666" height="334" alt="image" src="https://github.com/user-attachments/assets/d0e667e8-a61c-4240-b8c6-9c72cd0496de" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
