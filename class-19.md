# Class-19
## Message Queues

### Links
- [Rooms and Namespaces](https://socket.io/docs/rooms-and-namespaces/)
- [Socket.io Emit Cheatsheet](https://socket.io/docs/emit-cheatsheet/)
- [Messaging Queues | System Design Basics](https://www.youtube.com/watch?v=sfQwMu0SCT8)


### Discussion Questions
1. **What is the main benefit of a message queue server?** It centralizes the logic of routing and makes sure that all connected clients have the most up to date data they need.
2. **Why might we want to initiate messages from an HTTP request?** It just needs to handle the queue name, event name, and payload.
3. **Is the Message Queue Server a socket.io client, a socket.io server, or an api server?** I think it's a socket.io server.


#### [Back to Home](README.md)