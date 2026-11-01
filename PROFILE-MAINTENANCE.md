# GitHub Profile Launch & Maintenance

This file documents the intended public profile configuration for **harunhira69**. It is not rendered on the profile page; it exists as a maintenance reference.

## Positioning

**Primary identity:** Full Stack Developer · Backend Engineering

**Short GitHub bio:**

> Full Stack Developer | Backend Engineering | TypeScript, Node.js, React & PostgreSQL

NestJS should remain visible as an actively explored/used backend technology without implying senior-level specialization.

## Profile Design

- The public profile is rendered from `harunhira69/README.md`; the separate `harunhira69-profile` repository is not the profile entry point.
- Use `assets/profile/hero.svg` for dark mode and `assets/profile/hero-light.svg` for light mode. Keep both variants consistent when updating the banner.
- Keep the introduction short, put selected projects before the toolkit, and use descriptive text links that work without third-party badge services.
- Prefer single-column project sections so the README remains readable on narrow screens.
- Keep implementation status explicit and describe concrete features rather than promising security, scalability, or production readiness.
- After banner or layout changes, check both themes and a narrow viewport. GitHub does not support arbitrary README CSS or JavaScript.

## Recommended Pinned Repositories

Use this order when configuring profile pins:

1. `gearup-backend`
2. `prisma_press`
3. `football_ticket_booking`
4. `PawMart-client`
5. `portfolio-harun`

Keep the sixth slot empty until a stronger public backend/NestJS project is ready.

## Repository Metadata

### gearup-backend

**Description**

> TypeScript backend for a role-based gear rental platform with Prisma, PostgreSQL, JWT authentication, Stripe payments, provider workflows, and admin operations.

**Topics**

`typescript` `nodejs` `express` `prisma` `postgresql` `rest-api` `jwt-authentication` `stripe` `zod` `rental-platform` `backend` `vercel`

### prisma_press

**Description**

> TypeScript publishing backend with JWT auth, post workflows, Prisma/PostgreSQL persistence, profile management, and Stripe subscriptions.

**Topics**

`typescript` `nodejs` `express` `prisma` `postgresql` `jwt` `stripe` `rest-api` `blog-api` `backend`

### football_ticket_booking

**Description**

> Football Ticket Booking System — relational database design, ERD modeling, constraints, joins, and SQL queries with PostgreSQL.

**Topics**

Keep the existing database-focused topics: `postgresql`, `sql`, `database-design`, `relational-databases`, `erdiagram`, `joins`, `subquery`.

### PawMart-client

**Description**

> Full-stack pet adoption and supplies marketplace built with React, Firebase authentication, Express, and MongoDB.

**Topics**

`react` `vite` `firebase` `mongodb` `express` `tailwindcss` `full-stack` `pet-adoption` `marketplace`

### PawMart-server

**Description**

> Express and MongoDB API for PawMart with products, listings, orders, and Firebase Admin token verification.

**Topics**

`nodejs` `express` `mongodb` `firebase-admin` `rest-api` `backend` `pawmart`

### portfolio-harun

**Description**

> Personal developer portfolio built with React, GSAP, Locomotive Scroll, Sass, and Vite.

**Topics**

`react` `gsap` `vite` `sass` `portfolio` `developer-portfolio` `frontend` `animation`

## Profile Links

- Portfolio: https://portfolio-harun-liard.vercel.app/
- LinkedIn: https://www.linkedin.com/in/harunmern/
- Resume: https://drive.google.com/drive/folders/15wQGbXdHvG8Ml9yj5-YluGcUiWlWCvKd
- Email: harunabhi4@gmail.com

## Publishing and Maintenance

- The README is published on the GitHub profile when the changes reach this repository's default branch, `main`.
- Validate both banner themes, local asset references, and the README at desktop and narrow widths before publishing.
- Keep account bio, pins, and project repository metadata aligned with the recommendations above; these are separate GitHub settings.
- The résumé link currently opens a Google Drive folder. Keep the link label explicit, or replace it with a verified direct résumé link when available.
- After publishing, verify the default-branch commit and the rendered public profile.

## Accuracy Rules

- Do not present PrismaPress comments as completed until its controller/service logic is implemented.
- Do not present PawMart server authentication as protecting every sensitive endpoint until server-side authorization is expanded.
- Keep NestJS positioned as active project work/exploration while the strongest NestJS marketplace repository remains private.
- Update featured-project wording whenever implementation status materially changes.
