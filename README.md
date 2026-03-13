<div align="center">
  <img src="./assets/sushi-1.png" alt="Sushiman Logo" width="150" />
  <h1>🍣 Sushiman</h1>
  <p><strong>Feel the taste of authentic Japanese food from anywhere and anytime.</strong></p>
  <p>A beautiful, fully-responsive, and modern restaurant landing page built with modern web principles.</p>
</div>

<br />

## 🌟 Overview

**Sushiman** is a premium landing page designed for an authentic Japanese sushi restaurant. It highlights the restaurant's top menu items, trending foods, and drinks with a minimalist and sophisticated visual hierarchy. The project focuses on clean code structure, beautiful UI/UX, and optimal performance.

> **Note:** This project was developed by following the excellent web design tutorial built by [JavaScript Mastery](https://www.youtube.com/@javascriptmastery/videos) as a learning exercise for mastering BEM and scalable CSS layout architectures.

## ✨ Features

- 🎨 **Modern & Vibrant UI/UX**: Designed with a thoughtful color palette (Crimson red & cream) emphasizing the authentic Japanese atmosphere.
- 📏 **BEM Methodology**: Adopts the **B**lock **E**lement **M**odifier naming convention for CSS. This ensures that the codebase is scalable, maintainable, and free of specificity conflicts.
- 🧩 **Modular CSS Architecture**: Styles are intelligently split into specific modules (e.g., `header.css`, `hero.css`, `trending.css`) mapped to their respective HTML sections, making the project highly organized.
- ♻️ **Reusable Styles & Variables**: Utilizes global CSS variables inside `:root` for colors and fonts, alongside utility classes (like `.flex-center`, `.flex-between`, `.sushi__title`) to prevent code repetition.
- 📱 **Fully Responsive**: Adapts seamlessly to all screen sizes—from large desktop monitors to smartphones—via fluid layouts and media queries.
- 🚀 **Smooth Animations**: Integrated with the [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) library to provide delightful typography and element reveal animations as the user scrolls.
- ⚡ **Powered by Vite**: Uses Vite as a lightning-fast build tool and local development server.

## 🛠️ Built With

- **HTML5** (Semantic structuring)
- **Vanilla CSS3** (Flexbox, Media Queries, Custom Properties)
- **JavaScript (ES6+)**
- **Vite** (Next Generation Frontend Tooling)
- **AOS** (Scroll Animation Library)

## 📐 CSS Architecture & Best Practices

This project takes styling seriously to ensure developer-friendly maintainability:

### 1. BEM Convention
You will find CSS classes strictly structured like `.header__nav`, `.about-us__image-sushi3`, and `.popular-foods__card`. This clarifies the relationship between the HTML layout and CSS rules at a glance.

### 2. Global Variables
Defined in `style.css`, updating a brand color or font globally only requires changing one line:
```css
:root {
  --playfair-display: "Playfair Display", serif;
  --primary-color: #b1454a; /* Crimson Red */
  --secondary-color: #121212; /* Dark typography */
  --color-creamson: #fff0de; /* Background base */
}
```

### 3. Reusable Utility Classes
Instead of repeating flexbox properties, universal utility classes are applied globally:
```css
.flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}
.flex-between {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

## 🚀 Getting Started

Follow these steps to run the landing page locally on your machine.

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed.

### Installation

1. **Clone the repository / open the folder:**
   ```bash
   cd html_css_js
   ```

2. **Install dependencies:**
   *(Required to download Vite & AOS)*
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Navigate to `http://localhost:5173` (or the port provided by Vite in your terminal) to view the application in action.

---
<p align="center">Built and styled for studying amazing Vanilla UI code practices.</p>
