# Goldencat Chatroom

A real-time chatroom web application built using Java 17, Spring Boot, WebSocket, and Thymeleaf. This application allows users to chat in a shared environment, featuring a modern tech stack with a responsive user interface.

## Features

- **Real-Time Messaging**: Users can send and receive messages instantly, powered by WebSocket technology.
- **User Login**: Simple username-based login to access the chatroom.
- **User Notifications**: Announcements are made when a user joins or leaves the chatroom.
- **Custom User Colors**: Unique, soothing colors are assigned to each user's messages for easy identification.
- **Responsive Design**: Built with Bootstrap to ensure a consistent experience across devices.
- **Social Media Integration**: Links to social profiles are provided in the chatroom header.

## Tech Stack

- **Backend**: Java 17, Spring Boot
- **Frontend**: Thymeleaf, Bootstrap, Font Awesome
- **Real-Time Communication**: Spring WebSocket, STOMP protocol
- **Build Tool**: Maven

## Setup Instructions

### Prerequisites
- Java 17 or higher
- Maven 3.6+

### Steps to Run Locally

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Goldencat98/ChatRoom.git
   cd ChatRoom
   ```

2. **Build the Project**:
   ```sh
   mvn clean install
   ```

3. **Run the Application**:
   ```sh
   mvn spring-boot:run
   ```

4. **Access the Application**:
   Open your browser and navigate to `http://localhost:8080`.

## Usage

- **Login**: Enter your desired username to join the chatroom.
- **Chat**: Send messages to other users in real-time. You will be notified when new users join or leave the chat.

## License

This project is licensed under the **Goldencat Chatroom License**. You may use, modify, and distribute the software for personal, non-commercial use. Commercial use requires prior approval from the creator.

For more details, see the [LICENSE](./License.md) file.

## Contact

For permissions related to commercial use or any questions, please contact: Code With Goldencat (codingwithgoldencat@gmail.com)

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the project.

## Screenshots

![Login Page](src/main/resources/static/screenshots/Login_Screenshot.png)
![Chat Room](src/main/resources/static/screenshots/MainPage_Screenshot.png)
![Chat Room With Multiuser](src/main/resources/static/screenshots/MultipleUser_Screenshot.png)

## Future Enhancements

- **Private Messaging**: Allow users to send direct messages to one another.
- **Authentication**: Implement user authentication for a more secure experience.
- **Media Sharing**: Add support for sharing images and files within the chat.

