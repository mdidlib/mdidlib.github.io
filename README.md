# MDID Library - GitHub Pages Deployment

This repository contains the online learning resources for the MDID Library (Wang Yangfeng Library) at Mingdao International Department.

**Live site:** https://mdidlib.github.io

## 📁 Site Structure

```
mdidlib.github.io/
├── index.html                      ← Main home page
├── digital-skills/                 ← For grades 7-10
│   ├── index.html                  ← Digital Skills landing page
│   ├── spot-the-fake.html
│   ├── search-like-pro.html
│   ├── source-detective.html
│   ├── paraphrase-master.html
│   ├── citation-builder.html
│   ├── synthesis-challenge.html
│   ├── privacy-guardian.html
│   ├── digital-footprint.html
│   └── fake-news-fighter.html
└── research-toolkit/               ← For grades 11-12 (IB)
    ├── index.html                  ← Research Toolkit landing page
    ├── research-foundations.html
    ├── sources-and-ai.html
    ├── citations-choice.html
    ├── citations-mla.html
    └── citations-apa.html
```

## 🔗 URLs

Once deployed, your pages will be available at:

| Page | URL |
|------|-----|
| Home | `https://mdidlib.github.io/` |
| Digital Skills | `https://mdidlib.github.io/digital-skills/` |
| Research Toolkit | `https://mdidlib.github.io/research-toolkit/` |

## 🚀 Initial Setup Instructions

### Step 1: Create a GitHub Account for the Library

1. Go to [github.com](https://github.com)
2. Click "Sign up"
3. Use the library email: `mdidlib@ms.mingdao.edu.tw`
4. Choose username: `mdidlib`
5. Complete the signup process and verify your email

### Step 2: Create the Repository

1. Once logged in, click the **+** icon in the top right → "New repository"
2. **Repository name:** `mdidlib.github.io` (this exact name enables GitHub Pages automatically)
3. **Description:** "MDID Library online learning resources"
4. Select **Public**
5. Check **"Add a README file"** (we'll replace it)
6. Click **"Create repository"**

### Step 3: Upload the Files

**Option A: Using the GitHub Web Interface (Easiest)**

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL the files and folders from this package:
   - `index.html`
   - `digital-skills/` (entire folder)
   - `research-toolkit/` (entire folder)
3. Scroll down, add commit message: "Initial upload of library resources"
4. Click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Clone the repository
git clone https://github.com/mdidlib/mdidlib.github.io.git
cd mdidlib.github.io

# Copy all files from this package into the repository folder
# (replace the auto-generated README.md)

# Add, commit, and push
git add .
git commit -m "Initial upload of library resources"
git push origin main
```

### Step 4: Enable GitHub Pages (if not automatic)

1. Go to your repository on GitHub
2. Click **"Settings"** (tab at the top)
3. In the left sidebar, click **"Pages"**
4. Under "Source", select **"Deploy from a branch"**
5. Under "Branch", select **"main"** and **"/ (root)"**
6. Click **"Save"**
7. Wait 1-2 minutes for deployment

### Step 5: Verify Your Site

1. Visit `https://mdidlib.github.io`
2. You should see the library home page
3. Test all navigation links

## 🔗 Linking from Squarespace

On your Squarespace library page (`mdid.info/library`), you can add links or buttons:

**Suggested button text and URLs:**

| Button Text | URL |
|-------------|-----|
| Digital Skills Modules | `https://mdidlib.github.io/digital-skills/` |
| Research Toolkit (IB) | `https://mdidlib.github.io/research-toolkit/` |
| All Online Resources | `https://mdidlib.github.io/` |

## ✏️ Making Updates

### To edit a single file:

1. Navigate to the file on GitHub
2. Click the **pencil icon** (Edit this file)
3. Make your changes
4. Click **"Commit changes"**
5. Changes go live in 1-2 minutes

### To upload new/updated files:

1. Go to the repository
2. Navigate to the correct folder
3. Click **"Add file"** → **"Upload files"**
4. Upload your updated files (they will replace existing ones with the same name)
5. Commit the changes

### To add a new module:

1. Create your HTML file
2. Upload it to the appropriate folder (`digital-skills/` or `research-toolkit/`)
3. Edit the `index.html` in that folder to add a link to the new module

## 🔄 Handoff Instructions (For Future Librarians)

If you're leaving and need to transfer this to someone else:

### Option 1: Add a Collaborator (Recommended)

1. Go to repository **Settings** → **Collaborators**
2. Click **"Add people"**
3. Enter the new person's GitHub username or email
4. They'll receive an invitation to collaborate
5. Once they accept, they can make changes
6. You can then remove yourself if needed

### Option 2: Transfer Repository Ownership

1. Go to repository **Settings**
2. Scroll to **"Danger Zone"** at the bottom
3. Click **"Transfer"**
4. Enter the new owner's GitHub username
5. They must accept the transfer

### Important: Update Account Email

If the library email changes:
1. Go to GitHub **Settings** (click your profile picture → Settings)
2. Click **"Emails"**
3. Add the new email and verify it
4. Set it as primary
5. Remove the old email

## 🛠️ Technical Notes

- All pages use **Tailwind CSS** via CDN (no build process needed)
- Interactive modules use **React** with Babel transpilation (runs in browser)
- No server-side code - everything is static HTML/CSS/JS
- The site works offline once loaded (good for classroom use)

## 📧 Contact

Library Email: mdidlib@ms.mingdao.edu.tw  
Library Website: https://mdid.info/library

---

*Last updated: December 2025*
*© 2025 Mingdao International Department Library*
