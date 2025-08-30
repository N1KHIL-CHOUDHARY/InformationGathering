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
<img width="735" height="694" alt="479587484-354b4935-5a03-4c5f-8637-b7b749d157a4" src="https://github.com/user-attachments/assets/4920cc03-d192-421b-9ee0-46b06693150f" />

### whois :
<img width="760" height="742" alt="479588652-79694cd4-c12c-4d63-b313-913e1506a733" src="https://github.com/user-attachments/assets/09b65619-0ca7-440e-b4a5-f8ec6808ffff" />

### netcat :
<img width="665" height="108" alt="479590058-bb93be15-acb6-4473-bc3b-590e015f712c" src="https://github.com/user-attachments/assets/6954ec15-8670-45b8-95a7-24f89e6b55f0" />

### nmap :
<img width="637" height="261" alt="479590448-37659d82-c9f5-47c1-a5bc-4baff004e2db" src="https://github.com/user-attachments/assets/4b89b4df-b5d1-4876-86d2-b8298e257310" />

### whatweb :
<img width="745" height="197" alt="479590853-928a6c89-b160-421c-add3-4dd7bd400aa0" src="https://github.com/user-attachments/assets/09fa27d3-73f2-4874-b009-378154915649" />

### httprint :
<img width="630" height="208" alt="479598583-25d1d98e-6ccd-4459-957f-c91ac4edd97e" src="https://github.com/user-attachments/assets/b671f174-01c3-4154-8801-e1b7f21dae74" />

### TCP traceroute :
<img width="747" height="394" alt="479599153-c957bd67-1b5e-42ba-baee-1fa5332cbb47" src="https://github.com/user-attachments/assets/d80ebeae-a9d1-45b2-b3ec-e2241150a1a2" />

### UDP traceroute :
<img width="731" height="527" alt="479599727-7478e1f6-9ed0-4a13-8629-fed1faa85635" src="https://github.com/user-attachments/assets/2780d89c-2653-4b30-b5e9-ff99b4aeb0ee" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
