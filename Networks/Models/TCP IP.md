Protocols of data communication are models that allow to understand and map how two devices in a network communicate. In the following case, it'll be addressed the TCP/IP model, which stands for **Transfer Data Protocol/Internet Protocol**.

## The model

The model serves as a structure used to visualize how data is organized and send inside a network, between devices. This model helps network engineers and cybersecurity analysts conceptualize process in the network and communicate where interruptions occur and threats to security.

The model has four layers:

### Network access layer

This layer deals with the data link, the creation of network packets and its transmission on the network. This layer deals with all the hardware responsible for network communication: [[Network#Network devices|Switches, hubs and modems]]. The ARP is part of this layer, since it can identify the MAC address associated with the IP address.

### Internet Layer

Also called the **network layer**, this layer is responsible for ensuring that the data sent from a certain device reaches the destination device, in the request, even tough the destination device can be in another network. The internet layer guarantees that the right IP addresses are annexed to the data package, allowing the devices to understand who is the sender and who is the receiver.

The network layer can also be used by some network protocols, such as:

- **Internet Protocol (IP)**: The **IP** sends data packages to the right destination and depends on the TCP/IP **(Transmission Control Protocol/ User Datagram IP)** to deliver to the right service. The packages created by the IP allows the communication between multiple networks. The TCP, in particular, resends all the packages that were lost or corrupted.
- **Internet Control Messages Protocol (ICMP)**: This protocol shares information about errors and updates the status on data packages. This is useful to detect and solve network problems.

### Transport Layer

This layer is responsible for the delivery of data packages between two systems or networks and includes protocols that control the data flow. The protocols can be listed as:

- **Transmission Control Protocol (TCP)**: The **TCP** is the protocol that allows internet communication between two devices, while sending data packages to each other. It guarantees that the data is transmitted in a reliable way. The **TCP** contains the service *port*, which contains the the **TCP** header in a **TCP/IP** package.
- **User Datagram Protocol (UDP)**: This is a protocol that does not establishes a connection between the involved devices before the transmission. It's used by apps that do not rely on the transmission. The data sent by the **UDP** are not tracked as precisely as in the **TCP** transmission. Since the **UDP** does not establish a connection between network devices, it's used mostly with real time sensitive applications, such as streaming or gaming applications.

### Application Layer

The **application layer** is similar, in the **TCP/IP** model, is similar to the **OSI Model** layers: **application**, **presentation** and **session**. This layer is responsible to make the network requests or answer them. It also defines which services and internet applications any user can access. The protocols inside this layer define how the package data will interact with the devices placed in destination. Some of the protocols are:

- Hypertext Transfer Protocol (HTTP)
- Simple Mail Transfer Protocol (SMTP)
- Secure Shell
- File Transfer Protocol (FTP)
- Domain Name System (DNS)

