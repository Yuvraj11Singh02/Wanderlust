# Wanderlust

Wanderlust is a full-stack web application built with **Node.js, Express.js, MongoDB, and EJS**. It allows users to explore, create, and review travel listings, making trip planning easier and more interactive.

---

## Features

- User authentication: Signup, Login, Logout
- Create, Read, Update, Delete (CRUD) operations for travel listings
- Add reviews to listings
- Interactive map integration for listing locations
- Flash messages for notifications
- Responsive design with custom CSS
- Error handling for smooth user experience

---

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Frontend:** EJS templating, HTML, CSS, JavaScript
- **Other Tools:** VS Code, Git, GitHub

---

## Installation

1. Clone the repository:  
   git clone https://github.com/Yuvraj11Singh02/Wanderlust.git  
   cd Wanderlust

2. Install dependencies:  
   npm install

3. Create a `.env` file in the root directory and add your environment variables:  
   DB_URL=your_mongodb_connection_string  
   SECRET=your_session_secret  
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name  
   CLOUDINARY_KEY=your_cloudinary_key  
   CLOUDINARY_SECRET=your_cloudinary_secret

4. Start the server:  
   nodemon app.js

5. Open your browser and visit:  
   http://localhost:8080

---

## Project Structure

Wanderlust/  
├─ controllers/       # Route controllers  
├─ models/            # Mongoose schemas  
├─ routes/            # Express routes  
├─ public/            # CSS, JS, images  
├─ views/             # EJS templates  
├─ utils/             # Utility functions  
├─ init/              # Initial data setup  
├─ app.js             # Main server file  
├─ package.json  
├─ package-lock.json  
├─ .gitignore  
└─ README.md

---

## Author

**Yuvraj Singh**  
[GitHub Profile](https://github.com/Yuvraj11Singh02)
