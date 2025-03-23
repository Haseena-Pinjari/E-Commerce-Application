# E-Commerce-Application
# E-Commerce Application

##  Objective
Build a simple e-commerce application with authentication, product listing, and backend API integration.

---

##  Tech Stack
- **Frontend:** React
- **Backend:** Node.js + Express
- **Database:** MongoDB

---

##  Features

###  Authentication (Login/Signup)
- User registration
- User login

###  Home Screen
- Fetch and display product list
- Search bar to filter products
- Category filter (optional)

###  Backend
- REST API with routes for login, signup, and products
- MongoDB integration

---

##  Setup Instructions

###  1. Clone the Repository
```bash
  git clone <repository-url>
  cd ecommerce_app
```

###  2. Install Backend Dependencies
```bash
  cd backend
  npm install
```

###  3. Install Frontend Dependencies
```bash
  cd ../frontend
  npm install
```

###  4. Configure Environment Variables
Create a `.env` file in the `backend` folder with:
```
MONGO_URI=<your_mongo_db_connection_string>
JWT_SECRET=<your_jwt_secret>
```

###  5. Run the Backend Server
```bash
  cd backend
  npm run dev
```

###  6. Run the Frontend App
```bash
  cd frontend
  npm start
```

###  7. Test API Routes (Optional)
- **Signup:** `POST http://localhost:5000/signup` with `{ username, email, password }`
- **Login:** `POST http://localhost:5000/login` with `{ email, password }`
- **Get Products:** `GET http://localhost:5000/products`

---

##  API Endpoints

###  Authentication
- `POST /signup` – Create new user
- `POST /login` – Authenticate user

###  Products
- `GET /products` – Fetch all products
- `GET /products?search=<name>` – Search products by name

---

##  Demo
- Add screenshots or a short video of the working app

---

##  Future Improvements
- Product details page
- Cart and checkout
- Enhanced UI/UX
- Wishlist functionality

---

##  Evaluation Criteria
- Code quality
- UI/UX and responsiveness
- API integration
- Authentication flow

---


