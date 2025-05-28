# Cybersecurity Incident Report

## Section 1: Identify the type of attack that may have caused this network interruption.

The website shows a timeout error message, which might be caused by a saturation of the port 443, which is used by the TCP service. The log shows that around 6.2 seconds after the server started recording connections the server was flooded with requests from the IP address `203.0.113.0`. It is highly likely that the event is a Denial of Service (DoS) of type SYN flood attack.

## Section 2: Explain how the attack is causing the website to malfunction.

When website visitors try to establish a connection with the web server, a three-way handshake occurs using the TCP protocol. It is possible that a threat actor uses this protocol to overwhelm the server with a high amount of `SYN` requests.

1. Firstly, a visitor trying to connect to the web page sends a request `[SYN]` to the web server. `SYN` stands for "synchronize".

2. Then the web server respones to the visitor agreeing to the connection with the `[SYN, ACK]` packet. The server reserves the system resources for the final step of the handshake. `SYN, ACK` stands for "synchronize acknowledge".

3. Lastly, the visitor's machine acknowledge the permission to connect, sending the `[ACK]` packet. `ACK` stands for "acknowledge".

When a malicious actor sends a number of `SYN` packets greater than the number of available ports on the server, th server is overwhelmed and is no longer able to respond. By the server logs we can tell that an attacker started sending `SYN` requests from the IP address `203.0.113.0`.

The logs indicate that after 7.3 seconds of recording, the server ran out of ports to allocate the requests. This stopped clients from being able to access the website. The IT team changed the firewall rules to stop requests from this IP address. It should be noted that this is a temporal solution, since the attacker could change or spoof IP addresses.

To avoid this type of attacks a Next Generation Firewall should be implemented, this firewall will be able to detect suspicious traffic and block it.
