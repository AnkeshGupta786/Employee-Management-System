# Employee-Management-System
A simple MERN (MongoDB, Express, React, Node.js) application for managing employee records—featuring full CRUD functionality and a clean, streamlined UI.


# 🚀 Features
✅ Create, Read, Update, and Delete employee records

Simplified UI with intuitive forms and data tables

Clear MERN folder structure for frontend and backend separation

Extensible foundation for adding features like search, filters, auth, and more

🛠 Tech Stack
Frontend: React, Axios, React Router

Backend: Node.js, Express

Database: MongoDB (via Mongoose)

Styling: CSS modules or Bootstrap (as per the repo)

REST API: JSON-based CRUD endpoints

# 📁 Folder Structure
graphql
Copy
Edit
/
├── backend/
│   ├── models/        # Mongoose schemas (e.g., Employee.js)
│   ├── routes/        # Express routes (CRUD operations)
│   ├── controllers/   # Controller logic
│   ├── config/        # DB config and environment variables
│   └── server.js      # Entry point for server
└── frontend/
    ├── public/
    ├── src/
    │   ├── components/  # Form, list, update components
    │   ├── pages/       # Views (e.g., Dashboard, AddEmployee)
    │   ├── services/    # API call wrappers (Axios)
    │   └── App.js       # Routes and layout
