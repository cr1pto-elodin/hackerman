As a pentester or a cyber security analyst, I need to understand the types of attacks and how they can be done.

First of all lest sumarize: [[#Phishing|Phishing]], [[#Malware|Malware]] and [[#Social Engineering|Social Engineering]].

## Phishing:

	Phishing is a kind of attack that uses digital communication
	channels to trick individuals and make them reveal confidential
	data or install malwares. Can be done as:

* **Business-to-business Compromise (BEC)**: An agent sends an email that seems to be from a trustful source, pretending to use the informations to a good and useful purpose. Usually to gain access to financial informations.
* **Spear phishing**: Attack that happens when an agent sends an email pretending to be a trustful source and targets one user or a group of users.
* **Whaling**: A type of spear phishing. The agents targets high executives from a company to obtain access to confidential data.
* **Vishing**: The exploit of electronic communication using voice to obtain confidential data or impersonate someone that can be trusted.
* **Smishing**: Similar to vishing, but using text messages instead.

## Malware:

	Malware is a type of software that is coded to damage computers or
	networks. The main goal is to obtain money or intel data that can 
	be used against a person, a company or a country. Can be coded as:

* **Virus**: A type of malware that is written to interfere with the operations of a computer. A virus can be downloaded by a naive user (or an external agent) that when executed, the file hides itself among other files. The main goal of a virus is to destroy or corrupt data inside a system.
* **Worms**: A malware that auto reproduces itself inside a network. It doesn't need to be downloaded by a user. Instead, it just needs to infect one system and then reproduces itself to contaminate all other devices.
* **Ransomware**: Malicious attack in which external agents encrypt data from a company and demand payment to restore the access.
* **Spyware**: Malware used to collect and sell information without consent. The spyware also can be used to access devices. 

## Social Engineering: 

	A technique that uses human error to obtain access to confidential
	data or physical spaces. Human error is usually the result of
	trusting someone without questioning. The mission of someone using
	this is to create a space of trust, with false confidence and lies
	to exploit the bigger number of people as possible.

* **Social media phishing**: Use the content that the target has available online inside its social media. 
* **Watering hole attack**: The attack is made to a website visited by a specific group of users.
* **Pshysical social engineering**: The attacker pretends to be an employer, a costumer or a supplier to gain access to certain locations.

	`Social engineering is highly effective. This happens because people are prone to trust and respect authority. The number of social engineering attacks is only growing with time and the number of new social medias. Posting locations, photos and even other personal data can be fun, it only becomes more risky.

	The reasons why social engineering is useful is:

* **Authority**: The agents pretends to be individuals with power. People are, usually, conditioned to follow orders from persons in power.
* **Intimidation**: They use intimidation to gain what they want. This includes persuade and intimidate. 
* **Consent/social prove**: The agent make an individual believe that is doing an action that others have done in the past, making it seem legitimate. For example, asks for permissions to a certain employer, saying that it had them in the past and others had given it to him.
* **Scarcity**: Tactic used to suggest that an item or service has its offer is limited.
* **Familiarity**: The agents establish a false emotional connection with users that can be exploited.
* **Trust**: The agent establish a false emotional connection with the target that is exploited over time. They use this kind of relationship to develop trust and gain personal information.
* **Urgency**: An agent persuades the target to answer its demands without questioning. 

## Network interception attack

This kind of attack is executed by monitoring a network and intercepting the packages and stealing valuable information or interfering with the company's processes somehow.

The threat agents can use tools such as hardware or software devices that monitor the traffic in a network. When capturing packages sent, the threat actor can see info that they don't have access to and they can also change the destiny or content of the information. This can lead to many damages to the company business. 

For example, an attack can intercept a banking transfer and change the account that will receive the money to one that's controlled by the threat agent.

## Backdoor attacks

Backdoors are weak points left intentionally by developers or the admin of a system/network, that won't go into the usual flow of authentication. The backdoors have the goal to help devs/admins to do the solving of problems, without bureaucratic barriers. However, the backdoors can be installed by attackers after compromising a company, with the goal to maintain a previous access permanently.

After accessing a backdoor, the threat agent can cause damages such as: install malwares, do a **Denial of Service Attack**, steal private informations or can change the security configurations of a system with the main objective of leaving breaches for another attacks.

## Denial of Service (DoS) Attack

It's an attack that targets a network or server and floods it with network traffic. The main goal of this attack that it disrupts business operations in an organization.

- **Distributed denial of service (DDoS) attack**: A type of DoS attack that uses multiple devices or servers in different locations to flood the target network with unwanted traffic.

Bellow there are three network level DoS attacks:

1. **SYN (synchronize) flood attack**: A type of attack that simulates a TCP handshake connection and floods a server with SYN packets.
2. **Internet Control Message Protocol (ICMP) flood**: A type of attack performed by an attacker repeatedly sending ICMP packets to a network server.
3. **Ping of death**: A type of attack caused when a hacker pings a system by sending it an oversized ICMP packet that's bigger than 64KB.

## Packet interception

**Packet sniffing** is a practice that captures and intercepts data packets in a network.

A NIC is the hardware part that connects the device to a network. This device reads the data transmission, and if it contains the MAC address of the device, accepts the packet and sends it to the device to process the informations based on the protocol. However, a NIC can be in a malicious mode, that will allow it to listen to all traffic in the network. 

Threat actos can use softwares, such as WireShark, to capture data in a private network and store them for later use. With this, they can use information for personal gain. However, they can use the IP and MAC address of an authenticated user of a private network to do a **IP spoofing**.

### IP spoofing

After the interception of data packets in a network, the threat actor can disguise himself with the IP and MAC addresses captured and authenticated, to realize this attack. The firewalls can avoid spoofing attacks by setting rules to refuse packets from IPs not authorized and suspicious traffic.

#### Types of attacks:

##### On-Path Attack

This attack happens when a hacker intercepts communication between two devices or servers that have a trusted connection. The transmission between these devices can have valuable information, like usernames and passwords, that the threat actor can collect. 

Sometimes this attack is called **man-in-the-middle attack**, because the hacker is hiding between two trustable parts.

This information intercepted can make a DNS request. If a threat actor can intercept a transmission that contains a DNS search, they can make a spoofing DNS response and redirect the device to a domain with a different IP address, maybe one that contains malicious codes or other threats.

The simplest and most important way is to cryptograph data in transit, using TLS, for example, or even a [[Network#Virtual Private Networks (VPNs)|VPN]].

##### Smurf attack

A **smurf attack** happens when a threat agent discover the IP address of an authenticated user and floods it with packets. When the spoofing packet reaches the address of transmission, it's sent to all devices and servers in the network.

This type of attack is the combination between **spoofing attack** and [[#Denial of Service (DoS) Attack|DoS]] attack to flood the target network. For example, a spoofing packet can include a a ICMP ping. ICMP protocol is used to solve problems in a network, but if too many ICMP messages are transmitted, the echo answers will overflow the servers and they'll shut down.

## Brute Force Attacks

This kind of attack is a process of trial and error to find private informations.
These are the types that can be done:

1. **Simple Brute Force**: This is a process where the attackers try to guess the credentials of a user.
2. **Dictionary attacks**: The attackers can use a list of common passwords and credentials stolen from other attacks.

