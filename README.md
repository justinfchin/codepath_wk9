# Project 9 - Honeypot 

Time spent: **16** hours spent in total

Honeypot deplayed:
- Dionaea with HTTP

## Issues Encountered
- Took some time to figure out how to utilize Google Cloud. 
  - I had to start a free trial along with my credit card
  - Then create a VM instance with Compute Engine. 
- Took unfortunately a lot of time to figure out why I could not visit my page with the external ip. 
  - I had to allow http/https access on gcloud via the firewall and via my instance
  - [Follow this link if facing same problem](https://github.com/RedolentSun/gcloud-instructions-for-mhn/blob/master/README.md)

## Summary of the Data Collected
- What we did
  - We setup a honeypot which intentionally exposes insecure features in order to obtain information about the attacks
  - Google Cloud was used to host our server
  - We had to VMs, one to be the bait and the other to collect information. . 
- Number of Attacks
  - 1,024
- Number of Malware Samples
  - 672
- Top 5 Attacker IPs:
  -  24.193.197.43 (611 attacks)
  -  81.140.10.255 (83 attacks)
  -  158.69.241.18 (70 attacks)
  -  195.154.181.191 (53 attacks)
  -  191.101.167.7 (28 attacks)

## Unresolved Questions from Data
- We are given the date, country, sourceIP, destination port, and protocol of the attack. But this is just surface level information. 

## Note
- json export of the data 
