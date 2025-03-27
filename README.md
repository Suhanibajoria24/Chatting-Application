
# Chatting Application

## Introduction
This is a simple Java-based chatting application that enables real-time communication between a server and a client using sockets. The application provides a user-friendly graphical interface (GUI) built with Swing.

## Features
- **Real-time Messaging**: Send and receive messages instantly.
- **Graphical User Interface**: Built using Java Swing for an intuitive chatting experience.
- **Client-Server Architecture**: Uses sockets for network communication.
- **User Profiles**: Displays profile pictures, status, and active status.
- **Basic Multimedia Support**: Icons for video call, voice call, and more options.

## Technologies Used
- **Programming Language**: Java
- **Networking**: Java Sockets
- **GUI**: Java Swing

## Installation & Usage
### Prerequisites
- Java Development Kit (JDK) installed
- Any Java IDE (Eclipse, IntelliJ IDEA, NetBeans) or a text editor

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Suhanibajoria24/Chatting-Application.git
   ```
2. Open the project in your preferred Java IDE.
3. Compile and run `Server.java` first.
4. Compile and run `Client.java` to connect to the server.
5. Start chatting!

## How It Works
1. **Server** starts listening on a port (6001 in this case).
2. **Client** connects to the server using the local IP address (`127.0.0.1`).
3. Messages are exchanged between the server and client through data streams.
4. Messages appear in the GUI in a formatted chat box.

## Future Enhancements
- Support for multiple clients.
- Emoji and media sharing support.
- Cloud-based chat storage.
- End-to-end encryption for security.

## Contributing
Feel free to fork the repository and contribute by submitting pull requests. Any contributions are welcome!

## License
This project is open-source and available under the [MIT License](LICENSE).

