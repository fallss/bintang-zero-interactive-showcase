# 🌟 Bintang Zero 0.0% — Interactive 3D Product Showcase

[![Live Demo](https://img.shields.io/badge/Live_Demo-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://bintang-zero-interactive-showcase.vercel.app/)
[![Status](https://img.shields.io/badge/Status-Online-059669?style=for-the-badge)](https://bintang-zero-interactive-showcase.vercel.app/)
[![WebGL](https://img.shields.io/badge/3D-Google_Model--Viewer-3b82f6?style=for-the-badge&logo=webgl&logoColor=white)](https://modelviewer.dev/)
[![GSAP](https://img.shields.io/badge/Animations-GSAP_3.12-88CE02?style=for-the-badge&logo=greensock&logoColor=white)](https://greensock.com/gsap/)

An immersive, award-winning 3D web experience and luxury landing page celebrating Indonesia's iconic non-alcoholic malt beverage: **Bintang Zero 0.0%** and **Bintang Radler Lemon 0.0%**. 

Built with **Google `<model-viewer>`**, **GSAP**, **WebGL**, and the native **Web Audio API**.

---

## 🌐 Live Demo

Experience the interactive 3D showcase live in production:  
👉 **[https://bintang-zero-interactive-showcase.vercel.app/](https://bintang-zero-interactive-showcase.vercel.app/)**

> **Tip**: Best experienced on desktop and modern mobile browsers with WebGL & hardware acceleration enabled. Turn on the **Sound FX** toggle for immersive sound design.

---

## ✨ Key Features

- **Interactive 3D Product Showcase**: Real-time 360° interactive rotation, auto-spin mode, and instant camera presets using `@google/model-viewer`.
- **Instant Flavour Switching**: Seamless transition between *Zero Original 0.0%* and *Radler Lemon 0.0%* with synchronized background transitions, spin blur, and dynamic asset swap without page reloads.
- **Authentic Floating Ingredients**: Physics-driven floating particles with real-time cursor parallax and magnetic repulsion effect (crisp ice cubes with water splashes, aromatic hop cones, golden malt barley, and fresh lemon slices).
- **Live Tasting Profile Matrix**: Real-time visual progress gauges showing crispness, malt richness, citrus zest, and sweetness balance with custom food pairing recommendations.
- **The Perfect 3°C Pour Ritual**: Interactive 3-step guide detailing the optimal ice-cold serving ritual accompanied by high-definition lifestyle imagery.
- **Craft & Ingredients Bento Grid**: Modern bento layout detailing the natural brewing craftsmanship: European malt barley, selected natural hops, real lemon juice, and crystalline spring water.
- **Quality & 0.0% Guarantee**: Comprehensive breakdown of low-temperature vacuum dealcoholization, BPOM registration, and Halal MUI certification.
- **In-Browser Sound FX Engine**: Procedurally synthesized beverage fizz and can pop effects using the native **Web Audio API** (zero external audio file dependencies).
- **Fast Order Modal**: Integrated retailer modal linking directly to official stores on Tokopedia, Shopee Mall, Klik Indomaret, Alfagift, and GrabMart.

---

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: Modern CSS3 (CSS Variables, Glassmorphism, Responsive Flexbox & CSS Grid)
- **3D & WebGL**: [Google Model-Viewer](https://modelviewer.dev/) (`@google/model-viewer`)
- **Animation**: [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/)
- **Audio**: Web Audio API (Synthesized acoustic waveforms)
- **Typography**: Google Fonts (*Outfit* & *Plus Jakarta Sans*)
- **Deployment & Hosting**: [Vercel](https://vercel.com/)

---

## 🚀 Getting Started

### Prerequisites
Any modern web browser with WebGL support (Chrome, Edge, Safari, Firefox).

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/fallss/bintang-zero-interactive-showcase.git
   cd bintang-zero-interactive-showcase
   ```

2. **Serve with a local HTTP server:**
   Using Python:
   ```bash
   # Python 3
   python3 -m http.server 8080
   ```
   Or using Node.js:
   ```bash
   npx serve .
   ```

3. **Open in your browser:**
   ```text
   http://localhost:8080/index.html
   ```

---

## 📁 Project Structure

```text
├── index.html              # Main interactive single-page application
├── bintang 1.glb           # 3D GLTF model: Bintang Zero 0.0%
├── bintang 2.glb           # 3D GLTF model: Bintang Radler Lemon 0.0%
├── bintang-1-card.png      # Transparent PNG render (Zero Can)
├── bintang-2-card.png      # Transparent PNG render (Radler Can)
├── assets/
│   ├── lemon-slice.png     # Studio isolated lemon slice with water splash
│   ├── lemon-wedge.png     # Studio isolated cut lemon wedge
│   ├── ice-cube.png        # Crystalline ice cube with splash droplets
│   ├── hop.png             # Fresh brewing green hop cone
│   ├── barley.png          # Golden malt barley ear
│   └── lifestyle-pour.jpg  # Cinematic 3°C cold-pour photography
├── vercel.json             # Vercel deployment & 3D asset headers configuration
└── README.md               # Project documentation
```

---

## 📄 License & Legal Notice

This project is created for creative portfolio, educational, and design demonstration purposes. 
All brand names, logos, and product trademarks of **Bintang**, **Bintang Zero**, and **Bintang Radler** are the property of **PT Multi Bintang Indonesia Tbk**.
