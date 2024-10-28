# Terminal Chat Room
A basic chat room application implemented in Java, with a focus on:

Socket Communication: Server and client sockets handle real-time messaging.
I/O Stream Management: Ensures efficient data transfer between users.
Multithreading: Supports multiple users simultaneously with dedicated threads.
Thread Safety: Safeguards against concurrent access issues during message handling.

## Technologies Used
Language: Java
Networking: Java Sockets (ServerSocket and Socket)
Concurrency: Multithreading with thread-safe mechanisms

## Installation and Execution
### java Server
Run ServerTest.

### java Client
Configure Socket host to Server ip.
Open new terminal windows for each client and execute.
Run ClientTest.

## Features
Real-time Messaging: Messages are instantly relayed to all active users.
Console-based UI: A terminal interface displays messages and handles input/output.
Thread Management: Each client connection operates in its own thread, allowing for multiple users.
