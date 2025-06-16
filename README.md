# 🛒 E-comm-WebApp

A modern full-stack E-Commerce Web Application built using the **MERN stack**. It offers a smooth shopping experience for users and a powerful dashboard for admins. This app is optimized for performance, scalability, and responsive design.


---

## 🚀 Features

### 🧑 User Panel
- Signup/Login (JWT Auth)
- Browse products with categories and search
- Product detail view
- Add to cart, update quantity, remove item
- Place orders and view order history

### 🛠️ Admin Panel
- Add, update, delete products
- Manage users and their roles
- View and update order status
- Admin-only route protection

---

## ⚙️ Tech Stack

- **Frontend:** React.js, Redux Toolkit, Tailwind CSS, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT, bcrypt, cookies
- **Dev Tools:** Postman, VS Code, Git

---

## 📊 Project Stats

| Metric                     | Value                       |
|----------------------------|-----------------------------|
| React Components           | 25+                         |
| REST API Endpoints         | 20+                         |
| Avg Load Time              | 1.6s                        |
| Products in Test DB        | 500+                        |
| Dummy Users for Testing    | 100+                        |
| Mobile Responsiveness      | 100%                        |
| Lighthouse Performance     | 94+                         |
| Target Monthly Users       | 2,000+                      |

---

## 📁 Project Structure

```
E-comm-WebApp/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── components/
│   ├── pages/
│   └── App.js
└── README.md
```

---

## 🛠️ Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/hrsh1n1/E-comm-WebApp.git
cd E-comm-WebApp
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Add environment variables to `.env`:
```env
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
```

4. Start backend server:
```bash
npm run dev
```

5. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

6. Start frontend dev server:
```bash
npm start
```

---

## 📦 Upcoming Improvements

- Stripe or PayPal integration
- Product reviews & ratings
- Email notifications
- Social login (Google, GitHub)
- Progressive Web App (PWA) support

---

## 🙋‍♀️ Author

**Harshini Dadhich**  
📬 [LinkedIn](https://www.linkedin.com/in/harshini-dadhich-82455b291/)

---

## 📄 License

Licensed under the [MIT License](LICENSE).

