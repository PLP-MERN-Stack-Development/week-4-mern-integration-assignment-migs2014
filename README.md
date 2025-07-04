
📝 MERN Blog Platform
A clean and functional blogging platform powered by the MERN stack (MongoDB, Express.js, React, and Node.js). This project supports core blog features like post creation, editing, and browsing—designed with modular code organization, simple authentication, and a modern UI architecture.
________________________________________
🌟 Features
•	✅ User Authentication (via JWT)
Secure login and registration handled on the backend with middleware protection.
•	✍️ Post Management
Create, edit, delete, and read blog posts, powered by Express routes and MongoDB models.
•	🛠 Modular Architecture
Clean separation between frontend and backend for easy maintenance and scalability.
•	🚀 Fast & Modern Frontend
Built with React, Vite, pnpm, Tailwind CSS, and shadcn/ui components.
________________________________________
📂 Project Structure
.
├── client/                   # Frontend
│   └── src/
│       ├── assets/           # Static files and icons
│       ├── components/       # Reusable UI components
│       ├── context/          # Global state/context providers
│       ├── hooks/            # Custom hooks
│       ├── lib/              # Axios config and utilities
│       ├── pages/            # Page components like Home, Dashboard, PostForm
│       └── rooter/           # Route definitions (probably a typo of 'router')
│
├── backend/                  # Backend
│   ├── config/               # DB connection and environment configs
│   ├── controllers/          # Logic for handling routes (e.g., postController.js)
│   ├── middleware/           # Authentication and error handling
│   ├── models/               # Mongoose schemas (User, Post, Category)
│   └── routes/               # Express route definitions
________________________________________
⚙️ Getting Started
1️⃣ Install Dependencies
# Install root dependencies
pnpm install

# Install frontend dependencies
cd client && pnpm install
2️⃣ Setup Environment
•	Create .env files for both backend and frontend.
•	Backend should include: 
•	MONGO_URI=your_mongodb_url
•	JWT_SECRET=your_jwt_secret
3️⃣ Run the App
# Start the backend
cd backend && pnpm dev

# In a separate terminal, start the frontend
cd client && pnpm dev
________________________________________
🧩 Future Plans
Feature	Description
🌗 Dark/Light Theme	Add toggle with Tailwind’s darkMode
🧑⚕️ Role-Based Access
Admin-only dashboard and post approvals
🖼 Cover Image Upload	Integrate Cloudinary for post images
🌍 Localization	Add i18n support for multiple languages
🧠 Rich Text Editor	Enhance UX with TipTap or Quill

