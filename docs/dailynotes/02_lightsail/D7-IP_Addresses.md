# IP addressing in Amazon lightsail

## Day 7

- [ ] What is IP addresses?
- [ ] IPv4 vs IPv6
- [ ] What is NAT?
- [ ] How IP networking works in Cloud
- [ ] Types of IP addresses

## What is IP address?

- An IP address is a unique identifier that's used to identify devices on a network.
- IP addresses are made up of a series of numbers separated by periods, like 192.168.0.1.
- There are two types of IP addresses: IPv4 and IPv6.
- IPv4 addresses are the most common and are made up of four sets of numbers between 0 and 255.
- IPv6 addresses are newer and use a longer format that includes letters and numbers.
- Every device on a network needs a unique IP address to communicate with other devices.
- IP addresses are assigned by a network administrator or automatically by a device.
- Private IP addresses are used for communication within a local network, while public IP addresses are used for communication over the internet.
- IP addresses can be static (never change) or dynamic (assigned automatically and can change over time).
- Private IP addresses in each classes are as follows
  - Class A: 10.0.0.0 to 10.255.255.255
  - Class B: 172.16.0.0 to 172.31.255.255
  - Class C: 192.168.0.0 to 192.168.255.255


## IPv4 vs IPv6

| IPv4                             | IPv6                                          |
|----------------------------------|-----------------------------------------------|
| 32-bit address                   | 128-bit address                               |
| Addresses are in decimal format  | Addresses are in hexadecimal format           |
| Supports up to 4.3 billion unique addresses | Supports up to 3.4 x 10^38 unique addresses |
| Uses ARP to map IP addresses to MAC addresses | Uses ICMPv6 Neighbor Discovery to map IP addresses to MAC addresses |
| No built-in security features     | Built-in support for IPSec security            |
| Header contains 13 fields         | Header contains 8 fields                       |
| Header does not identify packet flow for QoS handling by routers | Header includes flow label for QoS handling by routers |
| Fragments packets for reassembly by hosts | Does not fragment packets                      |
| IPv4 options are rarely used       | IPv6 options are more commonly used for mobility, quality of service, and routing     |
| Classful addressing                | Classless addressing                            |


## What is NAT?

- NAT is a technique used to share a single public IP address across multiple devices on a private network.
- NAT can be compared to a local Wi-Fi router, where devices on a local network are assigned private IP addresses.
- When a device on the local network wants to communicate with a resource on the internet, the router uses NAT to translate the private IP address of the device to the public IP address assigned by the ISP.
- This allows the device to communicate with the resource on the internet while still keeping its private IP address hidden from the outside world.
- When the resource on the internet sends a response back to the device, the router uses NAT to translate the public IP address back to the private IP address of the device using following methods
  - Static NAT: In this type of NAT, a one-to-one mapping is created between a public IP address and a private IP address. This is useful when you have a single device that needs to be accessible from the internet.
  - Dynamic NAT: In dynamic NAT, a pool of public IP addresses is assigned to a group of private IP addresses. When a device on the private network sends a request to the internet, a public IP address is dynamically assigned from the pool and mapped to the private IP address of the device.
  - Overloading NAT (or PAT): In this type of NAT, a single public IP address is shared by multiple devices on the private network. Each device is assigned a unique port number that is used to map incoming traffic from the public IP address to the correct device on the private network.
  - Destination NAT: This type of NAT is used to forward traffic from a public IP address to a private IP address, based on the destination IP address of the incoming traffic.


## How IP addressing works in Lightsail


- When you create an instance in Lightsail, it is assigned a private IP address that is only accessible within a *private* network
- Each instance is assigned a private IP address by default, which is used for internal communication between instances and services within your account.
- In Amazon Lightsail, a public IP address is attached to a private IP address through the use of Network Address Translation (NAT).
- To make your instance accessible from the internet, you need to associate a public IP address with it.
- The NAT system in the network infrastructure automatically maps the public IP address to the private IP address.
- This allows traffic to be routed from the internet to your instance using the public IP address.
- By using NAT to associate a public IP address with your instance's private IP address, you can enable internet connectivity for your instance while still keeping it protected within your VPC network.
- You can assign a public IP address to your instance, which can be used to access your instance over the internet. This can be useful if you want to host a website or other internet-facing application.
- There are two types of public IP addresses available in Lightsail: static and dynamic. A static IP address remains the same for the lifetime of your instance, while a dynamic IP address can change if you stop and start your instance.


## Creating a Static IP

- To allocate a static IP address to your instance by navigating to the Networking tab in the Lightsail console and selecting "Create static IP." Once you have a static IP address, you can associate it with your instance to ensure that it remains the same even if you stop and start your instance.
- It's important to note that there may be additional charges for using a static IP address in Lightsail, so be sure to check the pricing details before enabling this feature.
