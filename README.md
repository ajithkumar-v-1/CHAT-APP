Chat Application
A real-time, cross-platform chat application designed to facilitate seamless communication between users. Built using the MERN Stack (MongoDB, Express.js, React.js, Node.js), this application integrates with Cloudinary for image uploads and uses WebSockets for real-time messaging. It provides a secure, responsive, and interactive environment for users to chat effectively.

Features
User Management
Signup and Login: Users can create accounts, log in with credentials, and securely update their profiles.
Profile Management: Users can update personal details, profile picture, and manage privacy settings.
Messaging
Real-time Messaging: Send and receive text messages, images, and attachments instantly.
Image Upload: Support for base64 image upload using Cloudinary, ensuring quick image delivery.
Message Notifications: Users receive notifications for new messages, even when the app is closed.
Conversation Management: View, search, and filter messages with ease, and manage conversation threads.
User Interface
Responsive Design: A mobile-first design that ensures the application is usable across all devices (mobile, tablet, desktop).
Dark/Light Mode: Toggle between dark and light themes for a personalized experience.
Typing Indicators: Real-time display of typing indicators when users are composing messages.
Real-time Features
WebSocket Integration: Use of WebSockets for faster and more reliable message delivery.
Socket Notifications: Notifications when a user is mentioned or when a new message is received.
Tech Stack
Frontend:

React.js: For interactive and dynamic UI with state management using Context API.
React Router: For client-side routing.
Axios: For HTTP requests.
Lucide React: For icons.
Backend:

Node.js: As the runtime environment.
Express.js: For routing, middleware, and RESTful API handling.
MongoDB: Database to store user information, messages, and chat logs.
Mongoose: ODM for MongoDB to interact with the database.
Cloudinary: For image hosting and management.
Deployment:

Heroku: For backend deployment.
Vercel or Netlify: For frontend deployment.
Setup
Prerequisites
Node.js (v12 or above)
MongoDB (running locally or accessible remotely)
Cloudinary account (for image uploads)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-repo/chat-app.git
cd chat-app
Install dependencies:

bash
Copy code
cd front-end
npm install
cd ../back-end
npm install
Configure environment variables:

Create .env files in the front-end and back-end directories.
Set up environment variables such as:
REACT_APP_API_URL: Base URL for your backend API (e.g., http://localhost:8080/api)
CLOUDINARY_URL: Cloudinary API endpoint and credentials.
MONGO_URI: MongoDB connection string.
SESSION_SECRET: Secret key for JWT and session management.
Run the application:

Frontend:
bash
Copy code
cd front-end
npm run dev
Backend:
bash
Copy code
cd back-end
npm run dev
Start the application:

Access the chat application at http://localhost:5173 (for frontend) and http://localhost:8080 (for backend).
