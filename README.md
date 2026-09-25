# PRABU-WOW — The Nusantara Simulator

A small browser strategy simulator about running a fictional Nusantara-style state while balancing infrastructure, policies, money, debt, inflation, employment, environment, and public approval.

> **Manage the country. Ignore logic. Repeat.** 😎

## 🎮 Play Online

**GitHub Pages:**  
https://stephanus-supandi.github.io/prabu_WOW/

**Blogger:**  
https://solitudelabs.blogspot.com/2026/09/prabu-wow-nusantara-simulator.html

## 🧠 Gameplay

You play as **PRABU-WOW**, managing a fictional nation month by month.

### Core systems

- 💰 GDP, budget, debt, inflation, employment, infrastructure, environment, and approval
- 🏗️ Infrastructure projects with construction time and economic/environmental effects
- 📜 Policy actions such as tax changes, fuel subsidies, quantitative easing, anti-corruption measures, and propaganda
- 🎲 Random events that can help or hurt the economy
- 🗞️ Dynamic Nusantara news ticker
- 📈 Monthly economic simulation
- 💾 Local browser save/load
- ⚡ Normal, Hard, and CHAOS modes
- 🔊 Procedural Web Audio effects
- ⛶ Fullscreen support
- 📱 Responsive layout for desktop and smaller screens

## 🗺️ Rendering

The game is a **single-file HTML/JavaScript project** with procedural canvas rendering.

No backend is required.

The game uses:

- HTML5
- CSS
- JavaScript
- Canvas 2D
- Web Audio API
- localStorage

The visual layer is generated in-browser rather than relying on an asset pipeline.

## 📁 Files

`index.html` is the GitHub Pages entry point.

`prabu_wow_simulator_final.html` is the standalone source copy.

Both files are kept in the repository root.

## ▶️ Run Locally

Open `index.html` directly in a modern browser, or serve the folder with a small local HTTP server:

```bash
python -m http.server 8000
```

Then open:

http://localhost:8000/

## ⚠️ Disclaimer

PRABU-WOW is a fictional game / parody-style simulator created for entertainment and experimentation.

It is not an official simulation of any real government, country, institution, public figure, or political organization. Game mechanics, economic relationships, events, names, and outcomes are intentionally simplified and fictional.

This project is not intended as economic, financial, governmental, or political advice.

## 🛠️ Project Status

Current release: **v0.x / prototype**

The project is intentionally experimental. Mechanics, balancing, rendering, and presentation may change in future versions.

## 🏛️ Credits

**Solitude Labs / BLOON**

Built as a browser-game experiment combining procedural graphics, simulation logic, UI design, and Web Audio.

---

**PRABU-WOW**

*Manage the country. Ignore logic. Repeat.*
