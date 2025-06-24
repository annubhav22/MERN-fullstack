MERN Stack E-commerce App - Backend
A full-featured MERN (MongoDB, Express, React, Node.js) e-commerce backend with integrated authentication, product management, category filtering, Stripe payments, and admin capabilities. Built using industry best practices for scalable and secure deployment.

🔧 Key Features Implemented
✅ User authentication via Passport (Local + JWT strategy)

✅ Category-based filtering and product display

✅ Stripe Payment Integration with webhooks

✅ RESTful API with Express and MongoDB (Mongoose ODM)

✅ Admin support for product/order management

✅ Secure cookie-based JWT authentication and session handling

✅ Integrated with frontend (React + Redux) using axios

⚙️ Tech Stack
Backend: Node.js, Express.js

Authentication: Passport JS (Local + JWT)

Database: MongoDB (hosted on MongoDB Atlas), Mongoose

Payment: Stripe (Payment Intent API)

Session Management: express-session + JWT in cookies

Frontend Integration: React 18, Redux Toolkit, React Router

Deployment: Backend - Render | Frontend - Vercel (or similar)

📂 Project Structure Highlights
/routes: Contains RESTful route handlers for products, categories, users, orders, and cart

/controller: API logic for database operations and response handling

/model: Mongoose schemas for all major data models

/services: Custom middleware for auth checks, cookie parsing, etc.