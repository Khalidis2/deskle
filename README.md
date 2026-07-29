# Deskle

A daily word-guessing game for the office break. Pick 3, 4, or 5 letters and guess the word of the day in 6 tries.

Single self-contained file — no build step, no dependencies. `index.html` is the entire site.

## Deploy this (no coding required)

**1. Put this on GitHub**
- Go to [github.com/new](https://github.com/new) and create a new repository (e.g. `deskle`)
- On the new repo's page, click **"uploading an existing file"**
- Drag `index.html` and this `README.md` into the browser window
- Click **Commit changes**

**2. Deploy on Vercel (free)**
- Go to [vercel.com/new](https://vercel.com/new)
- Sign in with your GitHub account
- Click **Import** next to the `deskle` repository
- Leave all settings as default (it's a static site, Vercel will detect it automatically)
- Click **Deploy**

Vercel gives you a free `.vercel.app` URL immediately. Once you buy your domain, add it under **Project Settings → Domains** in Vercel and follow the DNS instructions it shows you.

Every time this `index.html` is updated and re-uploaded to GitHub, Vercel automatically redeploys the new version within seconds — no extra steps needed.
