# User Authentication App 🔐

A simple user authentication system built with **Node.js**, **Express**, **MongoDB**, and **Mongoose**. This project features **password hashing** with Bcrypt, **JWT-based authentication**, and **cookie management**.

---

## 🚀 Features

- User Registration with secure password hashing 🔐
- Login with JWT token generation and cookie storage 🍪
- Logout functionality
- EJS templating for frontend rendering


---

## 🧰 Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** Bcrypt for password hashing, JWT for token management
- **Frontend:** EJS templating engine
- **Middleware:** Cookie-parser

---

## 🗂 Folder Structure

- AUTH/
- ├── models/
- │   └── user.js              # Mongoose User schema
- ├── node_modules/            # Installed dependencies (ignored by Git)
- ├── public/                  # Static assets
- │   ├── images/              # Image files
- │   ├── javascripts/         # JavaScript files
- │   └── stylesheets/
- │       └── style.css        # Custom CSS styles
- ├── views/                   # EJS templates
- │   ├── index.ejs            # Homepage view
- │   └── login.ejs            # Login view
- ├── .gitignore               # Ignores node_modules, etc.
- ├── app.js                   # Main server file
- ├── package.json             # Project metadata and dependencies
- └── package-lock.json        # Exact dependency tree


