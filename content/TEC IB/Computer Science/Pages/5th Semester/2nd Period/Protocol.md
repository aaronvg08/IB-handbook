A protocol in [[Networks|networks]] is the way that data is sent through devices. It is a set of rules and standards that define how data is transmitted and received across a network.

A data packet is a formatted piece of information transmitted over a network. Contains both the data itself and control information (source and destination addresses).

Data packets are sent through there phases:

- **Sync**: The data packet tells the server to pay attention since they are about to receive data.
- **Data packet**: Data is transmitted to the server or device.
- **Acknowledge**: The data packet tells the server that it's done and it should verify the data to make sure that it is complete and its [[Integrity|integrity]] is protected.

# User Datagram Protocol (UDP)

The User Datagram Protocol (UDP) is a [[Protocol|protocol]] for [[Networks|networks]] that is fast and connectionless. There is no guarantee that the data is received properly or completely. This is used for streaming video where maintaining broadcast is more important than keeping detail.

>[!warning]
>There is no verification since it is used for non-sensitive transmission.

# Transmission Control Protocol (TCP)

The Transmission Control Protocol (TCP) is a [[Protocol|protocol]] for [[Networks|networks]]. It establishes and maintains an active connection with the remote server until the application programs have finished exchanging information.

Some common applications for the TCP are:

- Simple Mail Transfer Protocol **(SMTP)**: port 587.
- Hypertext Transfer Protocol **(HTPP)**: port 80.
- Hypertext Transfer Protocol Secure **(HTTPS)**: port 443.
- Secure Shell **(SSH)**: port 22.
- Dynamic Host Configuration Protocol **(DHCP)**: port 68.

>[!note]
>There is a constant connection between the two machines and there is a constant exchange of information and verification between the two.



