# LAN-CHAT-APP
Project Overview

The LAN Chat Application is a client-server-based system that enables real-time text communication and file sharing over a Local Area Network (LAN). This project is implemented using Java and demonstrates the concepts of networking, multithreading, and object-oriented programming.

Features

Real-time Messaging: Clients can send and receive messages instantaneously.

File Sharing: Users can share files seamlessly over the network.

Multi-Client Support: The server can handle up to 10 clients simultaneously (this limit can be adjusted by modifying a single line of code).

User-Friendly GUI: Clients use a Java Swing-based graphical interface for interaction, while the server runs as a command-line application.

Technologies Used

Programming Language: Java

Core Concepts:

Networking: Socket, ServerSocket, DataInputStream, DataOutputStream

Multithreading: To handle concurrent client connections

File I/O: FileInputStream, BufferedInputStream, and OutputStream for file transfer

Object-Oriented Programming (OOP): Modular design for better code organization

Libraries:

Java Swing and AWT (for GUI components)

Core Java Utilities (java.util.*, java.io.*, java.net.*)

Prerequisites

Java Development Kit (JDK) installed

Basic understanding of Java programming

Knowledge of networking fundamentals

How to Run the Project

Setting Up the Server

Open a terminal window and navigate to the directory where the downloaded files are saved.

Compile the server.java file using the following command:

javac server.java

Run the server program:

java server

The server will start listening for client connections on the specified port (default: 7777).

It will not display any output except when a new client is connected.

Setting Up the Clients

Open a new terminal window and navigate to the same directory.

Compile the client.java file using the following command:

javac client.java

Run the client program:

java client

This will open the client GUI window.

Enter the necessary details (e.g., username, server IP) and click the "Join Chat" button to connect to the server.

When connected, the server terminal will display a message confirming the connection.

Connecting Multiple Clients

Repeat the steps to open additional terminal windows and run more client instances.

Each client can interact with the server and other connected clients through the GUI.

Sending and Receiving Messages

Once connected, clients can send and receive messages in real time using the GUI.

File sharing is also supported between clients.

Known Issues

Disconnected clients are not automatically removed from the server's client list. This can be fixed with minor adjustments in the code.

Future Enhancements

Database Integration:

Use SQL to store chat histories, user credentials, and file metadata.

Implement JDBC for database connectivity.

Security Features:

Encrypt messages using AES or RSA.

Use SSL/TLS for secure communication.

Scalability:

Implement thread pooling or non-blocking I/O to support a larger user base.

Advanced Communication:

Add support for voice and video calls.

Challenges Faced

Efficiently managing threads for multiple clients.

Ensuring smooth file transfer over the network.

Debugging and handling exceptions during connection issues.

About the Author

This project was developed by Sakshi Kathane, a software engineering enthusiasst with a keen interest in networking and Java development. The project serves as a practical implementation of core Java concepts and aims to provide a foundation for more advanced networking applications.

License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license terms.

Author: Sakshi Kathane Email: Sakshikathane09@gmail.com LinkedIn: Sakshi Kathane
