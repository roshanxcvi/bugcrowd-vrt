# Bugcrowd VRT - Interactive Mind Map

An interactive, visual mind map of **Bugcrowd's Vulnerability Rating Taxonomy (VRT)** — the industry-standard classification system for security vulnerabilities.

**Developed by [roshanxcvi](https://github.com/roshanxcvi)**

## Live Demo

Visit the live site: **[https://roshanxcvi.github.io/bugcrowd-vrt/](https://roshanxcvi.github.io/bugcrowd-vrt/)**

## Features

- **Interactive Mind Map** — Root node on the left, branches expand to the right with smooth curved connectors
- **18 Vulnerability Categories** — Server-Side Injection, XSS, Broken Auth, IDOR, CSRF, AI/ML Security, Blockchain, and more
- **100+ Vulnerability Types** — Each with detailed descriptions explaining how the bug works, real-world examples, and impact
- **Priority Ratings** — Color-coded P1 (Critical) to P5 (Informational) badges on every node
- **Click for Details** — Click any node to see a detailed info panel with vulnerability description
- **Search** — Filter nodes by name or description
- **Dark Mode** — Toggle between light and dark themes
- **Pan and Zoom** — Scroll to zoom, drag to pan, with zoom controls
- **Expand/Collapse** — Expand all nodes or collapse to top-level categories
- **Mobile Friendly** — Touch support for pan and zoom

## How to Use

1. Open the live site or index.html in any browser
2. Click the Bugcrowd VRT root node to expand categories
3. Click any + node to expand its sub-categories
4. Click any node to see its detailed description
5. Use the search bar to find specific vulnerabilities
6. Toggle Dark/Light mode with the button in the header

## Deploy to GitHub Pages

### Step 1: Create a GitHub repo

Go to github.com and create a new repository named `bugcrowd-vrt`

### Step 2: Push the code

```bash
git init
git add index.html README.md
git commit -m "Bugcrowd VRT Mind Map"
git branch -M main
git remote add origin https://github.com/roshanxcvi/bugcrowd-vrt.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** (tab at the top)
3. Click **Pages** (left sidebar)
4. Under Source, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait 1-2 minutes, your site will be live at:

**https://roshanxcvi.github.io/bugcrowd-vrt/**

## Tech Stack

- React 18 (via CDN - no build step needed)
- SVG for the mind map rendering
- IBM Plex Sans and Mono fonts
- Single HTML file - just open in any browser

## Data Source

Based on Bugcrowd's open-source Vulnerability Rating Taxonomy:
https://github.com/bugcrowd/vulnerability-rating-taxonomy (Apache 2.0 License)

## License

MIT License - free to use, modify, and share.
