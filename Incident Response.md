# Protfolio Activity #4 - Using the NIST Cybersecurity Framework to respond to a security incident  


## Incident Report Analysis  

__Summary__ :  

In a recent incident at a multimedia company providing various services to small businesses, a DDoS attack compromised the internal network for two hours, resulting in a service disruption. The attack flooded the network with ICMP packets, causing network services to halt. The company's cybersecurity team identified an unconfigured firewall vulnerability that allowed a malicious actor to execute the attack. In response, they implemented measures including a new firewall rule for ICMP packet rate limitation, source IP address verification, network monitoring software for anomaly detection, and an IDS/IPS system for filtering suspicious ICMP traffic.

__Identify__ :  

After a breif investigation on all the users related to this incident, the team found that an intern's login and password were obatined by a malicious threat actor and used to access data from the company's database.

__Protect__ :  

In order to prtect the assets from being compromised, our organization need to implement a MFA and set a limit to login attempts to prevent future attacks. 

__Detect__ :  

The team is working to implement a firewall to filter ports from authorized users and limit unauthorized users trying to gain access. In addition, we are looking into implementing an IDS to monitor all incoming traffic. 

__Respond__ :  

The team immediately disabled the intern's account and prevent it from further accessing the network. We have contacted the manager of this incident and provided training for both the interns and employees on how to protect login credentials. 

__Recover__ :  

We will be returning all system data back to the state it was from last night before the incident. We have sent out notices via email to all employees stating that all customer information as well as other data that have been entered since the night before will all be deleted. 




