# CleanYourTab — Official Website & Deployment Guide

> **Transform any Android tablet with Google Antigravity AI.**  
> 100% Free · No Root Required · 1-Click Reversible

---

## 🚀 Quick Local Preview

You can preview the website locally on your computer with a single command:

```bash
cd /Users/azmathmohammed/.gemini/antigravity/scratch/cleanyourtab
python3 -m http.server 8080
```

Then open your browser and go to:
👉 **`http://localhost:8080`**

---

## 🌐 How to Host for FREE ($0/Month)

### Method 1: GitHub Pages (Recommended & Easiest)

1. Create a new public repository on GitHub named `cleanyourtab` (or `cleanyourtab.github.io`).
2. In your terminal, initialize and push this folder:
   ```bash
   cd /Users/azmathmohammed/.gemini/antigravity/scratch/cleanyourtab
   git init
   git add .
   git commit -m "Initial commit for CleanYourTab website"
   git branch -M main
   git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/cleanyourtab.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings > Pages**.
4. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
5. Your website will be live in ~60 seconds at:
   👉 **`https://<YOUR_GITHUB_USERNAME>.github.io/cleanyourtab/`**

---

### Method 2: Vercel (Fastest Edge CDN)

1. Go to [vercel.com](https://vercel.com) and log in with GitHub (100% free).
2. Click **Add New > Project** and select your `cleanyourtab` repository.
3. Keep default settings and click **Deploy**.
4. You get an instant worldwide edge URL: `https://cleanyourtab.vercel.app`.

---

### Custom Domain (Optional)
If you buy a domain (like `cleanyourtab.com` or `cleanyourtab.org` for ~$10/year):
1. In GitHub Pages or Vercel settings, type your custom domain.
2. In your domain registrar (GoDaddy, Namecheap, Cloudflare), set the CNAME or A records as instructed.
3. Free automatic SSL/HTTPS will be issued automatically.

