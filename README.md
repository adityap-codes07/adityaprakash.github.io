# Aditya Prakash — Research Engineer & Software Engineer Portfolio

A minimal, high-performance, responsive single-page portfolio website designed with clean semantic HTML, modern CSS design tokens, and a custom interactive canvas animation. Built to showcase academic research foundations, open-source contributions, engineering projects, and a custom built-in interactive terminal simulator.

---

## ✨ Features

* **System-Aware Dark Mode:** Uses CSS variables mapped to `[data-theme="dark"]` for instantaneous theme switching with smooth transitions.
* **Interactive Neural Canvas:** An HTML5 `<canvas>` rendering engine animating a dynamic graphical network structure that acts as a focal point on the hero screen.
* **Bespoke Grid Layouts:** Responsive layouts crafted with strict CSS Grid and Flexbox mechanics—completely free of bloated framework overhead.
* **Interactive Easter Egg Terminal:** Built-in hidden command-line simulation screen allows tech-savvy visitors to query your profile directly using shell commands.
* **Fully Scannable Sections:** Deduplicated, high-impact modules for Engineering Work, SymPy Open-Source Contributions, and Academic Research Focuses.

---

## 🛠️ Architecture & Technical Stack

The project relies purely on vanilla web core modules to maximize page speed performance and cross-device optimization:

| Layer | Technologies Used | Purpose |
| :--- | :--- | :--- |
| **Structure** | HTML5 Semantic Tags | High SEO indexability and strong structural hierarchy |
| **Styling** | Modern CSS3 (Variables, Grids, Tokens) | Fast-rendering, cohesive layouts without bulky frameworks |
| **Interactivity** | Vanilla JavaScript (ES6+) | Micro-interactions, light/dark toggling, state machines |
| **Graphics** | HTML5 Canvas API | Fluid, hardware-accelerated relational node animation |
| **Typography** | Google Fonts | Space Grotesk (Display), Inter (Body), JetBrains Mono (Terminal) |

---

## 📁 File Structure

├── index.html       # Single-page containing architecture, inline styles, and logic scripts
└── README.md        # Documentation and deployment configuration guide
Design Strategy Note: Code is strategically packed inside a unified single-page format to ensure zero extra HTTP asset requests during load time, optimizing runtime performance across both desktop architectures and mobile layouts.

## 💻 Technical Customization & Setup
Running the Website Locally
Clone the repository:

## Bash 
git clone [https://github.com/adityap-codes07/portfolio.git](https://github.com/adityap-codes07/portfolio.git)
cd portfolio
Launch with any local web server:

Using Python 3:

## Bash
python -m http.server 8000```
Using Node.js (serve):

## Bash
npx serve .
Open your browser and navigate to http://localhost:8000 (or the server port assigned).

## Adjusting Design Tokens
The styling landscape utilizes structural custom CSS properties at the top of the stylesheet. Modify these tokens within your <style> block to adapt typography, core branding colors, or curvature radii instantly across light and dark viewports:

CSS
:root {
  --bg: #FFFFFF;
  --text: #1C2331;
  --accent: #C9909A;  /* Custom Rose Branding */
  --navy: #1B2A4A;    /* Deep Structural Accent Color */
  --font-display: 'Space Grotesk', sans-serif;
}
## 📈 Optimization & Accessibility
Fluid Typography: Uses CSS clamp() functions to allow titles to seamlessly scale without generating explicit media query breakpoints.

Performance Safety Guard: Implements @media (prefers-reduced-motion: reduce) rules to instantly turn off rendering calculations and transitions for users with specific accessibility parameters enabled.

Network Preconnections: Explicitly uses preconnect tags to initialize structural handshakes with Google Font delivery channels early in the engine parsing loop.

## 📄 License
This portfolio codebase is open source and available under the MIT License. Feel free to customize and use it as your own!
