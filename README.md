# 📜 Divânu Lugāti't-Türk — Interactive Digital Atlas

An interactive, web-based digital atlas inspired by **Kaşgarlı Mahmud’s Divânu Lugāti't-Türk map (11th century)**.

This project recreates the historical map in a modern, explorable format using web technologies.  
Instead of only viewing the map as an image, users can **zoom, explore regions, and click areas to learn more**.

---

## ✨ Features

- 🗺️ High‑resolution historical map overlay
- 🔍 Smooth zoom & pan navigation (Leaflet.js)
- 🧠 Clickable regions with information popups
- 🌌 Cinematic dark / space themed UI
- 🪟 Glassmorphism styled info cards
- ⚡ Fast and lightweight (pure HTML/CSS/JS)
- 📚 Wikipedia links for deeper research

---

## 🎯 Purpose

The goal of this project is to:

- Digitize a historical cultural artifact
- Make learning history interactive
- Combine **technology + humanities**
- Transform static maps into discoverable experiences

This project demonstrates how software can be used for **digital heritage preservation** and **educational visualization**.

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (Glassmorphism + modern UI)
- JavaScript (Vanilla)
- Leaflet.js (map engine)
- JSON (region + detail data)

---

## 📂 Project Structure

```
.
├── index.html        # Main application
├── harita.png        # Map image overlay
├── map.json          # Region boundaries
├── details.json      # Information & descriptions
└── README.md
```

---

## 🚀 How to Run

### Option 1 — GitHub Pages (recommended)
Host the repository on GitHub Pages and open the link.

### Option 2 — Local
Simply open:

```
index.html
```

in your browser.

No server or installation required.

---

## 🧩 How It Works

1. Leaflet runs in simple CRS mode (image-based coordinates)
2. The historical map is loaded as an image overlay
3. Regions are defined in `map.json`
4. Details/descriptions come from `details.json`
5. Click → popup opens with information

---

## 📸 Preview

Open the live demo:

👉 https://ahmetberatkocyigit.github.io/map/

---


## ⭐ Future Plans

- Timeline mode
- Search functionality
- Mobile optimization
- More historical annotations
- Multi-language support
- Gamified exploration mode

---

## 📜 License

This project is open-source and free to use for educational purposes.
