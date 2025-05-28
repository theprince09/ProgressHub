# ProgressHub
Track. Learn. Grow. Your developer journey in one place.

progresshub/
├── backend/
│   ├── config/
│   │   └── db.js                # MongoDB connection
│   ├── controllers/
│   │   ├── authController.js
│   │   └── userController.js
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   └── errorHandler.js
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── userRoutes.js
│   ├── .env
│   ├── server.js               # Entry point
│   └── package.json
├── node_modules/
├── public/
│   ├── index.html
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── Navbar.jsx
│   │   └── PrivateRoute.jsx
│   ├── context/
│   │   └── AuthContext.jsx
│   ├── features/
│   │   ├── certificates/
│   │   │   ├── CertificateCard.jsx
│   │   │   └── certificateService.js
│   │   ├── github/
│   │   │   ├── GithubStats.jsx
│   │   │   └── githubService.js
│   │   ├── leetcode/
│   │   │   ├── LeetCodeStats.jsx
│   │   │   └── leetcodeService.js
│   ├── hooks/
│   │   └── useAuth.js
│   ├── pages/
│   │   ├── Dashboard.jsx
│   │   ├── Landingpage.jsx
│   │   └── Login.jsx
│   ├── services/
│   │   ├── api.js              # Axios instance
│   │   └── authService.js
│   ├── utils/
│   │   └── formatDate.js
│   ├── styles/
│   │   ├── App.css
│   │   ├── index.css
│   │   └── styles.css
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── package.json
├── vite.config.js
└── README.md
