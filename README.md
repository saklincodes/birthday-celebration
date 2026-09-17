<div align="center">

# 🎂 Interactive Birthday Celebration Web Experience

An aesthetic, animated, and customizable interactive birthday greeting website built with modern CSS animations, vanilla JavaScript, and dynamic typewriter effects.

[![GitHub stars](https://img.shields.io/github/stars/saklincodes/birthday-celebration?style=for-the-badge&color=ff7882)](https://github.com/saklincodes/birthday-celebration/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/saklincodes/birthday-celebration?style=for-the-badge&color=ff6699)](https://github.com/saklincodes/birthday-celebration/network/members)
[![Vercel](https://img.shields.io/badge/Vercel-Deployed-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://birthday-celebration-woad-chi.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-black.svg?style=for-the-badge)](LICENSE)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️%20&%20Code-ff3366?style=for-the-badge)](https://github.com/saklincodes)

<br />

🚀 **[View Live Demo](https://birthday-celebration-woad-chi.vercel.app)**

<br />

[Explore Features](#-key-features) •
[Quick Start](#-quick-start) •
[Customization Guide](#-customization-guide) •
[Tech Stack](#-tech-stack) •
[Project Structure](#-project-structure)

</div>

---

## 🌟 Overview

**Birthday Celebration** is an interactive web experience crafted to deliver a personalized, romantic, and memorable birthday surprise. Designed with rich micro-animations, particle cursor effects, and responsive typography, this project requires **zero build tools** or external bundling pipelines—just clean, accessible, and high-performance frontend code.

---

## ✨ Key Features

- 🎭 **Cinematic Intro Animations:** Staggered letter-drop typography and festive party hat entrance via CSS keyframe sequences.
- ⌨️ **Typewriter Text Engine:** Dynamic letter-by-letter typing animation displaying custom celebration taglines (e.g., *To The Prettiest Girl*).
- 💌 **Interactive Letter & Modal:** Smooth slide-down envelope mechanism revealing a custom love letter with floating heart GIFs and kitty animations.
- 💖 **Floating Heart Trail Cursor:** Real-time canvas/DOM particle physics trailing user mouse movements with randomized pastel hues.
- 🎈 **Festive Decorative Elements:** Floating balloons, rotating circular typography badges, pulsating stars, and floral accents.
- 📱 **Fully Responsive Layout:** Optimized across mobile, tablet, and high-resolution desktop viewports.
- ⚡ **Zero Dependencies / No Build Step:** Pure HTML5, Vanilla CSS3, JavaScript, and lightweight jQuery for DOM animations.

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/saklincodes/birthday-celebration.git
cd birthday-celebration
```

### 2. Launch in Browser

Simply double-click `index.html` or open it with your favorite browser:

```bash
# On Windows PowerShell
Start-Process index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

> 💡 **Pro Tip:** For the best development experience with hot-reloading, use the [VS Code Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.

---

## ⚙️ Customization Guide

Easily adapt this project for your loved one by modifying a few straightforward variables in `index.html` and `style.css`:

### 📝 1. Content & Messages (`index.html`)

Near the bottom of `index.html` (inside the `<script>` tag), you can customize:

| Variable / Element | Description | Default Value |
| :--- | :--- | :--- |
| `datetxt` | Tagline / Date reveal text | `"To The Prettiest Girl"` |
| `datatxtletter` | Long message typed inside the popup letter | Custom birthday message |
| `titleLetter` | Envelope letter title heading | `"To you"` |
| `.name span` | Recipient name on the profile badge | `My Love` |
| `.image img` | Recipient avatar image | `./images/r5.jpg` |

```javascript
// Example Configuration:
let datetxt = "To The Prettiest Girl";
let titleLetter = "For My Dearest";
let datatxtletter = "Wishing you endless happiness, laughter, and love on your special day! 💕";
```

### 🎨 2. Theme & Color Tokens (`style.css`)

CSS custom properties defined in `:root` allow instant palette re-theming:

```css
:root {
  --color-pink: #feecea;        /* Background tint */
  --color-white: #ffffff;       /* Header contrast */
  --color-black: #333333;       /* Bold outlines */
  --color-text-pink: #ff7882;   /* Main accent pink */
  --color-heart: #F61F1F;       /* Heart particle red */
  --color-bg-letter: #fff8e4;   /* Letter parchment background */
  --color-border: #DACCBF;      /* Subtle border tone */
}
```

---

## 📂 Project Structure

```text
birthday-celebration/
├── images/                   # Asset bundle (balloons, hats, decorations, GIFs)
│   ├── 1.png                 # Bunting banners
│   ├── balloon1.png          # Balloon decor #1
│   ├── balloon2.png          # Balloon decor #2
│   ├── hat.png               # Party hat illustration
│   ├── r5.jpg                # Recipient portrait photo
│   └── mewmew.gif            # Cute cat animation asset
├── index.html                # Semantic HTML structure & animation logic
├── style.css                 # Design tokens, typography & keyframe animations
└── README.md                 # Project documentation
```

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
  <img src="https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white" alt="Font Awesome" />
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white" alt="Google Fonts" />
</p>

---

## 🤝 Contributing

Contributions, feature suggestions, and pull requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, customize, and share it for your personal celebrations.

---

<div align="center">

Crafted with ❤️ by [**saklincodes**](https://github.com/saklincodes)

*If this project brought a smile to your loved one's face, don't forget to give it a ⭐ on GitHub!*

</div>
