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

### 2. Data Transmission
- **Analog vs. Digital**: Data transmission can occur in analog or digital formats. Analog transmission involves continuous signals that vary in amplitude or frequency, while digital transmission involves discrete signals represented as binary digits (0s and 1s). Digital transmission is more resilient to noise and distortion, making it the preferred method for most modern communication systems.
   - [Khan Academy - Digital and analog information
](https://www.khanacademy.org/science/ms-physics/x1baed5db7c1bb50b:waves/x1baed5db7c1bb50b:digital-signals/v/digital-and-analog-information)
- **Bandwidth**: Bandwidth refers to the maximum data transfer rate of a network or communication channel. It determines the amount of data that can be transmitted per unit of time and is measured in bits per second (bps), kilobits per second (kbps), or megabits per second (Mbps). Higher bandwidth allows for faster data transmission and better network performance.
- **Latency**: Latency, also known as delay, is the time it takes for data to travel from its source to its destination over a network. Latency can be affected by various factors, including the distance between devices, the speed of light, network congestion, and processing time. Low latency is essential for real-time applications such as voice and video communication, online gaming, and financial transactions.

### 3. Network Devices
- **Routers**: Routers are network devices that forward data packets between different computer networks. They operate at the network layer of the OSI model and use routing tables and protocols to determine the best path for packet delivery. Routers play a crucial role in connecting devices across multiple networks and enabling communication between them.
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

### 5. Network Topologies

![5f1086baa37c842a30184650_network-topology-types-diagram](https://github.com/zelhajou/42-net_practice/assets/39954629/b0b8d397-e828-445c-951c-bfcd54eaa207)

- **Bus Topology**: In a bus topology, all devices are connected to a single communication line (bus). Data is transmitted along the bus, and each device receives the data but only processes data addressed to it.
- **Star Topology**: In a star topology, each device is connected to a central hub or switch. Data is transmitted from one device to the hub/switch and then forwarded to the intended recipient.
- **Ring Topology**: In a ring topology, devices are connected in a closed-loop configuration. Data circulates around the ring, with each device receiving and forwarding data packets to the next device until they reach their destination.
- **Mesh Topology**: In a mesh topology, devices are interconnected with multiple redundant paths. This redundancy provides fault tolerance and ensures reliable communication, but it can be costly and complex to implement.

  - [Network Topologies (Star, Bus, Ring, Mesh, Ad hoc, Infrastructure, & Wireless Mesh Topology)](https://www.youtube.com/watch?v=zbqrNg4C98U)📹
  - [IT Dose - Network Topologies Bus - Ring - Mesh - Star](https://youtu.be/cLuBLwa3XlI)[AR]📹



## Net Practice Resources


- [Guide to NetPractice](https://github.com/lpaube/NetPractice?tab=readme-ov-file)

- [NetPractice](https://42-cursus.gitbook.io/guide/rank-04/netpractice)
