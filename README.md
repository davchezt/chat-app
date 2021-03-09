# Chat App

Windows Forms Application made in Visual Studio, written in C# (.NET Framework v4.6.1).

Application is made for sole purpose of showing how to implement `TcpListener` and `TcpClient` classes as well as asynchronous read and write functions.

Used `ConcurrentDictionary` class which is a thread-safe collection of key/value pairs to store client information.

Used `Task` class to prevent race conditions.

Server uses multithreading to accept clients (i.e. server can accept multiple clients).

All the code you need is in these two files:

* [/src/Server/Server/Server.cs](https://github.com/ivan-sincek/chat-app/blob/master/src/Server/Server/Server.cs)
* [/src/Client/Client/Client.cs](https://github.com/ivan-sincek/chat-app/blob/master/src/Client/Client/Client.cs)

Tested on Windows 10 Enterprise OS (64-bit).

Made for educational purposes. I hope it will help!

## How to Run

Run [\\exec\\Server.exe](https://github.com/ivan-sincek/chat-app/tree/master/exec) and [\\exec\\Client.exe](https://github.com/ivan-sincek/chat-app/tree/master/exec).

## Images

<p align="center"><img src="https://github.com/ivan-sincek/chat-app/blob/master/img/server.jpg" alt="Server"></p>

<p align="center">Figure 1 - Server</p>

<p align="center"><img src="https://github.com/ivan-sincek/chat-app/blob/master/img/client.jpg" alt="Client"></p>

<p align="center">Figure 2 - Client</p>
