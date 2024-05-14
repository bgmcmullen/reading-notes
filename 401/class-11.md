# Class 11 Reading Notes:


## Web Sockets

### What is a Web Socket?
A web socket is a communication protocol that facilitates two-way communication between machines.
### Describe the Web Socket request/response handshake and what happens once the connection is established.
The client sends an HTTP GET request. If successful, the server will return a status code 101, switching protocols.
### Web Sockets provide a standardized way for the server to send content to a client without first receiving _____ from that client.
a request

## Socket.io Tutorial

### What does the event handler io.on() do?
io.on() is used as the main entry point for event listening on the server.
Describe some possible proof of life or proof that the code works as expected.
A console.log('A user connected') in the io.on() function can be used to prove the code is working.
### What does socket.emit() do?
Socket.emit sends an event and can be used by the client or server.


## Socket.io vs Web Sockets

### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
WebSocket is the communication protocol while Socket.io is the communication library.
### When would you use Socket.IO?
Socket.IO provides real-time multidirectional communication between the client and server. There are numerous uses for this like multiplayer games, collaboration tools, or chat applications.
### When would you use WebSockets?
WebSocket is used to maintain communication over a single TCP connection. They can be used for things like real-time data streams and high-performance applications.

## OSI Model Explained

### What are a couple of key takeaways from this video?
The Application Layer facilitates communication between applications.\
The Presentation Layer receives information from the application layer and can compress and encrypt data.\
The Session Layer establishes, manages, and terminates connections between applications.\
The Transport Layer provides communication between sender and receiver.\
The Network Layer allows communication between networks.\
The Data Link Layer runs node-to-node communication.\
The Physical Layer manages physical connections between devices.\

### TCP Handshakes Explained

## Translate the gist of this video to a non-technical friend.
TCP makes sure your message gets to your friend’s computer without any missing parts or jumbled information.

