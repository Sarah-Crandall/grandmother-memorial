# Setup Instructions

## Uploading to Your GitHub Repository

### Option 1: Using GitHub Website (Easiest)

1. **Create a new repository on GitHub**
   - Go to https://github.com/Sarah-Crandall
   - Click the "+" icon in the top right
   - Select "New repository"
   - Name it `grandmother-memorial` (or your preferred name)
   - Choose "Public" or "Private" based on your preference
   - Do NOT initialize with README (we already have one)
   - Click "Create repository"

2. **Upload files**
   - On the new repository page, click "uploading an existing file"
   - Drag and drop all these files:
     - index.html
     - story-1.html
     - README.md
     - .gitignore
   - Add a commit message like "Initial commit: Memorial website"
   - Click "Commit changes"

3. **Enable GitHub Pages (to make it a live website)**
   - Go to repository Settings
   - Click "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save
   - Your site will be live at: `https://sarah-crandall.github.io/grandmother-memorial/`
   - (It may take 1-2 minutes to deploy)

### Option 2: Using Git Command Line

If you have Git installed on your computer:

```bash
# Navigate to where you want to store the project
cd ~/Documents/Projects

# Create a new directory
mkdir grandmother-memorial
cd grandmother-memorial

# Initialize git
git init

# Copy all the HTML files into this directory
# (Copy index.html, story-1.html, README.md, .gitignore)

# Add all files
git add .

# Commit
git commit -m "Initial commit: Memorial website"

# Connect to GitHub
git remote add origin https://github.com/Sarah-Crandall/grandmother-memorial.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Option 3: Using GitHub Desktop

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Open GitHub Desktop
3. Click "File" → "New repository"
4. Name: `grandmother-memorial`
5. Choose a location on your computer
6. Click "Create repository"
7. Copy all the HTML files into that folder
8. In GitHub Desktop, you'll see the files appear
9. Add a commit message: "Initial commit: Memorial website"
10. Click "Commit to main"
11. Click "Publish repository" to push to GitHub
12. Choose whether to keep it private or make it public

## After Uploading

### Setting Up GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Click "Pages" in the left menu
4. Under "Source":
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Choose "/ (root)" folder
   - Click "Save"

Your website will be published at:
```
https://sarah-crandall.github.io/grandmother-memorial/
```

### Custom Domain (Optional)

If you want to use a custom domain like `grandmothersstories.com`:
1. Buy a domain from a registrar (Namecheap, Google Domains, etc.)
2. In GitHub Pages settings, add your custom domain
3. Follow GitHub's instructions to configure your domain's DNS

## Testing Locally

Before uploading, you can test the website:
1. Open the folder containing the HTML files
2. Double-click `index.html`
3. It will open in your web browser
4. Test all the links and navigation

## Updating the Website Later

When you want to add more stories:

**Using GitHub Website:**
1. Go to your repository
2. Click "Add file" → "Upload files"
3. Drag and drop new HTML files
4. Commit changes

**Using Git Command Line:**
```bash
git add .
git commit -m "Added story 2"
git push
```

**Using GitHub Desktop:**
1. Make your changes
2. Commit in GitHub Desktop
3. Click "Push origin"

## Privacy Considerations

**If you want the site to be PRIVATE:**
- Keep the GitHub repository private
- Only people you explicitly give access can see it
- You can share the live GitHub Pages link with specific people

**If you want the site to be PUBLIC:**
- Anyone can visit the website URL
- Consider this before including family photos or sensitive information

**Password Protection:**
- GitHub Pages doesn't offer password protection
- For a password-protected site, consider:
  - Netlify (has password protection feature)
  - Vercel (can add authentication)
  - Or keep the repository completely private

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Desktop Guide](https://docs.github.com/en/desktop)
- [Git Command Line Tutorial](https://git-scm.com/docs/gittutorial)

---

Happy preserving! 💝
