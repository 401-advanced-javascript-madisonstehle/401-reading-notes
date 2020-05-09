# Class-17
## TCP Server

### Links
- [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0) (video)
- [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk) (video)
- [OSI Model](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
- [What is TCP](https://searchnetworking.techtarget.com/definition/TCP)
- [Build a TCP Server](https://techbrij.com/node-js-tcp-server-client-promisify) (Code)
- [Net Module Documentation](https://nodejs.org/api/net.html)


### Discussion Questions
1. **What do the layers in the OSI and TCP/IP models represent?** They represent the procedure that protocols use to transfer data
2. **What is the benefit of transforming data into packets?** When the data is in small packets, it's easier to send quickly and efficiently.
3. **UDP is often referrered to as a connectionless protocol. Why is this?** UDP packets are small and lightweight, and sends simple information. It doesn't have a strong secure connection.
4. **Can a socket server application have multiple socket connections? Can a socket connection application be connected to multiple socket servers? Can an application be both a socket server and a socket connection?** There can be multiple socket connections listening on a single socket server. I think an app can probably be both a socket server and a connection, because it might have to get data from somewhere else to get what it needs to deliver to the original client.


#### [Back to Home](README.md)