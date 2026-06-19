An editorial-magazine style portfolio built with **Vanilla HTML5, CSS3, and JavaScript**. Designed for modern, high-impact creative developers and AI engineers. Fully responsive, lightweight, and packed with smooth micro-interactions, custom animations, and a rich dark aesthetic.

Live Demo: [View Portfolio](https://krishna4532.github.io/) *(Or deploy to your favorite hosting platform)*

---

## 🎨 Design System & Aesthetic Spec
- **Color Palette**:
  - **Background**: Matte Deep Charcoal (`#0D0D0D`) for a premium digital editorial vibe.
  - **Accents & Typography**: Muted warm amber/gold (`#E5A93C`) & Stark White (`#FFFFFF`).
  - **Grid**: Blueprint Grid Background with subtle radial masking and dynamic Noise Grain overlays.
- **Typography**: Ultra-bold condensed headings (Inter, Space Grotesk) and JetBrains Mono for system metrics.
- **Micro-interactions**: 
  - Dual-ring custom cursor tracking.
  - Smooth hover scaling on cards with golden accent sidebars.
  - Interactive scroll progress indicator.
  - Live status typing ticker in the sub-header.

---

## ✨ Features
- **⚡ Zero Dependency**: Zero bundlers, zero framework overhead, zero runtime lag. Written in pure HTML, CSS, and JS.
- **🎬 Cinematic Page Loader**: Locking scroll with a custom monogram percentage counter (`0% - 100%`) before revealing page content.
- **📟 Now Building Live Ticker**: A continuous typewriter animation cycle showing real-time development focuses.
- **📊 Interactive Counters**: JavaScript-based scroll-triggered statistical counters that count up to targets.
- **📁 Projects Bento Grid**: Dynamic client-side categorization (All / AI Agents / Web Architecture) with filter buttons.
- **📋 Copy-to-Clipboard Email**: Native email copying with instant visual floating tooltips.
- **📱 Fully Responsive**: Custom media query breakpoints ensuring visual layouts map beautifully across mobile, tablet, and desktop screens.

---

## 📂 Project Structure
The repository is simple, keeping deployment and maintenance extremely straightforward:
```text
portfolio/
├── index.html       # Single-file source code (HTML layout, custom CSS, JS engines)
├── image.jpeg       # User profile picture used in the hero avatar pod
└── README.md        # Documentation
```

---

## 🚀 Quick Start & Setup

### 1. Run Locally
You can run this project locally in two ways:
* **Option A**: Double-click `index.html` to open it directly in any browser.
* **Option B** (Recommended for file paths & assets): Run a local development server:
  ```bash
  # Using Python (built-in)
  python -m http.server 8000
  
  # Or using Node.js / npm
  npx serve .
  ```
  Then visit `http://localhost:8000` or `http://localhost:3000`.

### 2. Customization Guide
Open `index.html` in your text editor and modify the following fields:

#### Profile Picture:
Replace the file `image.jpeg` with your own profile image, or edit the source path on the image tag:
```html
<img class="pod-img" src="./image.jpeg" alt="Krishna Kumar — Full-Stack & AI Engineer" />
```

#### Personal Info & Bio:
- Search for `// Krishna Kumar` in the navbar and update to your name.
- Change the heading text in the `<section class="hero">` block.
- Update the philosophy, stats (`data-target` values), and paragraph bio.

#### Project Grid:
Modify the project cards within `<div id="part-ai">` and `<div id="part-web">`. Each card has filtering data attributes:
```html
<div class="pc pc-lg rv" data-cat="ai"> <!-- data-cat: "ai" or "web" -->
  ...
</div>
```

---

## 🌐 Deployment
Since this is a static site, you can host it for free in seconds:

### **GitHub Pages**
1. Push this folder to a GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set source to **Deploy from a branch** and select your main branch.
4. Click save and wait for the URL!

### **Vercel / Netlify / Cloudflare Pages**
Import your repository directly into their dashboard; no build command or output directory settings are required since it is a pure static HTML codebase.
# krishna-portfolio
