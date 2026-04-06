[README.md](https://github.com/user-attachments/files/26517688/README.md)
[README.md](https://github.com/user-attachments/files/26517688/README.md)
# English Box — Teacher Aimee

A class scheduling app for online English lessons.

---

## ✏️ Before you deploy — customise these 3 things

Open `src/App.jsx` and edit the top of the file:

```js
const TEACHER_PASSWORD = "Mimi7600!";          // ← choose a private password
const PAYMENT_LINK     = "https://go.hotmart.com/J104820713V?dp=1"; // ← your PayPal / Stripe link
```

---

## 🚀 Deploy to Vercel in 5 steps (free)

### Step 1 — Install Node.js
Download and install from https://nodejs.org (choose the LTS version).

### Step 2 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 3 — Upload this project to GitHub
1. Go to https://github.com/new and create a new **public** repository called `english-box`.
2. On your computer, open a terminal in this folder and run:

```bash
npm install          # installs dependencies (creates node_modules/)
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/english-box.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

### Step 4 — Deploy on Vercel
1. Go to https://vercel.com and sign up with your GitHub account.
2. Click **"Add New Project"**.
3. Import your `english-box` repository.
4. Leave all settings as default — Vercel detects Vite automatically.
5. Click **Deploy**.

In about 60 seconds you'll get a live URL like:
`https://english-box.vercel.app`

### Step 5 — Share with students!
Send them the URL. Done. 🎉

---

## 🌐 Optional: custom domain

1. Buy a domain (e.g. `englishbox.com`) at https://namecheap.com (~$12/yr).
2. In Vercel → your project → **Settings → Domains**, add your domain.
3. Follow Vercel's instructions to point your domain there (takes ~10 min).

---

## ⚠️ Important limitation

This app stores all data in the **browser's localStorage**.
This means each device/browser has its own separate data — if a student books on their phone, you won't see it on your laptop dashboard.

**When you're ready to fix this**, ask for the Supabase database upgrade, which syncs all data in real time across all devices for free.

---

## 🔧 Run locally (optional, for testing)

```bash
npm install
npm run dev
```

Then open http://localhost:5173 in your browser.
