# Net Practice

## Overview

This repository contains practice exercises and projects related to networking concepts, as part of the curriculum at 42 School. These exercises are designed to help students grasp various networking principles and protocols, enhancing their understanding and skills in this domain.

## Introduction to Networking
Networking is a foundational concept in the realm of computer science and technology. It revolves around the interconnection of devices and systems to share resources, information, and communication. In today's interconnected world, networking is crucial in enabling communication between computers, smartphones, servers, and other devices, both locally and globally.

At its core, networking involves exchanging data between devices over a communication medium, such as cables, wireless signals, or optical fibers. This exchange of data enables users to access websites, send emails, stream videos, transfer files, and perform countless other tasks that rely on network connectivity.

  - [Fireship - Computer Networking in 100 Seconds](https://youtu.be/keeqnciDVOo) 📹
  - [NetworkChuck -  What is a Network?](https://youtu.be/S7MNX_UD7vY?list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P) 📹
  - [Crash Course - Computer Networks](https://youtu.be/3QhU9jd03a0) 📹

### Key Components of Networking:
1. **Devices**: Networking involves various types of devices, including computers, routers, switches, modems, access points, and servers. These devices serve different functions within a network and are interconnected to facilitate communication and data exchange.
2. **Protocols**: Protocols are rules and conventions that govern communication between devices on a network. They define how data is formatted, transmitted, received, and interpreted by devices. Common network protocols include TCP/IP, HTTP, FTP, DNS, and SMTP
3. **Topologies**: Network topology refers to the physical or logical arrangement of devices and connections within a network. Common network topologies include bus, star, ring, and mesh configurations, each with its advantages and limitations in terms of scalability, fault tolerance, and performance.
4. **Addressing**: Network addressing involves assigning unique identifiers to devices on a network to facilitate communication. IP addresses are used to identify devices within a network, while MAC addresses are used to identify devices at the data link layer.
5. **Security**: Network security is a critical aspect of networking that involves protecting data, devices, and infrastructure from unauthorized access, attacks, and threats. Security measures include encryption, authentication, firewalls, intrusion detection systems, and security protocols.

### Evolution of Networking:
Networking has evolved significantly over the years, driven by technological advancements and changing user demands. From early local area networks (LANs) and wide area networks (WANs) to modern cloud computing and mobile networking technologies, the landscape of networking continues to evolve rapidly.

Emerging technologies such as software-defined networking (SDN), network function virtualization (NFV), 5G networking, and the Internet of Things (IoT) are reshaping the way networks are designed, deployed, and managed. These technologies offer new opportunities and challenges for businesses, governments, and individuals seeking to harness the power of network connectivity.

### Importance of Networking:
Networking is essential for businesses, organizations, and individuals alike, enabling collaboration, innovation, and connectivity on a global scale. It facilitates access to information, resources, and services, driving productivity, efficiency, and growth in various industries and sectors.

In the digital age, networking has become synonymous with communication, collaboration, and connectivity. Whether it's connecting people through social media, enabling remote work and learning, or powering e-commerce and online services, networking is the backbone of our interconnected world.

## Network Basics
Networking encompasses a wide range of concepts and principles that form the foundation of communication and data exchange in computer networks.

### 1. Networking Models (OSI, TCP/IP):
- **OSI Model (Open Systems Interconnection)**: The OSI model is a conceptual framework that standardizes the functions of a telecommunication or computing system into seven abstraction layers. Each layer serves a specific purpose, such as physical transmission, data link connection, network addressing, and application services. The OSI model provides a structured approach to understanding and implementing network protocols and services.
  - [Cloudflare - What is the OSI model](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
  - [Geeksforgeeks - Layers of OSI model](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
  - [What is OSI Model | Real World Examples](https://youtu.be/0y6FtKsg6J4) 📹
  - [OSI Layers](https://youtu.be/A31bxOyj5mk)[AR] 📹
- **TCP/IP Model (Transmission Control Protocol/Internet Protocol)**: The TCP/IP model is a simplified version of the OSI model, commonly used in modern networking environments, especially on the internet. It consists of four layers: Network Interface, Internet, Transport, and Application. The TCP/IP model defines the protocols and services used for communication between devices on the internet, including IP addressing, routing, TCP, UDP, and application-layer protocols such as HTTP, FTP, and DNS.
  - [Geeksforgeeks - TCP/IP model](https://www.geeksforgeeks.org/tcp-ip-model/)
  - [NetworkChuck - What is TCP/IP and OSI?](https://www.youtube.com/watch?v=CRdL1PcherM&list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P&index=4&pp=iAQB) 
### 2. Data Transmission
- **Analog vs. Digital**: Data transmission can occur in analog or digital formats. Analog transmission involves continuous signals that vary in amplitude or frequency, while digital transmission involves discrete signals represented as binary digits (0s and 1s). Digital transmission is more resilient to noise and distortion, making it the preferred method for most modern communication systems.
   - [Khan Academy - Digital and analog information
](https://www.khanacademy.org/science/ms-physics/x1baed5db7c1bb50b:waves/x1baed5db7c1bb50b:digital-signals/v/digital-and-analog-information)
- **Bandwidth**: Bandwidth refers to the maximum data transfer rate of a network or communication channel. It determines the amount of data that can be transmitted per unit of time and is measured in bits per second (bps), kilobits per second (kbps), or megabits per second (Mbps). Higher bandwidth allows for faster data transmission and better network performance.
- **Latency**: Latency, also known as delay, is the time it takes for data to travel from its source to its destination over a network. Latency can be affected by various factors, including the distance between devices, the speed of light, network congestion, and processing time. Low latency is essential for real-time applications such as voice and video communication, online gaming, and financial transactions.

### 3. Network Devices
- **Routers**: Routers are network devices that forward data packets between different computer networks. They operate at the network layer of the OSI model and use routing tables and protocols to determine the best path for packet delivery. Routers play a crucial role in connecting devices across multiple networks and enabling communication between them.
  - [NetworkChuck - What is ROUTER?](https://www.youtube.com/watch?v=p9ScLm9S3B4&list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P&index=3&pp=iAQB) 
- **Switches**: Switches are network devices that connect multiple devices within a local area network (LAN). They operate at the data link layer of the OSI model and use MAC addresses to forward data packets to the intended recipient. Switches improve network efficiency and performance by reducing collisions and segmenting network traffic.
  - [NetworkChuck - What is a SWITCH?](https://youtu.be/9eH16Fxeb9o?list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P)📹
- **Hubs**: Hubs are network devices that connect multiple devices within a LAN. Unlike switches, hubs operate at the physical layer of the OSI model and broadcast data packets to all connected devices. This broadcasting can lead to network congestion and reduced performance, making hubs less common in modern network environments.
- **Modems**: Modems (modulator-demodulator) are devices that modulate digital data signals into analog signals for transmission over analog communication channels, such as telephone lines, and demodulate analog signals back into digital data signals for reception. Modems are commonly used to connect devices to the internet via dial-up, DSL, cable, or fiber-optic connections.

  - [Geeksforgeeks - Network Devices (Hub, Repeater, Bridge, Switch, Router, Gateways and Brouter)](https://www.geeksforgeeks.org/network-devices-hub-repeater-bridge-switch-router-gateways/)
  - [Hub vs Switch vs Router](https://youtu.be/_ifRgCb8o60)[AR]📹
  - [NETWORK DEVICES الفرق بين أجهزة الشبكة](https://www.youtube.com/watch?v=X2LF8rzWijk&pp=ygUWbmV0d29yayBkZXZpY2VzINi02LHYrQ%3D%3D)[AR]📹
  - [Hub, Switch, & Router Explained - What's the difference?](https://youtu.be/1z0ULvg_pW8)📹
  - [Modem vs Router - What's the difference?](https://www.youtube.com/watch?v=Mad4kQ5835Y)📹
  - [Layer 2 vs Layer 3 Switches](https://www.youtube.com/watch?v=bdNS0K4Bt8U)📹

### 4. Network Protocols

- **TCP (Transmission Control Protocol)**: TCP is a reliable, connection-oriented protocol used for transmitting data packets over networks. It provides mechanisms for establishing and terminating connections, acknowledging received data packets, retransmitting lost packets, and controlling data flow to ensure reliable and orderly communication between devices.
- **IP (Internet Protocol)**: IP is a network layer protocol responsible for addressing and routing data packets across interconnected networks. It assigns unique IP addresses to devices and uses routing algorithms to determine the best path for packet delivery. IP is the foundation of the internet and is used to transmit data between devices worldwide.
  - [NetworkChuck - what is an IP Address?](https://www.youtube.com/watch?v=5WfiTHiU4x8) 📹
- **UDP (User Datagram Protocol)**: UDP is a connectionless, unreliable protocol used for transmitting data packets over networks. Unlike TCP, UDP does not establish a connection before sending data and does not provide error checking, sequencing, or flow control mechanisms. UDP is commonly used for real-time applications such as voice and video streaming, where low latency and high throughput are more important than reliability.
- **ICMP (Internet Control Message Protocol)**: ICMP is a network layer protocol used for sending control messages and error reporting between devices on IP networks. It includes messages such as echo request/reply (ping), destination unreachable, time exceeded, and parameter problem. ICMP plays a critical role in diagnosing network connectivity issues, troubleshooting routing problems, and monitoring network performance.
- **ARP (Address Resolution Protocol)**: ARP is a protocol used for mapping IP addresses to MAC addresses on a local network. It enables devices to determine the hardware address of a target device for communication. ARP is essential for transmitting data between devices within the same subnet and is commonly used in Ethernet networks.
  - [ByteByteGo - Top 8 Most Popular Network Protocols Explained](https://youtu.be/P6SZLcGE4us)

### 5. Network Topologies

![5f1086baa37c842a30184650_network-topology-types-diagram](https://github.com/zelhajou/42-net_practice/assets/39954629/b0b8d397-e828-445c-951c-bfcd54eaa207)

- **Bus Topology**: In a bus topology, all devices are connected to a single communication line (bus). Data is transmitted along the bus, and each device receives the data but only processes data addressed to it.
- **Star Topology**: In a star topology, each device is connected to a central hub or switch. Data is transmitted from one device to the hub/switch and then forwarded to the intended recipient.
- **Ring Topology**: In a ring topology, devices are connected in a closed-loop configuration. Data circulates around the ring, with each device receiving and forwarding data packets to the next device until they reach their destination.
- **Mesh Topology**: In a mesh topology, devices are interconnected with multiple redundant paths. This redundancy provides fault tolerance and ensures reliable communication, but it can be costly and complex to implement.

  - [Network Topologies (Star, Bus, Ring, Mesh, Ad hoc, Infrastructure, & Wireless Mesh Topology)](https://www.youtube.com/watch?v=zbqrNg4C98U)📹
  - [IT Dose - Network Topologies Bus - Ring - Mesh - Star](https://youtu.be/cLuBLwa3XlI)[AR]📹

## Network Communication
- **Local Area Networks (LANs)**: LANs are networks that connect devices within a limited geographic area, such as a home, office, or campus. They typically use Ethernet or Wi-Fi technology and are often used for sharing resources such as files, printers, and internet access.
- **Wide Area Networks (WANs)**: WANs connect devices over a wide geographic area, often spanning multiple cities or countries. Examples include the internet, private leased lines, and virtual private networks (VPNs).
- **Wireless Networking**: Wireless technologies enable communication between devices without the need for physical cables. Common wireless standards include Wi-Fi (802.11), Bluetooth, and cellular networks (e.g., 3G, 4G, 5G).
- **Ethernet Technologies**: Ethernet is a widely used networking technology that defines standards for data transmission over wired LANs. Variants include Ethernet, Fast Ethernet, Gigabit Ethernet, and 10 Gigabit Ethernet.
- **Data Link Layer**: The data link layer is responsible for transferring data between adjacent network nodes. It includes functions such as framing, addressing (MAC addresses), error detection, and flow control.
- **Network Layer**: The network layer handles routing and forwarding of data packets across interconnected networks. It includes protocols such as IP (Internet Protocol), ICMP (Internet Control Message Protocol), and ARP (Address Resolution Protocol).

## Internet Protocol (IP)

- **IPv4 Addressing**: IPv4 (Internet Protocol version 4) addresses are numerical identifiers assigned to devices on a network. IPv4 addresses are 32 bits long and are expressed in dotted-decimal notation (e.g., 192.168.1.1).
  - **Subnetting**: Subnetting is the process of dividing a larger network into smaller, more manageable subnetworks or subnets. It involves borrowing bits from the host portion of an IP address to create multiple subnets, each with its own unique range of IP addresses. Subnetting allows network administrators to efficiently allocate IP addresses and manage network resources by organizing devices into logical groups based on their network requirements. Subnet masks are used to identify the network portion and the host portion of an IP address, determining which devices belong to the same subnet and can communicate directly with each other without the need for routing.
- **IPv6 Addressing**: IPv6 (Internet Protocol version 6) addresses are the next generation of IP addresses designed to overcome the limitations of IPv4. IPv6 addresses are 128 bits long and are expressed in hexadecimal notation (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).
- **IP Routing**: IP routing involves forwarding data packets between networks based on destination IP addresses. Routing protocols such as RIP (Routing Information Protocol), OSPF (Open Shortest Path First), and BGP (Border Gateway Protocol) are used to determine the best path for packet delivery.
- **ICMP (Internet Control Message Protocol)**: ICMP is a network layer protocol used for sending control messages and error reporting between devices on IP networks. Common ICMP messages include ping (echo request/reply) and traceroute (packet path tracing).
- **ARP (Address Resolution Protocol)**: ARP is a protocol used for mapping IP addresses to MAC addresses on a local network. It enables devices to determine the hardware address of a target device for communication.

## Transport Layer
- **Transmission Control Protocol (TCP)**: TCP is a reliable, connection-oriented protocol used for transmitting data packets over networks. It provides features such as error detection, flow control, congestion control, and reliable data delivery through mechanisms like acknowledgment, sequencing, and retransmission.
- **User Datagram Protocol (UDP)**: UDP is a connectionless, unreliable protocol used for transmitting data packets over networks. It offers low-overhead communication without the reliability mechanisms of TCP, making it suitable for real-time applications such as VoIP (Voice over IP) and online gaming.
- **Port Numbers**: Port numbers are used to identify specific communication endpoints within a device. They allow multiple network services to run concurrently on a single device. Well-known port numbers (0-1023) are reserved for standard services, while registered port numbers (1024-49151) and dynamic/private port numbers (49152-65535) are used for other applications.
- **TLS (Transport Layer Security)**: TLS is a cryptographic protocol used to secure communication over a computer network. It provides encryption, data integrity, and authentication for data transmissions between clients and servers. TLS ensures that data exchanged between parties remains confidential and tamper-proof, protecting against eavesdropping, data manipulation, and impersonation attacks. and is widely used to secure HTTP, although it can be used with any protocol. TLS is often used in combination with HTTPS, which is HTTP over TLS.
  - [SSL and HTTPS](https://www.youtube.com/watch?v=S2iBR2ZlZf0)
  - [SSL/TLS - Cristina Formaini](https://www.youtube.com/watch?v=Rp3iZUvXWlM)

## Application Layer Protocols:
- **Hypertext Transfer Protocol (HTTP)**: HTTP is a protocol used for transferring hypertext documents, such as web pages, over the internet. It operates on top of TCP and uses port 80 by default. HTTP defines methods for requesting and transmitting data between clients (web browsers) and servers.
  - [Everything you need to know about HTTP](https://cs.fyi/guide/http-in-depth)
  - [What is HTTP?](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)
  - [An overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
  - [HTTP/3 From A To Z: Core Concepts](https://www.smashingmagazine.com/2021/08/http3-core-concepts-part1/)
  - [HTTP/1 to HTTP/2 to HTTP/3](https://www.youtube.com/watch?v=a-sBfyiXysI)
  - [HTTP Crash Course & Exploration](https://www.youtube.com/watch?v=iYM2zFP3Zn0)
- **File Transfer Protocol (FTP)**: FTP is a protocol used for transferring files between a client and a server over a network. It supports various operations such as file upload, download, renaming, and deletion. FTP operates on TCP and uses port 21 for control connections and port 20 for data connections.
- **Domain Name System (DNS)**: DNS is a distributed naming system that translates domain names into IP addresses and vice versa. It enables users to access websites using human-readable domain names instead of numerical IP addresses. DNS operates on both UDP (for queries) and TCP (for zone transfers).
  - [What is DNS?](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
  - [How DNS works (comic)](https://howdns.works/)
  - [DNS and How does it Work?](https://www.youtube.com/watch?v=Wj0od2ag5sk)
  - [DNS Records](https://www.youtube.com/watch?v=7lxgpKh_fRY)
  - [Complete DNS mini-series](https://www.youtube.com/watch?v=zEmUuNFBgN8&list=PLTk5ZYSbd9MhMmOiPhfRJNW7bhxHo4q-K)
  - [DNS in One Picture](https://roadmap.sh/guides/dns-in-one-picture)
  - [DNS Explained](https://youtu.be/72snZctFFtA)
  - [What is a Domain Name?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)
  - [Beginner's Guide: What is a Domain Name and How Does it Work?](https://www.wpbeginner.com/beginners-guide/beginners-guide-what-is-a-domain-name-and-how-do-domains-work/)
- **Simple Mail Transfer Protocol (SMTP)**: SMTP is a protocol used for sending email messages between mail servers. It defines how email messages are transmitted and delivered over the internet. SMTP operates on TCP and uses port 25 by default.
- **Secure Shell (SSH)**: SSH is a cryptographic network protocol used for secure remote access to networked devices. It provides encrypted communication and authentication mechanisms for secure login sessions. SSH operates on TCP and uses port 22 by default.
- **Telnet**: Telnet is a protocol used for remote terminal emulation over a network. It allows users to access and manage devices remotely using a command-line interface. Telnet operates on TCP and uses port 23 by default.
- **Dynamic Host Configuration Protocol (DHCP)**: DHCP is a protocol used for dynamically assigning IP addresses to network devices. It simplifies network configuration by automatically allocating IP addresses, subnet masks, default gateways, and other parameters to devices when they connect to a network.
- **Network Time Protocol (NTP)**: NTP is a protocol used for synchronizing the clocks of networked devices. It ensures accurate timekeeping across distributed systems by synchronizing devices with a reference time source.

## Net Practice Resources
- [Guide to NetPractice](https://github.com/lpaube/NetPractice?tab=readme-ov-file)
- [NetPractice](https://42-cursus.gitbook.io/guide/rank-04/netpractice)
