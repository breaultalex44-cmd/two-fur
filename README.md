# 🐺 Two-Fur | Frost & Aurora Edition

> **Pan-Canadian Winter Hub, Global Intelligence & Expanded Festivals Calendar**

**Two-Fur** is a premium, high-performance web calendar application optimized for both mobile and desktop screens. It combines pan-Canadian statutory holidays, global election tracking, live lunar cycles, 15+ major international festivals, and a dynamic local event logging engine ("Take a Tok") into a unified, fluid interface.

🌐 **Live Demo:** [https://breaultalex44-cmd.github.io/two-fur/](https://breaultalex44-cmd.github.io/two-fur/)

---

## ❄️ Frost & Aurora Design System

- **Atmospheric Winter Aesthetic:** Styled with deep arctic gradients, frosted glassmorphism (`backdrop-filter`) panels, custom icy scrollbars, and dynamic neon accent lighting.
- **Mobile-First Responsiveness:** Features an interactive, draggable bottom sheet for seamless single-handed navigation on compact mobile screens.

---

## ✨ Key Features & Capabilities

### 📅 1. Comprehensive Pan-Canadian & Global Intelligence
- **Canadian Statutory & Provincial Holidays:** Full, accurate coverage across all provinces and territories for 2026 and 2027.
- **15+ Worldwide Cultural Festivals:** Integrated tracking for iconic global celebrations including *Venice Carnival, Rio Carnival, Holi Festival of Colors, Songkran, Oktoberfest, Diwali, and Día de los Muertos*.
- **World Elections & Global Observances:** Stay informed on international electoral shifts, UN observances, and historic milestones.
- **Lunar Phase Engine:** Real-time astronomical calculation of moon phases (*New Moon, First Quarter, Full Moon, Last Quarter*) rendered directly on calendar cells.

### 📝 2. "Take a Tok" Dynamic Event Creator
- **Custom Event Logging:** Instantly log personal tasks, operational briefings, or social events with category tagging, priority levels, time windows, and locations.
- **Persistent Pinned Badges:** Pin critical tasks across all calendar views with custom highlighted badges.
- **Zero-Backend Local Persistence:** All custom logs are encrypted in client memory and stored reliably via the browser's `localStorage` API.

### 🔍 3. Real-Time Global Search
- Instant keyword filtering across holidays, festivals, custom logs, and detailed intelligence summaries, complete with one-tap date jumping.

---

## 🛠️ Tech Stack & Architecture

| Layer | Technology / Implementation |
| :--- | :--- |
| **Core Architecture** | Single-file Vanilla HTML5 & Modern ES6+ JavaScript |
| **Styling & Effects** | Tailwind CSS (CDN) with Custom Glassmorphism CSS |
| **State & Storage** | Browser `localStorage` API for zero-latency data persistence |
| **Layout & Touch** | Mobile touch-action event handling & smooth physics dragging |
