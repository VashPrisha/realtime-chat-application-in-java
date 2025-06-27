# realtime-chat-application-in-java
A real-time chat application built in Java using Swing and AWT for the GUI, and Socket programming with multithreading for simultaneous message exchange. It enables multiple clients to communicate instantly over a network with a responsive, user-friendly interface.

# Real-Time Chat Application in Java

## 📌 Project Overview

This is a real-time chat application built in Java using Swing and AWT for the GUI, socket programming for network communication, and multithreading to handle multiple clients. It enables instant messaging between users connected to a central server.

## 💻 Features

- Real-time text chat between multiple clients  
- User-friendly GUI using Swing and AWT  
- Server handles multiple clients using threads  
- Broadcasts messages to all connected users  
- Simple and lightweight architecture

## 🛠️ Technologies Used

- Java  
- Swing & AWT  
- Socket Programming  
- Multithreading

## 🗂️ Project Structure

```
ChatApp/
├── Server.java         // Main server program
├── Client.java         // GUI-based chat client
├── ClientHandler.java  // Handles individual client threads
├── README.md           // Project documentation
```

## 🚀 How to Run

1. **Compile the code:**
   ```bash
   javac *.java
   ```

2. **Start the server:**
   ```bash
   java Server
   ```

3. **Start the client(s):**
   ```bash
   java Client
   ```

> Make sure server and clients run on the same network or adjust IP and port accordingly.

## 🔧 Future Improvements

- User authentication/login system  
- Private one-on-one chats  
- File sharing support  
- Enhanced GUI and sound notifications
