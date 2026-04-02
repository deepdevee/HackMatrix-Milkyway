# 🚗🌿 Commute Emission Comparer

> HackMatrix 2026 — VIT Bhopal | Track: Sustainability | Problem ID: HM20

A simple web app that shows commuters the **CO₂ emissions and travel cost** of their daily route across four transport modes — Car, Bus, Metro, and Cycling — side by side, so they can make greener choices without any guesswork.

---

## 🧩 Problem Statement

People are unaware of the CO₂ difference between commuting by car versus public transport. Without a simple, visual comparison tool, most commuters default to driving — contributing unnecessarily to urban carbon emissions.

---

## 💡 Our Solution

Enter your commute distance (in km) and instantly get a side-by-side breakdown of:

| Mode | CO₂ Emitted | Daily Cost | Monthly Savings vs Car |
|------|------------|------------|------------------------|
| 🚗 Car | ~0.21 kg/km | High | — |
| 🚌 Bus | ~0.089 kg/km | Low | ✅ Highlighted |
| 🚇 Metro | ~0.041 kg/km | Low | ✅ Highlighted |
| 🚴 Cycling | 0 kg/km | Free | ✅ Best |

The app highlights the **greenest** and **most affordable** option automatically.

---

## ✨ Features

- 📏 Simple distance input form
- 📊 Side-by-side emission & cost comparison table
- 💰 Monthly savings calculator
- 🏅 Greener mode recommendation badge
- 📱 Responsive — works on mobile and desktop
- ⚡ No backend, no login — instant results

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript |
| Visualisation | Chart.js |
| Maps (optional) | OpenStreetMap |
| Emission Data | IPCC / Govt transport constants |
| Hosting | GitHub Pages / Vercel |

> No backend or database required — all calculations run client-side.

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/commute-emission-comparer.git

# Open in browser
cd commute-emission-comparer
open index.html
```

No npm install, no build step. Just open `index.html` and it works.

---

## 📁 Project Structure

```
commute-emission-comparer/
├── index.html          # Main app page
├── style.css           # Styling
├── script.js           # Emission calculation logic
├── README.md           # This file
└── assets/
    └── icons/          # Transport mode icons
```

---

## 🧮 Emission Factors Used

| Mode | CO₂ per km | Source |
|------|-----------|--------|
| Car (petrol) | 0.21 kg | IPCC / Govt data |
| Bus | 0.089 kg | IPCC / Govt data |
| Metro / Rail | 0.041 kg | IPCC / Govt data |
| Cycling | 0.000 kg | — |

---

## 📈 Future Scope

- 🗺️ Live distance input via Google Maps / OpenStreetMap API
- 🏙️ City-specific emission factors
- 👤 User profile to track commute habits over time
- 🎮 Gamification — streak rewards for choosing green modes
- 🏆 City leaderboard showing collective CO₂ saved

---

## 👥 Team

| Name | Role |
|------|------|
| [Member 1] | Frontend & UI |
| [Member 2] | Logic & Calculations |
| [Member 3] | Design & Presentation |
| [Member 4] | Research & Documentation |

---

## 🏫 Event Details

- **Hackathon:** HackMatrix 2026
- **Organiser:** Linpack Club, VIT Bhopal University
- **Problem ID:** HM20
- **Track:** Sustainability
- **Platform:** Web App
- **Contact:** linpackclub@vitbhopal.ac.in

---

## 📄 License

MIT License — free to use, modify, and share.
