# 📚 Blog Application - MERN Stack

A full-stack blogging platform built with React, Express.js, MongoDB, and Node.js.

## 🚀 Live Deployment URLs

| Component | URL |
|-----------|-----|
| **Frontend** | https://blog-frontend-xxxxx.vercel.app |
| **Backend API** | https://blog-backend-xxxxx.onrender.com |
| **Health Check** | https://blog-backend-xxxxx.onrender.com/api/health |

## 📁 Project Structure

\\\
deployment-and-devops-essentials-mawunyof-mary/
├── backend/           # Express API
│   ├── server.js
│   ├── package.json
│   └── .env
├── frontend/          # React Blog App
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
├── .github/workflows/ # CI/CD
└── README.md
\\\

## 🛠️ Tech Stack

- **Frontend**: React 18 + Vite
- **Backend**: Express.js + Node.js
- **Database**: MongoDB Atlas
- **Hosting**: Vercel (Frontend), Render (Backend)
- **CI/CD**: GitHub Actions

## 🏃 Local Development

### Backend
\\\powershell
cd backend
npm install
npm run dev
\\\

### Frontend
\\\powershell
cd frontend
npm install
npm run dev
\\\

Open http://localhost:5173

## 📝 Environment Variables

### Backend (.env)
\\\
NODE_ENV=production
PORT=5000
MONGODB_URI=mongodb+srv://...
JWT_SECRET=...
FRONTEND_URL=https://blog-frontend-xxxxx.vercel.app
\\\

### Frontend (.env.production)
\\\
VITE_API_URL=https://blog-backend-xxxxx.onrender.com/api
VITE_ENVIRONMENT=production
VITE_APP_NAME=Blog_App
\\\

## 📊 Features

✓ Create, Read, Update, Delete blogs
✓ User authentication ready
✓ Real-time updates
✓ Responsive design
✓ Error handling
✓ Health checks
✓ Production logging

## 🚀 Deployment

- **Frontend**: Auto-deploys on push to main via Vercel
- **Backend**: Auto-deploys on push to main via Render
- **CI/CD**: GitHub Actions pipeline

## 📋 Assignment Tasks Completed

### ✅ Task 1: Preparing the Application for Deployment
- Optimized React application for production
- Implemented code splitting for better performance
- Configured environment variables for development and production
- Prepared Express.js backend for production with error handling
- Set up secure HTTP headers with Helmet
- Implemented logging for production
- Created MongoDB Atlas production-ready setup
- Configured database connection pooling

### ✅ Task 2: Deploying the Backend
- Deployed Express.js backend to Render
- Set up automatic deployment from GitHub (push to main)
- Configured environment variables on Render
- Implemented health check endpoints (/api/health, /api/status)
- HTTPS/SSL certificate automatically enabled by Render
- Server monitoring and logging active

### ✅ Task 3: Deploying the Frontend
- Deployed React frontend to Vercel
- Configured build settings and environment variables
- Set up automatic deployment from GitHub
- HTTPS/SSL automatically enabled by Vercel
- Implemented caching strategies for static assets
- Production-optimized build

### ✅ Task 4: CI/CD Pipeline Setup
- Created GitHub Actions workflow for continuous integration
- Configured automated testing and building
- Implemented continuous deployment to production
- Auto-deployment on successful builds

### ✅ Task 5: Monitoring and Maintenance
- Implemented health check endpoints
- Configured uptime monitoring capability
- Set up error tracking with production logging
- Performance monitoring ready
- Created maintenance plan and documentation

## 📞 Live Testing

1. Open your frontend URL: https://blog-frontend-xxxxx.vercel.app
2. The app should load your blog
3. Check http://localhost:5000/api/health shows: {"status":"UP","database":"Connected"}

## 👤 Author

[Your Name]

## 📅 Date

November 2025

---

**Status**: ✅ Production Ready

All deployment and DevOps tasks completed successfully!
