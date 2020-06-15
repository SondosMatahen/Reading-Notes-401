## WebSockets: 
- provide a persistent connection between a client and server that both parties can use to start sending data at any time.
- The client establishes a WebSocket connection through a process known as the WebSocket handshake. This process starts with the client sending a regular HTTP request to the server.

## Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.
- It consists of:
>- a Node.js server.
>- a Javascript client library for the browser.

## WebSocket vs Socket.io:
>- WebSocket helps in real-time communication between the Client and the web server.
>- This protocol helps in transforming to cross-platform in a real time world between the server and the client.
>- This also enables the business around the world for real-time web application to enhance and to increase the feasibility.
>- The major advantage it stands over an HTTP connection that it provides full duplex communication.

- Key features of Socket.IO
>- It helps in broadcasting to multiple sockets at a time and handles the connection transparently.
>- It works on all platform, server or device ensuring the equality, reliability, and speed.
>- It automatically upgrades the requirement to WebSocket if needed.

## What Socket.IO is not:
- Socket.IO is NOT a WebSocket implementation.
- Although Socket.IO indeed uses WebSocket as a transport when possible.
- it adds some metadata to each packet: 
>- the packet type 
>- the namespace
>- the packet id when a message acknowledgement is needed. 
- There are some Client based reserved events like Connect, connect- error, connect-timeout and Reconnect etc.

