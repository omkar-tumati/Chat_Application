# Java Socket Chat Application  

🚀 A simple **multi-user chat application** built using **Java socket networking**, enabling real-time communication between clients through a central server.  

## Features  
✅ Multi-client support (group chat)  
✅ Private messaging support  
✅ Java Sockets (TCP/IP) for communication  
✅ Simple text-based interface (GUI optional)  
✅ Message logging for history  
✅ Error handling for connection issues  

## How It Works  
1. **Server:** Listens for client connections and relays messages.  
2. **Client:** Connects to the server, sends, and receives messages.  
3. **Message Transmission:** Server ensures messages reach the intended recipients.

## Setup Instructions  

### 1. Clone the Repository  
```bash
git clone https://github.com/your-username/chat-app.git
cd chat-app
```

### 2. Compile the Code
```bash
javac Server.java Client.java
```

### 3. Run the Server
```bash
java Server
```

###  4. Run the Client (Multiple times for different users)
```bash
java Client
```

