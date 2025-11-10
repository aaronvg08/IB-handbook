An Internet Protocol (IP) address is a unique numerical label assigned to each device connected to a computer [[Networks|network]]. The purpose of an IP address is to:

- Identify a device on the network.
- Locate the device to enable communication with other devices over a network like the [[Internet|internet]].

# IPv4 address

An IPv4 address is a 32-bit address that is typically displayed as four numbers separated by dots, and it indicates the network and host of the device.

![[ip address.png|center|300]]

# IPv6

An IPv6 address is a 128-bit address that is typically displayed as eight groups of four bytes written in [[Hexadecimal|hexadecimal]].

![[ipv6 address.png|center|600]]

It was made out of a necessity to store more values since 32-bit addresses (IPv4) can run out eventually since it only has $2^{32}-1$ values. This one has $2^{128}-1$ values instead, so it's very unlikely to run out.

# Subnet Mask

A subnet mask is the configuration of which numbers in an IP address indicate the network and which ones indicate the host (or device). It fills the address with ones in [[Binary|binary]] so that those values never change.

![[subnet mask.png|center|400]]