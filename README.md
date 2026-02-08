# 🏡 Real Estate Web Application

A modern full-stack **Real Estate Web Application** built using **Vite + React + TypeScript + Tailwind CSS**, with a separate backend server setup.  
This project provides a clean UI, fast performance, and a scalable client–server structure.

---

## 🚀 Features

- Responsive Real Estate UI  
- Built with **React + Vite + TypeScript**  
- Styled using **Tailwind CSS**  
- Backend server integration  
- Client + Server folder structure  
- Netlify deployment support  

---

## 📂 Project Structure

```

Real Estate/
│
├── client/          # Frontend (React + Vite)
├── server/          # Backend Server
├── public/          # Static assets
├── shared/          # Shared components/utilities
│
├── package.json
├── vite.config.ts
├── tailwind.config.ts
├── netlify.toml
└── README.md

````

---

## ⚙️ Requirements

Before running the project, install:

- **Node.js** (v16 or higher)
- **npm** or **pnpm**

Download Node.js: https://nodejs.org/

---

## 🛠 Installation

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/your-username/real-estate-app.git
cd real-estate-app
````

---

### 2️⃣ Install Dependencies

Run this in the root folder:

```sh
npm install
```

---

## ▶️ Running the Project

This project has both **frontend** and **backend**.

---

### ✅ Start Frontend (Client)

Open terminal:

```sh
cd client
npm install
npm run dev
```

Frontend will run at:

```
http://localhost:5173
```

---

### ✅ Start Backend (Server)

Open another terminal:

```sh
cd server
npm install
npm run dev
```

Backend will run at:

```
http://localhost:5000
```

---

## 🌐 Environment Variables

This project uses a `.env` file for configuration.

Example:

```env
VITE_API_URL=http://localhost:5000
```

Make sure `.env` is set correctly before running.

---

## 📦 Build for Production

To build the project:

```sh
npm run build
```

To preview production build:

```sh
npm run preview
```

---

## 🚀 Deployment

Netlify deployment is supported through:

* `netlify.toml`

You can directly deploy the frontend using Netlify.

---

## ⚠️ Important Note (GitHub Upload)

Do NOT upload `node_modules`.

Make sure `.gitignore` includes:

```
node_modules
.env
dist
```

---

## 📄 License

This project is licensed under the MIT License.

```
```
