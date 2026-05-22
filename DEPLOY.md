# Publish Ahmed's Portfolio Online

Follow **one** method below. After publishing, your link will work on any phone, laptop, or tablet.

---

## Option A — GitHub Pages (recommended)

Your GitHub: [github.com/ahmedverse-asynx](https://github.com/ahmedverse-asynx)

### Steps

1. Install [Git for Windows](https://git-scm.com/download/win) if you don't have it.
2. On GitHub, click **New repository**
   - Name: `portfolio` (or `ahmedverse-asynx.github.io` for a shorter URL)
   - Public → Create
3. Open PowerShell in this folder (`portfolio`) and run:

```powershell
git init
git add .
git commit -m "Publish Ahmed's portfolio"
git branch -M main
git remote add origin https://github.com/ahmedverse-asynx/portfolio.git
git push -u origin main
```

4. On GitHub: **Settings → Pages**
   - Source: **Deploy from branch**
   - Branch: `main` → folder `/ (root)` → Save
5. Wait 1–2 minutes. Your live link:

**https://ahmedverse-asynx.github.io/portfolio/**

(If you named the repo `ahmedverse-asynx.github.io`, the link is **https://ahmedverse-asynx.github.io/**)

---

## Option B — Netlify Drop (no Git, fastest)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `portfolio` folder onto the page
3. Netlify gives you a link like `https://random-name.netlify.app`
4. Optional: **Site settings → Domain management → Options → Edit site name** to get something like `https://ahmed-asim.netlify.app`

---

## Option C — Vercel

1. Go to [vercel.com](https://vercel.com) and sign up with GitHub
2. **Add New Project** → import your `portfolio` repo (after Option A), or upload via CLI

---

## Share your link

Once live, share the URL on:
- LinkedIn
- GitHub profile
- Resume / CV
- Email signature
