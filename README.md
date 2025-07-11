# Computer-Networking

Notes from the study of Computer Networking - A top down approach.

# INDEX

## Chapter 1: Computer Networks and the Internet 
* <b>1.1 What Is the Internet</b>
	* A Nuts and Bolt description
 	* A Services Description
 	* What is a Protocol?
* <b>1.2 The Network Edge</b>
	* Access Networks
 		* ISP to modem/router: DSL, Cable, FTTH, and 5G Fixed Wireless Access (FWA)
   		* Router to end system (LAN): Ethernet and WiFi
     	* Wide-Area Wireless Access: 3G and LTE 4G and 5G
 	* Physical Media
    	* Twisted Pair Copper Wire
    	* Coaxial Cable
     	* Fiber Optics
      	* Terrestrial Radio Channels (Bluetooth, WiFi, Cellular)
      	* Satellite Radio Channels 
* <b>1.3 The Network Core</b>
	* Packet Switching
 		* Store-and-Forward Packet Switching
   		* Queuing Delays and Packet Loss
     	* Forwarding Tables and Routing Protocols 
 	* Circuit Switching
  		* Multiplexing in Circuit Switched Networks
    	* Packet Switching vs Circuit Switching
  	* A Network of Networks
* <b>1.4 Delay, Loss, and Throughput in Packet-switched networks</b>
	* Overview of Delay in Packet-Switched Networks
 		* Types of delays
	 		* Processing delay
	   		* Queuing delay
			* Transmission delay
			* Propogation delay
		* Comparing Transmission and Propagation Delay
  	* Queuing Delay and Packet Loss
  		* Traffic Intensity
  	 	* Packet Loss
  	* End-to-End Delay
  		* Traceroute
  	 	* End System, Application, and Other Delays	
  	* Throughput in Computer Networks
  		* Bottlenecks
* <b>1.5 Protocol Layers and Their Service Models</b>
	* Layered Architecture
 		* Protocol Layering
   		* Application Layer (packet: message)
     	* Transport Layer (packet: segment)
      	* Network Layer (packet: datagram)
      	* Link Layer (packet: frame)
      	* Physical Layer
	* Encapsulation
* <b>1.6 Networks Under Attack</b>
	* Types of Attacks
 		* Malware in the End-system via the Internet
  		* Denial of Service - Attack on Servers and Network Infrastructure
  		* Packet Sniffing
  		* Masquerade As Someone Else - IP Spoofing
* <b>1.7 History of Computer Networking and the Internet</b>
	* The Development of Packet Switching: 1961–1972
 	* Proprietary Networks and Internetworking: 1972–1980
  	* A Proliferation of Networks: 1980–1990
  	* The Internet Explosion: The 1990s
  	* The New Millennium

## Chapter 2: Application Layer
* <b>2.1 Principles of Network Applications</b>
	* Network Application Architectures
 		* Client-Server Architecture
   		* Peer-to-Peer Architecture
 	* Processes Communicating
  		* Processes
    	* Client and Server Processes
     	* Sockets - The Interface Between the Process and the Computer Network
      	* Addressing Processes using Ports
	* Transport Services Available to Applications
 		* Reliable data transfer
   		* Throughput
     	* Timing
      	* Security
	* Transport Services Provided by the Internet
 		* TCP Services (Connection-oriented, Reliable data transfer, Congestion control, TLS enhancement for security)
   		* UDP Services (Connectionless, Unreliable data transfer, No congestion control)
     	* Services Not Provided by Internet Transport Protocols (Throughput, Timing)
  	* Application-Layer Protocols
* <b>2.2 The Web and HTTP</b>
	* Overview of HTTP
 	* Non-Persistent and Persistent Connections
  		* HTTP with Non-Persistent Connections
		* HTTP with Persistent Connections
  	* HTTP Message Format
  		* HTTP Request Message
		* HTTP Response Message
  	* User-Server Interaction: Cookies
  	* Web Caching
  		* Advantages of Web Caching
  	 	* The Conditional Get
  	* HTTP/2
  		* Head-of-Line Blocking
  	 	* HTTP/2 Framing
  	  	* Response Message Prioritization and Server Pushing
  	  	* HTTP/3
* <b>2.3 Electronic Mail in the Internet</b>	
	* SMTP
 		* Transcript between SMTP mail servers
   	* Mail Message Formats
   	* Mail Access Protocols
* <b>2.4 DNS—The Internet’s Directory Service</b>
	* Services Provided by DNS
 		* Translating Hostnames to IP address
   		* Host aliasing
     	* Mail server aliasing
      	* Load distribution
	* Overview of How DNS Works
 		* Drawbacks of a centralised DNS design
   		* A Distributed, Hierarchical Database
     	* Root DNS servers
      	* Top-level domain (TLD) servers
      	* Authoritative DNS servers
      	* Local DNS server (Recursive DNS resolvers)
      	* DNS Caching
	* DNS Records and Messages
 		* DNS Resource Records
   		* DNS Messages
     	* Inserting Records into the DNS Database
  	* DNS Security
  		* Attacks on DNS (DDoS, Man-in-the-middle, DNS Poisoning)
  	 	* DNSSEC
* <b>2.5 Peer-to-Peer File Distribution</b>
	* Overview of P2P architecture
 	* Scalability of P2P Architectures
  		* Distribution time for the client-server architecture
    	* Distribution time for the P2P architecture
     	* Comparing D<sub>client-server</sub> and D<sub>P2P</sub>
	* BitTorrent
 		* Overview of how BitTorrent works
* <b>2.6 Video Streaming and Content Distribution Networks </b>
