# RemoteControlX

A Java RMI-based system to remotely control Windows machines through a simple GUI.

## 🔧 Features
- 🔌 Remote Shutdown
- 🔁 Restart
- 🔒 Log Off
- 💬 Send Custom Messages

## 📚 Technologies Used
- Java RMI (Remote Method Invocation)
- Java Swing (GUI)
- Java Networking

## 📦 Modules
- ReceiveMessageInterface.java: RMI interface
- RmiServer.java: RMI server handling remote operations
- RmiClientGUI.java: Swing-based client for sending commands

## ⚙ Requirements
- Java 8 or higher
- Windows OS (for shutdown, restart, logoff support)
- Port *3232* must be open and available for RMI communication
- RMI registry (automatically started by the server)

## 🚀 How to Run

### ✅ Step 1: Compile All Classes
```bash
javac GUI/*.java
