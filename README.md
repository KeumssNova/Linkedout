# LinkedOut

LinkedOut is a **custom media-oriented Linktree alternative** built for internal use.  
It provides advanced features like **custom backgrounds, media embeds, newsletter collection, and analytics** – optimized for artists and media projects.

---

## 🚀 Tech Stack

- **Frontend**: React + Vite + TailwindCSS (deployed on Vercel)  
- **Backend**: Node.js + Express + MongoDB (deployed on Render)  
- **Database**: MongoDB Atlas  

---

## 📂 Project Structure

linkedout/
│── backend/ # API & server
│ ├── src/
│ │ ├── index.js # Express app entry
│ │ ├── routes/ # API routes
│ │ ├── controllers/ # Logic for each route
│ │ ├── models/ # MongoDB models (User, Link, Stat, Email)
│ │ ├── utils/ # Helpers (analytics, parsing, etc.)
│ └── package.json

│── frontend/ # React app
│ ├── src/
│ │ ├── pages/ # Page components (ProfilePage, Dashboard)
│ │ ├── components/ # UI components (LinkButton, StatsChart, Navbar)
│ │ ├── services/ # API calls (axios)
│ │ ├── App.jsx
│ │ └── main.jsx
│ └── package.json

│── README.md

yaml
Copier le code

---

## 🔧 Installation & Setup

### 1. Clone the repo
```bash
git clone https://github.com/your-username/linkedout.git
cd linkedout
```
2. Setup Backend

```bash
cd backend
yarn install
cp .env.example .env   # add your MongoDB URI, port, etc.
yarn dev
```
3. Setup Frontend
```bash
Copier le code
cd frontend
yarn install
yarn dev
```

🌐 Deployment
Frontend (React + Vite) → Vercel

Backend (Express API) → Render

Database → MongoDB Atlas

✨ Features
 Profile pages with avatar, bio, and link list.

 Custom backgrounds (image or video).

 Light/Dark mode toggle.

 Media embeds (YouTube, Spotify, TikTok, etc).

 Newsletter collection (store emails in DB).

 Click tracking & analytics (stats dashboard).

 Admin dashboard for managing links, design, and analytics.

📌 Roadmap
 Add authentication (JWT or session-based).

 Support multiple profiles (multi-user system).

 Advanced analytics (geo, device type, trends).

 SaaS version (plans, Stripe payments).
