# Farzad Zeinali — Personal Website

Personal academic website for **Farzad Zeinali**, PhD Candidate & Graduate Research Assistant in Industrial Engineering at Clemson University.

**Live site:** [https://fzeinali.github.io](https://fzeinali.github.io)

## About

Decision scientist with expertise in simulation, optimization, statistics, and machine learning. This site showcases research, publications, education, awards, and contact information.

## Tech Stack

- HTML, CSS, JavaScript
- Hosted on GitHub Pages

## Project Structure

```
├── index.html    # Main page (About, Education, News, Awards, Publications, Leadership, Contact)
├── styles.css    # Styling
├── script.js     # Mobile navigation
└── README.md
```

## Deploy / Update

The site deploys automatically from the `main` branch. To push updates:

```bash
git add .
git commit -m "Your commit message"
git push origin main
```

GitHub Pages will rebuild the site in 1–2 minutes.

## Local Preview

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

Then visit `http://localhost:8000`

## Customize

- **index.html** — Update content (about, news, publications, contact)
- **styles.css** — Adjust colors in `:root` variables (`--accent`, `--bg`, etc.)
