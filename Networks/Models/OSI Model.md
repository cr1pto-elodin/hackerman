
The [[TCP IP|TCP/IP]] model is a simplified version of the OSI Model. OSI stands for Open System Interconnection. The OSI Model is separated in 7 layers that explain with details how the process works.

The **TCP/IP** is a structure used to visualize how data is organized and transmitted in a network. However, the OSI model is a concept used as standard that describes seven layers that computers use to communicate and send data through the network.

It's very important to understand that these models are concepts to help understand process in a certain network. Some companies can use one model, the other or even a third one to help network engineers and cybersecurity analysts.

## Layer 7: Application Layer

This layer includes the processes that envolves directly the standard user. Here are all the network protocols that softwares use to connect a single user to the Internet. This characteristic that identifies the **application layer**: connecting the users to the Internet by using apps and requests.

Protocols used here: HTTP/HTTPS, STMP or DNS.

## Layer 6: Presentation Layer

The functions of this layers revolves around the data translation and cryptography. This layer adds and substitutes data for means that can be understood by applications in the systems of sending and receiving. These processes needs to be standard by the layer, so side A can understand side B, and vice versa.

Some functions are: cryptography, data compact and confirmation that the set of chars can be understood in the other side. An example is the SSL cryptography, which occurs in this layers, and is used between Web servers and browsers.

## Layer 5: Session Layer

A session is when a connection is established between two devices. An open session allows devices to communicate between them. The protocols of this sessions keep the session open while data is being transferred and end this session when the transmission ends.

The session layer is also responsible for activities like authentication, reconnection and definition of verifying points between a data transfer. If a session is interrupted, the verifying points can make the session resume from the the point where the connection was lost. Sessions always require a request and an answer between applications.
## Layer 4: Transport Layer

This layer deals with the delivery of data packets between devices. It also deals with speed of data transfer, flow of transference and the data division into smaller parts that will become the packets. These smaller parts need to be remounted on the other side of the connection.
## Layer 3: Network Layer

This layer gets the frames from the **Data Link Layer** and delivers them into the right address. This address is written in all data packages, which includes IP addresses that tells to the network devices where the packages should be sent.

## Layer 2: Data Link Layer

This layer organizes the sending and receiving of data in a single network. It includes all the data exchanges between devices in a local network and the network interface cards (NIC).

Protocols used here are: 

- Network Control Protocol (NCP)
- High Data Level Control (HDLC)
- Synchronous Data Link Control (SDLC)

## Layer 1: Physical Layer

Finally we get the layer that corresponds to hardware that are used in the transmission.