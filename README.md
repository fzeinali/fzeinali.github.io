# Personal Website

A simple, modern personal website built with HTML, CSS, and JavaScript. Hosted on GitHub Pages.

## Deploy to GitHub Pages

### Option A: User/Organization site (recommended for personal sites)

Your site will live at `https://YOUR_USERNAME.github.io`

1. **Create a new repository** on GitHub named `YOUR_USERNAME.github.io` (replace with your GitHub username)
2. **Initialize git and push** from your project folder:

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages** in your repo:
   - Go to **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Choose the `main` branch and `/ (root)` folder
   - Click **Save**

4. Your site will be live in 1–2 minutes at `https://YOUR_USERNAME.github.io`

### Option B: Project site

Your site will live at `https://YOUR_USERNAME.github.io/REPO_NAME`

1. Create any repository (e.g. `my-website`)
2. Push your code as in Option A
3. In **Settings** → **Pages**, set source to `main` branch, `/ (root)`
4. Your site will be at `https://YOUR_USERNAME.github.io/my-website`

## Customize

- **index.html**: Update your name, tagline, about text, projects, and contact links
- **styles.css**: Adjust colors in the `:root` variables (e.g. `--accent`, `--bg`)

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve
```

Then visit `http://localhost:8000`
