# Rohit Kharode — Developer & Designer Portfolio

> A modern, dark-themed personal portfolio website showcasing design expertise and development skills. Built with cutting-edge web technologies for seamless performance and stunning visuals.


---

## 🎯 Overview

A Computer Science graduate from NSUT, focused on creating exceptional digital experiences through UI/UX design, front-end development, and AI integration. This portfolio showcases projects, services, and technical expertise in a visually compelling, scroll-driven interface.

### Key Features
- ✨ **Cinematic Hero** — Full-screen video background with interactive elements
- 🎭 **Smooth Animations** — Scroll-driven reveals and magnetic hover effects  
- 📱 **Fully Responsive** — Optimized for desktop, tablet, and mobile
- ⚡ **Performance First** — Lazy loading, optimized images, minimal JavaScript
- 🎨 **Custom Branding** — Tailored gradients, typography, and color palette

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|---------------|
| **Frontend Framework** | React 18 + TypeScript |
| **Build Tool** | Vite |
| **Styling** | Tailwind CSS |
| **Animations** | Framer Motion |
| **Icons** | Lucide React |
| **Typography** | Kanit (Google Fonts) |
| **Deployment** | Vercel |

---

## 📋 Sections

1. **Hero** — Full-screen video, animated name, navigation, sound toggle
2. **About** — Bio, background, skills organized by category (Languages, Frameworks, Tools, AI)
3. **Services** — 4 core offerings: UI/UX Design, Web Design, Frontend Development, GenAI Integration
4. **Projects** — Sticky-stacking cards with image galleries and live links
5. **Contact** — Email, WhatsApp, LinkedIn, and GitHub integration

---

## 📁 Project Structure

```
src/
├── App.tsx                    # Main app wrapper
├── main.tsx                   # React entry point
├── index.css                  # Global styles + hero gradient
│
└── components/
    ├── HeroSection.tsx        # Video bg, nav, intro text
    ├── AboutSection.tsx       # Bio, animated text, skills
    ├── ServicesSection.tsx    # Service offerings
    ├── ProjectsSection.tsx    # Sticky project cards
    ├── ContactSection.tsx     # Contact methods
    │
    ├── ContactButton.tsx      # CTA button with gradient
    ├── LiveProjectButton.tsx  # Ghost outline button
    ├── FadeIn.tsx             # Scroll animation wrapper
    ├── Magnet.tsx             # Magnetic hover effect
    ├── AnimatedText.tsx       # Character-by-char reveal
    ├── VideoModal.tsx         # Modal for video playback
    └── MarqueeSection.tsx     # Marquee text effect
```

---

## 🚀 Quick Start

### Installation
```bash
# Install dependencies
npm install

# Start development server
npm run dev
# → Open http://localhost:5173

# Build for production
npm run build

# Preview production build
npm run preview
```

### Deploy to Vercel
1. Push your code to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your repository
4. Click Deploy — no environment variables needed!

---

## ⚙️ Customization

Want to personalize this portfolio? Here's where to edit:

| What | Where |
|------|-------|
| **Name, tagline, nav links** | `src/components/HeroSection.tsx` |
| **Bio and skills** | `src/components/AboutSection.tsx` |
| **Services offered** | `src/components/ServicesSection.tsx` (SERVICES array) |
| **Projects & images** | `src/components/ProjectsSection.tsx` (PROJECTS array) |
| **Contact methods** | `src/components/ContactSection.tsx` (CONTACT_METHODS array) |
| **Project images** | Add images to `public/` → reference as `/filename.png` |
| **Colors & fonts** | `src/index.css` + `tailwind.config.js` |
| **Page title & meta** | `index.html` |

---

## 📸 Featured Projects

| Project | Stack | Live Link |
|---------|-------|-----------|
| **Mdicare** | React, TypeScript, Tailwind CSS | [View Live](https://mdicare.vercel.app) |
| **LawLab** | React, Figma Design, Framer Motion | [View Live](https://lawlab-self.vercel.app) |

---

## 📝 License

This portfolio is open source. Feel free to use it as inspiration for your own portfolio!

---

## 🙏 Credits

**Designed & Built by:** [Rohit Kharode](https://linkedin.com/in/rohit-kharode)  
**Inspired by:** Original design concept by Harsh Goyal  
**Icons:** Lucide React  
**Fonts:** Kanit by Google Fonts

---

Made with ❤️ and React
