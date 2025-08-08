# 💬 Real-Time Chat Application

A fully responsive real-time chat app using **Java (Spring Boot)** for the backend and **HTML/Bootstrap/JS** on the frontend. It supports instant messaging using **WebSockets (STOMP over SockJS)**, with features like user presence indicators and a dark mode UI.

---

## 🚀 Features

- 🔐 Simple user identification via name input
- 💬 Real-time messaging via WebSockets (STOMP)
- 🌙 Dark mode toggle
- 🟢 Online/offline connection management
- 📦 Lightweight and easy to deploy

---

## 🖼️ Screenshots

<img width="1919" height="878" alt="image" src="https://github.com/user-attachments/assets/3a30aea4-b28f-4b02-8b27-169d9aa8333c" />


---

## 🛠️ Tech Stack

### 🔙 Backend
- Java
- Spring Boot
- Spring WebSocket
- STOMP over SockJS
- Maven

### 🔜 Frontend
- HTML5 / CSS3
- Bootstrap 5
- JavaScript (Vanilla)
- SockJS & STOMP.js

---

## 🧑‍💻 How to Run the Project

### ⚙️ Backend (Spring Boot)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd chat-app/backend
   ```

2. Configure `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/chat_db
   spring.datasource.username=root
   spring.datasource.password=your_password
   ```

3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

---

### 🌐 Frontend (Static HTML)

1. Open the HTML file:
   ```bash
   cd ../frontend
   open index.html   # or just double-click to open in browser
   ```

> Make sure the backend server is running on the same origin or adjust the WebSocket endpoint in JS accordingly.

---

## 📁 Project Structure

```
chat-app/
│
├── backend/
│   ├── src/main/java/
│   ├── src/main/resources/
│   └── pom.xml
│
├── frontend/
│   ├── index.html
│   └── screenshots/
```

---

## 🔌 WebSocket Endpoints

| Type   | Endpoint           | Description                   |
|--------|--------------------|-------------------------------|
| STOMP  | /app/sendMessage   | Send a message to the broker  |
| SUB    | /topic/messages    | Subscribe to chat messages    |
| WS     | /chat              | WebSocket endpoint (SockJS)   |

---

## ✅ To-Do / Future Enhancements

- ✅ Dark/Light mode toggle
- ✅ Real-time chat UI with avatars
- 🔄 Authentication with JWT or sessions
- 🔄 Chat persistence using DB
- 🔄 Group chat / channels
- 🔄 Typing indicators
- 🔄 File/image sharing

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Om Shukla**  
📫 Email: work.omshukla@gmail.com <br>
🌐 Portfolio: https://om-shukla-portfolio.netlify.app/
