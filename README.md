# 🛍️ NEXMART — E-Commerce Web Application

A fully functional, modern e-commerce frontend built with **pure HTML, CSS & JavaScript** — no frameworks, no dependencies, no build tools required.

![NEXMART Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## ✨ Features

- 🏠 **Hero Section** — Animated headline with floating product card & live stats
- 🗂️ **Category Filtering** — Filter by Electronics, Fashion, Home & Living
- 🔍 **Live Search** — Real-time product search as you type
- 🛒 **Shopping Cart** — Slide-in sidebar with quantity controls & total
- ❤️ **Wishlist** — Toggle wishlist per product
- 📢 **Promo Ticker** — Auto-scrolling announcement banner
- 🔔 **Toast Notifications** — Feedback for add-to-cart, wishlist actions
- 📱 **Responsive** — Mobile-first, works on all screen sizes
- 🎨 **Dark Aesthetic** — Premium dark theme with gold accents

---

## 🚀 Getting Started

### Option 1 — Open Directly
Just open `index.html` in any browser. No server needed.

### Option 2 — GitHub Pages (Recommended)

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save** — your site is live in ~60 seconds!

### Option 3 — Local Server
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# VS Code
# Use "Live Server" extension
```

---

## 📁 Project Structure

```
nexmart/
│
├── index.html        ← Complete application (single file)
├── README.md         ← You are here
└── .gitignore        ← Standard ignores
```

---

## 🎨 Tech Stack

| Layer      | Technology         |
|------------|--------------------|
| Markup     | HTML5              |
| Styling    | CSS3 (Variables, Grid, Flexbox, Animations) |
| Logic      | Vanilla JavaScript |
| Fonts      | Google Fonts (Bebas Neue, DM Sans, DM Serif Display) |

---

## 🛠️ Customization

### Add Products
Edit the `PRODUCTS` array in the `<script>` tag inside `index.html`:

```js
{ 
  id: 9, 
  name: "My Product", 
  cat: "electronics",       // electronics | fashion | home
  desc: "Short description",
  price: 1999,
  oldPrice: 2999,           // null if no discount
  emoji: "📦",
  rating: 4.5,
  badge: "New",             // "Hot" | "Sale" | "New" | null
  isNew: true,
  popular: false 
}
```

### Change Colors
Edit the CSS variables at the top of `<style>`:

```css
:root {
  --accent: #e8c547;    /* Gold — main accent */
  --accent2: #ff6b35;   /* Orange — badge color */
  --bg: #0a0a0a;        /* Page background */
  --text: #f0ece0;      /* Body text */
}
```

---

## 📸 Sections Overview

| # | Section | Description |
|---|---------|-------------|
| 1 | **Navbar** | Logo, search, cart, wishlist |
| 2 | **Hero** | Full-width headline + floating card |
| 3 | **Ticker** | Promo announcement scroller |
| 4 | **Categories** | 4-column clickable filter cards |
| 5 | **Products** | Filterable, searchable grid |
| 6 | **Promo Banner** | Sale highlight with CTA |
| 7 | **Footer** | Links + brand info |
| 8 | **Cart Sidebar** | Full cart with checkout flow |

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

> Built with ♥ — Upload to GitHub and share your store with the world!
