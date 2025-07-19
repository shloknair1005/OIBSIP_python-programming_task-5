# OIBSIP_python-programming_task-5

💬 Python CLI Chat App
This is a command-line chat application built in Python using sockets and threading. It allows multiple clients to connect to a server and exchange messages in real time. The project demonstrates the basics of network communication, socket programming, and concurrency using threads.

🧠 Project Overview
The project consists of two main components:

Server: Listens for client connections and handles broadcasting messages to all connected clients.

Client: Connects to the server, sends messages, and receives messages from other users in real time.

Each connected client runs on a separate thread, allowing for simultaneous communication.

🔧 Features
Real-time messaging over a local network

Multi-client support

Message broadcasting to all connected users

Clear client-server architecture

Fully functional via the command line

🛠️ Requirements
Python 3.x

No external libraries required

Works on Windows, macOS, and Linux

🚀 How It Works
Start the server on your machine (host).

Clients on the same network run the client script and connect to the server using the IP address and port.

Once connected, users can type and send messages.

All messages are broadcast to every connected client in real-time.

🌐 Use Cases
Local network chatroom for fun or testing

Foundation for more advanced messaging apps

Great for learning socket programming and multithreading

📦 Possible Enhancements
Add username support and message formatting

Support private messaging (DMs)

Add message timestamps

Encrypt messages for secure chat

Create a GUI version using Tkinter or a web version with Flask/WebSockets

👨‍💻 Author
Shlok Nair
Aspiring ML Engineer | Python Developer | Always Building Cool Stuff

