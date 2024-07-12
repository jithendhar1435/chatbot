
Real-Time Chat Application with Spring Boot
This repository contains a real-time chat application built using Spring Boot, designed to facilitate instant messaging between users via WebSocket communication. The application also includes features for user authentication, file upload/download, and a basic chatbot for automated responses.

Features
Backend Capabilities
Authentication: Implements user authentication with session validation and basic authentication mechanisms.
WebSocket Communication: Enables real-time messaging between users, ensuring seamless and immediate chat interaction.
File Handling: Supports file upload and download functionalities within the chat interface.
JPA Persistence: Uses JPA for data persistence, ensuring reliability and data integrity.
Secure HTTPS Connection: Utilizes self-signed HTTPS for secure communication over the web.
User Interface Capabilities
Responsive Design: Ensures the application is responsive and accessible across various devices and screen sizes.
Modal and Toast Notifications: Provides modal dialogs and toast notifications for user interactions and notifications.
HttpRequest Handling: Manages HTTP requests for seamless user experience during chat sessions.
Prerequisites
Java Development Kit (JDK) 8 or later
Apache Maven
MySQL or another relational database (configured in application.properties)
How to Build and Run
Clone the Repository

bash
Copy code
git clone https://github.com/jithendhar1435/realtime-chatbot.git
cd realtime-chat-springboot
Build the Application

bash
Copy code
mvn package
Run the Application

bash
Copy code
java -jar target/realtime-chat-springboot-0.0.1-SNAPSHOT.jar
Access the Application

Open your web browser (Firefox or Chrome recommended) and navigate to:

http
Copy code
http://localhost:8080/
Sign-up Users

Sign-up at least two user accounts to start chatting.

Usage
Chatting: Send text messages in real-time using WebSocket communication.
File Handling: Upload and download files within the chat interface.
Authentication: Log in and authenticate users to access chat functionalities securely.
Directory Structure
src/main/java: Contains Java source files.
src/main/resources: Includes application properties, static resources, and templates.
Configuration
application.properties: Configure database settings, server port, and other application-specific properties.
Contributing
Contributions are welcome! Fork this repository, make improvements, and submit a pull request. Help enhance this chat application for better functionality and usability.

License
This project is licensed under the MIT License. See the LICENSE file for details.