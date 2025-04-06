---
title: Computer Network Viva Questions with answers
layout: post
date: '2025-03-31'
---

### **Basic Questions**  
1. **What is a computer network?**  
   A computer network is a system of interconnected devices that communicate and share resources using protocols over wired or wireless connections.  

2. **What are the types of computer networks?**  
   - **LAN (Local Area Network)** – Covers a small area like a home, school, or office.  
   - **MAN (Metropolitan Area Network)** – Covers a city or a large campus.  
   - **WAN (Wide Area Network)** – Covers large geographic areas like countries or continents (e.g., the Internet).  

3. **What is the difference between the Internet and an intranet?**  
   - **Internet** is a global network connecting millions of private, public, academic, business, and government networks.  
   - **Intranet** is a private network restricted to an organization for internal communication.  

4. **What are the different types of network topologies?**  
   - **Bus** – Uses a single backbone cable; failure in the cable affects the entire network.  
   - **Star** – All devices connect to a central hub or switch; failure of the hub affects the network.  
   - **Ring** – Each device connects to two others, forming a ring; failure in one device can break the loop.  
   - **Mesh** – Every device connects to every other device, ensuring redundancy.  
   - **Hybrid** – A mix of two or more topologies.  

5. **What is a MAC address?**  
   A **Media Access Control (MAC) address** is a unique identifier assigned to a network interface card (NIC) by the manufacturer. It is used for communication within a network segment.  

---

### **OSI & TCP/IP Model Questions**  
6. **What are the seven layers of the OSI model?**  
   - **Physical** – Transmission of raw data over the medium.  
   - **Data Link** – Handles error detection and framing (e.g., MAC address).  
   - **Network** – Manages routing and IP addressing.  
   - **Transport** – Ensures reliable transmission (e.g., TCP, UDP).  
   - **Session** – Establishes and maintains sessions between applications.  
   - **Presentation** – Formats, encrypts, and compresses data.  
   - **Application** – Provides network services to end users (e.g., HTTP, FTP).  

7. **Compare TCP and UDP.**  
   - **TCP (Transmission Control Protocol)**: Reliable, connection-oriented, ensures data delivery (e.g., web browsing, email).  
   - **UDP (User Datagram Protocol)**: Unreliable, connectionless, faster, used in real-time applications (e.g., video streaming, VoIP).  

8. **What is encapsulation in networking?**  
   Encapsulation is the process of adding headers and trailers to data as it moves through the OSI layers before transmission.  

---

### **IP Addressing & Routing**  
9. **What is an IP address?**  
   An **IP address** is a numerical label assigned to a device for identification and communication over a network.  

10. **Differentiate between IPv4 and IPv6.**  
   - **IPv4**: 32-bit address, uses decimal notation, supports ~4.3 billion addresses.  
   - **IPv6**: 128-bit address, uses hexadecimal notation, supports trillions of addresses.  

11. **What is a subnet mask?**  
   A **subnet mask** separates the network and host portions of an IP address to determine which devices belong to the same subnet.  

12. **What is the difference between static and dynamic IP addresses?**  
   - **Static IP**: Manually assigned, does not change, used in servers.  
   - **Dynamic IP**: Assigned by **DHCP (Dynamic Host Configuration Protocol)**, changes periodically.  

13. **What is a default gateway?**  
   A **default gateway** is a router that connects a local network to external networks, forwarding packets that need to reach other networks.  

14. **What is NAT (Network Address Translation)?**  
   NAT allows multiple devices on a local network to share a single public IP address, improving security and conserving IP addresses.  

---

### **Networking Devices & Protocols**  
15. **What is the function of a router?**  
   A router forwards data between different networks based on IP addresses.  

16. **What is a switch?**  
   A switch operates at the **data link layer**, directing data only to the intended recipient, improving efficiency over hubs.  

17. **What is the difference between a hub, switch, and router?**  
   - **Hub**: Broadcasts data to all devices in a network.  
   - **Switch**: Sends data only to the intended device.  
   - **Router**: Connects different networks and directs traffic based on IP addresses.  

18. **What is ARP (Address Resolution Protocol)?**  
   ARP maps an **IP address to a MAC address** for communication within a network.  

19. **What is DNS (Domain Name System)?**  
   DNS translates domain names (e.g., google.com) into IP addresses (e.g., 142.250.183.238).  

20. **What is DHCP (Dynamic Host Configuration Protocol)?**  
   DHCP automatically assigns **IP addresses** to devices in a network.  

---

### **Security & Miscellaneous Questions**  
21. **What is a firewall?**  
   A firewall is a security system that monitors and controls incoming and outgoing network traffic based on security rules.  

22. **What is a VPN (Virtual Private Network)?**  
   A VPN encrypts data and routes it through a secure server, masking the user's actual IP address for privacy.  

23. **What is a proxy server?**  
   A proxy server acts as an intermediary between a user and the internet, often used for security, anonymity, or content filtering.  

24. **What is bandwidth?**  
   Bandwidth is the maximum data transfer rate of a network or internet connection, measured in **bps (bits per second)**.  

25. **What is latency?**  
   Latency is the time taken for a data packet to travel from source to destination, usually measured in **milliseconds (ms)**.  

26. **What is ping?**  
   **Ping** is a network command that tests the reachability of a host and measures round-trip time (RTT).  

27. **What is packet switching?**  
   Packet switching breaks data into packets that travel independently to their destination, allowing efficient and fast transmission (e.g., the Internet).  

28. **What is the difference between unicast, multicast, and broadcast?**  
   - **Unicast** – One-to-one communication.  
   - **Multicast** – One-to-many (specific group).  
   - **Broadcast** – One-to-all devices in a network.  

29. **What is a man-in-the-middle (MITM) attack?**  
   A MITM attack occurs when an attacker secretly intercepts and possibly alters communication between two parties.  

30. **What is a denial-of-service (DoS) attack?**  
   A DoS attack floods a network or server with excessive traffic to disrupt normal operation.  

---

### **Bonus: Tricky Questions**  
31. **Why is TCP more reliable than UDP?**  
   TCP provides **error checking, retransmissions, congestion control, and three-way handshake**, ensuring data is delivered correctly.  

32. **How does HTTPS work?**  
   HTTPS uses **SSL/TLS encryption** to secure communication between a client and a server, preventing eavesdropping and data tampering.  

33. **What happens when you type a URL in a browser and press Enter?**  
   - DNS resolves the domain name to an IP address.  
   - Browser establishes a **TCP connection** with the server.  
   - HTTP/HTTPS request is sent to the server.  
   - Server responds with the requested webpage.  
   - Browser renders the webpage.  

---

### **Network Devices and OSI Layers**  

1. **Which device operates at the Physical Layer (Layer 1)?**  
   - **Hubs, Repeaters, Cables (Ethernet, Fiber Optic), and Network Interface Cards (NICs)** work at the **Physical Layer**.  
   - They deal with raw data transmission, signals, and bit representation.  

2. **Which device operates at the Data Link Layer (Layer 2)?**  
   - **Switches and Bridges** operate at the **Data Link Layer**.  
   - They use **MAC addresses** for forwarding frames within a network.  

3. **Which device operates at the Network Layer (Layer 3)?**  
   - **Routers and Layer 3 Switches** operate at the **Network Layer**.  
   - They use **IP addresses** for routing packets across different networks.  

4. **Which device operates at the Transport Layer (Layer 4)?**  
   - **Firewalls and Load Balancers** work at the **Transport Layer**.  
   - They handle **port numbers, segmentation, and flow control** (e.g., TCP and UDP).  

5. **Which device operates at the Session Layer (Layer 5)?**  
   - Some **Gateways** and **Proxies** operate at the **Session Layer**.  
   - They establish, maintain, and terminate communication sessions.  

6. **Which device operates at the Presentation Layer (Layer 6)?**  
   - **Encryption/Decryption Devices (SSL/TLS)** and **Data Compressors** work at the **Presentation Layer**.  
   - They format data for compatibility and security.  

7. **Which device operates at the Application Layer (Layer 7)?**  
   - **Web Servers, Email Servers, Proxies, and DNS Servers** operate at the **Application Layer**.  
   - They interact with end-user applications like browsers, email clients, and file transfers.  

---

### **More Layer-Specific Questions**  

8. **What is the role of a repeater in networking?**  
   - A repeater regenerates and amplifies weak signals to extend transmission distances.  
   - It operates at **Layer 1 (Physical Layer)**.  

9. **What is the main function of a switch?**  
   - A switch intelligently forwards data to the correct device using **MAC addresses**.  
   - It operates at **Layer 2 (Data Link Layer)**.  

10. **How does a router differ from a switch?**  
    - A **router** operates at **Layer 3 (Network Layer)** and routes packets based on **IP addresses**.  
    - A **switch** operates at **Layer 2 (Data Link Layer)** and forwards frames using **MAC addresses**.  

11. **What is a Layer 3 switch?**  
    - A **Layer 3 switch** performs both **switching (Layer 2)** and **routing (Layer 3)** functions.  
    - It allows communication between different subnets.  

12. **How does a firewall work, and at which layer does it operate?**  
    - A **firewall** monitors and filters incoming/outgoing traffic based on security rules.  
    - It primarily operates at **Layer 4 (Transport Layer)** but can extend to **Layer 7 (Application Layer)** in advanced configurations.  

13. **What is the function of a proxy server, and which OSI layer does it belong to?**  
    - A **proxy server** acts as an intermediary between clients and servers, providing caching, security, and anonymity.  
    - It operates at **Layer 7 (Application Layer)**.  

14. **At which layer does NAT (Network Address Translation) work?**  
    - NAT operates at **Layer 3 (Network Layer)** because it modifies IP addresses for internet access.  

15. **What layer does DNS work in?**  
    - DNS (Domain Name System) works at **Layer 7 (Application Layer)** because it translates domain names into IP addresses.  

16. **At which OSI layer does SSL/TLS encryption work?**  
    - **SSL/TLS encryption** operates at **Layer 6 (Presentation Layer)** for encryption and decryption.  

---

### **Tricky Layer Questions**  

17. **Can a device work at multiple OSI layers?**  
    - Yes, some devices like **firewalls, proxies, and gateways** operate at multiple layers.  

18. **What is the highest OSI layer that a switch can operate at?**  
    - A basic switch operates at **Layer 2**, but **Layer 3 switches** can function at the **Network Layer**.  

19. **What happens if a router fails?**  
    - Network packets cannot be forwarded between different networks, breaking external communication.  

20. **Why are hubs considered obsolete?**  
    - Hubs send data to all devices, causing network congestion, whereas **switches** send data only to intended recipients.  

---

This should cover all the **must-know viva questions** about **network devices and OSI layers**. Let me know if you need more! 🚀