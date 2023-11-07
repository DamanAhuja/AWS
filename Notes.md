# Computer System
## CDN (Computer Delivery Netwok):
CDN is a system of distributed servers that deliver web pages and other web cntents to a user based on the geographical location.
- ***SnowBall***: 
    It is a way of transferring the data physically.
## Computation:
- ***Host***:
    It provides the functionality to start.
- ***VM***:
    It is a digital version of a physical computer.
    - **Hypervisor**: An Application used to create VM.
         - Type 1: It is downloaded directly on the Bare Metal.
              - XEN
              - KVM
         - Type 2: It is downloaded on an OS.
              - Oracle
              - VMware
- ***Containers***:
    Packages Of Software
    - ***Docker***: Used to handle containers
    - ***LXC***
    - ***RKT***
    - ***PODMAN***
## Netwoking
- ***OVS***:
    - ***Open VSwitch***
- ***Load Balancer***:
    - ***Layer 4***: It makes routing decisions at the transport layer.
    - ***Layer 7****: It is best suited for load balancing of HTTP and HTTPs traffic.   
- ***OSI Layer***:
    - Physical
    - Data link
    - Network
    - Transport
    - Session
    - Presentation
    - Application
- **IP Addresss**- Internet Protcol (IPv4,IPv6) 
  - Public IP - B/W Internet and Device, assigned by internet service provider to the device 
  - Private IP - in a private network [starts with 10., 172.16, 192.168] 
  - Local IP - [starts with 127.00.0]
- **Port No.** - a way to identify a specific process to which an internet or other network message is to be forwarded when it arrives at a server.[for http - 80 
  - SSH(Secure Shell) - 22 
  - SMTP - 25   
  - Telnet - 23 
  - https - 443 
  - DNS - 53
- **DNS** - turns domain names into IP addresses, which allow browsers to get to websites and other internet resources.  
## Storage: 
- ***Primary***
  - **RAM**
  - **ROM**
- ***Secondary***
  - **Optical Disc**
  - **HDD**
  - **SDD** 
## Architecture:
- ***Von Neumann***
- ***Hagward***
- **ISA** - Instruction Set Architecture - An Instruction Set Architecture (ISA) is part of the abstract model of a computer that defines how the CPU is controlled by the software. The ISA acts as an interface between the hardware and the software, specifying both what the processor is capable of doing as well as how it gets done.
- **CISC** - Complex Instruction Set Computer- Closed source - intel, AMD 
- **RISC** - Reduced Instruction Set Computer- Closed source - ARM
- **System Design**
  - **CAP** Theorem (**C**onsistency, **A**vailability, **P**artition tolerance) - All 3 of them can not be achived at the same time, 2 have to be chosen based on the requirements.
  - **Redundancy and Replication**:
    - Ensuring that data has its backup in case of emergency.
    - Increases Reliability of system
    - ***Service Redundancy***: Shared nothing acrchitecture, Every node is independant.  
## Database:
- **SQL**: Relational Database
  - Structured
  - Predefined schemes
  - Data is in Rows and Columns
- **NoSQL**: Non-Relational Database
  - Unstructured
  - Distributed
  - Dynamic 
- **ACID Compliance**: (**A**tomicity, **C**onsistency, **I**solation, **D**urability) Reduces anomalies
## Caching
- **Application Server Cache**: Placing a cache directly on a request layer node (Local Storage of Response).
- **Bottle Neck**- If a same requaest is sent to different nodes by load balancer
- **Distributed cache**: Divided using consistent *Hashing* function.
  - **Hashing**: The process of transforming any given key or a string of characters into another value.  
- **Gloabal Cache**
