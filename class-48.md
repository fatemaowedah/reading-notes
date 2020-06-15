### Socket.io
#### Web Sockets
computer communications protocol, providing full-duplex communication channels over a single TCP connection, the location of  webSoket in the 7th layer of OSI and it depend on TCP in 4th layer it enacle the interaction between web browser and web server, it hep us in a two-way ongoing conversation can take place between the client and the server, most browsers support the protocol, provides full-duplex communication,enables messages on top of TCP, when you want toestablish a WebSocket connection, the client sends a WebSocket handshake request, to server and this server returns a WebSocket handshake response, it begain with HTTP req/res to help the server to handle HTTP connections, when the connection is stablish be bidirectional binary protocol which does not conform to the HTTP protocol ande the clent and server can send WebSocket data or text frames back and forth in full-duplex mode, when you use webSockets it is butter to use token or protection when you have sensitive data, if the user use HTTP connect it will set up a tunnel.
#### Why do we need WebSocket?
It provides the full duplex communication established between the Client and the Web Server,It also lives up to the standards and provides the accuracy and efficiency stream events to and from with negligible latency,,overhead and reduce complexity.
It makes real-time communication effortless and efficient.
#### Socket.io
JavaScript library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for node.js. Both components have an identical API.
#### Why Socket.IO?
the most powerful JavaScript frameworks on GitHub, and most depended-upon NPM (Node Package Manager) module, it is the solution around which most real-time systems are architected, providing a bi-directional communication channel between a client and a server, server can push messages to clients, push it to the concerned connected clients,I handle all the degradation of your technical alternatives to get full duplex communication in real time,It also handles the various support level and the inconsistencies from the browser,It also gives the additional feature room support for basic publish infrastructure and thinks like automatic reconnect.
Currently, AFAIK is the most used one and easier to help with vanilla web sockets.
#### Difference Between WebSocket and Socket.io
- WebSocket: communication Protocol which provides bidirectional communication between the Client and the Server over a TCP connection, WebSocket remains open all the time so they allow the real-time data transfer,
- Socket.IO: nables real-time and full duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface.
#### Connections 
With Socket.io, you connect to a server over HTTP. The session is “kept alive” through it’s internal use of the WebSocket Protocol, with session information being preserved.
#### Messaging
Socket.io uses the same methodology/terminology sent with emit() and received with on(), when we use event driven node app, he entire app is in memory, and (through a common event pool), all parts of your application can emit and hear events, the purpose of it have events shared between disconnected participants, Through server.
#### Socket.io Documentation
it is consists of a Node.js server,Javascript client library for the browser, Auto-reconnection support, Disconnection detection, Binary support, Multiplexing support, Room support, you can isttalling it by `npm install --save socket.io` and to install javascript client `npm install --save socket.io-client`.
#### Socket.io Server API
you must reqauire 'socket.io' when you do new server use: new Server(httpServer[, options]), or use new Server(port[, options]), or new Server(options),The Client class represents an incoming transport (engine.io) connection. A Client can be associated with many multiplexed Sockets that belong to different Namespace,client.conn or client.request.