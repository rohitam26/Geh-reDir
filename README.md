# Twogether (GehöreDir) — Shared Space for Couples

[![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20Responsive-38BDAE.svg)](#)
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero%20(Pure%20Vanilla)-brightgreen.svg)](#)

**Twogether (GehöreDir)** is an aesthetic, all-in-one shared space web application designed for couples to plan, track, and manage their joint life, shared finances, and shared milestones seamlessly in one private space.

Engineered as a lightweight, zero-dependency client-side application, Twogether provides offline-first persistent storage via `localStorage`, dual-partner profile attribution, and an elegant warm luxury design system.

---

## 🌟 Key Features

### 1. 👥 Dual-Partner Authentication & Presence
- **Personalized Roles:** Seamless switching between "Her" and "Him" profile views with distinct avatar highlights and customized dashboard greetings.
- **Demo Data Preloader:** Instant one-click demo data population for quick walkthroughs and testing.
- **Offline-First Persistence:** Complete state management stored safely in browser `localStorage`.

### 2. 💳 Shared Finance & Expense Management
- **Transaction Logging:** Track joint and individual expenses with categories, payment methods, and notes.
- **Fair Split Calculation:** Real-time balance settlement calculation indicating who owes what.
- **Monthly Filter & Analytics:** Filter expenses by month, category, or payer with automated spending summaries.

### 3. 🪙 Collaborative Savings Goals
- **Milestone Tracking:** Set target amounts and target dates for vacations, shared assets, or emergency funds.
- **Dual Contributions:** Record deposits from either partner with real-time percentage progress bars and milestone indicators.

### 4. 📅 Interactive Joint Calendar
- **Shared Event Scheduling:** Dedicated calendar view for anniversaries, date nights, appointments, and travel.
- **Date Navigation & Filters:** Interactive monthly calendar grid with clickable day inspection and event category chips.

### 5. ✅ Collaborative To-Do & Chores
- **Task Delegation:** Assign tasks to either partner or mark as shared.
- **Dynamic Badging:** Real-time badge counters in the sidebar showing pending items.
- **Categorization:** Separate chores, shopping lists, and quick reminders with instant completion toggles.

### 6. 🎯 Long-Term Life Goals
- **Couple Vision Board:** Track shared long-term milestones, dream trips, and career goals with target timelines.

---

## 🎨 Design System

The application features a bespoke warm-luxury aesthetic designed for intimacy and clarity:

| Token | Color | Hex Code | Purpose |
|:---|:---|:---|:---|
| **Cream** | Sand White | `#FAF8F4` | Primary app background |
| **Rose Deep** | Dusty Rose | `#B5607A` | Primary accent & active states |
| **Lavender** | Soft Violet | `#C4B5E8` | Secondary badges & tags |
| **Gold** | Warm Gold | `#C9A96E` | Highlights & milestone medals |
| **Ink** | Charcoal Espresso | `#2C2420` | High-contrast typography |

- **Typography:** *Cormorant Garamond* (headings & titles) + *DM Sans* (interface & numbers).
- **Responsive:** Fluid sidebar with mobile hamburger menu and collapsible navigation.

---

## 🚀 Getting Started

Because Twogether is built with pure standard web technologies, there are **no build steps or package installations required**.

### Quick Run
1. Clone the repository:
   ```bash
   git clone git@github-rohitam26:rohitam26/Geh-reDir.git
   cd Geh-reDir
   ```
2. Open `GehöreDir.html` in any web browser:
   - **macOS:** `open GehöreDir.html`
   - **Linux:** `xdg-open GehöreDir.html`
   - **Windows:** `start GehöreDir.html`

---

## 🛠️ Technology Stack

- **Markup & Layout:** Semantic HTML5, CSS Grid, and Flexbox
- **Styling:** Custom CSS3 design tokens and responsive media queries
- **Typography:** Google Fonts (*Cormorant Garamond*, *DM Sans*)
- **Scripting:** Modern Vanilla JavaScript (ES6+)
- **Storage:** Client-side HTML5 `localStorage`

---

## 🔒 Privacy & Data Ownership

All data created in Twogether remains entirely inside your browser's private `localStorage`. No personal details, finances, or notes are transmitted to third-party tracking servers.
