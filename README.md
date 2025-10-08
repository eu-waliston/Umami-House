# 🍣 Umami House

**Umami House** is a modern online platform for ordering authentic Japanese food. Built with JavaScript on both the backend and frontend, the app delivers a seamless user experience from browsing the menu to placing an order.

> “Umami” is the fifth taste — and this app is all about delivering it right to your door.

---

## 📁 Project Structure

```bash

umami-house/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── config/
│ ├── utils/
│ └── server.js
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── assets/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ ├── App.js
│ │ └── index.js
│ └── package.json
│
├── .env
├── .gitignore
├── README.md
└── package.json

```


---

## ⚙️ Tech Stack

**Frontend:**
- React.js (Vite or CRA)
- React Router
- Axios
- Styled Components / TailwindCSS

**Backend:**
- Node.js
- Express.js
- MongoDB (via Mongoose)
- JWT Authentication
- Multer (for image uploads)

**Others:**
- Nodemon (dev)
- Dotenv
- CORS

---

# Install dependencies

```bash

# Backend

cd backend
npm install

# frontend

cd frontend
npm install

```

## Set up your environment variables

### Create a .env file in the backend/ directory with:

```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

# 🛠 Features

- 🧾 Full menu with categories (sushi, ramen, bento, etc.)

- 👤 User authentication (register, login, JWT)

- 🛒 Add to cart and checkout

- 🧾 Order history and order tracking

- 🖼 Admin dashboard to manage menu items and orders

- 📦 Image upload for dishes

- 📱 Responsive design for mobile users

# 🧪 Future Improvements

- Payment integration (Stripe, Pix)

- Delivery tracking system

- Reviews and ratings for dishes

- Multi-language support (EN/JP/PT-BR)

# 🍱 About

Umami House was created to bring authentic Japanese food closer to users through a fast, responsive, and visually rich online experience. Whether you're craving sushi rolls or a hearty bowl of ramen, we've got you covered!
