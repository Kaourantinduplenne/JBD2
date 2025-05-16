# DeeJayBD

A document management application for offshore rigs, allowing navigation by rig and department, and PDF access (view/download).

## 🔐 Admin Access

To enable Admin Mode for uploading new PDFs:
- Click "Enter Admin Mode"
- Enter password: `admin123`

## 🛠 Tech Stack

- React (with Hooks)
- Vite (for fast bundling)
- Lucide Icons
- Tailwind-ready (UI is compatible)

## 📁 Folder Structure

- `/src` – React code (App.jsx is the main component)
- `index.html` – now in the root as required by Vite

## 🚀 Running Locally

```bash
npm install
npm run dev
```

## 🌐 Deploying on Vercel or Netlify

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com/) or [netlify.com](https://netlify.com/)
3. Import your repo
4. Set build command: `npm run build`
5. Set output directory: `dist`
