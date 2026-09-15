---
layout: default
---

# Example Project Title

![Example Project Image](images/example-project.png)

### Overview

example overview

### Objectives

- Example objective one
- Example objective two
- Example objective three

### Technologies Used

- example technology
- example technology
- example technology
- example technology

### Methodology

example methodology

### Key Findings

- Example finding
- Example finding
- Example finding

### Skills Demonstrated

- example skill
- example skill
- example skill
- example skill

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

