---
layout: default
---

# Network

### Multi-Floor Network Design

![Multi-Floor Network Design](images/network-coursework-1.png)

### Overview

Designed and implemented a network in Cisco Packet Tracer using VLANs, router-on-a-stick and OSPF. The network provided departmental segmentation, inter-floor communication and basic network services.

### Objectives

- Design a reliable and scalable network for multiple floors
- Implement VLANs for departmental segmentation
- Configure inter-VLAN routing and OSPF
- Configure and test network services
- Apply basic security controls

### Technologies Used

- Cisco Packet Tracer
- VLANs
- Router-on-a-stick
- OSPF
- IPv4 subnetting
- HTTP and email servers
- Wireless networking

### Methodology

The network topology and IP addressing scheme were designed before configuring the routers and switches. VLANs were used to separate departments, while router-on-a-stick enabled communication between VLANs. OSPF was configured to provide routing between floors, followed by the implementation and testing of network services and device security.

### Key Findings

- VLANs successfully separated departmental traffic
- Inter-VLAN and inter-floor communication was successful
- OSPF successfully provided dynamic routing
- HTTP, email and wireless services were successfully tested
- Basic network-device security controls were implemented

### Skills Demonstrated

- Network design
- VLAN segmentation
- Routing and switching
- OSPF
- IP addressing and subnetting
- Cisco Packet Tracer fundamentals
- Network troubleshooting
- Device security


### Secure Network Implementation & Traffic Analysis

![Secure Network Implementation](images/network-coursework-2.png)

### Overview

Designed and implemented a secure network in Cisco Packet Tracer using VLSM, VLANs and ACLs. DHCP, Internet, web and email services were configured, with network traffic analysed using Packet Tracer's simulation tools.

### Objectives

- Efficiently allocate IP addresses using VLSM
- Implement VLAN-based network segmentation
- Control inter-VLAN access using ACLs
- Configure DHCP and network services
- Analyse and verify network traffic

### Technologies Used

- Cisco Packet Tracer simulation tools
- VLANs
- VLSM
- Router-on-a-stick
- Access Control Lists (ACLs)
- DHCP
- TCP/IP
- ICMP
- HTTP and SMTP

### Methodology

VLSM was used to allocate appropriately sized subnets based on number of hosts. VLANs were configured to separate departments, followed by router-on-a-stick for inter-VLAN routing. ACLs were implemented to restrict unauthorised communication between VLANs. DHCP and network services were configured before using Packet Tracer simulation mode to analyse and verify network traffic.

### Key Findings

- VLSM successfully created subnets with no overlaps
- VLANs successfully segmented departmental networks
- ACLs successfully restricted unauthorised VLAN communication
- DHCP correctly assigned IP addresses
- Internet, web and email connectivity worked successfully
- Packet analysis demonstrated Layer 2 and Layer 3 communication

### Skills Demonstrated

- Network security
- ACL configuration
- Network segmentation
- VLSM and subnetting
- DHCP configuration
- Packet and traffic analysis
- TCP/IP networking
- Access control
- Network troubleshooting
- Security verification

---

# Programming

### Secure Password Manager

![Secure Password Manager](images/programming-coursework-1.png)

### Overview

Developed a secure password manager in Python using a command-line interface for creating accounts and retrieving stored passwords. Passwords were encrypted using Fernet and stored in an SQLite database, with the encryption key saved for reuse between sessions.

### Objectives

- Develop a secure password management system
- Encrypt passwords before storing them
- Store user information using SQLite
- Validate user input and handle errors
- Maintain encryption key persistence between sessions

### Technologies Used

- Python
- Fernet encryption
- SQLite
- Object-oriented programming
- OS library
- Exception handling

### Methodology

The program used separate User and Manager classes to manage user information and password encryption. Usernames and passwords were validated before being stored, while passwords were encrypted using a Fernet key. The encrypted password was then stored in the SQLite database. The key was loaded from a file if it already existed or generated when required. Testing was carried out to verify encryption, database storage, password retrieval and key persistence.

### Key Findings

- Passwords were successfully encrypted before being stored
- Encrypted passwords could be decrypted using the stored Fernet key
- User information was successfully stored and retrieved from SQLite
- Input validation prevented empty usernames and passwords
- Key persistence allowed passwords to remain accessible after restarting the program
- All documented tests passed

### Skills Demonstrated

- Python programming
- Object-oriented programming
- Symmetric encryption
- SQLite database management
- Input validation
- Error handling
- Debugging
- Security-focused development


### Security Log Ingestion & Anomaly Detection

![Security Log Ingestion & Anomaly Detection](images/programming-coursework-2.png)

### Overview

Developed a Python program that ingests text and JSON log files, extracts relevant information and normalises the data before identifying potential security anomalies. The system detects multiple failed login attempts, blacklisted IP addresses and out-of-hours access before generating a daily summary file.

### Objectives

- Ingest text and JSON log files
- Extract and parse relevant log information
- Normalise log data into a consistent format
- Detect suspicious or anomalous activity
- Generate summary reports of detected anomalies

### Technologies Used

- Python
- JSON
- Datetime
- OS library
- Exception handling
- File handling

### Methodology

The program first detects the type of log before ingesting the file. Log entries are then parsed to extract timestamps, IP addresses, user identifiers and event types. The data is normalised by filling missing information with unknown. Detection rules are then applied to identify multiple failed login attempts, blacklisted IP access, out-of-hours access and relevant JSON log events. Detected anomalies are formatted and written to a daily summary file.

### Key Findings

- Text and JSON logs were successfully ingested
- Relevant log information was successfully extracted and parsed
- Logs were successfully normalised into a consistent structure
- Anomaly detection successfully identified suspicious log activity
- Duplicate entries were controlled using sets
- Daily summary files were successfully generated
- Debugging resolved timestamp and JSON anomaly detection issues

### Skills Demonstrated

- Python programming
- Log analysis
- Security monitoring
- Anomaly detection
- Data parsing and normalisation
- File handling
- Debugging and testing
- Security-focused problem solving

---

# Computer Architecture and Operating Systems

### General-Purpose Operating Systems & Process Management

![General-Purpose Operating Systems](images/caos-coursework-1.png)

### Overview

Analysed the structure and operation of general-purpose and embedded operating systems, focusing on process management, memory management, file management and user interaction. The coursework also examined the security differences between general-purpose and embedded systems using a real-world vehicle security incident.

### Objectives

- Analyse the architecture of general-purpose operating systems
- Compare general-purpose and embedded operating systems
- Examine the lifecycle of processes
- Understand memory and file management
- Analyse operating system security considerations

### Technologies Used

- Linux
- Operating system concepts
- System calls
- Process management
- Virtual memory
- File systems
- Terminal and shell

### Methodology

The coursework examined how operating systems manage processes from creation to termination. The lifecycle of a process was analysed using system calls such as fork(), exec(), read(), write() and exit(). Memory allocation and virtual memory were also examined, alongside file permissions and terminal I/O. General-purpose and embedded operating systems were then compared in terms of architecture, functionality and security.

### Key Findings

- General-purpose operating systems support multiple processes and applications
- User and kernel spaces provide different levels of access to system resources
- System calls provide controlled access to operating system resources
- Virtual memory provides isolation between processes
- Embedded systems have reduced functionality but can still contain exploitable vulnerabilities
- Poor configuration and exposed interfaces can increase security risks

### Skills Demonstrated

- Operating system analysis
- Process management
- Memory management
- File management
- Linux fundamentals
- System call analysis
- Security analysis
- Operating system architecture


### Binary Analysis and Reverse Engineering

![Binary Analysis and Reverse Engineering](images/caos-coursework-2.png)

### Overview

Analysed a compiled binary to understand its authentication logic and identify weaknesses within the program. Debugging and disassembly techniques were used to examine functions, input handling, registers and control flow before identifying how the authentication mechanism could be bypassed.

### Objectives

- Analyse the structure of a compiled binary
- Identify security protections within an executable
- Examine program control flow using disassembly
- Analyse registers and function behaviour
- Identify weaknesses in client-side authentication

### Technologies Used

- Linux
- GDB
- Pwndbg
- Assembly language
- Binary analysis tools
- Disassembly
- Debugging

### Methodology

The binary was first examined to identify its type and architecture before being executed to understand its normal behaviour. Protection mechanisms were analysed using checksec, followed by function identification and disassembly. Breakpoints were placed at key functions including input handling and password comparison. Register analysis was then used to examine how user input and the stored passphrase were processed during authentication.

### Key Findings

- The binary contained authentication logic within the executable
- User input was processed using scanf
- The passphrase was compared using strcmp
- Register analysis exposed the values used during authentication
- The stored password could be identified during debugging
- Client-side authentication logic can be vulnerable to reverse engineering

### Skills Demonstrated

- Reverse engineering
- Binary analysis
- GDB debugging
- Assembly analysis
- Register analysis
- Disassembly
- Vulnerability identification
- Security analysis


### Stack-Based Buffer Overflow Analysis

![Stack-Based Buffer Overflow Analysis](images/caos-coursework-3.png)

### Overview

Analysed and exploited a stack-based buffer overflow vulnerability within a binary. The investigation examined missing protection mechanisms, identified an unsafe strcpy function and determined the offset required to overwrite the saved instruction pointer.

### Objectives

- Identify buffer overflow vulnerabilities
- Analyse binary protection mechanisms
- Examine stack memory and program execution
- Determine the buffer overflow offset
- Develop mitigations against buffer overflow attacks

### Technologies Used

- Linux
- GDB
- Pwndbg
- checksec
- Cyclic patterns
- Assembly and disassembly
- Stack analysis

### Methodology

The binary was analysed using checksec to identify enabled protection mechanisms. Disassembly was then used to identify the vulnerable function and the use of strcpy without bounds checking. A cyclic pattern was generated and used to determine the offset to the saved instruction pointer. A controlled input was then used to demonstrate that the return address could be overwritten, confirming successful stack corruption.

### Key Findings

- Stack canaries, NX and PIE protections were absent
- The vulnerable function used strcpy without bounds checking
- The buffer overflow offset was identified as 72 bytes
- The saved instruction pointer could be overwritten
- Controlled input caused the program to crash through stack corruption
- Safer input functions and system-level protections can reduce the risk

### Skills Demonstrated

- Buffer overflow analysis
- Vulnerability analysis
- Binary exploitation
- Stack analysis
- GDB and Pwndbg
- Memory corruption analysis
- Security mitigation
- Secure programming


