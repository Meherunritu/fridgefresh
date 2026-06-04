# fridgefresh
Zero-Waste Recipe Planner
# 🥬 FridgeFresh — Zero-Waste Recipe Planner

> A mobile-first, single-page web application that helps you track fridge ingredients, discover recipes based on what's about to expire, and follow step-by-step cooking instructions — all with zero page reloads.

![FridgeFresh Banner](https://images.unsplash.com/photo-1490818387583-1baba5e638af?w=1200&h=400&fit=crop&q=80)

---

## ✨ Live Demo

🌐 **[View Live on GitHub Pages](https://your-username.github.io/fridgefresh)**

> Replace the link above with your own GitHub Pages URL after deployment.

---

## 📸 Features at a Glance

| Feature | Description |
|---|---|
| 🗂 **Inventory Dashboard** | Add ingredients with expiry tracking and color-coded freshness badges |
| 🍳 **Recipe Matcher** | Smart recipe suggestions ranked by match % and expiry urgency |
| 👨‍🍳 **Cooking Mode** | Distraction-free, step-by-step kitchen UI with progress tracking |
| 🎨 **Custom Cursor** | Animated cursor with spring-physics hover interactions |
| 🌿 **Living Background** | Animated mesh gradient with floating ambient particles |
| 🎉 **Confetti Burst** | Celebration animation when you finish cooking a recipe |
| 📱 **Mobile-First** | Fully responsive, works on all screen sizes |

---

## 🛠 Tech Stack

- **HTML5** — Single `index.html` file, no build tools required
- **Tailwind CSS** — Loaded via CDN for utility styling
- **Vanilla JavaScript** — Zero dependencies, no frameworks
- **Google Fonts** — Playfair Display + Outfit typefaces
- **Unsplash** — Recipe imagery via URL (no API key needed)

---

## 🎨 Design System

### Color Palette

| Name | Hex | Usage |
|---|---|---|
| Forest Dark | `#0d3b2e` | Primary text, nav background |
| Forest Mid | `#1a5c46` | Headings, accents |
| Forest Light | `#2d8b63` | Buttons, highlights |
| Mint | `#a8edca` | Particles, tags |
| Cream | `#fdf8f0` | Page background |
| Amber | `#f59e0b` | Warnings, match badges |
| Blush | `#e07a5f` | Expiring today badges, delete buttons |
| Sage | `#6b9e82` | Secondary text, borders |

### Typography

- **Display / Headlines** — [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (serif, italic for emphasis)
- **Body / UI** — [Outfit](https://fonts.google.com/specimen/Outfit) (clean geometric sans-serif)

---

## 🗂 Project Structure

```
fridgefresh/
│
├── index.html        ← The entire application (HTML + CSS + JS)
└── README.md         ← This file
```

Everything lives in one file — no folders, no npm install, no terminal needed.

---

## 🚀 How to Run Locally

No setup required. Just open the file:

1. Download or clone this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. That's it — it works instantly with built-in dummy data

```bash
# Or clone via terminal
git clone https://github.com/your-username/fridgefresh.git
cd fridgefresh
open index.html
```

---

## 🌐 Deploy to GitHub Pages

1. Push `index.html` and `README.md` to a **public** GitHub repository
2. Go to **Settings → Pages**
3. Set Branch to `main`, folder to `/ (root)`
4. Click **Save**
5. Your site goes live at `https://your-username.github.io/repo-name`

Full beginner guide in [DEPLOYMENT.md](./DEPLOYMENT.md) *(optional)*.

---

## 📱 The Three Views

### 1. Inventory Dashboard
- Add ingredients with name, category, and days until expiry
- Items are sorted by urgency (expiring first)
- Color-coded badges: 🔴 Expires Today · 🟠 2 Days Left · 🟢 Fresh
- Animated delete with spring-physics hover effects on every row
- Live stats: total items, expiring count, fresh count

### 2. Recipe Match Screen
- 4 recipe cards matched against your expiring ingredients
- Each card shows: match percentage, prep time, expiring ingredients used
- Filter by: All · Under 20 min · Best Match (80%+)
- Cards lift and rotate on hover with a cinematic play button reveal
- Click any card to enter Cooking Mode

### 3. Cooking Mode
- Full dark-screen, distraction-free layout
- Large readable step text with step title
- Animated shimmer progress bar
- Clickable step dots for quick navigation
- Previous / Next navigation buttons
- Ingredient reminder shown on step 1
- 🎉 Confetti explosion on completion

---

## 🔮 Possible Future Enhancements

- [ ] LocalStorage persistence so inventory survives page refresh
- [ ] Search/filter ingredients by name or category
- [ ] Add custom recipes
- [ ] Shopping list generator for missing ingredients
- [ ] Dark mode toggle
- [ ] PWA support (installable on mobile home screen)
- [ ] Barcode scanner for quick item entry

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

Built as a portfolio submission project.

**GitHub:** [@your-username](https://github.com/your-username)

---

<p align="center">
  Made with 🥬 and zero waste
</p>
