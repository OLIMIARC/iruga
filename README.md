# IRUGA — Where Serious Engineering Begins

Fabrication & Innovation Studio — Fort Portal, Western Uganda.

## Hosting on GitHub Pages (Free)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
- Click the **+** icon → **New repository**
- Name it exactly: `iruga` (or anything you want — this only matters for the free URL)
- Set it to **Public**
- Click **Create repository**

### Step 3 — Upload the file
- Click **Add file** → **Upload files**
- Upload `index.html`
- At the bottom, click **Commit changes**

### Step 4 — Enable GitHub Pages
- Go to your repo → **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Branch: `main`, folder: `/ (root)`
- Click **Save**

Your site will be live at:
`https://YOUR-USERNAME.github.io/iruga/`

---

## Pointing a Custom Domain at GitHub Pages

This is the recommended approach — professional, free hosting + your own domain.

### Buy a cheap domain
Good registrars for affordable domains:
- **Porkbun** (porkbun.com) — often under $10/yr, clean interface
- **Namecheap** (namecheap.com) — reliable, good prices
- **Cloudflare Registrar** (cloudflare.com) — sells at cost, no markup

Good domain ideas: `iruga.studio`, `iruga.co`, `irugastudio.com`  
`.studio` domains are often ~$10–15/yr and fit the brand perfectly.

### Connect the domain (after buying)

**1. In your domain registrar's DNS settings, add these records:**

| Type  | Name | Value                    |
|-------|------|--------------------------|
| A     | @    | 185.199.108.153          |
| A     | @    | 185.199.109.153          |
| A     | @    | 185.199.110.153          |
| A     | @    | 185.199.111.153          |
| CNAME | www  | YOUR-USERNAME.github.io  |

**2. In GitHub Pages settings:**
- Under **Custom domain**, type your domain (e.g. `iruga.studio`)
- Click **Save**
- Wait 10–30 minutes for DNS to propagate
- Check **Enforce HTTPS** once it appears (gives you the padlock — free SSL)

### Is GitHub Pages respectable?

Yes — completely. GitHub Pages is used by:
- Major open source projects (Bootstrap, Vue.js, React)
- Portfolios of engineers at top companies worldwide
- Startups as landing pages before they need a server

What matters is the domain on the address bar. Once you point `iruga.studio` at it, nobody knows or cares that it's GitHub Pages. The site loads fast (served from GitHub's CDN globally), has free HTTPS, and has essentially 100% uptime. For a studio site that doesn't need a backend, it's the correct choice.

---

## Files

```
iruga-site/
└── index.html   ← the entire site (single file)
```
