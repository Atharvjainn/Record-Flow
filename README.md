# 🎥 RecordFlow — Modern Screen & Camera Recording Platform

RecordFlow is a **sleek, high-performance video recording and sharing platform** that enables creators to capture, upload, and manage professional-quality screen and camera recordings with zero friction.

It is built using a **modern TypeScript-first full-stack web stack**, focusing on real-time recording capabilities, seamless cloud storage, and elegant user experience.

---

## 🚀 Live Demo

🔗 https://cicid.vercel.app/

---

## ✨ Features

- 🎬 Multi-mode recording (camera-only and screen-only)
- ⏸️ Recording controls with pause/resume functionality
- 📤 Instant uploads to Cloudinary with auto-generated thumbnails
- 🔐 OAuth (Google & GitHub) + email/password authentication
- 👁️ Public/private visibility controls
- 🎨 Smooth animations with Framer Motion
- 📊 Video dashboard with filtering and sorting
- 🔗 One-click link sharing
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

### 🖥️ Frontend

- Next.js 15 (**TypeScript**)
- React 19
- Framer Motion
- Zustand
- Tailwind CSS
- MediaRecorder API
- Web Audio API

### ⚙️ Backend

- Next.js API Routes
- Better Auth
- Prisma
- PostgreSQL (Neon)
- Cloudinary
- REST APIs

---

## 🧑‍💻 Getting Started (Local Setup)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/recordflow.git
cd recordflow
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Set Environment Variables

Create a `.env` file in the root directory:

```bash
# Database
DATABASE_URL=<YOUR_POSTGRESQL_CONNECTION_STRING>

# Better Auth
BETTER_AUTH_SECRET=<RANDOM_SECRET_STRING>
BETTER_AUTH_URL=http://localhost:3000

# OAuth Providers
GITHUB_CLIENT_ID=<YOUR_GITHUB_CLIENT_ID>
GITHUB_CLIENT_SECRET=<YOUR_GITHUB_CLIENT_SECRET>
GOOGLE_CLIENT_ID=<YOUR_GOOGLE_CLIENT_ID>
GOOGLE_CLIENT_SECRET=<YOUR_GOOGLE_CLIENT_SECRET>

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_CLOUD_NAME>
NEXT_PUBLIC_CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_API_SECRET>
NEXT_PUBLIC_CLOUDINARY_UPLOAD_PRESET=<YOUR_CLOUDINARY_UPLOAD_PRESET>

# App
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

### 4️⃣ Set Up Database

```bash
# Generate Prisma Client
npx prisma generate

# Run migrations
npx prisma migrate deploy
```

### 5️⃣ Run the Project

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 👨‍💻 Author

**Atharv Jain**

---

## 📄 License

Distributed under the **MIT License**.
