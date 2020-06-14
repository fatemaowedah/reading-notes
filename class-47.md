### TCP Servers
#### Event Queues
EventEmitter is all objects that emit events in nodejs, it is way to handle controlling asynchronous event,disconnected services can communicate with one another using a central “Hub” server (or Queue), it is recive messages and sent ,essages to connected subsribers.
#### OSI Model
Open Systems Interconnection Reference Model (OSI model) enables diverse communication systems to communicate using standard protocolsو it is seven layer model layer have specific job and communicates with the layers above and below itself, this is the seven layer: physical layer, datalink layer, network layer, transoprt layer, session layer, presentation layer, application layer.
#### Why does the OSI model matter?
useful for troubleshooting network problems, one person who can’t get their laptop on the Internet, or a web site being down for thousands of users, the OSI model can help to break down the problem and isolate the source of the trouble, avoid unnecesserary work by narrowed down to one specific layer of the model.
#### What are the seven layers of the OSI model?
The Application Layer: only layer that directly interacts with data from the user, rely on the application layer to initiate communications, The Presentation Layer:esponsible for preparing data so that it can be used by the application layer,responsible for translation, encryption, and compression of data, The Session Layer:responsible for opening and closing communication between the two devices,The Transport Layer: responsible for end-to-end communication between the two devices, The Network Layer: responsible for facilitating data transfer between two different networks. If the two devices communicating are on the same network, The Data Link Layer: similar to the network layer, except the data link layer facilitates data transfer between two devices on the SAME network,The Physical Layer.
#### How data flows through the OSI model?
the data travel down the seven layers of the OSI model on the sending device and then travel up the seven layers on the receiving end.
#### Internet Protocol Suite
conceptual model for the protocols used by the internet,the IP and TCP were the original protocols in the suite, it have four layers: Link, Internet, Transport, and Application.
#### TCP
Transmission Control Protocol, establish and maintain a network conversation through which application programs can exchange data, defines how computers send packets of data to each other, TCP cover the fourth layer and trasport layer and the session layer, it send HTML file to a client.
#### What TCP is used for and why it is important?
we use it to organized the data it make a secure transmission between the server and client, establishes the rules and standard procedures for the way information is communicated over the internet, it is flexible and highly scalable.
#### TCP HEADER
it contain Source port, Destination port,Sequence number,Acknowledgement number,Data Offset, NS flag, and 3 undefined bits,CWR, ECE, URG, ACK, PSH, RST, SYN, and FYN flags,Window size,Checksum,Urgent pointer,Options.
#### Node.js v14.4.0 Documentation
##### net
provides an asynchronous network API for creating stream-based TCP or IPC, this IPC maybe be to servers `net.createServer()` or for client `net.createConnection()`, net support IPC , we can add class `net.server`, 
##### net.isIP(input)
input is string return integer, Returns 0 for invalid strings, returns 4 for IP version 4 and returns 6 for IP version 6.
##### net.isIPv4(input)
the input is string and return boolean if the version 4IP otherwise return false.
##### net.isIPv6(input) 
the input is string and return boolean if the version 6IP otherwise return false.

