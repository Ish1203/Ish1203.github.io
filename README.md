# Ish Dubey — Portfolio Website

A stunning, responsive, dark cyberpunk-aesthetic portfolio website.

---

## 🚀 Running Locally in VS Code

### Option 1: Live Server (Recommended — Easiest)

1. **Open VS Code** and open the `ish-portfolio` folder:
   - Go to `File → Open Folder` → select the `ish-portfolio` folder

2. **Install the Live Server extension:**
   - Click the Extensions icon (or press `Ctrl+Shift+X`)
   - Search for **Live Server** by Ritwick Dey
   - Click **Install**

3. **Start the server:**
   - Right-click on `index.html` in the file explorer
   - Select **"Open with Live Server"**
   - Your browser will open at `http://127.0.0.1:5500`
   - Any changes you save will **auto-refresh** the browser ✨

### Option 2: VS Code Built-in Simple Browser

1. Open `index.html`
2. Press `Ctrl+Shift+P` → type `Simple Browser` → Enter
3. Type in the URL: `http://127.0.0.1:5500/index.html`

---

## 🌐 Deploying to GitHub Pages (One-click link for anyone)

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click **"New repository"** (the green button or `+` icon)
3. Name it exactly: **`your-username.github.io`**
   - Example: if your GitHub username is `ishdubey`, name it `ishdubey.github.io`
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A — Via GitHub Website (No Git needed):**
1. Open your new repository
2. Click **"uploading an existing file"** link
3. Drag and drop all 3 files: `index.html`, `style.css`, `script.js`
4. Click **"Commit changes"**

**Option B — Via Git Terminal:**
```bash
# Open terminal in VS Code (Ctrl + `)
cd path/to/ish-portfolio

git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** (left sidebar)
4. Under **Source**, select **"Deploy from a branch"**
5. Set Branch to **main** / `/(root)`
6. Click **Save**

### Step 4: Your Live Link 🎉

After ~2 minutes, your portfolio will be live at:
```
https://YOUR-USERNAME.github.io
```

Share this link on your resume, LinkedIn, anywhere!

---

## 📁 File Structure

```
ish-portfolio/
├── index.html    ← Main HTML structure
├── style.css     ← All styling and animations
├── script.js     ← Canvas, typed text, scroll effects
└── README.md     ← This file
```

---

## ✏️ Customizing Your Portfolio

### Update your info:
- **Links:** Search for `href="https://github.com"` and `href="https://linkedin.com"` in `index.html` and replace with your actual URLs
- **Photo:** Replace the initials placeholder by adding an `<img>` tag inside `.about-img-placeholder`
- **Name/bio:** All editable directly in `index.html`

### Add a new project:
Copy any `.project-card` block in `index.html` and update the content.

---

## 🛠 Tech Stack Used

- Pure HTML5, CSS3, Vanilla JavaScript
- No frameworks, no build tools — just open and it works
- Google Fonts (Syne, Space Mono, DM Sans)
- Canvas API for particle system
- IntersectionObserver for scroll animations
