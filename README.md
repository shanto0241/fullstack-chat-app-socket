# 💬 Realtime Chat App

A sleek and modern **Realtime Chat Application** that delivers seamless communication and beautiful UI/UX. This app integrates cutting-edge tools and technologies to provide a robust, scalable, and visually appealing chat experience.

---

## 🌟 Features

- 🔐 **Authentication**: Secure user signup/login using JWT.
- 🌈 **Themes**: Customize your chat experience with light and dark mode support. Also 30 others.
- 🔥 **Realtime Chat**: Powered by **Socket.IO** for instant, bidirectional communication.
- 📸 **Image Uploads**: Leverage **Cloudinary** for fast and secure media management.
- 🗄️ **Database**: Built with **MongoDB** for reliable data storage.
- ✨ **Responsive Design**: Optimized for all devices using **DaisyUI** and **Tailwind CSS**.

---

## 🛠️ Tech Stack

- **Frontend**:
  - React.js
  - DaisyUI & Tailwind CSS (for responsive and visually appealing design)
- **Backend**:
  - Express.js
  - Socket.IO (for real-time WebSocket communication)
- **Database**:
  - MongoDB (NoSQL, scalable database)
- **Cloud Services**:
  - Cloudinary (image uploads and management)

---

## 🚀 Live Demo

🔗 [Realtime Chat App](https://your-app-link.vercel.app/)

---

## 🔧 Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shanto0241/fullstack-chat-app-socket.git
   cd realtime-chat-app
   ```

````

2. Install dependencies:

   ```bash
   # Install root dependencies
   npm install

   # Install frontend dependencies
   cd frontend
   npm install

   # Install backend dependencies
   cd ../backend
   npm install
   ```

3. Set up environment variables [backend]:
   Create a `.env` file in the root directory and provide the following:

   ```env
   MONGO_URI=<your-mongodb-uri>
   JWT_SECRET=<your-jwt-secret>
   CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
   CLOUDINARY_API_KEY=<your-cloudinary-api-key>
   CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
   ```

4. Start the app:

   ```bash
   # Start the backend server
   cd backend
   npm run dev

   # Start the frontend
   cd ../frontend
   npm run dev
   ```

5. Open the app in your browser:

   ```
   backend:: http://localhost:5001
   frontend:: http://localhost:5173
   ```

---

## 🌐 API Endpoints

### **Authentication**

* `POST /api/auth/signup`
* `POST /api/auth/login`
* `POST /api/auth/logout`
* `PUT  /update-profile`
* `GET  /check`


### **Messages**

* `GET /users`
* `GET /:id`
* `POST /send/:id`

## 📚 Future Enhancements

* 📝 Typing indicators for active conversations.
* 📱 Mobile push notifications.
* 🖼️ Inline image previews for uploaded media.
* 📊 Analytics dashboard for chat activity.

---

## 🤝 Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.


## ✨ Acknowledgments

* **Socket.IO** for real-time communication.
* **Cloudinary** for effortless image management.
* **DaisyUI** for an amazing UI library.

---

**Developed by
Sudipta Sinha Shanta
Happy chatting! 🎉

```
````
