# Basic TCP Client

Simple TCP client that uses Winsock to connect to an external server (Cloudflare at 1.1.1.1 on port 443). It doesn't do much it just tries to connect and prints whether it succeeded or failed.
It is kind of messy, does not have that much value but was a learning experience to dive into other libraries than the standard ones. 
Alongside this project I learned about networking in school and read a lot about how TCP and other networking concepts behave. 

This will work as a skeleton for further network related programming projects for myself.

### What I learned:
- Initializing Winsock
- Creating and connecting TCP sockets
- Handling error codes
- Using `inet_addr` and `htons`
- Became interested about networking

### To improve:
- Handle timeouts and retries
- Make a proper HTTP or file transfer client
- Overall code quality
