<p align="center">
  <img src="./images/logo.jpg" alt="Mona Hotel Logo" width="180"/>
</p>

<h1 align="center">🏨 Mona Hotel — Responsive Hotel Booking Website</h1>

<p align="center">
  <strong>A fully responsive, single-page hotel website built with HTML5, CSS3, JavaScript & Bootstrap 5</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap 5"/>
  <img src="https://img.shields.io/badge/Font_Awesome_6-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white" alt="Font Awesome 6"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-completed-brightgreen?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/responsive-yes-blue?style=flat-square" alt="Responsive"/>
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square" alt="License"/>
</p>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Screenshots](#-screenshots)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Page Sections](#-page-sections)
- [Responsive Design](#-responsive-design)
- [Form Validation](#-form-validation)
- [Color Palette](#-color-palette)
- [Browser Support](#-browser-support)
- [Author](#-author)
- [License](#-license)

---

## 🌟 Overview

**Mona Hotel** is a professional, pixel-perfect, single-page hotel website designed for a fictional luxury 5-star hotel brand located in Bình Dương, Vietnam. The project demonstrates real-world front-end development skills including semantic HTML structure, custom CSS styling, responsive layout engineering, interactive JavaScript components, and Bootstrap integration.

The website serves as a complete hotel landing page with:
- A full-screen hero carousel for first impressions
- Service showcases with call-to-action buttons
- Room listings with detailed specifications and pricing
- An interactive booking form with client-side validation
- A news/blog section with card layouts
- A comprehensive footer with contact information and newsletter signup

> **Course:** CSW 304 — Web Development  
> **Student ID:** 2131200071  
> **Student:** Nguyễn Hoàng Giang

---

## 📸 Screenshots

### Desktop View
<p align="center">
  <img src="./Desktop UI.png" alt="Desktop Full Page" width="600"/>
</p>

### Desktop — Sticky Navigation & Go-to-Top Button
<p align="center">
  <img src="./Desktop UI (Menu and Go top Button) - scroll.JPG" alt="Desktop Sticky Nav" width="800"/>
</p>

### Mobile View
<p align="center">
  <img src="./Mobile UI.png" alt="Mobile Full Page" width="300"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Mobile UI - Menu.png" alt="Mobile Sidebar Menu" width="300"/>
</p>

---

## ✨ Features

### 🎨 UI/UX
| Feature | Description |
|---------|-------------|
| **Hero Carousel** | Auto-sliding image carousel with 4 high-quality slides, navigation arrows, and dot indicators |
| **Sticky Navigation** | Navigation bar becomes fixed on scroll for persistent access to menu items |
| **Hover Effects** | Card lift animations, button color transitions, and image zoom effects |
| **Go-to-Top Button** | Floating button with smooth scroll, appears when user scrolls past the hero section |
| **Gold Accent Theme** | Consistent luxury gold (#CFB855) accent color throughout the design |

### 📱 Responsive Design
| Feature | Description |
|---------|-------------|
| **Mobile Sidebar** | Slide-in sidebar navigation with hamburger toggle button for mobile |
| **Collapsible Submenus** | Dropdown submenus (Dịch Vụ, Loại Phòng) with toggle animation on mobile |
| **Adaptive Layout** | Grid system adjusts from multi-column (desktop) to single-column (mobile) |
| **Hidden Elements** | Top header bar and welcome paragraph hidden on mobile for cleaner UX |

### ⚙️ Functionality
| Feature | Description |
|---------|-------------|
| **Booking Form Validation** | Full client-side validation for name, phone (10 digits), dates, guests, and room type |
| **Numeric-only Phone Input** | Restricts phone field to numeric characters only via `keypress` event |
| **Dynamic Error Messages** | Inline error messages appear/disappear per field with `.show` class toggling |
| **Dropdown Menus** | Bootstrap-powered dropdown menus with hover activation on desktop |

---

## 🛠 Tech Stack

| Technology | Version | Usage |
|-----------|---------|-------|
| **HTML5** | — | Semantic page structure and content |
| **CSS3** | — | Custom styling, animations, transitions, media queries |
| **JavaScript** | ES6+ | Form validation, DOM manipulation, scroll events, sidebar toggle |
| **Bootstrap** | 5.3.3 | Grid system, carousel, dropdown, form controls, utilities |
| **Font Awesome** | 6.7.2 | Icon library for UI elements (200+ icons used) |
| **Google Fonts** | — | Roboto (body), Merriweather (headings) |

---

## 📁 Project Structure

```
Mona Hotel/
│
├── 📄 Mona_hotel.html          # Main HTML file (708 lines)
├── 🎨 Mona_hotel.css           # Custom stylesheet (912 lines)
├── 📖 README.md                # Project documentation (this file)
│
├── 📸 Desktop UI.png           # Desktop screenshot
├── 📸 Desktop UI (Menu...).JPG # Desktop sticky nav screenshot
├── 📸 Mobile UI.png            # Mobile screenshot
├── 📸 Mobile UI - Menu.png     # Mobile sidebar screenshot
│
└── 🖼️ images/                  # Image assets (20 files)
    ├── logo.jpg                # Hotel brand logo
    ├── slide-1.jpg             # Carousel slide 1
    ├── slide-2.jpg             # Carousel slide 2
    ├── slide-3.jpg             # Carousel slide 3
    ├── slide-4.jpg             # Carousel slide 4
    ├── introduction.jpg        # Introduction section image
    ├── swimming-service.jpg    # Swimming pool service
    ├── restaurant-service.jpg  # Restaurant service
    ├── restroom-service.jpg    # Rest room service
    ├── standard-room.jpg       # Standard room type
    ├── double-room.jpg         # Double room type
    ├── luxury-room.jpg         # Luxury room type
    ├── booking-background.jpg  # Booking section background
    ├── news-1.jpg ~ news-6.*   # News article images (6 files)
    └── prize.png               # Award badges
```

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge, Safari)
- No build tools, package managers, or servers required

### Installation & Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/mona-hotel.git

# 2. Navigate to the project directory
cd mona-hotel

# 3. Open in browser
# Option A: Double-click Mona_hotel.html
# Option B: Use VS Code Live Server extension
# Option C: Use any local HTTP server
python -m http.server 8000
```

Then navigate to `http://localhost:8000/Mona_hotel.html` in your browser.

> **💡 Tip:** For the best experience, use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VS Code extension for hot-reloading during development.

---

## 📑 Page Sections

The website is structured as a single-page application with **8 major sections**:

```
┌─────────────────────────────────────────┐
│  1. TOP HEADER BAR                      │  ← Address, Phone, Social Links
├─────────────────────────────────────────┤
│  2. NAVIGATION BAR (Sticky on scroll)   │  ← Logo, Menu, Search
├─────────────────────────────────────────┤
│  3. HERO CAROUSEL                       │  ← 4 auto-sliding images + welcome text
├─────────────────────────────────────────┤
│  4. INTRODUCTION                        │  ← Hotel description + CTA button
├─────────────────────────────────────────┤
│  5. SERVICES (Dịch Vụ)                  │  ← 3 service cards (Pool, Room, Restaurant)
├─────────────────────────────────────────┤
│  6. FACILITIES (Tiện Ích)               │  ← 6 facility items with icons
├─────────────────────────────────────────┤
│  7. ROOM TYPES (Các Loại Phòng)         │  ← 3 room cards with specs + pricing
├─────────────────────────────────────────┤
│  8. BOOKING FORM (Liên Hệ Đặt Phòng)   │  ← 6-field form with full validation
├─────────────────────────────────────────┤
│  9. NEWS (Tin Tức)                       │  ← 3 article cards + 3 thumbnail cards
├─────────────────────────────────────────┤
│ 10. FOOTER                              │  ← Logo, Contact, Awards, Newsletter
└─────────────────────────────────────────┘
```

### Room Types & Pricing

| Room Type | Capacity | Area | Bed | Price |
|-----------|----------|------|-----|-------|
| Standard Room | 2 guests | 20m² | 1 double bed | $30/night |
| Double Room | 4 guests | 30m² | 2 double beds | $60/night |
| Luxury Room | 2 guests | 50m² | 1 King-size bed | $120/night |

---

## 📱 Responsive Design

The website implements a **mobile-first responsive strategy** with a breakpoint at **767.98px**:

| Viewport | Layout | Navigation | Hero Height |
|----------|--------|------------|-------------|
| **Desktop** (≥768px) | Multi-column grid | Horizontal navbar + dropdowns | 100vh |
| **Mobile** (<768px) | Single-column stack | Hamburger → Slide-in sidebar | 50vh |

### Key Responsive Behaviors:
- **Desktop → Mobile:** Top header bar is hidden; navigation collapses into a sidebar
- **Welcome overlay:** Text width adjusts from 60% to 85%, font scales down
- **Service/Room cards:** Stack vertically on mobile with full-width layout
- **Booking form:** Labels center-aligned, submit button stretches to 90% width
- **Footer:** Logo and awards center-aligned; section headers uppercased

---

## ✅ Form Validation

The booking form implements **client-side JavaScript validation** with the following rules:

```
┌──────────────────────────────────────────────────────────┐
│  Field         │  Validation Rule          │  Error Msg  │
├──────────────────────────────────────────────────────────┤
│  Họ tên        │  Not empty (trimmed)      │  ✗ shown    │
│  Số điện thoại │  Exactly 10 digits        │  ✗ shown    │
│  Ngày đến      │  Not empty                │  ✗ shown    │
│  Ngày đi       │  Not empty                │  ✗ shown    │
│  Số người      │  Not empty & ≥ 1          │  ✗ shown    │
│  Loại phòng    │  Not default "---"        │  ✗ shown    │
└──────────────────────────────────────────────────────────┘
```

**Validation Flow:**
1. `event.preventDefault()` blocks native form submission
2. All existing `.show` classes are cleared (reset previous errors)
3. Each field is validated sequentially
4. Failed fields display inline error via `.error.show` class
5. On success → `alert("Đặt phòng thành công!")`

---

## 🎨 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| 🟡 **Gold** | `#CFB855` / `#C9B046` / `#CAB148` | Primary accent, icons, buttons, headings |
| ⚫ **Black** | `#000000` / `#1C1C1C` | Header, footer, service/room section backgrounds |
| ⬜ **White** | `#FFFFFF` | Card backgrounds, body text |
| 🔘 **Gray** | `#818181` / `#878787` / `#929292` | Secondary text, descriptions, nav links |
| 🟤 **Dark Gray** | `#212529` / `#333` | Dropdown menus, card titles |
| ⬛ **Light BG** | `#F5F5F5` | Introduction section background |

---

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Google Chrome | 90+ | ✅ Fully Supported |
| Mozilla Firefox | 88+ | ✅ Fully Supported |
| Microsoft Edge | 90+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Opera | 76+ | ✅ Fully Supported |

---

## 🧩 Key Implementation Details

### Sticky Navigation
```javascript
window.addEventListener("scroll", function () {
  const topHeaderHeight = document.querySelector(".top-header").offsetHeight;
  const logoMenuBar = document.querySelector(".logo-menu-bar");
  if (window.scrollY >= topHeaderHeight) {
    logoMenuBar.classList.add("sticky");
  } else {
    logoMenuBar.classList.remove("sticky");
  }
});
```

### Mobile Sidebar Toggle
```javascript
function openSidebar() {
  document.getElementById("mobile-sidebar").classList.add("open");
}
function closeSidebar() {
  document.getElementById("mobile-sidebar").classList.remove("open");
}
function toggleSubMenu(event, submenuId) {
  event.preventDefault();
  const submenu = document.getElementById(submenuId);
  submenu.style.display = submenu.style.display === "block" ? "none" : "block";
}
```

### Go-to-Top Button
```javascript
const goTopBtn = document.querySelector('.go-top');
window.addEventListener('scroll', () => {
  goTopBtn.classList.toggle('visible', window.scrollY > 100);
});
goTopBtn.addEventListener('click', () => {
  window.scrollTo({ top: 0, behavior: 'smooth' });
});
```

---

## 👤 Author

**Nguyễn Hoàng Giang**
- 🆔 Student ID: 2131200071
- 🏫 Course: CSW 304 — Web Development
- 📧 Email: monahotel@gmail.com

---

## 📄 License

This project is developed for **educational purposes** as part of the CSW 304 coursework.  
All images and content are used for demonstration only and belong to their respective owners.

---

<p align="center">
  <sub>Built with ❤️ using HTML, CSS, JavaScript & Bootstrap</sub>
</p>
