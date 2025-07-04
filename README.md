# 📝 To-Do App (MERN Stack)

A full-stack to-do list web application with user authentication, task creation, priority settings, and status updates.

---

## 🚀 Project Description

This is a **MERN (MongoDB, Express, React, Node.js)** based to-do list app that allows users to:

- ✅ Register and log in with secure JWT authentication
- 📝 Add, delete, and update tasks
- 🟡 Set task **priority** and **status**
- 🔐 Access personalized task data securely

The frontend is built with **React** and styled using TailwindCSS. The backend is powered by **Node.js + Express** and connected to a **MongoDB Atlas** database.

---

## 🛠️ Technologies Used

### 🔹 Frontend:
- React
- React Router
- Tailwind CSS (via CDN)
- Axios / Fetch API

### 🔹 Backend:
- Node.js
- Express
- MongoDB Atlas
- Mongoose
- JWT (jsonwebtoken)
- bcryptjs
- CORS

### Hosting:
- **Frontend**: Render (Static Site)
- **Backend**: Render (Web Service)
- **Database**: MongoDB Atlas


### 🔹 Deployment:
- **Frontend**: [Render Static Site](https://todofrontend-mkrr.onrender.com)
- **Backend**: [Render Web Service](https://todobackend-b0nj.onrender.com)
- **Database**: [MongoDB Atlas](mongodb+srv://Kunal:<db_password>@cluster0.gq5eiin.mongodb.net/)

---



---

## 🚀 Deployment Notes

### Backend (Render Web Service):

- Set environment variable `MONGOURL` in Render with your MongoDB Atlas connection string
- Start command: `node index.js`

### Frontend (Render Static Site):

- Build command: `npm run build`
- Publish directory: `build`
- Backend API URL in frontend set to: `https://your-backend-name.onrender.com`

---

## 🙌 Author

**Kunal Tyagi**

Feel free to fork this project, explore the code, or reach out with feedback!

---

## 📄 License

This project is for educational and demo purposes.
