# Ratna Kumar Pattanaik -- Cybersecurity & Developer Portfolio

A high-performance, dark-themed portfolio landing page for **Ratna Kumar Pattanaik** (B.Tech CSE Undergraduate &bull; Cybersecurity Enthusiast at NIST University), built with React, TypeScript, Tailwind CSS, Framer Motion, and Lucide React.

## 🚀 Tech Stack

- **React 18** with **TypeScript**
- **Vite** for fast HMR and bundling
- **Tailwind CSS 3.4** for utility-first responsive styling
- **Framer Motion** for smooth scroll-driven and interactive animations
- **Google Fonts ('Kanit')** (weights 300 to 900)
- **Lucide React** for icons

## 🎨 Design System

- **Background**: `#0C0C0C` (Dark aesthetic)
- **Typography**: Google Font **Kanit** (sans-serif)
- **Heading Gradient (`.hero-heading`)**: `linear-gradient(180deg, #646973 0%, #BBCCD7 100%)` with text clipping
- **Palette**: `#0C0C0C`, `#D7E2EA`, with radiant magenta-to-purple-to-orange gradient highlights for action buttons

## 📂 Project Architecture

```
jack-3d-portfolio/
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── tsconfig.json
├── vite.config.ts
└── src/
    ├── main.tsx
    ├── App.tsx
    ├── index.css
    ├── types/
    │   └── index.ts
    ├── components/
    │   ├── common/
    │   │   ├── FadeIn.tsx           # Viewport-aware scroll reveal wrapper
    │   │   ├── Magnet.tsx           # Mouse-following magnetic effect
    │   │   ├── ContactButton.tsx    # Styled gradient pill button with inner shadows
    │   │   ├── LiveProjectButton.tsx # Ghost outline button
    │   │   └── AnimatedText.tsx     # Character-by-character scroll opacity reveal
    │   └── sections/
    │       ├── HeroSection.tsx      # Navbar, massive title, magnetic 3D portrait, bottom bar
    │       ├── MarqueeSection.tsx   # Dual passive scroll horizontal GIF marquees
    │       ├── AboutSection.tsx     # 4 Corner 3D objects, scroll text reveal, contact CTA
    │       ├── ServicesSection.tsx  # Crisp white curved card with 5 services & bold numbers
    │       └── ProjectsSection.tsx  # Sticky stacking cards with scale-down transforms
```

## 🛠️ How to Run

1. Open this folder in your terminal:
   ```bash
   cd "C:\Users\P R Pattanaik\.gemini\antigravity\scratch\jack-3d-portfolio"
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development server:
   ```bash
   npm run dev
   ```
4. Build for production:
   ```bash
   npm run build
   ```
