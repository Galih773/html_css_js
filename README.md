<div align="center">
  <br />
    <a href="https://youtu.be/QRrPE9aj3wI?feature=shared" target="_blank">
      <img src="https://github.com/adrianhajdin/project_html_css_website/assets/151519281/562e0f27-4b93-41cb-a63d-7c50940fc0ad" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-HTML_5-black?style=for-the-badge&logoColor=white&logo=html5&color=E34F26" alt="html5" />
    <img src="https://img.shields.io/badge/-css3-black?style=for-the-badge&logoColor=white&logo=css3&color=1572B6" alt="css3" />
  </div>

  <h3 align="center">Sushiman - Landing Page</h3>

   <div align="center">
     This awesome project was built step-by-step alongside the brilliant <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a> YouTube tutorial. 
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features & Best Practices](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Code Snippets](#snippets)
6. 🔗 [Assets & Links](#links)
7. 🚀 [More from JSM](#more)

## 🚨 Study Source

This repository is my personal code implementation from studying the fantastic web design tutorial by <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a>. 

By building this project, I significantly leveled up my Vanilla CSS workflow and layout structural concepts!

<a href="https://youtu.be/QRrPE9aj3wI?feature=shared" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="introduction">🤖 Introduction</a>

**Sushiman** is a premium landing page designed for an authentic Japanese sushi restaurant. It highlights the restaurant's top menu items, trending foods, and drinks with a minimalist and sophisticated visual hierarchy. 

While following the JSM tutorial, my primary focus was not just copying code, but deeply understanding modern CSS architecture, BEM methodology, and how to structure a scalable project for production.

## <a name="tech-stack">⚙️ Tech Stack</a>

- **HTML 5** (Semantic Document Structuring)
- **CSS 3** (Flexbox, Grid, Custom Variables)
- **Vite** (Next-Generation Frontend Tooling & Local Server)

## <a name="features">🔋 Features & Best Practices Applied</a>

This project was built with a strong emphasis on clean code and developer-friendly maintainability. Here is what makes the codebase robust:

👉 **BEM Methodology**: Adopts the **B**lock **E**lement **M**odifier naming convention for CSS classes (e.g., `.header__logo`, `.popular-foods__card`). This promotes a clear HTML-to-CSS relationship and avoids specificity conflicts.

👉 **Modular CSS Architecture**: Styles are intelligently split into specific files based on their layout sections (e.g., `header.css`, `hero.css`, `trending.css`). They are then imported into a central `style.css` file, making maintenance incredibly easy.

👉 **Reusable Global Variables**: Utilizes global CSS variables inside `:root` for brand colors and fonts. Changing the theme of the entire website only requires editing one single file.

👉 **Reusable Utility Classes**: Instead of repeating flexbox properties everywhere, universal utility classes are applied globally (e.g., `.flex-center`, `.flex-between`).

👉 **Smooth Scroll Animations**: Integrated with the AOS library to provide delightful typography and element reveal animations as the user scrolls down the landing page.

👉 **Fully Responsive Layouts**: The application fluidly adapts to all devices, from desktop monitors to smartphones, by avoiding fixed `px` widths where possible and using smart Media Queries.

**Sections Included:**
* Dynamic Navigation Bar 
* Creative Splitted Hero Section
* "About Us" Image Grids
* Popular Food Cards
* Trending Sushi and Drinks Layout
* Interactive Newsletter Signup and Footer

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/project_html_css_website.git
cd project_html_css_website
```

**Installation**

Install the project dependencies (specifically for Vite server & AOS module):

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the beautiful sushi!

## <a name="snippets">🕸️ Code Snippets</a>

Here is a glimpse into how clean and modular the CSS approach is:

<details>
<summary><code>style.css</code> (Global Configuration)</summary>

```css
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;800;900&display=swap");

/* Modular imports for independent component styling */
@import url("./sections/header.css");
@import url("./sections/hero.css");
@import url("./sections/about.css");
@import url("./sections/popular.css");
@import url("./sections/trending.css");

/* CSS variables for reusablity across all files */
:root {
  --playfair-display: "Playfair Display", serif;
  --plus-jakarta-sans: "Plus Jakarta Sans", sans-serif;

  --primary-color: #b1454a;
  --secondary-color: #121212;
  --color-creamson: #fff0de;
}

/* Reusable Utility Classes */
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

</details>

<details>
<summary><code>header.css</code> (BEM Styling Example)</summary>

```css
/* Block */
.header__nav {
  display: flex;
  overflow: hidden;
}

/* Element */
.header__logo {
  flex: 1;
  display: flex;
  position: relative;
  padding: 20px;
}

.header__logo-overlay {
  position: absolute;
  inset: 0;
  width: 100%;
  background-color: var(--primary-color);
  z-index: -1;
}

.header__menu li {
  font-weight: 500;
  text-transform: uppercase;
  font-family: var(--plus-jakarta-sans);
  color: var(--secondary-color);
  cursor: pointer;
}
```

</details>


## <a name="links">🔗 Assets & Links</a>

The beautiful assets and icons used in this project are provided by JSM [here](https://drive.google.com/file/d/1feqXd1mPKjdQDjd3l4hV_JcX-l1mJRor/view).

## <a name="more">🚀 More from JSM</a>

**Advance your skills with Next.js 14 Pro Course**

Enjoyed creating this project? Dive deeper into our PRO courses for a richer learning adventure. They're packed with detailed explanations, cool features, and exercises to boost your skills. Give it a go!

<a href="https://jsmastery.pro/next14" target="_blank">
<img src="https://github.com/sujatagunale/EasyRead/assets/151519281/557837ce-f612-4530-ab24-189e75133c71" alt="Project Banner">
</a>

<br />
<br />

**Accelerate your professional journey with the Expert Training program**

And if you're hungry for more than just a course and want to understand how we learn and tackle tech challenges, hop into our personalized masterclass. We cover best practices, different web skills, and offer mentorship to boost your confidence. Let's learn and grow together!

<a href="https://www.jsmastery.pro/masterclass" target="_blank">
<img src="https://github.com/sujatagunale/EasyRead/assets/151519281/fed352ad-f27b-400d-9b8f-c7fe628acb84" alt="Project Banner">
</a>

---
<p align="center">Made with ❤️ while studying from JavaScript Mastery.</p>
