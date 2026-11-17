
# 2. Part B — Configuring the LAN

## 2.1 Static IP Configuration
### Pi A (192.168.50.1)
> Insert screenshot here

### Pi B (192.168.50.2)
> Insert screenshot here

## 2.2 Explanation
Explain:
- What is a static IP address?

- ANSWER=A static IP address is an IP address that is manually assigned to a device and does not change automatically. Unlike dynamic IP addresses, which are assigned by a DHCP server, a static IP remains fixed until it is manually modified. Static IP addresses are commonly used for servers, network printers, and devices that need a permanent network address.
- Why both devices cannot use the same address

- ANSWER=Both devices cannot use the same IP address because every device on a network must have a unique identifier. If two devices are assigned the same IP address, an IP conflict occurs, causing communication problems and preventing reliable network connectivity. The network would be unable to determine which device should receive the data being sent. 
- Why we use /24

- ANSWER=The/24 notation represents a subnet mask of 255.255.255.0. It means that the first 24 bits identify the network portion of the address, while the remaining 8 bits are used for host devices. Using a /24 subnet allows devices such as 192.168.50.1 and 192.168.50.2 to be part of the same local network and communicate with each other directly. A /24 network can support up to 254 usable host addresses

