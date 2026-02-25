# My Weekly Log

A personal weekly blog built with Astro, deployed on Netlify.

## Getting Started

### Install dependencies
```bash
npm install
```

### Run locally
```bash
npm run dev
```

### Build for production
```bash
npm run build
```

---

## Writing a New Post

1. Create a new file in `src/pages/posts/` — e.g. `week-2.md`
2. Copy this template:

```markdown
---
layout: ../../layouts/Post.astro
title: "Week 2 — Your Title Here"
date: 2026-03-04
excerpt: "A short summary of this week."
built: true
read: true
did: true
---

## 🔨 What I Built

Write what you built or worked on this week.

## 📖 What I Read

Write what you read — books, articles, anything.

## ✦ What I Did

Write what you did — places, food, people, experiences.
```

3. Save the file. The homepage will automatically show the latest post.

---

## Deploying to Netlify

1. Push this folder to a GitHub repository
2. Go to [netlify.com](https://netlify.com) and sign up
3. Click **"Add new site" → "Import an existing project"**
4. Connect your GitHub repo
5. Netlify will auto-detect the build settings from `netlify.toml`
6. Click **Deploy** — your site will be live at a free `.netlify.app` URL!
