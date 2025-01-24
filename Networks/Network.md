A network is a group of interconnected computer devices. They can be mobile phones, but they can also be tablets, notebooks or personal computers. There are many types of networks and network tools that are used to create the connection between multiple devices.

## Network devices

Network devices maintain information and services for users of a network. These devices connect over wired or wireless connection. After establishing a connection, to the network, the devices send data packets. The data packets provide information about the source and the destination of the data. 

### Devices and desktop computers

Most internet users are familiar with everyday devices, such as personal computers, laptops, mobile phones and tablets. Each device and desktop has a unique MAC address and IP address, which identify it on the network. They also have a network interface that sends and receives data packets. These devices can connect to the network via a hard wire or a wireless connection.

### Subnets

A **subnetwork** is a logical subdivision of a larger network. Subnets help divide an IP network into smaller, manageable pieces. Each subnet can operate independently, which improves network performance and security.

### Proxy servers

A server that fulfills the requests of a client by forwarding them on to other servers. They use the **network address translation (NAT)** to serve as a barrier between clients of a network ad the external threats. These are the types of proxy servers:

1. **Forward proxy server**: Regulates and restricts a person's access outside of the internal network.
2. **Reverse proxy server**: Regulates and restrict's the external agents access to an internal server.

### Firewalls

A firewall is a network security device that monitors traffic to or from your network. Firewalls can also restrict specific incoming and outgoing network traffic. The organization sets the rule that will work on the firewalls. Note that they often reside between the secured and controlled internal network and the untrusted network resources outside the organization, such as the internet.

Firewalls can have:

- **Port filtering**: Function that blocks or allows certain port numbers to limit unwanted communication.

Types of Firewalls:

- **Hardware Firewall**: Most basic way to defend a network. It inspects each data package before it enters the network.
- **Software Firewall**: It does the same functions as the hardware firewalls, but it is installed in the devices, such as PC, notebooks or even servers. They will analyze all the traffic that goes into the device and usually costs less than a physical firewall.
- **Cloud-based Firewall**: These are software-based firewalls that are hosted by a cloud service provider. Organizations can configure the firewall rules on the cloud service provider's interface, and the firewall will perform security operations on all incoming traffic before it reaches the organization's onsite network. They also protect any assets or processes that are being hosted on the cloud.

The firewall can be:

- **Stateful**: A class of firewall that keeps track of information passing through it and proactively filters out threats.
- **Stateless**: A class of firewall that operates based on predefined rules and does not keep track of information from data packets. It doesn't store any information about the traffic and it also doesn't keep track of all the suspicious behavior that could be happening inside a network. For this reason, these firewalls are considered less secure.
### Servers

Servers provide informations and services for devices like computers, smart home devices, and smartphones on the network. The devices that are connected to a server are called clients. 

### Virtual Private Networks (VPNs)

A **Virtual Private Network** is a technology that creates a secure, encrypted connection between the client device and a remote server (**VPN** server) over the internet. It provides privacy, security and anonymity by routing your traffic through a secure tunnel, effectively masking your IP address and encrypting data to prevent unauthorized access. The features above make it safe to use a device, like a personal computer, that is in a network that cannot be trusted.

#### Key features of a VPN

1. Encryption: Data is encrypted using protocols so that even if intercepted, it cannot be read without the encryption key.
2. Secure Tunneling: VPNs use secure tunneling protocols to encapsulate and encrypt the traffic between the client and the server.
3. IP Masking: The VPN assigns a new IP address, hiding the client's actual location.
4. Access Control: VPNs can restrict access to specific resources by requiring valid VPN credentials to establish a connection.

#### Summary of Key VPN Types

| **VPN Type**       | **Purpose**                   | **Protocols**             | **Example Use Case**             |
| ------------------ | ----------------------------- | ------------------------- | -------------------------------- |
| Remote Access VPN  | Individual secure access      | OpenVPN, IPSec, WireGuard | Work from home                   |
| Site-to-Site VPN   | Connects networks             | IPSec, MPLS               | Branch offices                   |
| Client-to-Site VPN | Individual client connection  | OpenVPN, SSTP, L2TP       | Freelancers accessing resources  |
| SSL VPN            | Secure access via web browser | SSL/TLS                   | Access internal web applications |
| MPLS VPN           | High-speed secure connections | MPLS                      | Bank branches                    |
| Mobile VPN         | Persistent mobile connections | OpenVPN, IPSec            | Law enforcement in the field     |
| Cloud VPN          | On-prem to cloud connectivity | IPSec, IKEv2              | AWS or Azure access              |

### Hubs and switches

A **hub** is a device that provides a common point of connection for all devices connected to it. Hubs additionally repeat all information out to all ports. From a security perspective, this makes hubs vulnerable to eavesdropping. For this reason, hubs are commonly used for a limited network setup like a home office.

A **switch** forwards packets between devices directly connected to it. They analyze the destination address of each data packet and send it to the intended device. Switches maintain a MAC address table that matches MAC addresses of devices on the network to port numbers on the switch and forward incoming data packets according to the destination MAC address. 

**Switches** are part of the data link layer in the TCP/IP model.

### Routers

**Routers** connect networks and direct traffic, based on the IP address of the destination network. Routers allow devices on different networks to communicate with each other. In the TCP/IP model, routers are a part of the network layer. In the TCP/Ip model, routers are part of the network layer. 

**Routers** can also include a firewall feature that allows or block incoming traffic based on information on the transmission.

### Modems and wireless access points

#### Modems

Modems usually connect your home or office with an internet service provider. IPSs provides internet connectivity via telephone lines or coaxial cables. Modems receive transmission or digital signals from the internet and translate them into analog signals that can travel  through the physical connection provided by your ISP. Usually, modems connect to a router that takes the decoded transmissions and sends them to on the local network.

Note: Enterprise networks used by large organizations to connect their users and devices often use other broadband technologies to handle high-volume traffic, instead of using a modem.

#### Wireless Access Points

This device sends and receive digital signals over radio waves creating a wireless network. Devices with wireless adapters connect to the access point using Wi-Fi. Wi-Fi refers to a set of standards that are used by a network devices to communicate wirelessly. Wireless access points and the devices connected to them use Wi-Fi protocols to send data through radio waves where they are sent to routers and switches and directed along the path to their final destination.