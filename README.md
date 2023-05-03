OBJECTIVE

You will create a client and a server application for this project that allows client-to-client communication but not server-to-client communication. The server application will only be used to exchange contact details for clients who are currently active.

Clients can connect to the server, log in with a password, and view the list of clients who are currently active. Any active client can be selected as the connection point, and the remote client will be prompted to accept the new connection. Once a connection has been established successfully, clients can communicate with one another independently of the server. Additionally, a client can ask the server to send a message to every client in its database by making a broadcast request. The broadcast message should be received by all clients who will be active within 30 minutes.

Given port number 6401

FEATURES
1. message Brodcasting
2. Hashing Passwords
3. Peer to peer messaging
4. List of active clients
5. Login-SignUp
6. Login request every 30mins

Prerequisities

1.Importing Libraries

2.C++ compiler

Execution.
1. Direct the terminal to the place where the code is kept.
2. Compiling the server code at the terminal by typing g++ server.cpp -o server pthread
3. Issue the command "./server" to launch the server code.
4. The server starts to monitor for incoming client requests. 
5. Launch a new terminal and type g++ client.cpp -o client pthread to compile the client code.
6. Use the command./client to run the client code.

