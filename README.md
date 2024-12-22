
# WaveMessenger - Real-time Chat Application

WaveMessenger is a powerful real-time chat platform that offers seamless one-to-one and group messaging. Designed with security and speed in mind, the app ensures instant message delivery and intuitive group management, making communication effortless.

## 🚀 Live Demo
[🔗 Try WaveMessenger Live App](#)

---

## 🛠️ Tools & Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Chakra-UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-time Communication:** Socket.io

---

## ✨ Features

### 🔒 **Secure Communication**
- Real-time messaging with WebSocket technology ensures fast and secure message delivery.
- Optimized WebSocket connections to minimize latency, providing users with a smooth experience.

### 💬 **Messaging Features**
- **One-to-One Messaging:** Send and receive messages instantly with minimal delay.
- **Group Messaging:** 
  - Admin-controlled groups with permissions for managing members.
  - Group admins have the ability to manage members and permissions effortlessly.

### ⚙️ **Admin Controls**
- **User Management:** Group admins can add/remove members and manage permissions.
- **Enhanced UX:** User-friendly interface for easy group management and intuitive chat experience.

### 🌟 **Additional Features**
- **Seamless Messaging:** All messages delivered in real-time using Socket.io.
- **Responsive UI:** Built with Chakra-UI to ensure modern and accessible design.
- **Database-Driven:** Persistent data storage with MongoDB ensures chat history is retained.

---

## 📡 **API Features**
- **User Authentication:** Secure login and registration functionality.
- **Message History:** Retrieve chat histories for one-to-one and group conversations.
- **Group Management APIs:** 
  - Endpoints to manage group settings, members, and permissions.

---

## 💻 Installation and Setup

To run WaveMessenger locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kaifhb/WaveMessenger.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd WaveMessenger
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the root directory and add the following:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

5. **Start the development server:**
   ```bash
   npm start
   ```

6. **Access the application:**
   - Open [http://localhost:3000](http://localhost:3000) to start using WaveMessenger.

---

## 🔮 **Future Enhancements**
- **Notifications:** Add push notifications for new messages and group updates.
- **Media Sharing:** Enable file and image sharing within chats.
- **Video/Audio Calls:** Integrate real-time calling features using WebRTC.
- **Theming Options:** Introduce light and dark modes for better accessibility and personalization.

---

## 📂 Repository

Check out the full codebase on GitHub:

[🔗 GitHub Repository](https://github.com/kaifhb/WaveMessenger)

---

## 💡 **Key Achievements**
- **Reduced Latency:** Optimized WebSocket connections to ensure lightning-fast message delivery.
- **Enhanced User Experience:** Introduced powerful admin controls for seamless group management.
- **Seamless Communication:** Real-time messaging for groups and individuals, ensuring minimal delays.

---

## 💬 **Contributing**

Contributions are welcome! Feel free to fork the repository, submit issues, and create pull requests for any improvements or bug fixes.
