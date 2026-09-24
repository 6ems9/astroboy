# AstroBoy | Folio VCard

A clean and modern personal portfolio vCard built with pure Astro.

This project is fully powered by Astro — no React, Vue, or other UI framework. It’s designed to showcase a personal profile, resume, portfolio work, and contact details in a lightweight single-page layout.

## Features

- Pure Astro project
- Responsive portfolio layout
- About, Resume, Portfolio, and Contact sections
- Smooth scrolling and active nav state
- Easy content editing via data files
- Fast static build

## Getting Started

```bash
npm install
npm run dev
```

Open:

```bash
http://localhost:4321
```

## Build

```bash
npm run build
npm run preview
```

## Customize Content

Update your content in:

- src/data/about_resume.ts
- src/data/portfolio.ts

You can change:

- name, role, email, phone, and location
- about text and skills
- experience and education
- portfolio items and links
- social media URLs

## Project Structure

```bash
src/
├── data/
│   ├── about_resume.ts
│   └── portfolio.ts
├── pages/
│   └── index.astro
├── styles/
│   └── global.css
└── public/
```

## License

MIT
