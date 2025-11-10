A virtual private network (VPN) is a secure connection on a [[Networks|network]] that extends a private network across a public network, allowing users to send and receive data as if their devices were directly connected to the private network. 

![[virtual private network (vpn).png|center|600]]

The primary goal of a VPN is to provide secure remote access to a private network and its resources, such as files, printers, and software applications, from any location with internet access.

# Technologies

A VPN can function over unlimited distances since it uses the internet to create a secure and encrypted connection between devices and the private network. This encryption ensures that data transmitted over the VPN is protected from unauthorized access.

- **VPN Protocols**: Rules and standards to transmit data over the VPN.
	- **IPsec (Internet Protocol Security)**: Authenticates and encrypts each packet.
	- **SSL/TLS (Secure Sockets Layer / Transport Layer Security)**: Provides a secure tunnel through which data can be transmitted.
- **Tunneling**: Encapsulates a network packet inside another. It creates a "tunnel" through the public internet, making the connection appear to be a private network link by hiding the original [[Internet Protocol (IP) address|IP addresses]] and encrypting the data.

>[!tldr]
>Tunneling is like wearing a disguise.

