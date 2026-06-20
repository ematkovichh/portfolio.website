# How to Push Your Updated Portfolio to GitHub

## Step 1: Download Your Updated Portfolio
The updated `Portfolio.dc.html` file is ready in your project.

## Step 2: Push to GitHub

### Option A: Using Git (Command Line)

```bash
# 1. Navigate to your portfolio repository
cd path/to/your/portfolio.website

# 2. Copy the updated Portfolio.dc.html to your repo
# Replace the old one with the new version

# 3. Stage the changes
git add Portfolio.dc.html

# 4. Commit the changes
git commit -m "Update portfolio: Add horizontal polaroids and showcase sections for Nocturne and Observer"

# 5. Push to GitHub
git push origin main
```

### Option B: Using GitHub Desktop
1. Open GitHub Desktop
2. Select your `portfolio.website` repository
3. Replace the old `Portfolio.dc.html` with the new one
4. Click "Commit to main"
5. Add commit message: "Update portfolio: Add horizontal polaroids and showcase sections"
6. Click "Push origin"

### Option C: Direct Upload on GitHub
1. Go to https://github.com/ematkovichh/portfolio.website
2. Click "Add file" → "Upload files"
3. Drag and drop the updated `Portfolio.dc.html`
4. Scroll down and click "Commit changes"

## What Was Changed:
✅ Fixed image paths (changed from `uploads/` to GitHub raw URL)
✅ Made Nocturne, Y2K Art, and Statistical have horizontal polaroids (280×150px)
✅ Added dedicated **Nocturne Showcase** section
✅ Added dedicated **Observer Showcase** section
✅ Updated navigation menu with new section links
✅ All images now load from GitHub properly

## View Your Updated Portfolio:
- **GitHub Pages:** https://ematkovichh.github.io/portfolio.website/
- **Direct GitHub:** https://github.com/ematkovichh/portfolio.website

---

After pushing, GitHub Pages will automatically update your live site within a few minutes!
