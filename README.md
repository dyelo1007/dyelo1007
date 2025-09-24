PC Builder & Interactive Quiz Platform
<div align="center">

</div>

Hi there 👋 Welcome to my project!
This repository contains the source code for my full-stack application, developed as a third-year Computer Science student. It's an interactive platform featuring a PC parts builder and a comprehensive quiz system, built from the ground up to solidify my skills in modern web technologies.

<p align="center">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/React-20232A%3Fstyle%3Dfor-the-badge%26logo%3Dreact%26logoColor%3D61DAFB" alt="React">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/TypeScript-007ACC%3Fstyle%3Dfor-the-badge%26logo%3Dtypescript%26logoColor%3Dwhite" alt="TypeScript">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Node.js-339933%3Fstyle%3Dfor-the-badge%26logo%3Dnodedotjs%26logoColor%3Dwhite" alt="Node.js">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/MongoDB-4EA94B%3Fstyle%3Dfor-the-badge%26logo%3Dmongodb%26logoColor%3Dwhite" alt="MongoDB">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Tailwind_CSS-38B2AC%3Fstyle%3Dfor-the-badge%26logo%3Dtailwind-css%26logoColor%3Dwhite" alt="Tailwind CSS">
</p>

📸 Application Preview
<!--
TODO: This is the most important part!
Take a high-quality screenshot or, even better, record a short GIF of your application in action and place it here.
You can drag and drop the image/gif directly into the GitHub editor.
-->

<div align="center">
<img src="https://www.google.com/search?q=https://placehold.co/800x500/1a1b26/eeeeee%3Ftext%3DYour%2BScreenshot%2BHere" alt="Application Screenshot" width="80%">
</div>

✨ Key Features
This project is divided into two main user roles, each with a rich set of features:

👨‍🎓 For Students:
Interactive Quiz Mode: Take quizzes created by admins, with immediate feedback and a summary of results.

PC Part Builder: Plan and create custom PC builds by selecting from a database of components.

Saved Builds: Save multiple PC configurations to your personal account.

User Profile Management: Update your username, bio, and profile picture.

👑 For Admins:
Full Quiz Management (CRUD): Create, read, update, and delete quizzes.

Visibility Control: Toggle quizzes to be visible or hidden from students.

Student Results Dashboard: View a comprehensive list of all students, their quiz attempt status, scores, and submission times.

Content Management Hub: A central place to manage all interactive modes of the application.

🛠️ Tech Stack & Tools
This project was built using the MERN stack with TypeScript for end-to-end type safety.

Category

Technology

Frontend

React TypeScript Vite React Router Tailwind CSS Shadcn/UI Axios

Backend

Node.js Express.js TypeScript

Database

MongoDB Mongoose

Auth

JSON Web Tokens (JWT) bcrypt.js

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
Node.js (v18 or later)

npm

MongoDB (local installation or a cloud instance like MongoDB Atlas)

Backend Setup
Navigate to the backend directory:

cd backend

Install NPM packages:

npm install

Create a .env file in the backend root and add your variables:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000

Run the development server:

npm run dev

Frontend Setup
Navigate to the frontend directory:

cd frontend

Install NPM packages:

npm install

Create a .env file in the frontend root and add your backend API URL:

VITE_API_URL=http://localhost:5000

Run the development server:

npm run dev

The application should now be running on http://localhost:5173.

💡 Project Philosophy & Learning Journey
This project is my primary vehicle for transitioning from academic concepts to practical, real-world application development. The main goals were:

End-to-End Type Safety: Using TypeScript on both the client and server to reduce bugs and improve the developer experience.

Modern Tooling: Adopting Vite for its incredible speed and Tailwind CSS with Shadcn/UI for a modern, component-driven, and theme-aware design system.

Secure Authentication: Implementing a secure JWT-based authentication flow with role-based access control.

Clean Architecture: Separating concerns on the backend (routes, controllers, models) and frontend (services, components, pages) for maintainability.

🎯 Future Goals
While the core features are complete, I plan to continue expanding the platform:

[ ] Implement Challenge & Simulation Modes: Build out the remaining interactive learning modules.

[ ] Deploy to a Live Server: Host the application on a platform like Vercel (frontend) and Render (backend).

[ ] Enhance User Profiles: Add more detailed statistics, badges, and progress tracking.

📬 Contact
Mark - [Your Email Here] - [Link to your LinkedIn, optional]

Project Link: https://github.com/your-username/your-repo-name

<!--
Thanks for checking out my project!

Mark
-->
