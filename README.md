# Airbnb Clone Project  
Front End Start - Npm Run Dev
Backend Start - npm Start
🏠 Airbnb Clone – MERN Stack

A full-stack Airbnb-style web application built using MongoDB, Express.js, React.js, Node.js, featuring authentication, property listings, image upload, and responsive UI.

🚀 Features
👤 Authentication

JWT-based Login & Signup

Protected Routes

User profile & stored data

🏡 Property Listings

Add / Edit / Delete listings

View all listings

Dynamic filters & search

Single listing page with full details

📤 Image Upload

Upload multiple images

Preview images

Cloud / Local storage support

🎨 UI / UX

Modern Airbnb-like design

Fully responsive

Tailwind / Custom CSS

🛠️ Tech Stack
Frontend

React.js

React Router

Axios

TailwindCSS / Custom Styling

Backend

Node.js

Express.js

JWT Authentication

Multer for Image Uploads

Database

MongoDB + Mongoose

📂 Folder Structure
airbnb-clone/
│
├── client/               # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── tailwind.config.js
│
├── api/                  # Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── uploads/
│   ├── index.js
│   └── config.js
│
└── README.md

⚙️ Installation & Setup
1️⃣ Clone this repo
git clone https://github.com/yourusername/airbnb-clone.git
cd airbnb-clone

2️⃣ Install dependencies
Frontend
cd client
npm install
npm run dev

Backend
cd api
npm install
node index.js

🔐 Environment Variables

Create a .env file inside /api

MONGO_URL=your_mongo_connection
JWT_SECRET=your_secret_key
PORT=5000

🖼️ Sample Screenshots

Replace with your project images.

🧪 API Endpoints (Sample)
Auth
Method	Endpoint	Description
POST	/auth/register	Create new user
POST	/auth/login	Login user
Listings
Method	Endpoint	Description
POST	/listings	Create listing
GET	/listings	Get all listings
GET	/listings/:id	Get single listing
PUT	/listings/:id	Update listing
DELETE	/listings/:id	Delete listing
📌 Future Improvements

Wishlist / Favorites

Payment Integration

Live Maps

Reviews & Ratings

🙌 Author

Ankit Kumar
Full-Stack Developer (MERN)
