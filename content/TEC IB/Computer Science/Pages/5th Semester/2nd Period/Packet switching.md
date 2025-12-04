Packet switching is a method of sending data in small blocks called 'packets' across a network. Each packet may take a different path to the destination. 

![[packet switching.png|center|600]]

Packet switching works in the following stages:

- **Segmentation**: Divide the data into smaller pieces called packets using the MTU (maximum transmission unit) typically 1500 bytes.
- **Packet Header**: Each packet has information to ensure that the information reaches its destination. It also has an identifier for the sequence.
- **Routing**: Each packet is sent through the network independently and follows a path.
- **Reassembly**: When all packets reach their destination, the original message is reassembled and revised.