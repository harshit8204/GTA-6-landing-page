# 🎮 GTA 6 — Fan Landing Page

<div align="center">

![GTA VI](https://img.shields.io/badge/GTA%20VI-Fan%20Project-orange?style=for-the-badge&logoColor=white)
![React](https://img.shields.io/badge/React-18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-88%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-8%25-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**A cinematic, fan-made landing page for Grand Theft Auto VI — built with React and Vite.**

[🐛 Report Bug](https://github.com/harshit8204/GTA-6-landing-page/issues) &nbsp;·&nbsp; [✨ Request Feature](https://github.com/harshit8204/GTA-6-landing-page/issues)

</div>

---

## 📸 Preview

> 💡 Add a screenshot by placing `preview.png` in the `public/` folder and uncommenting below:
>
> <!-- ![GTA 6 Landing Page Preview](./public/preview.png) -->

---

## 📌 Table of Contents

- [About](#-about)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Available Scripts](#-available-scripts)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [Author](#-author)
- [License](#-license)
- [Disclaimer](#️-disclaimer)

---

## 🕹️ About

This is a **fan-made, non-commercial landing page** inspired by Rockstar Games' **Grand Theft Auto VI**. The project was built to practice modern React development, cinematic UI/UX design, smooth animations, and component-based architecture — all powered by the lightning-fast Vite build tool.

> ⚠️ This project is **not affiliated with or endorsed by Rockstar Games or Take-Two Interactive**.

---

## 🛠️ Tech Stack

| Technology | Role |
|------------|------|
| ⚛️ **React 18** | Component-based UI & state management |
| ⚡ **Vite 5** | Build tooling, dev server & HMR |
| 🎨 **CSS3** | Custom styling & animations |
| 🌐 **HTML5** | Semantic markup via `index.html` |
| 🔍 **ESLint** | Linting & code quality enforcement |

---

## ✨ Features

- 🎬 **Cinematic Hero Section** — full-screen immersive visuals
- 🎥 **Trailer Section** — embedded GTA 6 trailer
- 🗺️ **Vice City Showcase** — location/world highlights
- 🌑 **Dark Theme UI** — inspired by GTA VI's aesthetic
- 📱 **Fully Responsive** — mobile, tablet & desktop
- ⚡ **Hot Module Replacement** — instant updates during development
- 🧩 **Reusable Components** — clean, modular React architecture
- 🚀 **Production-ready Build** — optimized bundle via Vite

---

## 📁 Project Structure

```
GTA-6-landing-page/
│
├── public/                     # Static assets served as-is
│   └── (images, videos, icons)
│
├── src/                        # All React source code
│   ├── components/             # Reusable UI components
│   │   ├── Navbar.jsx          # Top navigation bar
│   │   ├── Hero.jsx            # Hero / banner section
│   │   ├── Trailer.jsx         # Trailer embed section
│   │   ├── Features.jsx        # Game features highlights
│   │   └── Footer.jsx          # Page footer
│   │
│   ├── assets/                 # Images & media imported in components
│   ├── App.jsx                 # Root component — assembles all sections
│   ├── App.css                 # Global app-level styles
│   └── main.jsx                # React DOM entry point
│
├── index.html                  # HTML shell / entry for Vite
├── vite.config.js              # Vite build & dev configuration
├── eslint.config.js            # ESLint rules
├── package.json                # Project metadata & npm scripts
├── package-lock.json           # Locked dependency tree
└── README.md                   # Project documentation
```

> **Note:** Component names above are representative — update them to match your actual files inside `src/components/`.

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have:

- [Node.js](https://nodejs.org/) **v16 or higher**
- **npm** (bundled with Node.js) or **yarn**

Check your versions:
```bash
node -v
npm -v
```

### 📥 Installation

**1. Clone the repository**
```bash
git clone https://github.com/harshit8204/GTA-6-landing-page.git
```

**2. Move into the project directory**
```bash
cd GTA-6-landing-page
```

**3. Install all dependencies**
```bash
npm install
```

**4. Start the development server**
```bash
npm run dev
```

**5. Open in your browser**
```
http://localhost:5173
```

---

## 📦 Available Scripts

| Command | What it does |
|---------|-------------|
| `npm run dev` | 🔥 Starts local dev server with live HMR |
| `npm run build` | 📦 Compiles optimized production bundle into `dist/` |
| `npm run preview` | 👁️ Serves the production build locally for testing |
| `npm run lint` | 🔍 Runs ESLint to check for code issues |

---

## 🌍 Deployment

To deploy your production build:

```bash
npm run build
```

This generates a `dist/` folder. You can then deploy it to:

| Platform | Command / Guide |
|----------|----------------|
| **Vercel** | `vercel --prod` or connect GitHub repo |
| **Netlify** | Drag & drop `dist/` or connect GitHub repo |
| **GitHub Pages** | Use `gh-pages` npm package |

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. **Fork** this repository
2. **Create** a new branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes with a clear message
   ```bash
   git commit -m "feat: describe what you added"
   ```
4. **Push** to your branch
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** on GitHub

---

## 👤 Author

**Harshit**

[![GitHub](https://img.shields.io/badge/GitHub-harshit8204-181717?style=flat-square&logo=github)](https://github.com/harshit8204)

---

## 📄 License

This project is open source and available under the **[MIT License](LICENSE)**.

---

## ⚠️ Disclaimer

This is a **fan-made, non-commercial project** built purely for educational and portfolio purposes.

**Grand Theft Auto VI**, the GTA name/logo, Vice City, and all related assets are registered trademarks of **Rockstar Games / Take-Two Interactive Software, Inc.**

This project has **no commercial intent** and is **not affiliated with, sponsored by, or endorsed by Rockstar Games** in any way. All rights belong to their respective owners.

---

<div align="center">

Made with ❤️ and a whole lot of respect for Rockstar Games

⭐ **If you like this project, please give it a star!** ⭐

</div>
