# IMPORTANT KEYWORDS


**Hardware**

Hardware includes the physical components that make up a computer system. From the memory (RAM) and storage devices to semiconductors that drive the computational logic, hardware plays a vital role in computing.


**Networking**

1. Local Area Network (LAN):

Connects devices within a limited area, such as a home, office, or school.

Uses Ethernet cables or Wi-Fi for connectivity.

High-speed, low-latency network ideal for sharing resources like printers and files.



2. Wide Area Network (WAN):

Spans a large geographic area, connecting multiple LANs across cities, states, or even countries.

The Internet is the largest example of a WAN.

Often uses leased telecommunication lines.



3. Metropolitan Area Network (MAN):

Covers a larger area than a LAN but smaller than a WAN, such as a city or campus.

Often used by cities, universities, or large companies to connect multiple locations.



4. Personal Area Network (PAN):

A small network for individual use, typically within a range of a few meters.

Examples include Bluetooth connections between a smartphone and headphones or a laptop and mouse.



5. Virtual Private Network (VPN):

A secure, encrypted network created over a public network, often used for secure remote access.

Allows users to connect to a private network from different locations.




**Operating Systems**

An operating system (OS) is system software that manages computer hardware and software resources, and provides common services for computer programs. Kernel: The core part of the OS that manages system resources. OS Layer: Abstracts hardware resources for higher-level software. Applications: Programs that run on top of the OS. CISC & RISC: Two primary CPU instruction set architectures. Virtual Machine: An emulation of a computer system.


**OSI**
The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and standardize the functions of a networking system. It was developed by the International Organization for Standardization (ISO) in the late 1970s and provides a structured way to approach network architecture


• The 7 layers of the OSI (Open Systems Interconnection) model are:

1. _Physical Layer_: Handles the physical connection between devices, including hardware aspects like cables, switches, and signal transmission.


2. _Data Link Layer_: Ensures reliable node-to-node data transfer. Manages error detection, error correction, and data framing. Divided into two sublayers: Logical Link Control (LLC) and Media Access Control (MAC).


3. _Network Layer_: Responsible for routing and forwarding data. Determines the best physical path for data, handling IP addresses and packet forwarding.


4. _Transport Layer_: Ensures end-to-end communication, reliability, and flow control. Manages segmentation, error correction, and retransmission. Protocols like TCP and UDP operate here.


5. _Session Layer_: Manages sessions between applications. Establishes, maintains, and terminates connections for ongoing communication between devices.


6. _Presentation Layer_: Formats and translates data for the application layer. Handles encryption, decryption, and data compression.


7. _Application Layer_: Interfaces with end-user applications. Manages high-level protocols, data exchange, and services like email, file transfer, and web browsing.




**DNS**

Domain Name System, is a fundamental component of the internet that translates human-readable domain names into IP addresses that computers use to identify each other on the network. Without DNS, users would have to remember and enter numerical IP addresses to visit websites, rather than simple and memorable domain names.


**Virtualization**

Virtualization allows multiple operating systems to run on the same physical hardware, facilitated by a hypervisor. The cloud enables on-demand availability of computing resources


**IP(internet protocol)**

An IP address (Internet Protocol address) is a unique numerical label assigned to each device connected to a network that uses the Internet Protocol for communication. IP addresses serve two main functions:

•Identification: They uniquely identify a device on a network, ensuring that data is sent to the correct destination. 

•Location Addressing: They provide the location of a device in the network, which helps in routing data packets across the internet.


**DBMS**

DBMS stands for Database Management System, which is a software system that provides an interface for interacting with databases. A DBMS manages and organizes data, supports data manipulation and retrieval, and ensures data integrity and security. It serves as a bridge between users and the database, handling data storage, queries, updates, and administration.


**KERNEL**

The kernel is the core component of an operating system that manages hardware resources, handles system calls, and facilitates communication between hardware and software. It controls processes, memory, device drivers, and file systems, providing essential services and ensuring efficient system operation.



**DEVOPS**

DevOps is a set of practices and cultural philosophies aimed at improving collaboration between development (Dev) and operations (Ops) teams. The goal of DevOps is to streamline the software development lifecycle (SDLC) and enhance the ability to deliver applications and services at high velocity. This involves integrating and automating the processes involved in software development, deployment, and operations.


**VIRTUAL MACHINE**

A virtual machine (VM) is a software-based emulation of a physical computer. It runs an operating system and applications just like a physical machine but is hosted on a physical computer known as a "host" machine. VMs allow multiple operating systems to run on a single physical machine simultaneously, providing flexibility, scalability, and isolation for various computing tasks.


**LOAD BALANCER**

A load balancer is a crucial component in network architecture and application deployment, designed to distribute incoming network or application traffic across multiple servers or resources. This helps ensure that no single server becomes overwhelmed, improving the overall performance, reliability, and availability of services.



**OPEN SOURCE**

Open Source refers to a type of software licensing and development model where the source code of a software program is made available to the public for use, modification, and distribution. This model promotes transparency, collaboration, and community-driven innovation.


**CLOSED SOURCE**

Closed Source software, also known as proprietary software, refers to software whose source code is not made available to the public. Unlike open source software, where the source code is freely accessible and can be modified or redistributed, closed source software is controlled by its owner, who restricts access to the code.


**DOCKER:**

Docker is a platform that allows developers to automate the deployment of applications inside lightweight, portable containers.

It packages an application along with all of its dependencies, libraries, and configuration files, so it can run consistently across different environments (e.g., development, testing, and production).

Docker provides tools to create, manage, and deploy containers, making it easier to build and share applications.


**CONTAINER:**

A container is a standardized unit that includes the application code, runtime, libraries, and dependencies, isolating the application from the underlying system.

Unlike virtual machines (VMs), containers share the host system's OS kernel, making them much more lightweight and efficient.

Containers ensure consistency across environments since they package everything the application needs. This makes them ideal for microservices and distributed applications.


**Nginx:**

Nginx (pronounced "Engine-X") is a high-performance web server and reverse proxy server. It is often used for serving static content, load balancing, caching, and as an API gateway.

As a reverse proxy, it can forward requests to other servers (like application servers) and is commonly used with Docker containers to handle web traffic.

Nginx is known for its ability to handle high levels of concurrent connections, making it a popular choice for web applications that need to scale.



