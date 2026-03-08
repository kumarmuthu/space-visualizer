# 🌌 space-visualizer

Interactive 3D Solar System built with Three.js featuring realistic orbits, planet labels, and smooth camera controls.

🎥 **Live Preview (GitHub Pages)**  
You can view the 3D Solar System project live here:  
[https://kumarmuthu.github.io/space-visualizer/](https://kumarmuthu.github.io/space-visualizer/)

| Version   | Link                                                                                | Description           |
|-----------|------------------------------------------------------------------------------------ |-----------------------|
| 🪐 **V1** | [space-visualizer/V1](https://kumarmuthu.github.io/space-visualizer/V1/index.html) | Original Solar System |
| ✨ **V2** | [space-visualizer/V2](https://kumarmuthu.github.io/space-visualizer/index.html)    | JPL Keplerian Edition |

---

## 🧠 About

**space-visualizer** is a browser-based 3D simulation of the Solar System using WebGL via Three.js. It showcases:

- ☀ The Sun at the center
- 🪐 8 Planets orbiting the Sun
- 🌙 Moon orbiting Earth
- ⭐ Starfield background
- 🖱 Mouse/Touch controls (rotate & zoom)
- 🎚 Speed controller
- 🏷 Labels for Sun, Moon & planets

---

## ⚙️ Features

### V1 — Original

✔ Sun with canvas-generated glow sprite  
✔ 8 planets with individual orbital speeds  
✔ Moon orbiting Earth  
✔ Saturn rings  
✔ Circular orbit lines  
✔ 6,000 star background  
✔ Speed slider control  
✔ Mouse / touch rotate & zoom  
✔ Planet + Moon name labels

### V2 — JPL Keplerian Edition

✔ Everything in V1, plus:  
✔ Real JPL Keplerian orbital elements (accurate positions)  
✔ Clickable planets & orbit lines with info modal  
✔ Sun, Moon & planet info panels  
✔ Time warp speed control (up to 1 day/sec)  
✔ Device compass orientation support  
✔ Layered star field with color variation  
✔ Planet glow sprites & pulsing Sun corona  
✔ Orbit highlight on click  
✔ Live ecliptic longitude & AU distance readout

---

## 📁 Demo Screenshot

**TODO**

---

## 📁 Folder Structure

```
space-visualizer/
├── index.html        ← Landing page (links to V1 & V2)
├── LICENSE
├── README.md
├── V1/
│   └── index.html   ← Original visualizer
└── V2/
    └── index.html   ← JPL Keplerian edition
```

---

## 📦 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/kumarmuthu/space-visualizer.git
   ```

2. Open `index.html` in your browser.

---

## 📤 Deploy on GitHub Pages

1. Go to your repository **Settings → Pages**
2. Select **Branch: main** and **/ (root)**
3. Save and wait a minute
4. Open your GitHub Pages URL

---

## 🖱 Controls

| Action      | Control                                 |
|-------------|-----------------------------------------|
| Rotate      | Drag mouse / touch drag                 |
| Zoom        | Mouse wheel / pinch                     |
| Speed       | Slider at top-left                      |
| Planet info | Click any planet or orbit line (V2)     |
| Compass     | Enable via compass button — mobile (V2) |

---

## 🛠 Built With

* [Three.js r128](https://threejs.org/) – 3D graphics engine
* JPL Keplerian Elements – Real planetary orbital data (V2)
* JavaScript & HTML5 – Core web technologies

---

## ✨ Future Ideas

* Real NASA planet textures
* Asteroid belt simulation
* Dwarf planets (Pluto, Ceres, Eris)
* Planet moons beyond Earth
* VR / WebXR support

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Muthukumar S  
GitHub: [https://github.com/kumarmuthu](https://github.com/kumarmuthu)

---
