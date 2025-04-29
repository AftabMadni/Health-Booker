# Health-Booker

**Health-Booker** is a full-stack healthcare appointment booking web application built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). It allows patients to book appointments with doctors, manage schedules, and access medical services online.

---

## 🚀 Features

- 🔐 User Authentication (Patients & Doctors)
- 📅 Book, cancel, and manage appointments
- 👩‍⚕️ Doctor profile management
- 🏥 Admin panel to manage users and appointments
- 📊 Dashboard with upcoming and past appointments
- 📧 Email notifications

---

## 🛠️ Tech Stack

- **Frontend**: React.js, React Router, Bootstrap / Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Tokens)
- **API Testing**: Postman
- **Version Control**: Git & GitHub

---

## 🔧 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/AftabMadni/Health-Booker.git
   cd Health-Booker
   ```

2. **Install server dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies**
   ```bash
   cd ../client
   npm install
   ```

4. **Set up environment variables**  
   Create a `.env` file in both `server` and `client` directories. Example:
   ```
   // server/.env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the app**
   - Server: `npm run dev` (in the `server` folder)
   - Client: `npm start` (in the `client` folder)

---

## 📂 Project Structure

```
Health-Booker/
│
├── client/       # React frontend
├── server/       # Express backend
└── README.md     # Project overview
```
