# Oral Dental Care

Modern, gentle, and professional dental clinic website built with HTML5, CSS3, and Vanilla JavaScript.

## Deployment Guide

### Overview
Welcome to the Oral Dental Care deployment guide. This document provides clear, step-by-step instructions for publishing the modern dental clinic website live to Vercel, Netlify, or GitHub Pages with a public URL. The project is a lightweight, high-performance static site (HTML5, CSS3, vanilla JavaScript) with zero build steps required.

### Vercel Deployment
To deploy Oral Dental Care to Vercel with automatic SSL and global CDN:
1. Push your repository to GitHub, GitLab, or Bitbucket.
2. Log in to the [Vercel Dashboard](https://vercel.com) and click **Add New > Project**.
3. Import your Oral Dental Care repository.
4. Leave build settings as default (static site, root directory `./`).
5. Click **Deploy** to publish instantly with a live public URL.
Alternatively, use the Vercel CLI: run `vercel` in your project terminal and follow the interactive prompts.

### Netlify Deployment
To deploy Oral Dental Care to Netlify:
1. Log in to [Netlify](https://netlify.com) and select **Add new site > Import an existing project**.
2. Connect your Git provider and select the Oral Dental Care repository.
3. Keep publish settings as default (leave build command empty, publish directory: `.` or root).
4. Click **Deploy site**.
Alternatively, use the Netlify CLI: install via `npm install netlify-cli -g`, run `netlify login`, and run `netlify deploy --prod`.

### GitHub Pages Deployment
To host Oral Dental Care for free via GitHub Pages:
1. Push your project code to a public GitHub repository.
2. Navigate to repository on GitHub and click **Settings**.
3. In the left sidebar, click **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Set branch to `main` (or `master`) and folder to `/ (root)`, then click **Save**.
6. Your live public URL will be generated at `https://[GitHub-Username].github.io/[Repository-Name]/`.
