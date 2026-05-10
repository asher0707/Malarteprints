# Malarte Printing Studio — Website

Static website for **Malarte Printing Studio**, a Milan-based 3D printing studio.

## Structure

```
malarte-site/
├── index.html          # Main website (single page)
├── images/
│   ├── hero.png              # Hero section photo
│   ├── card-architecture.png # Capabilities card 1
│   ├── card-prototyping.png  # Capabilities card 2
│   ├── card-fashion.png      # Capabilities card 3
│   └── card-figures.png      # Capabilities card 4
└── README.md
```

## Deploy on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Tech

- Pure HTML + CSS + JavaScript — no frameworks, no build step
- Glassmorphism design with `#c7e306` accent
- Fonts: Bebas Neue (display) + Inter (body) via Google Fonts
- Embedded YouTube video via iframe
- Custom cursor, scroll animations, parallax, marquee
