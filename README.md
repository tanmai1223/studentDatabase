# Student Database Management System

A full-stack **MERN (MongoDB, Express, React, Node.js)** application for managing student data with secure authentication and role-based access.

---

## 🔗 Live Demo

- 🌐 Frontend: [Netlify Deployment](https://studentdatabaseproject.netlify.app/)
- 🌐 Backend: [Render Deployment](https://studentback-ocnq.onrender.com)

---

## 🧠 Features

### 🔐 Authentication
- Secure **Login** & **Registration**.
- Passwords are hashed using **bcryptjs**.
- JWT token-based login.
- Role-based access control (Admin/User).

### 👤 User Role

- ✅ Directed to **Homepage** on login.
- 📊 Homepage displays charts with student data insights.
- 📋 Sidebar: `Home`, `View`
- 👁️ View page displays a table of all students.
- 📝 Click any row to view full student details with **edit** option.
- 🔒 Logout button in header.

### 👨‍💼 Admin Role

- ✅ Directed to **Admin Dashboard** on login.
- 📋 Sidebar: `Home`, `Add`, `View`
- ➕ Add page has a form to insert new student data.
- 📊 View page shows the student table.
- 👁️ Click a row to view complete details.
- ✏️ Edit student info or 🗑️ delete the record directly.

---

## 🛠️ Tech Stack

### Frontend:
- React.js
- Axios
- React Router
- Chart.js or Recharts (for displaying charts)

### Backend:
- Node.js
- Express.js
- MongoDB (with Mongoose)
- bcryptjs (for password hashing)
- jsonwebtoken (for authentication)

---

## 📁 Folder Structure

```bash
├── client/                # React frontend
│   ├── src/
│   │   ├── Pages/         # Login, Register, Admin, Home etc.
│   │   ├── Components/    # Header, Sidebar, Chart, etc.
│   │   ├── Context/       # Auth context
│   │   └── ...
├── server/                # Express backend
│   ├── model/             # Mongoose schemas
│   ├── routes/            # Login, Register, Student APIs
│   ├── middleware/        # Auth middlewares
│   └── ...
```
---

## 🚀 Deployment
- Frontend deployed to Netlify
- Backend deployed to Render
- MongoDB Atlas used for cloud database
- .env file used for sensitive credentials (PORT, DB_URI, JWT_SECRET)

---

## 📸 Screenshots
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7dd95991-4b34-4e9b-ba07-862ddcd6e983" />-LoginPage
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0132fde3-88f7-4102-8b20-822651934f78" />-RegisterPage
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c23f89b6-11b9-4688-81e6-6d7b04dd7e4a" />-HomePage
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40859643-c857-40b6-8f60-5d454863f0ce" />-ViewPage
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42b64e94-e966-49a6-9f6e-fea77bb8710d" />-DetailsPage
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/63de40e2-03cc-4843-a8c8-3871342893d1" />-AddPage

---

## ✨ Future Improvements
- Add student image upload
- Export data as PDF or Excel
- Search and filter features in tables
- Pagination for large datasets

---

## 🙋‍♀️ Author
Hekkadka Tanmai
📧 htanmai.23@gmail.com
📍 Hyderabad, Telangana

---

## 📌 License
This project is open-source and available under the MIT License.










