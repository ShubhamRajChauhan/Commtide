# 💬 Real-Time Chat Application

A full-stack real-time chat application that enables multiple users to join and chat simultaneously. The application uses **Spring Boot**, **WebSockets**, and **STOMP** on the backend, and **Thymeleaf**, **JavaScript**, and **Bootstrap** on the frontend. It allows for dynamic real-time communication across users using WebSockets with fallback mechanisms via **SockJS**.

---

## 🖥️ Project Preview

### 📌 User Interface:
<img width="958" height="472" alt="Chat Application UI" src="https://github.com/user-attachments/assets/a5135fcf-1706-4f10-b427-02d94253680e" />

### 📌 Working Demo View:
<img width="958" height="472" alt="Working Demo View" src="https://github.com/user-attachments/assets/d991d3fa-0793-47dc-8b5a-3e5f3da404ef" />

---

## 🚀 Features

- ✅ Real-time chat using WebSockets
- ✅ Multiple users can join and chat simultaneously
- ✅ Uses STOMP protocol for message broadcasting
- ✅ Responsive and clean UI
- ✅ Enter name and send messages without reload
- ✅ WebSocket fallback support with SockJS

---

## 🧱 Tech Stack

### 🔧 Backend (Server-Side)
- Spring Boot
- Spring WebSocket
- Spring Messaging (STOMP Protocol)
- Thymeleaf

### 🎨 Frontend (Client-Side)
- Thymeleaf
- JavaScript (ES6)
- SockJS
- STOMP.js
- HTML/CSS
- Bootstrap

### 🛠 Development & Infrastructure
- Maven or Gradle (for build and dependency management)

---

## 🏃‍♂️ Getting Started

### Prerequisites
- Java 17+
- Maven or Gradle
- Internet Browser

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/commtide.git
   cd commtide

2. **Run the application**
   ```bash
   ./mvnw spring-boot:run

3. **Open in Browser**
   ```bash
   http://localhost:8080/chat
   
## 📁 Project Structure
```
src
├── main
│   ├── java/com/chatapp
│   │   ├── config/           # WebSocket configuration
│   │   ├── controller/       # ChatController
│   │   └── model/            # Message model
│   └── resources/
│       ├── static/           # JS, CSS, and frontend assets
│       ├── templates/        # Thymeleaf templates
│       └── application.yml   # Configuration file

```

## 🧪 How It Works

1. Users enter their name and send a message.
2. The message is sent over WebSocket using STOMP protocol.
3. Backend controller receives it and broadcasts to all subscribed clients.
4. Frontend listens for messages and updates the chat in real-time.

## 📃 License
This project is licensed under the MIT License.

## 🙋‍♂️ Author

**Shubham Raj Chauhan**  
[LinkedIn](www.linkedin.com/in/shubham-raj-chauhan-5a4aa5280)  
📧 Email: shubhamrajchauhan07@gmail.com
