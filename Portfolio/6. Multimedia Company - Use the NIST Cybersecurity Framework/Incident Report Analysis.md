# Incident Report Analysis

## Instructions

| Summary   | The company experienced a DDoS attack that rendered our system unsuable for 2 hours until the response team was able to fix it. The network services were flooded with ICMP packets, this overwhelmed tha organization's servers. The cybersecurity team found that the malicious actor managed to do this thanks to an unconfigured firewall. |
| :---      | :---  |
| Identify  | The cybersecurity team audited the organization's network devices affected by the attack to find the vulnerabilities that were abused. The team found out that a miscongfiguration on the network's firewall allowed the threat actor's communication. It appears that the threat actor used this misconfiguration to flood the internal servers with ICMP packets. |
| Protect   | The team has implemented multiple security measures to be able to protect against this kind of threats in the future. The first of them is that a new firewall rule was added to limit the amount of incoming ICMP packets. Source IP address verification was also added to the firewall to prevent traffic with spoofed IP addresses. An IDS/IPS system was also added, this will help filter out ICMP traffic. |
| Detect    | For anomaly detection a network monitoring software was implemented, this will allow the team to detect any abnormal traffic patterns. The IDS/IPS will also alert on any traffic with suspicious characteristics. |
| Respond   | The security operations blocked the incoming traffic ICMP packets, and stopped all non-critical network services. |
| Recover   | After implementing the previous security measures, the team restored the network services. |

---

| Reflections/Notes:    |
| :---                  |
| The security team don't decide if we are targeted by a DDoS attack or not, but we can always establish the most up-to-date security measures to maintain business continuity, and safeguard our assets. |