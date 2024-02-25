# Chat Room Application

This is a simple chat room application implemented in C++. The project consists of two main files: `server.cpp` for the server-side implementation and `client.cpp` for the client-side implementation.

## Server Side (`server.cpp`)

### How to Compile

```bash
g++ server.cpp -o server -lpthread
```

### How to Run

```bash
./server
```

### Server Features
- Multithreaded server that allows multiple clients to connect simultaneously.
- Each client is assigned a unique color for easy identification.
- Clients can join the chat room, send messages to everyone, and leave the chat room.

## Client Side (`client.cpp`)

### How to Compile

```bash
g++ client.cpp -o client -lpthread
```

### How to Run

```bash
./client
```

### Client Features
- Clients can join the chat room by providing their names.
- Messages are displayed with unique colors for each user.
- Clients can send messages to everyone in the chat room and exit using the `#exit` command.

## Usage Instructions

1. Compile the server and client programs using the provided compilation commands.
2. Run the server in one terminal window.
3. Run multiple client instances in separate terminal windows.
4. Enter a name when prompted for each client.
5. Start chatting with other clients in the chat room.

## Important Notes

- To exit the chat room, type `#exit` and press Enter.
- The server and clients communicate using sockets, and the messages are broadcasted to all connected clients.



Last updated on: 2024-02-12

Last updated on: 2024-02-14

Last updated on: 2024-02-15

Last updated on: 2024-02-16

Last updated on: 2024-02-21

Last updated on: 2024-02-22

Last updated on: 2024-02-22

Last updated on: 2024-02-25