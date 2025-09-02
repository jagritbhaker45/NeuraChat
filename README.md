NeuraChat – AI Chatbot App (MERN + Google Gemini + ImageKit + Stripe)

NeuraChat is a full-stack AI chatbot application built with the MERN stack (MongoDB, Express.js, React.js, Node.js).
It allows users to:

✍️ Generate AI-powered text content using Google Gemini

🖼️ Create AI-generated images via ImageKit

💳 Purchase credits securely through Stripe payment gateway

🔐 Sign up / log in with authentication

☁️ Deploy seamlessly on the cloud

✨ Features

🔑 User authentication (JWT)

💬 AI chatbot (text generation using Google Gemini)

🖼️ AI image generator (ImageKit integration)

💳 Credit-based system with Stripe payments

🌐 Full-stack MERN app with secure backend

📦 Deployed using Vercel / Render / MongoDB Atlas

🛠️ Tech Stack

Frontend: React.js, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB (Atlas)
AI Models: Google Gemini (text), ImageKit (images)
Payments: Stripe
Deployment: Vercel + MongoDB Atlas

Installation & Setup

Clone the repo:

git clone https://github.com/your-username/NeuraChat.git
cd NeuraChat


Install dependencies:

npm install
cd client && npm install
cd ..


Create a .env file in the server/ directory:

MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_gemini_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url
STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
JWT_SECRET=your_jwt_secret


Run the backend:

cd server
npm start


Run the frontend:

cd client
npm start


Open in browser:

http://localhost:5173

<img width="1365" height="590" alt="image" src="https://github.com/user-attachments/assets/8e769007-ffba-40f5-82e8-e5f491ccb021" />

