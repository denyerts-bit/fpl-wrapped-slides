fpl-wrapped-slides/
├── package.json
├── README.md
├── src/
│   ├── components/
│   │   └── WrappedSlide.tsx
│   └── lib/
│       └── useExport.ts{
  "name": "fpl-wrapped-slides",
  "version": "1.0.0",
  "main": "index.js",
  "license": "MIT",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "downloadjs": "^1.4.7",
    "framer-motion": "^10.16.4",
    "html-to-image": "^1.11.11",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "next": "13.5.0"
  }
}# FPL Wrapped Slides 🎉

Spotify Wrapped–style slides for Fantasy Premier League recaps.  
Designed to drop into **Lovable** or any Next.js project.

---

## 🚀 Features
- Animated slides (Framer Motion)
- Branded gradients
- Export each slide as a PNG image
- Built for shareability (Instagram/Twitter/WhatsApp)

---

## 🛠 Setup
1. Clone this repo:
   ```bash
   git clone https://github.com/denyerts/fpl-wrapped-slides.git
   cd fpl-wrapped-slides
   npm installnpm run dev
