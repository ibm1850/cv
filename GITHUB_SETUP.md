# Upload Your Portfolio to GitHub

Your repository is ready at: **https://github.com/ibm1850/cv.git**

Here are 3 ways to upload your files:

---

## Method 1: GitHub Web Interface (Easiest - No Git Required)

### Step 1: Upload Files
1. Go to your repository: https://github.com/ibm1850/cv
2. Click **"uploading an existing file"** (or the "Add file" button → "Upload files")
3. Drag and drop these 3 files:
   - `index.html`
   - `styles.css`
   - `script.js`
4. Scroll down and click **"Commit changes"**

### Step 2: Enable GitHub Pages
1. In your repository, click **"Settings"** tab (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select:
   - Branch: **main** (or master)
   - Folder: **/ (root)**
4. Click **"Save"**
5. Wait 1-2 minutes

### Step 3: View Your Live Site
Your portfolio will be live at:
**https://ibm1850.github.io/cv/**

---

## Method 2: GitHub Desktop (Easy GUI)

### Step 1: Install GitHub Desktop
1. Download from: https://desktop.github.com/
2. Install and sign in with your GitHub account

### Step 2: Clone Repository
1. Open GitHub Desktop
2. Click **"File"** → **"Clone repository"**
3. Go to **"URL"** tab
4. Paste: `https://github.com/ibm1850/cv.git`
5. Choose a local path (e.g., `C:\Users\PC\Desktop\cv-github`)
6. Click **"Clone"**

### Step 3: Copy Your Files
1. Copy these files from `C:\Users\PC\Desktop\cv\`:
   - `index.html`
   - `styles.css`
   - `script.js`
2. Paste them into the cloned folder: `C:\Users\PC\Desktop\cv-github\`

### Step 4: Commit and Push
1. In GitHub Desktop, you'll see the files listed
2. Write a commit message: "Initial portfolio commit"
3. Click **"Commit to main"**
4. Click **"Push origin"** (top right)

### Step 5: Enable GitHub Pages
Follow Step 2 from Method 1 above.

---

## Method 3: Command Line (If Git is Installed)

### Step 1: Install Git
1. Download from: https://git-scm.com/download/win
2. Install with default settings
3. Restart your terminal/PowerShell

### Step 2: Navigate to Your Folder
```powershell
cd C:\Users\PC\Desktop\cv
```

### Step 3: Initialize and Push
```powershell
git init
git add index.html styles.css script.js
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/ibm1850/cv.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
Follow Step 2 from Method 1 above.

---

## After Uploading - Enable GitHub Pages

**Important:** After uploading files, you MUST enable GitHub Pages:

1. Go to: https://github.com/ibm1850/cv/settings/pages
2. Under **"Source"**:
   - Select branch: **main**
   - Select folder: **/ (root)**
3. Click **"Save"**
4. Wait 1-2 minutes for deployment

Your site will be live at: **https://ibm1850.github.io/cv/**

---

## Quick Checklist

- [ ] Upload files to GitHub (choose one method above)
- [ ] Enable GitHub Pages in Settings
- [ ] Wait 1-2 minutes
- [ ] Visit: https://ibm1850.github.io/cv/
- [ ] Share your portfolio link! 🎉

---

## Troubleshooting

**If your site shows 404:**
- Make sure GitHub Pages is enabled in Settings
- Wait 2-3 minutes (deployment takes time)
- Check that `index.html` is in the root folder

**If changes don't appear:**
- Clear your browser cache (Ctrl + F5)
- Wait a few minutes for GitHub to update

---

## Next Steps (Optional)

1. **Custom Domain:** Add your own domain in GitHub Pages settings
2. **Update Content:** Edit files locally, then upload again
3. **Add README:** Create a README.md file describing your portfolio

Your portfolio is ready to go live! 🚀

