# CampQuest

CampQuest is a full-stack camping gear rental and sales platform.

It is designed to demonstrate a complete e-commerce flow with camping gear rentals, product sales, admin controls, and user support functions.

Key features:
- User registration/authentication (login, register, forgot/reset password)
- Product catalog (rental and sales items)
- Cart and checkout workflow
- Order management (rental orders and sales orders)
- Blog posts and user interactions (comments, likes, rating)
- Support ticket system and admin dashboard
- Admin product/category management and analytics

## Project structure

- `camp-quest-back-end`: Express API + MongoDB data models + auth + controllers
- `camp-quest-front-end`: React UI with Vite + context + components + pages
- `public/uploads`: image storage for product/blog uploads

## Why read this project

This repo is ideal to learn about building a real-world Node/React app with:
- Clean separation of frontend/backend responsibilities
- REST API design and route organization
- Mongoose schema modeling and MongoDB operations
- JWT auth middleware and role-based access control
- File upload and server-side file validation
- Form validation, error handling, and form UX flows

## Repo
Remote URL: `https://github.com/YashodhRalapanawa/CampQuest.git`

## Setup

### Back-end

```bash
cd camp-quest-back-end
npm install
npm run dev
```

### Front-end

```bash
cd camp-quest-front-end
npm install
npm run dev
```

## Git

Already ignored:
- `node_modules/`
- `camp-quest-back-end/node_modules/`
- `camp-quest-front-end/node_modules/`
- `.env` and `camp-quest-back-end/.env`

## Push to GitHub

```bash
git init
git remote add origin https://github.com/YashodhRalapanawa/CampQuest.git
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

> If the repo is already initialized, use `git remote set-url origin https://github.com/YashodhRalapanawa/CampQuest.git` instead.
