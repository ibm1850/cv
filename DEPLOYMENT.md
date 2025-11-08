# How to Deploy Your Portfolio

Here are several easy ways to make your portfolio live on the internet:

## Option 1: GitHub Pages (Recommended - Free & Easy)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com) and sign up (if you don't have an account)

### Step 2: Create a New Repository
1. Click the "+" icon in the top right → "New repository"
2. Name it: `portfolio` or `iyed-portfolio` (or any name you like)
3. Make it **Public** (required for free GitHub Pages)
4. Check "Add a README file"
5. Click "Create repository"

### Step 3: Upload Your Files
1. Click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository → Click "Settings" tab
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"
6. Wait 1-2 minutes, then visit: `https://yourusername.github.io/portfolio`

**Your portfolio will be live at:** `https://yourusername.github.io/repository-name`

---

## Option 2: Netlify (Easiest - Free)

### Method A: Drag & Drop
1. Go to [netlify.com](https://netlify.com) and sign up (free)
2. Drag and drop your entire `cv` folder onto the Netlify dashboard
3. Your site is live instantly! You'll get a URL like: `https://random-name-123.netlify.app`
4. You can customize the site name in Site settings → Change site name

### Method B: GitHub Integration
1. Push your code to GitHub (follow Option 1, Steps 1-3)
2. Go to [netlify.com](https://netlify.com) and sign up
3. Click "Add new site" → "Import an existing project"
4. Connect to GitHub and select your repository
5. Click "Deploy site"
6. Your site auto-updates whenever you push changes to GitHub!

---

## Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com) and sign up
2. Click "Add New Project"
3. Import your GitHub repository (or drag & drop files)
4. Click "Deploy"
5. Your site is live! URL format: `https://your-project.vercel.app`

---

## Option 4: Cloudflare Pages (Free)

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com) and sign up
2. Click "Create a project"
3. Connect your GitHub repository or upload files
4. Click "Save and Deploy"
5. Your site is live!

---

## Quick Comparison

| Platform | Ease | Free | Custom Domain | Auto Deploy |
|----------|------|------|---------------|-------------|
| GitHub Pages | ⭐⭐⭐ | ✅ | ✅ | ✅ |
| Netlify | ⭐⭐⭐⭐⭐ | ✅ | ✅ | ✅ |
| Vercel | ⭐⭐⭐⭐ | ✅ | ✅ | ✅ |
| Cloudflare Pages | ⭐⭐⭐⭐ | ✅ | ✅ | ✅ |

---

## Adding a Custom Domain (Optional)

All platforms above support custom domains:
1. Buy a domain from: Namecheap, GoDaddy, Google Domains, etc.
2. In your hosting platform settings, add your custom domain
3. Update DNS records as instructed
4. Your portfolio will be at: `https://iyedbenmohamed.com` (or whatever you choose)

---

## Quick Start Commands (If using Git)

If you want to use Git from command line:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add GitHub remote (replace with your repository URL)
git remote add origin https://github.com/yourusername/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## Recommended: GitHub Pages + Netlify

**Best approach:**
1. Use GitHub to store your code (version control)
2. Use Netlify for hosting (easiest deployment)
3. Connect them together for automatic updates

This way, you get:
- ✅ Version control (GitHub)
- ✅ Easy deployment (Netlify)
- ✅ Free hosting
- ✅ Automatic updates when you push changes

---

## Need Help?

- **GitHub Pages Docs:** https://docs.github.com/en/pages
- **Netlify Docs:** https://docs.netlify.com
- **Vercel Docs:** https://vercel.com/docs

Your portfolio is ready to go live! 🚀

