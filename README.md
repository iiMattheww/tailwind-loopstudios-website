# Tailwind Loopstudios Website (Practice)

A small practice project recreating the Loopstudios landing page using
Tailwind CSS and Vite. This repository is intended for personal reference
and learning — a simple, responsive portfolio-style static site.

**Features**

-   **Responsive:** mobile and desktop images and layout using Tailwind.
-   **Modern tooling:** Vite for fast dev server and build.
-   **Simple structure:** easy to reuse and adapt for other practice projects.

**Quick Start**

Prerequisites: Node.js (16+ recommended) and npm.

Install and run the dev server (PowerShell):

```powershell
npm install
npm run dev
```

Build for production and preview the build:

```powershell
npm run build
npm run preview
```

**Project Structure**

-   `index.html` — main HTML file
-   `src/` — source files
    -   `src/style.css` — Tailwind / project styles
    -   `src/script/main.js` — small JS for the menu toggle
    -   `src/assets/images/` — image assets (mobile / desktop folders)
-   `public/` — static public assets
-   `vite.config.ts`, `package.json`, `LICENSE`, `README.md`

**Deploying to GitHub**

Create a repo on GitHub and push the project (example commands):

```powershell
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

You can host the site with GitHub Pages (enable in repo settings) or use
Vercel / Netlify for zero-config deployments.

**License**

This project includes a `LICENSE` file. Keep or change the license as you prefer.