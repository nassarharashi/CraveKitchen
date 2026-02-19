<p align="center">
  <img src="https://img.shields.io/badge/🍽-CraveKitchen-f97316?style=for-the-badge&labelColor=1e293b" alt="CraveKitchen" />
</p>

<h1 align="center">CraveKitchen — Restaurant Website</h1>

<p align="center">
  A fully responsive, multi-page restaurant website built with <strong>HTML5 & Tailwind CSS</strong>.<br/>
  15 professionally crafted pages — pure HTML &amp; CSS, 
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Halal_Friendly-10B981?style=flat-square" />
  <img src="https://img.shields.io/badge/Dark_Mode-Default-6366F1?style=flat-square" />
</p>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Pages](#-pages)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Color Palette](#-color-palette)
- [Typography](#-typography)
- [Screenshots](#-screenshots)
- [License](#-license)

---

## 🔍 Overview

**CraveKitchen** is a modern, static restaurant website designed to provide a complete online presence for a halal-friendly restaurant. The project covers everything from menu browsing and reservations to gallery showcases, customer testimonials, team pages, and legal policies — all built with pure HTML and Tailwind CSS (Play CDN). **No JavaScript is used anywhere in the project.**

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| � **Dark Mode** | Permanent dark theme — set via `class="dark"` on `<html>`, no JS needed |
| 📱 **Fully Responsive** | Responsive layout with a persistent nav bar visible on all screen sizes |
| 🧭 **Sticky Navigation** | Backdrop-blur header that stays visible while scrolling |
| 🖼️ **Gallery** | 12-item photo gallery grid with category labels |
| 📋 **Reservation Form** | Integrated reservation form on the homepage |
| 📬 **Contact Form** | Full contact page with form, Google Maps embed, and directions |
| ❓ **FAQ Accordion** | Expandable FAQ sections using native `<details>` elements — no JS |
| ⭐ **Testimonials** | Customer review cards with ratings, stats, and featured review |
| 👨‍🍳 **Team Profiles** | Management, chefs, and service team with role descriptions |
| 🥩 **Halal-Compliant** | All content is halal-friendly — no alcohol, wine, or bar references |
| 📄 **Legal Pages** | Privacy Policy, Return/Cancellation Policy, Terms & Conditions |
| 🔗 **Consistent Navigation** | Unified nav and footer across all 15 pages |

---

## 📄 Pages

### Main Pages

| # | Page | File | Description |
|---|------|------|-------------|
| 1 | **Home** | `index.html` | Hero, features, menu highlights, gallery preview, testimonials, partners, reservation form |
| 2 | **About** | `about.html` | Story, stats, values, team preview, timeline (2010–2026) |
| 3 | **Menu** | `services.html` | Menu categories overview with 6 category cards, popular dishes, special offers |
| 4 | **Menu Detail** | `service.html` | Single category detail (Appetizers) with items, prices, FAQ accordion |
| 5 | **Gallery** | `portfolio.html` | Gallery grid (12 items) with category labels, services showcase, link to album |
| 6 | **Photo Album** | `album.html` | Categorized photo album: Dishes, Restaurant, Team, Events (20 photos) |
| 7 | **Blog** | `blog.html` | Blog listing with featured post and article grid |
| 8 | **Blog Post** | `post.html` | Full article view with sidebar, tags, and related posts |
| 9 | **Contact** | `contact.html` | Contact form, info cards, Google Maps, directions, quick info |

### Utility Pages

| # | Page | File | Description |
|---|------|------|-------------|
| 10 | **FAQ** | `faq.html` | 15 frequently asked questions in 4 categories with accordion |
| 11 | **Testimonials** | `testimonials.html` | Rating stats, featured review, 9 customer review cards |
| 12 | **Our Team** | `team.html` | Leadership (3), chefs (4), service team (4), careers CTA |

### Legal Pages

| # | Page | File | Description |
|---|------|------|-------------|
| 13 | **Privacy Policy** | `privacy.html` | Data collection, cookies, data sharing, user rights |
| 14 | **Cancellation & Refund** | `return-policy.html` | Reservation cancellation, order refunds, catering, gift cards |
| 15 | **Terms & Conditions** | `terms.html` | Reservations, dining policies, delivery, allergies, IP, liability |

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Semantic markup, `<details>` for accordions, `<section>` structure |
| **Tailwind CSS** | Utility-first styling via [Play CDN](https://cdn.tailwindcss.com) — no build step required |
| **Google Fonts** | [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (headings) + [Inter](https://fonts.google.com/specimen/Inter) (body) |

> ⚠️ **Zero JavaScript.** The project contains no custom JS. Dark mode is enabled permanently via `class="dark"` on the `<html>` element.

> **No build tools needed.** Just open `index.html` in your browser — no npm, no bundler, no server required.

---

## 📁 Project Structure

```
CraveKitchen/
├── index.html            # Home page
├── about.html            # About page
├── services.html         # Menu overview
├── service.html          # Menu category detail
├── portfolio.html        # Gallery with filters
├── album.html            # Photo album
├── blog.html             # Blog listing
├── post.html             # Single blog post
├── contact.html          # Contact page
├── faq.html              # FAQ page
├── testimonials.html     # Customer testimonials
├── team.html             # Team page
├── privacy.html          # Privacy Policy
├── return-policy.html    # Cancellation & Refund Policy
├── terms.html            # Terms & Conditions
└── README.md             # This file
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/CraveKitchen.git
   cd CraveKitchen
   ```

2. **Open in browser**
   ```
   Just double-click index.html — or use Live Server in VS Code.
   ```

3. **Optional: VS Code Live Server**
   - Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
   - Right-click `index.html` → **Open with Live Server**

> No dependencies to install. No build step. It just works.

---

## 🎨 Color Palette

The project uses a custom **orange** brand color palette defined in Tailwind config:

| Token | Hex | Preview |
|-------|-----|---------|
| `brand-50` | `#fff7ed` | ![#fff7ed](https://via.placeholder.com/20/fff7ed/fff7ed) |
| `brand-100` | `#ffedd5` | ![#ffedd5](https://via.placeholder.com/20/ffedd5/ffedd5) |
| `brand-200` | `#fed7aa` | ![#fed7aa](https://via.placeholder.com/20/fed7aa/fed7aa) |
| `brand-300` | `#fdba74` | ![#fdba74](https://via.placeholder.com/20/fdba74/fdba74) |
| `brand-400` | `#fb923c` | ![#fb923c](https://via.placeholder.com/20/fb923c/fb923c) |
| `brand-500` | `#f97316` | ![#f97316](https://via.placeholder.com/20/f97316/f97316) |
| `brand-600` | `#ea580c` | ![#ea580c](https://via.placeholder.com/20/ea580c/ea580c) |
| `brand-700` | `#c2410c` | ![#c2410c](https://via.placeholder.com/20/c2410c/c2410c) |
| `brand-800` | `#9a3412` | ![#9a3412](https://via.placeholder.com/20/9a3412/9a3412) |
| `brand-900` | `#7c2d12` | ![#7c2d12](https://via.placeholder.com/20/7c2d12/7c2d12) |

**Dark mode** is permanently enabled by setting `class="dark"` on the `<html>` tag. Tailwind's `class` strategy activates all `dark:` variants automatically — no JavaScript required.

---

## 🔤 Typography

| Role | Font | Weight Range |
|------|------|-------------|
| **Headings** | Playfair Display | 400 – 900 |
| **Body** | Inter | 300 – 900 |

Applied via CSS:
```css
body { font-family: 'Inter', system-ui, sans-serif; }
.font-display { font-family: 'Playfair Display', serif; }
```

---

## 📸 Screenshots

> Replace with actual screenshots of your project.

| Dark Mode (Default) |
|---------------------|
| ![Dark](https://placehold.co/600x400/0f172a/f97316?text=Dark+Mode+Default) |

---

## 📌 Key Design Decisions

- **No JavaScript** — The entire site works with pure HTML & CSS; no scripts, no toggles, no event listeners
- **Permanent dark mode** — `class="dark"` on `<html>` activates all Tailwind `dark:` variants site-wide
- **No build tools** — Tailwind Play CDN keeps the project simple and beginner-friendly
- **Static HTML** — Each page is self-contained with its own `<head>`, nav, and footer
- **Halal-compliant content** — No alcohol, wine, cocktail, or bar references anywhere on the site
- **Realistic content** — Actual menu items with prices, real opening hours, practical policies
- **Consistent UX** — Same navigation (Home, About, Menu, Gallery, Blog, Contact) and footer across all pages

---

## 📝 License

This project is for **educational purposes** (practical training course). Feel free to use it as a template or reference for your own projects.

---

<p align="center">
  Made with ❤️ and Tailwind CSS<br/>
  <strong>CraveKitchen</strong> — Fresh food, fast service. Open daily since 2010.
</p>
