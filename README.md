# Java Chat Application

## Overview
This is a simple chat application built using Java that allows multiple users to communicate over a network. It consists of a server and multiple clients, enabling real-time text-based messaging.

## Features
- Multi-client support
- Real-time messaging
- GUI-based client (using Swing)
- Command-line server
- Message broadcasting to all connected users

## Requirements
- Java Development Kit (JDK) 8 or later
- Basic knowledge of Java networking (sockets)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/java-chat-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd java-chat-app
   ```
3. Compile the Java files:
   ```sh
   javac Server.java Client.java
   ```

## Usage
### Running the Server
1. Start the server by running:
   ```sh
   java Server
   ```
   The server will start and listen for incoming client connections.

### Running the Client
1. Open a new terminal or command prompt.
2. Run the client application:
   ```sh
   java Client
   ```
3. Enter the server IP address and port number to connect.

## File Structure
```
java-chat-app/
|-- src/
|   |-- Server.java
|   |-- Client.java
|-- README.md
```

## Future Enhancements
- User authentication
- Private messaging
- File sharing
- Encrypted communication

## Contributing
Feel free to contribute by forking the repository and submitting pull requests.

## License
This project is licensed under the MIT License.

