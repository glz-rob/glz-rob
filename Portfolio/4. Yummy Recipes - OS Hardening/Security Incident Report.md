# Security Incident Report

## Section 1: Identify the network protocol involved in the incident

We know that the protocol involved is the HTTP (Hypertext Transfer Protocol) since that protocol takes care of the website communication. Also, the tcpdump traffic log shows that the affected port is the port for HTTP, confirming our assumptions. The log also shows that the HTTP protocol is being used to push the malware file to the users computers.

## Section 2: Document the incident

After receiving reports from the clients, the IT team started to run tests on a sandbox environment. Running the network protocol analyzer **tcpdump**, the IT team navigated to the URL `yummyrecipesforme.com`. As soon as the website loaded, it promted to download an executable file to update the browser. After finishing the download, the browser was redirected to the URL `greatrecipesforme.com`.

The tcpdump log showed that at first the browser was correctly directioned to the IP address for `yummyrecipesforme.com`. Then the server pushed the executable download. Afterwards the browser was redirected to `greatrecipesforme.com`.

A senior analyst confirms that the website was compromised, and that the source code for the website was modified.

## Section 3: Recommend one remediation for brute force attacks

It is recommended to implement a Strong Password Policy, including more frequent password changes for the higher the privileges a role has. It is encouraged to enforce two-factor authentication (2FA) to avoid brute force attacks in the future.