## News Aggregator

A **MERN stack** news aggregator application that provides users with the latest news from multiple sources in one place.  
The app features user authentication, clean UI, and seamless browsing of categorized news articles.

---

## Live Demo
- **Frontend:** [News Aggregator Frontend](https://news-aggregator-khaki.vercel.app)  
- **Backend:** [News Aggregator Backend](https://news-aggregator-q7em.onrender.com)

---

## ✨ Features
- **User Authentication** – Sign up, login, and secure session management.  
- **Aggregated News Feed** – Fetches news from multiple sources.  
- **Categories** – Browse news by topics (e.g., Tech, Sports, Business, etc.).  
- **Responsive Design** – Works smoothly across desktop and mobile devices.  
- **Fast & Scalable** – Optimized using React, Express, MongoDB, and Node.js.  

---

## Tech Stack
**Frontend:**  
- React.js  
- Tailwind CSS (for styling)  
- Axios  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB (Mongoose)  

**Deployment:**  
- Frontend → Vercel  
- Backend → Render  

---

## 📂 Project Structure
```

news-aggregator/
├── client/          # React frontend
│   ├── src/
│   └── public/
├── server/          # Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── config/
└── README.md

````

---

## ⚙️ Installation & Setup (Local)
1. **Clone the repository**
   ```bash
   git clone https://github.com/palla-vii/news-aggregator.git
   cd news-aggregator
   ```

2. **Setup Backend**

   ```bash
   cd server
   npm install
   # Create a .env file with:
   # MONGO_URI=your_mongodb_connection
   # JWT_SECRET=your_secret_key
   npm start
   ```

3. **Setup Frontend**

   ```bash
   cd client
   npm install
   npm start
   ```
   
---

## Environment Variables

For the backend, create a `.env` file in `server/` with:

```
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-secret-key>
PORT=5000
```

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo and create a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

Developed by [Pallavi](https://github.com/palla-vii)


