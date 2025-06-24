# Social engineering

## Types of phishing

Phishing is one of the most common types of **social engineering**. Sometimes, phishing attacks appear to come from a trusted person or business. This can lead to unsuspecting recipients into acting against their better judgement, causing them to break security procedures.

### The origins of phishing

Phishing can be traced back to the 1990s. As the interncet became more accessible it began to attract the attention of malicious actors/ These malicious actors realized that the internet gave them a level of anonymity to their crimes.

#### Early persuasion tactics

One of the earliest instances of phishing was aimed at a popular chat service called AOL Instant Messenger (AIM). Users began receiving emails asking them to verify their accounts or provide personal billing information. The users were unaware that these messages were sent by malicious actors pretending to be service providers.

During the AIM attacks, malicious actors carefully crafted emails that appeared to come directly from AOL. The messages used official logos, colors, and fonts to trick unsuspecting users into sharing their information and account details.

#### How phishing has evolved

In the early 200s, e-commerce and online payment systems started to become popular alternatives to traditional marketplace. The introduction of online transations presented new opportunities for attackers to commit crimes.

A number of techniques began to appear around this time period, many of which are still used today. The five main types of phishing are the following:

- **Email phishing** is a type of attack sent via email in which threat actors send messages pretending to be a trusted person or entity.

- **Smishing** is a type of phishing that uses Short Message Service (SMS). Smishing covers all forms of text messaging services, including Apple's iMessages, WhatsApp, and other chat mediums on phones.

- **Vishing** refers to the use of voice calls or voice messages to trick targets into providing personal information over the phone.

- **Spear phishing** is a subset of email phishing in chich specific people are purposefully targeted, such as the accountant of small business.

- **Whaling** refers to a category of spear phishing attempts that are aimed at high-ranking executives in an organization.

Email attacks remain the most common types that are used. While they were originally used to trick people into sharing access credentials and credit card information, email phishing became a popular method to infect computer systems and networks with malicious software.

#### Recent trends

Starting in the 2010s, attackers began to shift away from mass phishing attempts that relied on baiting unsuspecting people into a trap. Leveraging new technologies, criminals began carrying out what's known as targeted phishing attempts.

A type of targeted phishing that evolved in the 2010s is angle phishing. **Angler phishing** is a technique where attackers impersonate customer service representatives on social media.

# Malware

## Malicious Software

**Malware** is software designed to harm devices or networks.

Devices and systems that are connected to the internet are especially vulnerable to infection. When a device becomes infected, malware interferes with its normal operations. Attackers uses malware to take control of the infected system without the user's knowledge or permissions.

### Common types of malware

- **Virus** is a malicious code written to interfere with computer operations and cause damage to data and software. Virus typically hide inside of trusted applications. An important characteristic of viruses is that they have to be activated by the user to start the infection.

- **Worm** is malware that can duplicate and spread itself across systems on its own. They scan the connected network for other devices. They can infect everything on the network without requiring an action to trigger to spread.

- **Trojan** is a malware that looks like a legitimate file or program. t is typically disguised as files or useful applications to trick their target into installing them. Attackers often use trojans to gain access and install another kind of malware.

- **Ransomware** is a type of malicious attack where attackers encrypt an organization's data and demand payment to restore access. A unique feature of ransomware attacks is that they make themselves known to their targets. Whitout doing this, they couldn't collect the money they demand.

- **Spyware** is a malware used to gather and sell information without consent. Cybercriminals use spyware to steal information, like login credentials, account PINs, and other types of sensitive information.

### More types of malware

- **Adware** is a type of legitimate software that is sometimes used to display digital advertisements in applications. Malicious adware falls into a sub-category of malware known as **potential unwanted applications (PUA)**.

- **Scareware** is another type of PUA. This type of malware employs tactics to frighten users into infecting their own device.

- **Fileless malware** does not need to be installed by the user because it uses legitimate programs that are already installed to infect a computer. This type of infections resides in memory where the malware never touches the hard drive. This is unlike other types of malware, which are stored within a file on disk.

- **Rootkits** is malware that provides remote, administrative access to a computer. This kind of malware is often spread by a combination of two components: a dropper and a loader.

    - A **dropper** is a type of malware that comes packed with malicious code which is delivered and installed onto a target system.

    - A **loader** is a type of malware that downloads strains of malicious code from an external source and installs them onto a target system.

- **Botnet**, short for "robot network", is a collection of computers infected by malware that are under the control of a single threat actor, knwon as the "bot-herder".

## The rise of cryptojacking

**Cryptojacking** is a form of malware that installs software to illegally mine cryptocurrencies. Cryptojacking malware started being used to gain unauthorized control of personal computers to mine cryptocurrency.

### Signs of cryptojacking

- Slowdown

- Increased CPU usage

- Sudden system crashes

- Fast draining batteries

- Unusually high electricity costs

# Web-based exploits

**Web-based exploits** are malicious code or behavior that is used to take advantage of coding flaws in a web application. Attacks occur because web applications interact with multiple users across multiple networks.

An **injection attack** is malicious code inserted into a vulnerable application. The infected application often appears to work normally, that is because the injected code runs in the background. Applications are vulnerable to injection attacks because they are programmed to resceive data inputs.

## Cross-site scripting (XSS)

A common and dangerous type of injection attack that's a threat to web apps is cross-site scriptiing. **Cross-site scripting** is an injection attack that inserts code into a vulnerable website or web application.

### Types of cross-site scripting attacks

Hackers use these methods of cross-site scripting to steal sensitive information.

- **Reflected XSS Attack** is an instance where a malicious script is sent to the server and activated during the server's response.

- **Stored XSS Attack** is an instance when malicious script is injected directly on the server. Attackers target elements of a site that are served to the user, infected elements activate the malicious code when a user simply visits the site.

- **DOM-based XSS Attack** is an instance when malicious script exists in the webpage a browser loads.

## Exploitable gaps in databases

Someitmes backend queries are vulnerable to injection attacks. A **SQL injection** is an attack that executes unexpected queries on a database. like cross-site scripting, SQL injection occur due to a lack of sanitized input. The injection takes place in the area of the website that are designed to accept user input.

Websites that are vulnerable to SQL injection insert the user's input exactly as it's entered before running the code. This is a serious design flaw. This could cause the server to run a harmful query of code that is wasn't expecting. Malicious hackers can target these attack vectors to obtain sensitive information, modify tables and even gain administrative rights to the database.

The best way to defend against SQL injection is code that will sanitize the input. Developers can write code to search for specific SQL characters. One way this is done is with preapred statements.

A **prepared statement** is a coding technique that executes SQL statements before passing them on to the database.

## Prevent injection attacks

### Types of SQL injections

There are three main categories of SQL injection:

- In-band

- Out-of-band

- Inferential

#### In-band SQL injection

In-band, or classic, SQL injection is the most common type. An in-band injection is one that uses the *same communication channel* to launch the attack and gather the results.

#### Out-of-band SQL injection

An out-of-band injection is one that uses a *different communication chanel* to launch the attack and gather the results.

ut-of-band injection attacks are very uncommon because they'll only work when certain features are enabled on the target server.

#### Inferential SQL injection

Inferential SQL injection occurs when an attacker is unable to directly see the results of their attack. Instead, they can interpret the results by analyzing the *behavior* of the system.

### Injection prevention

A key to preventing SQL injection attacks is to *escape user inputs*—preventing someone from inserting any code that a program isn't expecting.

There are several ways to escape user inputs:

- **Prepared statements**: a coding technique that executes SQL statements before passing them on to a database.

- **Input sanitization**: programming that removes user input which could be interpreted as code.

- **Input validation**: programming that ensures user input meets a system's expectations.

Using a combination of these techniques can help prevent SQL injection attacks.

# Threat modeling

## A proactive approach to security

Anticipating attacks is the key to preparing for them. In cybersecurity this is done by performing an activity known as threat modeling. **Threat modeling** is the process of identifying assets, their vulnerabiltiies, and how each is exposed to threats. Create threat models is a lengthy and detailed activity, it is also considered to be an davanced skill in security.

There are several threat modeling frameworks used in the field. Ecah best suited for different applications. In general, there are six steps of a threat model:

1. **Define the scope** of the model. The team determines what they're building by creating an inventory of assets and classifying them.

2. **Identify threats**. The team defines all potential threat actors. After threat actors havebeen identified, the team puts together what is known as an attack tree.

    - An **attack tree** is a diagram that maps threats to assets.

3. **Characterize the environment**. The team applies an attacker mindset of h business. They consider how the customers and employee interact with the environment. Other factors they consider are external partners and third party vendors.

4. **Analyze threats**. Examine existing protectiong and identify gaps. Then rank threats according to their risk score that they assign.

5. The team decides how to **Mitigate risks**. The group creates their plan for defending against threats. The choices here are to avoid risk, transfer it, reduce it, or accept it.

6. **Evaluate findings**. Everything that was done during the exercise is documented, fixes are applied, and the team makes note of any successes they had. They also record any lessons learned.

## PASTA: The Process for Attack Simulation and Threat Analyzing

**PASTA** is a popular threat modeling framework that is used across many industries. PASTA is short for Process for Attack Simulation and Threat Analysis. There are seven stages of the PASTA framework.

1. **Define business and security objectives**. The team needs to decide what their goals are. The team starts by asking a lot of questions at this stage. They'll need to understand things like how personally identifiable information is handled.

2. **Define technical scope**. The team's focus is to identify the application components that must be evaluated.

3. **Decompose the application**. Identify the existing controls that will protect user data from threats. This normally means working with the application developers to produce a data flow diagram. A diagram like this will show how data gets from a user's device to the company's device.

4. **Perform a threat analysis**. The teams gets into their attacker mindset. Research is done to collet  the most up-to-date information on the type of attacks being used.

5. **Perform a vulnerability analysis**. The team more deeply investigates potential vulnerabilities by considering the root of the problem.

6. **Conduct attack modeling**. This is where the team tests the vulnerabilities that were analyzed by simulating attacks. The team does this by creating an attack tree.

7. **Analyze risk and impact**. The team assembles all the information they've collected in stages one through six. By this stage, the team is in position to make informed risk management recommendations.

## Traits of an effective threat model

### Why application security matters

Application have become an essential part of many organizations' success. If a vulnerbaility is not patched, it can impact millions of devices.

### Defending the application layer

Defending the application layer requires proper testing to uncover weaknesses that can lead to risk. Threat modeling is one of the primary ways to ensure that an application meets security requirements.

Conducting a thorough software analysis takes time and resources. Everything should be evaluated. As a result, a number of threat-modeling frameworks have been developed over the years to make the process smoother.

### Common frameworks

The "right" model depends on the situation and the types of risks an application might face.

#### STRIDE

**STRIDE** is s threat-modeling framework developed by Microsoft. It's commonly used to identify vulnerbailities in six specific attack vectors. The acronym represents each of these vectors: spoofing, tampering, repudiation, information disclosure, denial of service, and elevation of privilege.

#### PASTA

The **Process of Attack Simulation and Threat Analysis (PASTA)** is a risk-centric threat modeling process developed by wo OWASP leaders and supported by a cybersecurity firm called VerSprite. Its main focus is to discover evidence of viable threats and represent this informaqtion as a model. Its seven stage process consists of various activities that incorporate relevant security artifacts of the environment, like vulnerability assessment reports.

#### Trike

**Trike** is an open source methodology and tool that takes a seucrity-centric approach to threat modeling. It's commonly used to focus on security permissions, application use cases, privilege models, and other elements that support a secure environment.

#### VAST

The **Visual, Agile, and Simple (VAST) Modeling** framework is part of an automated threat-modeling platform called ThreatModeler. Many security teams opt to use VAST as a way of automating adn streamlining their threat modeling assessements.

### Participating in threat modeling

Threat modeling is often performed by experienced security professionals, but it’s almost never done alone. This is especially true when it comes to securing applications. Programs are complex systems responsible for handling a lot of data and processing a variety of commands from users and other systems.

One of the keys to threat modeling is asking the right questions:

- What are we working on?

- What kinds of things can go wrong?

- What are we doing about it?

- Have we addressed everything?

- Did we do a good job?
