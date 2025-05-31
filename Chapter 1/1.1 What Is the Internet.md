### A Nuts and Bolt description

* The Internet
  * It is a computer network that interconnects billions of computing devices throughout the world.
  * All of these devices are called hosts or end systems.

* End systems
  * End systems are connected together by a network of communication links and packet switches.
  * When one end system has data to send to another end system, the sending end system segments the data and adds header bytes to each segment.
  * The resulting packages of information, known as packets, are then sent through the network to the destination end system, where they are reassembled into the original data.

* Packet switches
  * A packet switch takes a packet arriving on one of its incoming communication links and forwards that packet on one of its outgoing communication links.
  * The two most prominent types of packet switches are routers and link-layer switches.
    * Both types of switches forward packets toward their ultimate destinations.
    * Link-layer switches are typically used in access networks
    * Routers are typically used in the network core.
  * The sequence of communication links and packet switches traversed by a packet from the sending end system to the receiving end system is known as a route or path through the network.

* ISPs
  * End systems access the Internet through Internet Service Providers (ISPs),
  * Each ISP is in itself a network of packet switches and communication links.
  * As the Internet is all about connecting end systems to each other, so the ISPs that provide access to end systems must also be interconnected.
  * Each ISP network is managed independently, runs the IP protocol, and conforms to certain naming and address conventions.
 
* Internet protocols and standards
  * End systems, packet switches, and other pieces of the Internet run protocols that control the sending and receiving of information within the Internet.
  * The Transmission Control Protocol (TCP) and the Internet Protocol (IP) are two of the most important protocols in the Internet.
    * The TCP protocol specifies a reliable, ordered, and error-checked method for transmitting data packets between computers over a network.
    * The IP protocol specifies the format of the packets that are sent and received among routers and end systems.
    * The Internet’s principal protocols are collectively known as TCP/IP. 
  * Internet standards are developed by the Internet Engineering Task Force (IETF).
    * The IETF standards documents are called requests for comments (RFCs).
    * RFCs started out as general requests for comments to resolve network and protocol design problems that faced the precursor to the Internet.
    * They define protocols such as TCP, IP, HTTP (for the Web), and SMTP (for e-mail).
  * Other bodies also specify standards for network components, most notably for network links.
    * The IEEE 802 LAN Standards Committee for example, specifies the Ethernet and wireless WiFi standards.

***

### A Services Description
