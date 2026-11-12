# B Sankeerth Rao — Developer Portfolio

A responsive, single-page developer portfolio built with semantic HTML5, TailwindCSS, and ES6+ JavaScript.

## Features

- **Mobile-First Responsive Layout**: Flexbox and CSS Grid sections adapting seamlessly across mobile, tablet, and desktop viewports.
- **Dark / Light Theme Toggle**: Persistent theme preference stored in `localStorage`.
- **Interactive Skills Filter**: Filter technical skills across Languages, Core CS, Databases, and Tools & Soft Skills.
- **Project Modal Popups**: Detailed architecture, tech stack, and implementation highlights for *Blood Bank Management System* and *Mini Code Mentor*.
- **Smooth Scrolling & Mobile Drawer**: Accessible navigation with keyboard (`Escape`) support.

## Tech Stack

- **HTML5**: Semantic landmarks (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- **CSS3 / TailwindCSS**: Utility-first responsive styling and dark mode
- **JavaScript (ES6+)**: DOM rendering, modal state management, filtering, and clipboard copy

## Quick Deployment

### Option 1: GitHub Pages
1. Create a public repository on GitHub (e.g., `portfolio` or `25eg105m09-cyber.github.io`).
2. Push `index.html` and `README.md` to the `main` branch:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial portfolio release"
   git branch -M main
   git remote add origin https://github.com/25eg105m09-cyber/portfolio.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Build and deployment**, select **Deploy from a branch** (`main` / `/ (root)`), and save.

### Option 2: Vercel
1. Import the GitHub repository in [Vercel](https://vercel.com/new) (or run `npx vercel --prod` in this folder).
2. Keep the default static site settings (no build command needed) and click **Deploy**.
