# StudyFlow — Landing Page

A single-page marketing site for StudyFlow AI (static HTML/CSS/JS, no build step).

## Deploy to Vercel

1. Push this folder to a new GitHub repo:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
2. Go to https://vercel.com/new and import that GitHub repo.
3. Framework preset: choose **Other** (or leave it — Vercel auto-detects static sites).
   - Build command: none
   - Output directory: `./` (root)
4. Click **Deploy**. Vercel will give you a live URL in under a minute.

Every future push to `main` will auto-redeploy.

## Local preview

Just open `index.html` in a browser, or run:
```bash
npx serve .
```
