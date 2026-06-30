# AI Automation Portfolio

A single-page portfolio site showcasing n8n automation and AI integration projects.

## 🚀 Live Demo

This is a static site — no build step required. You can preview it locally by opening `index.html` directly in a browser, or serve it with any static file server.

### Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## 📁 Structure

```
.
├── index.html                          # Single-page site (all CSS/JS inline)
├── favicon.svg                          # Site favicon
├── Joseph_Rey_Cabantan_Resume.pdf       # Linked from the "View resume" button
└── images/                              # Workflow screenshots used in the Projects section
    ├── booking-bot.png
    ├── inventory-check.png
    ├── feedback-agent.png
    ├── onboarding-workflow.png
    ├── erp-reporting.png
    └── real-estate-agent.png
```

## ✏️ Customizing

Everything lives in `index.html` — no framework, no dependencies, no build tools.

- **Contact info**: update the `mailto:` link and social links in the `#contact` section.
- **Resume**: the "View resume" button links to `Joseph_Rey_Cabantan_Resume.pdf` in the repo root — replace that file with an updated version (keep the same filename, or update the `href` in `index.html`).
- **Projects**: each project is a `.project-card` block inside the `#projects` section. To add a new one, drop a screenshot in `images/`, copy an existing card, and update the image path, title, description, and workflow chain labels.
- **About stats**: the four stat cards in the `#about` section are plain numbers/labels — easy to update as your project count or stack grows.

## 🛠️ Tech

Pure HTML/CSS/JS. Fonts loaded from Google Fonts (Fraunces, Inter, JetBrains Mono). No external JS dependencies.

## 📄 License

Personal portfolio — feel free to fork the structure for your own site, but please swap out the content and screenshots for your own work.
