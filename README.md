git clone https://github.com/denyerts/fpl-wrapped-slides.git
cd fpl-wrapped-slides

# Create folders
mkdir -p src/components src/lib src/pages

# package.json
cat > package.json <<'EOF'
{
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
}
EOF

# README
cat > README.md <<'EOF'
# FPL Wrapped Slides 🎉

Spotify Wrapped–style slides for Fantasy Premier League recaps.  
Designed to drop into **Lovable** or any Next.js project.

## 🚀 Features
- Animated slides (Framer Motion)
- Export slides as PNG images
- Branded gradients
- Demo League Report page

## 🛠 Setup
```bash
npm install
npm run dev
