# 🧮 Bazaar Calculator

A sleek, all-in-one calculator web app designed for everyday bazaar and marketplace needs. Built as a lightweight PWA — works offline, installs on any device, and runs entirely in the browser.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat&logo=pwa&logoColor=white)

---

## ✨ Features

### 🔢 Standard Calculator
- Basic arithmetic: add, subtract, multiply, divide
- Percentage calculations
- Keyboard support for quick input
- Expression history on the display

### 📏 Unit Converter
- **Temperature** — °C, °F, Kelvin
- **Length** — km, m, cm, mm, miles, yards, feet, inches
- **Weight** — tonne, quintal, kg, g, mg, lb, oz
- **Volume** — litres, mL, m³, US gallons, US fl oz

### 💱 Currency Converter
- 11 currencies: USD, INR, PKR, EUR, GBP, AED, SAR, JPY, CAD, AUD, CNY
- Editable exchange rates (saved to browser storage)
- Instant two-way conversion

### 🏡 Land Area Converter
- Marla, Kanal, Acre, Sq ft, Sq yd, Sq m, Hectare
- South Asian land units with accurate conversion factors
- Reference: 1 Acre = 8 Kanal, 1 Kanal = 20 Marla = 5,445 sq ft

### 📦 Container / Volume Calculator
- Calculate capacity from Length × Breadth × Height
- Supports metres, centimetres, feet, and inches
- Output in litres

### 🛒 Shop Price Calculator
- **Price for a weight** — Enter price/kg and weight in grams → get total cost
- **Weight for a budget** — Enter price/kg and budget → get how much you can buy
- Shows step-by-step formula breakdown

---

## 🎨 Design

- **Samsung-inspired** circular button layout
- **Dark mode** — auto-detects system preference, with manual override
- **Responsive** — full-screen on mobile, two-column layout on desktop (900px+)
- **Monospace display** using JetBrains Mono + Space Grotesk UI font
- **Indian number formatting** (en-IN locale with lakhs/crores)

---

## 🚀 Getting Started

### Option 1: Open directly
Just open `index.html` in any modern browser — no build step required.

### Option 2: Local server
```bash
# Python
python -m http.server 3000

# Node.js
npx serve .
```
Then visit `http://localhost:3000`

### Option 3: Install as PWA
Open the app in Chrome/Edge → click the install icon in the address bar → use it like a native app.

---

## 📁 Project Structure

```
bazaar-calculator-deploy/
├── index.html              # Single-file app (HTML + CSS + JS)
├── bazaarcalc_logo.svg     # App logo / favicon
├── manifest.webmanifest    # PWA manifest
├── sw.js                   # Service worker (offline support)
└── README.md               # This file
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Structure & semantics |
| **CSS3** | Styling, dark mode, responsive layout |
| **Vanilla JS** | All logic — zero dependencies |
| **PWA** | Installable, offline-capable |
| **Google Fonts** | JetBrains Mono & Space Grotesk |

---

## 📱 PWA Support

Bazaar Calculator is a **Progressive Web App**:
- ✅ Installable on Android, iOS, Windows, macOS
- ✅ Works offline after first visit
- ✅ Standalone display mode (no browser chrome)
- ✅ Safe-area support for notched devices

---

## 📄 License

This project is open source. Feel free to use, modify, and distribute.

---

<p align="center">
  Made with ❤️ for the bazaar
</p>
