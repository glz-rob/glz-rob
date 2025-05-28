# Cybersecurity Incident Report: Network Traffic Analysis

| Part 1: Provide a summary of the problem found in the DNS and ICMP traffic log.               |
| :- |
| The DNS service is unreachable through the port 53 when attempting to access yummyrecipesforme.com address. This is based on the results of the network analysis, which show that the ICMP echo reply returned the error message: `udp port 53 unreachable`. The port 53 is used for the DNS service. The most likely issue is that the DNS service is down. |

| Part 2: Explain your analysis of the data and provide at least one cause of the incident.     |
| :- |
| Around the 13:26 hours several clients reported that they were not able to access the web site www.yummyrecipesforme.com, and saw the error "destination port unreachable". The IT team first attempted to reach the website and also received the error "destination port unreachable". Afterwards, the team conducted tests with the network protocol analyzer tool **tcpdump**. The tests indicate that the affected port is port 53, which is used for the DNS service. Port 53 is not listening to requests. The most likely cause of the incident is a DoS attack on the DNS server. Our next steps include checking the server is up and running, and validate network and firewal configurations. |