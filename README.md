# CompTIASecurity+_prep

<img src="https://github.com/rpointjour/compTIA_security-_prep/assets/54840122/777d3347-f21a-4719-877c-b60341e657fb" alt="Security" style="width:50%;height:50%;" />

#
# Topics

- Intro to Network Devices (part 1)  

- Intro to Network Devices (part 2)

- Networking Services and Applications (part 1)

- Networking Services and Applications (part 2)

- DHCP in the Network

- Introduction to the DNS Service

- Introducing Network Address Translation

- WAN Technologies (part 1)

- WAN Technologies (part 2)

- WAN Technologies (part 3)

- WAN Technologies (part 4)

- Network Cabling (part 1)

- Network Cabling (part 2)

- Network Cabling (part 3)

- Network Topologies

- Network Infrastructure Implementations

- Introduction to IPv4 (part 1)

- Introduction to IPv4 (part 2)

- Introduction to IPv6

- Special IP Networking Concepts

- Introduction to Routing Concepts (part 1)

- Introduction to Routing Concepts (part 2)

- Introduction to Routing Protocols

- Basic Elements of Unified Communications

- Virtualization Technologies

- Storage Area Networks

- Basic Cloud Concepts

- Implementing a Basic Network

- Analyzing Monitoring Reports

- Network Monitoring (part 1)

- Network Monitoring (part 2)

- Supporting Configuration Management (part 1)

- Supporting Configuration Management (part 2)

- The Importance of Network Segmentation

- Applying Patches and Updates

- Configuring Switches (part 1)

- Configuring Switches (part 2)

- Wireless LAN Infrastructure (part 1)

- Wireless LAN Infrastructure (part 2)

- Risk and Security Related Concepts

- Common Network Vulnerabilities

- Common Network Threats (part 1)

- Common Network Threats (part 2)

- Network Hardening Techniques (part 1)

- Network Hardening Techniques (part 2)

- Network Hardening Techniques (part 3)

- Physical Network Security Control

- Firewall Basics

- Network Access Control

- Basic Forensic Concepts

- Network Troubleshooting Methodology

- Troubleshooting Connectivity with Utilities

- Troubleshooting Connectivity with Hardware

- Troubleshooting Wireless Networks (part 1)

- Troubleshooting Wireless Networks (part 2)

- Troubleshooting Copper Wire Networks (part 1)

- Troubleshooting Copper Wire Networks (part 2)

- Troubleshooting Fiber Cable Networks

- Network Troubleshooting Common Network Issues

- Common Network Security Issues

- Common WAN Components and Issues

- The OSI Networking Reference Model

- The Transport Layer Plus ICMP

- Basic Network Concepts (part 1)

- Basic Network Concepts (part 2)

- Basic Network Concepts (part 3)

- Introduction to Wireless Network Standards

- Introduction to Wired Network Standards

- Security Policies and other Documents

- Introduction to Safety Practices (part 1)

- Introduction to Safety Practices (part 2)

- Rack and Power Management

- Cable Management

- Basics of Change Management

- Common Networking Protocols (part 1)

- Common Networking Protocols (part 2)
#
# Intro to Network Devices (part 1)
- Layer 1 devices
	- Physical Layer
- Layer 2 devices
	- Data Link
- Layer 3 devices
	- Network

---
**Layer 1 Devices:**

- Analog Modem
	- 
	- Were developed to take the digital signal coming from a digital node and convert it to an analog signal (Wire)
	- Developed to also create connections between network segments via PSTN(Public Switched Telephone Network) using POTS(Plain Old Telephone System)
	- They provide for a SINGLE connection to a network
	- "Modulator/Demodulator"
	- Only concerned about the WIRE
	- Resides on Layer 1 (Physical Layer) of OSI Model
		- "Doesn't care where the signal comes from. Just does its job!"
- The Hub
	- 
	- Functions as a concentrator/repeater
		- "Doesn't care where signal comes from or where it's going!"
	- Takes electrical signal that arrives on a port and replicates that signal out all of the other ports
	- Few ports/many ports
	- "Not very common in modern networking"
---
**Layer 2 Devices:**

- Switch
	- 
	- Utilizes ASIC(Application-specific Integrated Circuit) chip!
	- The ASIC chip has specific programming that allows the switch to learn when a device is on the network and which parts it is connected to via device's Layer 2 MAC address
	- Few/many ports
	- Can be very simple/highly complex and programmable
	- Will only communicate with local network devices!
- Wireless Access Point (WAP)
	- 
	- Specific type of network bridge that connects ("bridges")
		-  Wireless network segments with wired network segments
	- Most common WAP Bridges:
		- 802.11 Wireless Network Segments with 802.3 Ethernet Network Segments
	- Only communicates with local network devices!
---
**Layer 3 Devices:**

- Multilayer Switch (MLS)
	- 
	- Provides normal Layer 2 network switching services, but also provides Layer 3 or higher OSI model services
	- Most common MLS is a Layer 3 switch
		- Utilizes ASIC chip for switching and is programmed to handle routing functions
		- Allows device to communicate and pass data to non-local network devices
	- Highly programmable and complex network device
	- Few/many ports
	- "Too expensive for small offices & home office networks"
		- Mostly used by Enterprise Local Area Networks
- Router
	- 
	- MOST common network device for connecting different networks together utilizing OSI model's L3 logical network information
	- Uses software programming for decision making as compared to the switch's ASIC chip
	- Uses this programming to keep track of different networks and what it considers to be the best possible route to reach those networks
	- Can communicate with BOTH local and non-local network devices!
	- In most cases it has fewer ports than a switch
