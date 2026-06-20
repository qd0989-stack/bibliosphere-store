# 🚀 Bibliosphere Store - Deployment Guide

## Option 1: One-Click Deploy to GitHub (Recommended)

### What you need:
1. A GitHub account (free at https://github.com)
2. A GitHub Personal Access Token (takes 1 minute to get)

### Steps:

**Step 1: Get a GitHub Token**
1. Go to: https://github.com/settings/tokens
2. Click "Generate new token (classic)"
3. Name it: "Bibliosphere Deploy"
4. Select scope: ✅ "repo" (full control)
5. Click "Generate token"
6. COPY the token immediately (you won't see it again!)

**Step 2: Run the Deploy Command**
```bash
./publish.sh YOUR_GITHUB_TOKEN_HERE
```

Example:
```bash
./publish.sh ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

**Step 3: Done!**
Your store will be live at: `https://YOURUSERNAME.github.io/bibliosphere-store`

---

## Option 2: Manual Upload (If you prefer)

### Steps:
1. Go to: https://github.com/new
2. Create a new repository named: `bibliosphere-store`
3. Make it Public
4. Click "uploading an existing file"
5. Drag ALL the files from this folder
6. Click "Commit changes"
7. Go to Settings → Pages → Select "main" branch → Save
8. Wait 2 minutes and your site is live!

---

## Option 3: Deploy to Netlify (Alternative)

1. Go to: https://app.netlify.com/drop
2. Drag this entire folder onto the page
3. Done! You'll get a free URL like `random-name-12345.netlify.app`

---

## What's Included

### Website Files
- `index.html` - Main bookstore with all books
- `epubs.html` - Direct download page for all books
- `landing-page.html` - Newsletter signup page
- `gumroad-landing.html` - Gumroad store page
- `404.html` - Custom error page

### Ebook Files (in `/epubs/`)
- drawing_for_beginners.epub
- rainbow_unicorn.epub
- dragons_apprentice.epub
- mystery_shadow_manor.epub
- brave_little_star.epub
- echoes_of_tomorrow.epub
- treasury_short_stories.epub
- activity_book.epub

---

## After Deployment

### Your store URL will be:
```
https://YOURUSERNAME.github.io/bibliosphere-store
```

### Next Steps:
1. **Customize** - Edit `index.html` to add your real Amazon/Gumroad links
2. **Promote** - Share your URL on Pinterest, Reddit, social media
3. **Update** - You can update files anytime and they'll go live automatically

---

## Troubleshooting

**"Token invalid" error?**
- Make sure you copied the entire token
- Check that you selected "repo" scope when creating it

**Site not showing?**
- Wait 2-5 minutes for GitHub Pages to activate
- Check Settings → Pages is enabled

**Want a custom domain?**
- Buy a free .tk domain at freenom.com
- Add it in Settings → Pages → Custom domain

---

## Need Help?

Check the main `START-HERE.md` file in the project root for full business setup instructions.

---

*Built with ❤️ by Bibliosphere Generator*
*Your digital book empire starts here!* 📚✨