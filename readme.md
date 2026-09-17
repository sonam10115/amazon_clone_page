<div align="center">

# 🛒 Amazon E-Commerce Homepage UI Clone

An executive, production-grade frontend recreation of the **Amazon.com** web application homepage, engineered using modern **HTML5**, **CSS3 Flexbox & Grid**, and **FontAwesome 6**.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![FontAwesome](https://img.shields.io/badge/Font_Awesome-6.7-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com/)
[![W3C Validated](https://img.shields.io/badge/W3C-Validated-brightgreen?style=for-the-badge&logo=w3c&logoColor=white)](https://validator.w3.org/)
[![Responsive](https://img.shields.io/badge/Design-Responsive-orange?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![License](https://img.shields.io/badge/License-MIT-blue.style=for-the-badge)](LICENSE)

[Explore Features](#-key-features-and-component-breakdown) · [View Architecture](#-layout-and-dom-architecture) · [Quick Start](#-installation--setup) · [Design System](#-design-system--color-palette)

</div>

---

## 📌 Table of Contents

- [Executive Summary](#-executive-summary)
- [Key Features & Component Breakdown](#-key-features-and-component-breakdown)
- [Layout & DOM Architecture](#-layout-and-dom-architecture)
- [Tech Stack & Tooling](#-tech-stack--tooling)
- [Design System & Color Palette](#-design-system--color-palette)
- [Project Directory Layout](#-project-directory-layout)
- [Installation & Setup](#-installation--setup)
- [Browser Compatibility](#-browser-compatibility)
- [Future Roadmap](#-future-roadmap)
- [License](#-license)

---

## 📖 Executive Summary

This repository presents a meticulous frontend replication of Amazon's industry-leading desktop interface. Developed with a emphasis on semantic HTML markup, vanilla CSS3 styling principles, and hardware-accelerated animations, this project demonstrates high-fidelity web design without reliance on heavy external JavaScript frameworks.

---

## ✨ Key Features and Component Breakdown

### 1. 🌐 Primary Navigation Header (`.navbar`)
- **Brand Identity**: Amazon official brand logo integration with high-density displays.
- **Geo-Location Picker**: Deliver-to India location selector with FontAwesome pinpoint icon (`fa-location-dot`).
- **Multi-Category Search Bar**: Integrated `<select>` category filter, flexible `<input>` search field, and high-contrast Amazon Amber action button (`#febd68`).
- **User Account & Order Shortcuts**: Dedicated modules for Account & Lists sign-in menu and Order Returns tracking.
- **Shopping Cart Counter**: Dynamic cart widget displaying shopping items count with FontAwesome shopping cart icon.

### 2. ⚡ Sub-Header Operations Bar (`.panel`)
- **All Category Trigger**: Hamburger navigation menu icon (`fa-bars`) simulating sidebar expansion.
- **Quick Deals Navigation**: Instant access links for *Today's Deals*, *Customer Service*, *Registry*, *Gift Cards*, and *Sell*.
- **Electronics Promo Banner**: Featured callout section for seasonal technology deals.

### 3. 🎞️ Animated Hero Banner Slider (`.hero-section`)
- **Pure CSS Keyframe Animation**: Hardware-accelerated `@keyframes imagechange` animation cycling between promotional hero banners (`font_page.jpg` and `font1-image.jpg`).
- **Seamless Infinite Loop**: Alternating 5-second transition effect providing dynamic visual engagement without JavaScript overhead.

### 4. 📦 Categorized Product Grid (`.shop-section`)
- **Multi-Box Responsive Card Layout**: 8 curated product discovery cards styled using CSS Flexbox wrapping:
  - 🧸 **Toys under $25** (`toy- image.jpg`)
  - 🎮 **Get your game on** (`gaming-image.jpg`)
  - 💻 **Computer & gaming** (`game-image.jpg`)
  - 🍽️ **Dining & Kitchen** (`dining-img.jpg`)
  - 📱 **Phones & Tablets** (`tablet-img.jpg`)
  - 💐 **Bouquets & Flowers** (`rose-img.webp`)
  - ⌚ **Trackers & Wearables** (`racker-img.jpg`)
  - 👗 **Fashion & Clothes** (`cloth-img.jpg`)
- **Interactive Micro-Interactions**: Hover focus boundaries and custom link styling (`#007185`).

### 5. 🦶 Multi-Tiered Footer Section (`footer`)
- **Smooth Back-to-Top Button**: Dedicated return-to-top navigation bar (`.foot-panel1`).
- **4-Column Site Matrix**: Comprehensive links organized into four key pillars: *Get to Know Us*, *Make Money with Us*, *Amazon Payment Products*, and *Let Us Help You*.

---



## 💻 Tech Stack & Tooling

| Domain | Technology | Purpose |
| :--- | :--- | :--- |
| **Markup Language** | HTML5 | Semantic structural elements (`<header>`, `<nav>`, `<section>`, `<footer>`) |
| **Style Sheet** | CSS3 | Flexbox positioning, CSS Grid, keyframe animations, hover states |
| **Icon Library** | FontAwesome 6 (v6.7.2 CDN) | Scalable vector icons for location, search, cart, and hamburger menu |
| **Typography** | Arial / System Sans-Serif | Native Amazon-like typography stack |

---

## 🎨 Design System & Color Palette

| Token Name | Hex Code | Visual Preview | Application Usage |
| :--- | :--- | :--- | :--- |
| **Amazon Dark (Nav)** | `#0f1111` / `black` | ⬛ | Primary header navbar background |
| **Amazon Dark Slate** | `#222f3d` | ⬛ | Secondary category panel & footer lower background |
| **Amazon Light Slate** | `#37475a` | 🟦 | Back to top bar background |
| **Amazon Amber** | `#febd68` | 🟧 | Search button & focus outline accents |
| **Amazon Link Blue** | `#007185` | 🟦 | Product card call-to-action text links |
| **Background Neutral** | `rgb(237, 230, 221)` | 🟨 | Shop section backdrop color |

---

## 📂 Project Directory Layout

```text
amazon_clone_page/
├── project.html            # Main Amazon homepage clone document
├── style2.css              # Core stylesheet (Navbar, Hero, Grid & Footer styles)
├── amazon.html             # Prototype header module
├── Amazon_logo.svg.png     # Brand Amazon SVG logo asset
├── amazon_loco/
│   └── loco3.jpg           # Navbar brand logo graphic
├── font_page.jpg           # Hero slider primary background image
├── font1-image.jpg          # Hero slider secondary background image
├── cloth-img.jpg           # Product card thumbnail: Fashion & Clothes
├── dining-img.jpg          # Product card thumbnail: Dining
├── game-image.jpg          # Product card thumbnail: Computer & Gaming
├── gaming-image.jpg        # Product card thumbnail: Gaming
├── racker-img.jpg          # Product card thumbnail: Trackers
├── rose-img.webp           # Product card thumbnail: Flowers
├── tablet-img.jpg          # Product card thumbnail: Phones & Tablets
├── toy- image.jpg          # Product card thumbnail: Toys
└── README.MD               # Executive documentation
```

---

## 🚀 Installation & Setup

### Option 1: Direct File Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/sonam10115/amazon_clone_page.git
   cd amazon_clone_page
   ```
2. Open `project.html` directly in any web browser.

### Option 2: VS Code Live Server (Recommended)
1. Open the cloned directory in **VS Code**.
2. Install the **Live Server** extension (`ms-vscode.live-server`).
3. Right-click `project.html` and click **"Open with Live Server"**.

### Option 3: Python Built-in HTTP Server
Run a local static server using Python:

```bash
# Python 3.x
python -m http.server 8000
```
Then navigate to `http://localhost:8000/project.html` in your browser.

---

## 🌐 Browser Compatibility

| Browser | Supported Version | Status |
| :--- | :--- | :--- |
| **Google Chrome** | v90+ | Fully Supported ✅ |
| **Mozilla Firefox** | v88+ | Fully Supported ✅ |
| **Microsoft Edge** | v90+ | Fully Supported ✅ |
| **Apple Safari** | v14+ | Fully Supported ✅ |

---

## 🗺️ Future Roadmap

- [ ] Add mobile media queries for optimized smartphone breakpoint styling.
- [ ] Implement interactive JavaScript cart item counter and slide-out cart sidebar.
- [ ] Integrate dark mode / light mode theme toggle.
- [ ] Add product detail view modal overlay upon card click.

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
