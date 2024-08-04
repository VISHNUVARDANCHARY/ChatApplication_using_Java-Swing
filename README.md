# ChatApplication_using_Java-Swing
 Chat Application usign java, which resembles the realtime application. Wonrks on the local system using the localhost database

# JavaChatApp

ChatApp is a Java-based chat application with a rich set of features, including user authentication, real-time messaging, image sharing, and more. It is built using the FlatLaf library for modern UI design and follows a well-organized project structure.

## Project Structure

The project follows a modular structure to ensure maintainability and scalability. Below is an overview of the main directories and their contents:


### Directory Descriptions

- **app**: Contains application-specific classes like `MessageType.java`.
- **components**: Holds various UI components such as chat elements (`Chat_Body.java`, `Chat_Bottom.java`, etc.).
- **emoji**: Contains classes for emoji handling (`Emoji.java`, `Model_Emoji.java`).
- **events**: Includes event handling classes (`EventChat.java`, `EventMain.java`, etc.).
- **form**: Contains forms and their corresponding UI files (`Chat.java`, `Login.java`, etc.).
- **icons**: Directory for icon resources.
- **main**: Contains the main entry point of the application (`Main.java`).
- **model**: Holds data model classes (`ModelLogin.java`, `ModelMessage.java`, etc.).
- **service**: Contains service-related classes (`Service.java`).
- **swing**: Custom Swing components and utilities (`ActiveStatus.java`, `ImageAvatar.java`, etc.).
- **themes**: Theme-related property files.

## Features

- **User Authentication**: Secure login and registration.
- **Real-Time Messaging**: Send and receive messages instantly.
- **Image Sharing**: Share images within the chat.
- **Emoji Support**: Use emojis in your messages.
- **Custom UI Components**: Modern and responsive UI components using FlatLaf.

## Setup

### Prerequisites

- JDK 11 or higher
- Xampp

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/HarChat.git
   cd HarChat
   
### Execution Process
- Open XAMPP Control panel v3.3.0
- Click on 'Start' buttons of MySQL  and Apache.
- Open localhost.
- update the localhost username and password in the service section file in the ServerSide Project.
- after all set, first Run ServerSide Project.
- next Run Chatapp project twice with registering
- Then Chat between the above two Running ChatApp Projects.

