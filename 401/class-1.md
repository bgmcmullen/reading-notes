# Class 13 Reading Notes:


## Socket.io Chat Example

### Explain to a non-technical recruiter what the Chat Example (above) does.
This chat example allows the client and server to exchange real-time messages using Socket.io.

### What proof of life are we getting on the backend from the above app?
In order to indicate proof of life, the server indicates “listening on (port number)” and should receive user connected and user disconnected messages.

### Socket.IO gives us the io.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
socket.broadcast.emit

## Rooms
### What is a room and how might a room be useful?
A room is simply a “channel” that sockets can join and leave.

### How do you join a room?
socket.join

### How do you leave a room?
socket.leave

## Namespaces
### What is a Namespace and what does it allow you to do?
A namespace is a communication channel that lets you split communication while still using a single connection.

### Each namespace potentially has its own what? (hint: 3 things)

Event handlers\
Rooms\
Middleware\
### Discuss a possible use case for separate namespaces.
Perhaps you could have a general chat and a project management chat limited only to project managers.

