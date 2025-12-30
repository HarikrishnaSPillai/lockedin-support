# LockedIn Support Site

This folder contains the static support website for the LockedIn iOS app.

## Contents
- `index.html`: Main support page.
- `privacy.html`: Privacy Policy (Apple compliant).
- `terms.html`: Terms of Service (Apple compliant).
- `style.css`: Dark theme styling.

## How to Deploy (GitHub Pages)

1. **Create a New Repository**:
   - Go to [GitHub.com](https://github.com) and create a new public repository named `lockedin-support`.
   - Do not initialize with README (since we have these files).

2. **Push Files**:
   - Open Terminal and navigate to this folder:
     ```bash
     cd /Users/harikrishnapillai/Documents/LockedIn/lockedin-support
     ```
   - Initialize git and push:
     ```bash
     git init
     git add .
     git commit -m "Initial commit of support site"
     git branch -M main
     git remote add origin https://github.com/YOUR_USERNAME/lockedin-support.git
     git push -u origin main
     ```
     *(Replace `YOUR_USERNAME` with your actual GitHub username)*

3. **Enable GitHub Pages**:
   - Go to your repository **Settings** on GitHub.
   - Click **Pages** in the left sidebar.
   - Under **Source**, select `Deploy from a branch`.
   - Under **Branch**, select `main` and `/ (root)`.
   - Click **Save**.

## Final URL
After a minute, your site will be live at:
`https://YOUR_USERNAME.github.io/lockedin-support/`

**Use this URL in App Store Connect** for the "Support URL" and "Marketing URL" fields.
- Privacy Policy URL: `.../privacy.html`
- Terms of Service URL: `.../terms.html`
