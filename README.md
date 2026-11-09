# Wanderly: Travel Company Homepage

A responsive, single-page homepage for a fictional travel company, built with **Astro**, plain CSS and a little vanilla JavaScript.

**Live demo:** _add your Vercel link here_

## Features
- Sticky header with a mobile hamburger menu
- Hero, destinations, packages, benefits, call to action and footer sections
- Mobile-first responsive layout (375px / 768px / 1280px)
- Semantic HTML, alt text on images, SEO meta tags
- No UI libraries, no Tailwind, no external APIs

## Tech Stack
Astro, HTML5, CSS3 (variables, Grid, Flexbox), vanilla JavaScript, Google Fonts (Poppins and Inter)

## Getting Started
```bash
git clone https://github.com/YOUR-USERNAME/wanderly.git
cd wanderly
npm install
npm run dev
```
Open http://localhost:4321

## Build
```bash
npm run build
npm run preview
```

## Project Structure
```
src/
├── components/   one file per section
├── layouts/      shared HTML shell
├── pages/        index.astro assembles the page
└── styles/       global.css (variables and all styles)
public/images/    local images
```

## Images
Photos are from Unsplash/Pexels. Add your own to `public/images/` using the file names listed in the project.