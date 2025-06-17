# Java Socket Console Chat Server

## Introduction

This project is a console-based chat server implemented in Java using socket programming. Multiple clients can connect to a single server and exchange messages in real time. Each client connection is handled in a separate thread, ensuring stable operation in a multithreaded environment.

## Features

- **Chat Server**: Manages client connections and message broadcasting
- **Multithreading**: Each client is handled in an independent thread
- **Real-time Messaging**: Broadcasts messages to all connected clients
- **Unique Client ID Management**

## Project Structure

```
src/
  main/
    java/
      com/
        hsk/
          socket/
            chat/
              server/
                Main.java
                ServerInfo.java
                ClientInfo.java
```

- **Main.java**: Entry point for running the server
- **ServerInfo.java**: Manages server socket, clients, and message broadcasting
- **ClientInfo.java**: Handles client connection and message transmission

## Build & Run

### Requirements

- Java 17 or higher
- Maven 3.x or higher

### Build

```sh
mvn clean package
```

### Run

```sh
java -cp target/Java-Socket-Console-Chat-Server-1.0-SNAPSHOT.jar com.hsk.socket.chat.server.Main
```

## Usage

1. Start the server.
2. Clients (to be implemented separately) can connect to the server, receive a unique ID, and exchange messages.
3. Server console displays logs for client connections and message transmissions.

## Future Improvements

- Provide a GUI-based client
- Implement chat room creation and message storage (DB integration)
- Develop a dedicated client program

---

## License

MIT License

---
