# Horizon · single‑file landing page

**Horizon** is a modern, fully responsive landing page built with **vanilla HTML, CSS, and JavaScript** — all in one single HTML file.  
It’s designed for speed, simplicity, and easy customization. No frameworks, no build step, no dependencies.

---

## ✨ Features

- ⚡ **Pure vanilla** — zero frameworks, no build tools  
- 📱 **Fully responsive** — works on mobile, tablet, desktop  
- 🧩 **Modular sections** — hero, social proof, features, CTA, footer  
- 🎨 **Clean, modern design** — gradients, subtle shadows, smooth animations  
- 🔔 **Interactive newsletter** — real‑time email validation + feedback  
- 🔗 **Smooth scroll** for anchor links  
- ♿ **Accessible** — semantic HTML, ARIA labels, high contrast  
- 🌍 **Cross‑browser** — works in all modern browsers  

---

## 🚀 Live demo

👉 [View live preview](https://landingpage-kappa-eight-38.vercel.app/) 

---

## 📁 Project structure

Just one file — no hidden complexity.
├── index.html # complete landing page (styles + script inline)
└── README.md 

---

## 🛠️ Customization guide

Everything is inline. Open `index.html` and start editing.

### 1. Colors & fonts

- **Primary blue:** `#2563eb`  
- **Dark background:** `#0f172a` (CTA section)  
- **Text gray:** `#475569`, `#334155`, `#64748b`  
- **Font:** `'Inter', -apple-system, ...` (system font stack – no download needed)  

To change the color scheme, replace the hex values in the `<style>` block.  
The gradient logo uses `background: linear-gradient(135deg, #2563eb, #7c3aed)`.

### 2. Content

| Section         | Location in HTML                                 |
|-----------------|--------------------------------------------------|
| Hero badge/title| `.hero-content .badge` / `h1`                   |
| Features        | `.features-grid` — 6 cards                      |
| Companies       | `.company-logos` — replace with your clients    |
| Newsletter      | `#cta` section — edit text & button             |
| Footer links    | `.footer-col` — update URLs and labels          |

### 3. JavaScript behavior

The only interactive component is the **newsletter signup**:

- Validates email (non‑empty + format)  
- Shows success / error messages  
- Clears input on success  
- Pressing `Enter` submits the form  

All code is inside the `<script>` tag at the bottom. You can easily extend it.

---

## 📸 Browser support

| Chrome | Firefox | Safari | Edge | Opera |
|--------|---------|--------|------|-------|
| ✅     | ✅      | ✅     | ✅   | ✅    |

*No IE11 support — uses modern CSS features like `backdrop-filter` and `grid`.*

---

## 🧠 Why one file?

- Perfect for **prototypes, MVPs, or simple product launches**  
- **Copy & paste** to any server or CMS  
- **Easy to email** or share as a single artifact  
- No build fatigue — just open and edit  

---

## ⚡ Deployment

Because it’s a single HTML file, you can deploy it anywhere:

- **GitHub Pages** — drag & drop  
- **Netlify / Vercel** — one‑click deploy  


---

## 🧩 Extending

Want to add more sections? Just copy a card block or feature grid.  
All styles are scoped and reusable.

**Suggested additions:**
- Pricing table  
- Testimonials slider  
- Dark mode toggle  
- Mobile hamburger menu  

---

## 📄 License

Free to use for personal and commercial projects. No attribution required — but it’s appreciated!  

---

## 🙋‍♀️ Questions?

Open an issue or reach out — I’m happy to help.

---

<p align="center">
  Made with ☕️ and vanilla JS  
  <br>
  <a href="https://github.com/developershubham01/hello">GitHub</a>
</p>
