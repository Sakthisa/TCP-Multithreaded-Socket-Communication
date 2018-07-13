# TCP-Multithreaded-Socket-Communication

## Description
A TCP communication network where the server can communicate with multiple clients and multiple clients can communicate with the server. This communication can work either within the localhost or between two machines connected to the same network. Clients have the ability to send any kind of file to the server which creates a copy of the file to a particular location. Clients also have the ability to send generic messages to the server. The server has the ability to piggyback any data back to the client in order to show clients that their message or file transfer was successful. The server utilizes a hash table in order to store previous client names for username authentication and for fast searching. 

## Language/Tools
This program was an individual project that was created in order to better understand TCP communication protocols as well as solidify understanding in Windows Forms, C# APIs and Libraries, and socket programming.

## Limitations
Only allowed to send small files (100 KB), large files causes the server and client to crash. Communication can only occur via the same network or through local host. The server doesn't have the ability to send back files to the client.

## Future Improvements
Trying to find a way to send any size file from both the client and server without any bytes lost. Allowing communication between different networks and devices. Having the capability of clients being able to interact with each other and send messages/files to each other. Lastly, making the communication more secure by using SSL streams to transmit information.
