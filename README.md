# Ayush Gupta | Portfolio

A modern portfolio website built with Next.js, Tailwind CSS, and motion-driven UI to showcase software engineering projects, skills, and experience.

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16.3.0-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind-4-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

## Overview

This project is a personal portfolio for Ayush Gupta, designed to present:

- Software engineering expertise
- Technical skills across frontend, backend, and AI tooling
- Key product projects and experience
- Contact and resume download options

The site is built as a responsive single-page experience with animated sections and a clean, premium visual style.

## Highlights

- Modern landing page with strong visual hierarchy
- Smooth motion effects and interactive cards
- Project showcase for AI and full-stack products
- Skills sections grouped by technology domains
- Resume CTA and contact interaction
- Responsive layout for desktop, tablet, and mobile

## Tech Stack

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- Framer Motion
- React Icons
- Nodemailer for contact handling

## Project Structure

```bash
.
├── README.md
├── frontend/
│   ├── app/
│   │   ├── api/
│   │   │   └── contact/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── Experience.tsx
│   │   ├── Home.tsx
│   │   ├── Projects.tsx
│   │   ├── Skills.tsx
│   │   └── layouts/
│   │       ├── Footer.tsx
│   │       └── Navbar.tsx
│   ├── public/
│   ├── package.json
│   ├── next.config.ts
│   ├── postcss.config.mjs
│   ├── tsconfig.json
│   └── eslint.config.mjs
└──
```

## Features

### Portfolio Experience
- Hero section with name, role, and summary
- Animated introduction with engaging motion design
- CTA buttons for resume and contact

### Skills Showcase
- Structured categories for:
  - Languages and core CS
  - Frontend and backend
  - AI and developer tools
  - Databases and deployment

### Project Highlights
- AI-driven product case studies
- Full-stack project examples
- Live and GitHub links for selected work

### Contact Integration
- Contact API route for portfolio form submissions
- Email sending support with Nodemailer

## Getting Started

1. Clone the repository

```bash
git clone <your-repository-url>
cd "Ayush tech"
```

2. Install frontend dependencies

```bash
cd frontend
npm install
```

3. Run the development server

```bash
npm run dev
```

4. Open the app in your browser

```bash
http://localhost:3000
```

## Production Build

```bash
cd frontend
npm run build
npm run start
```

## Scripts

```bash
npm run dev     # start local development server
npm run build   # create production build
npm run start   # run production build locally
npm run lint    # run ESLint checks
```

## Deployment

This app is ready for deployment on platforms such as:

- Vercel
- Netlify
- Render
- Railway

## Contact

For collaboration, opportunities, or inquiries:

- GitHub: https://github.com/theayushgupta21  
- LinkedIn: https://www.linkedin.com/in/theayushgupta21/

## License

This project is for personal portfolio use and is not intended for redistribution without permission.

---

Built with purpose, creativity, and a strong focus on product-driven engineering.
