
# 🧠 Task Management System

A full-stack Task Management System for small teams, with user authentication, task assignments, and a personalized dashboard.

## 🔧 Tech Stack

- **Frontend**: Next.js
- **Backend**: Node.js + Express/NestJS
- **Database**: MongoDB (Mongoose)
- **Deployment**: Frontend on Vercel, Backend on Render
- **Auth**: JWT-based authentication
- **Extras**: Notifications, Filtering, RBAC (optional)

---

## 🚀 Live Demo

- 🔗 Frontend: [your-vercel-link]
- 🔗 Backend: [your-render-link]
- 🔗 GitHub Repo: [your-github-link]

---

## 📁 Project Structure


---

## ✅ Features

### Authentication

- Register/Login using email & password
- JWT stored securely in local storage
- Auth-protected routes (dashboard, task pages)

### Task Management

- Create, Read, Update, Delete tasks
- Attributes: Title, Description, Due Date, Priority, Status
- Assign to other team members

### Dashboard

- View:
  - Tasks assigned to you
  - Tasks you created
  - Overdue tasks

### Team Collaboration

- Assign tasks to teammates
- Notifications when tasks are assigned

### Search & Filter

- Search by title/description
- Filter by status, priority, due date

---

## 🌐 Deployment Steps

### Backend (Render)

1. Push your backend code to GitHub.
2. Go to [https://render.com](https://render.com), create a new Web Service.
3. Choose your repo → Select Node.js → Set environment variables:
   - `MONGODB_URI`
   - `JWT_SECRET`
4. Click **Deploy**.

### Frontend (Vercel)

1. Push your frontend code to GitHub.
2. Go to [https://vercel.com](https://vercel.com), import GitHub repo.
3. Set environment variable:
   - `NEXT_PUBLIC_API_URL=https://your-backend-url.onrender.com/api`
4. Click **Deploy**.

---

## ⚙️ How to Run Locally

### Backend

```bash
cd backend
npm install
npm run dev
