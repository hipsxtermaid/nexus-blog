# NEXUS — Bold News & Stories Blog

A fully functional blog/news site with a Reader UI and Admin UI, built with React + Vite. All data persists via localStorage.

## Quick Start
```bash
npm install
npm run dev
```
Open http://localhost:5173

## Admin Login
URL: /admin/login
Default password: admin123

## Routes
### Reader
- / → Landing page
- /blog → All stories + search/filter
- /blog/:id → Full article reader
- /contact → Contact form

### Admin
- /admin/dashboard → Stats overview
- /admin/posts → Manage all posts
- /admin/posts/new → Create post
- /admin/messages → Read contact messages
- /admin/settings → Site config, password, categories

## Build
```bash
npm run build
```
Deploy the dist/ folder to Netlify, Vercel, or any static host.
