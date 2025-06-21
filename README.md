# 🏡 Airbnb Clone

An Airbnb-inspired web application that allows users to browse, book, and list vacation rentals. This project is designed as a full-stack development exercise, emphasizing modern web development practices and UI/UX design.

## 🚀 Project Goals

- Recreate the core functionalities of Airbnb (listing, search, booking, and user authentication)
- Practice building responsive and interactive front-end interfaces
- Gain experience with backend development, including APIs and database integration
- Strengthen understanding of state management and component architecture
- Learn deployment and hosting of full-stack web applications

## 🔧 Tech Stack

### Frontend:
- **React.js** – for building dynamic user interfaces
- **Tailwind CSS** – for fast and responsive styling
- **React Router** – for navigation and routing
- **Formik + Yup** – for form handling and validation

### Backend:
- **Node.js + Express.js** – for RESTful APIs
- **MongoDB + Mongoose** – for data modeling and storage
- **JWT** – for authentication and user sessions
- **Cloudinary / AWS S3** – for image hosting

### Dev Tools:
- **Vite** – for fast development and hot module replacement
- **Zustand / Redux** – for global state management
- **Postman** – for API testing
- **Git & GitHub** – for version control
- **Render / Vercel / Netlify** – for deployment

## ✨ Features

- User authentication (Sign up / Login / Logout)
- Host dashboard to list and manage properties
- Image upload and preview for listings
- Search and filter properties by location and price
- Booking and reservation system
- Responsive design for mobile and desktop

## 📂 Project Structure

airbnb-clone/
├── client/ # React frontend
│ ├── components/
│ ├── pages/
│ ├── utils/
│ └── App.jsx
├── server/ # Node.js backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
└── README.md

bash
Copy
Edit


## 🛠 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Hagos29/airbnb-clone.git
   cd airbnb-clone

2.Setup Backend
cd server
npm install
npm run dev

3.Setup frontend
cd client
npm install
npm run dev

4.Open the app in your browser at http://localhost:5173

📌 Future Improvements
Add reviews and ratings system

Implement messaging between hosts and guests

Payment gateway integration (e.g., Stripe)

Calendar availability and booking conflict prevention
