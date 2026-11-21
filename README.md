# 🎯 KANCHA: Street Marbles Ustad (कंचा: स्ट्रीट उस्ताद)

> **An authentic Indian street marble physics game built with Google Gemini in 2 prompts.**  
> Built as a single self-contained HTML5 file with zero dependencies, 60 FPS mobile gameplay, and procedural Web Audio.

[![Play Online](https://img.shields.io/badge/PLAY_NOW-Live_Demo-ff8f00?style=for-the-badge&logo=googlechrome&logoColor=black)](https://jalagamkalyan.github.io/kancha-street-ustad/)
[![YouTube](https://img.shields.io/badge/YouTube-Kalyan's_Lab-ff0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@KalyansLab)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

---

## 🎮 Play Instantly in Your Browser

👉 **[https://jalagamkalyan.github.io/kancha-street-ustad/](https://jalagamkalyan.github.io/kancha-street-ustad/)**  
*(Optimized for mobile touch slingshot aiming and desktop mouse controls)*

---

## 🧠 The Exact 2 Gemini Prompts Used

This entire game was architected and built using two simple prompts in Google Gemini:

### **Prompt 1: Research & Game Mechanics**
```text
Research the traditional Indian street game of Kancha (marbles/goti). 
Define the core gameplay rules: slingshot power aiming, pairwise elastic marble collision, the chalk circle boundary, ring trap foul penalties, and backspin english.
```

### **Prompt 2: Single-File Web Engine Architecture**
```text
Build Kancha: Street Marbles Ustad as a single self-contained index.html file using HTML5 Canvas and vanilla JavaScript. 
Include smooth touch/mouse slingshot controls, a spin pad for backspin brakes, AI opponent mode, and procedural Web Audio synthesis for marble clacks without any external asset files.
```

---

## 🕹️ Game Features Built by Gemini

1. **Slingshot Aim & Power:**  
   - Pull back on the golden Striker on the baseline crease to adjust shot angle and slingshot velocity.
   - Release to launch into the chalk ring.

2. **The "Ring Trap" Foul & Backspin Control:**  
   - In traditional street Kancha, if your striker comes to rest **inside** the chalk circle, it is a **Foul (-1 point penalty)**.
   - Use the **Spin Pad** to apply **Backspin Brake** or **Side Curve English**. When the striker strikes a marble, reverse impulse pulls it back out of the circle, preventing fouls!

3. **Raja Goti & Ring-Out Scoring:**  
   - Knocking any standard marble out of the chalk circle awards **+1 point** and grants a **Bonus Turn**.
   - Knocking the central red **Raja Goti** out awards **+3 points**.

4. **Striker Armory:**  
   - **Sona Gold:** Balanced classic street shooter ($m = 2.1$).
   - **Neelam Sapphire:** +35% Backspin & Curve grip ($m = 2.35$).
   - **Suraj Agate:** Heavy stone cluster crusher ($m = 2.65$).
   - **Faulad Steel:** Maximum momentum transfer & spin power ($m = 3.1$).

5. **Procedural Web Audio Engine:**  
   - Zero external sound files. Synthesizes glass marble clicks, sand friction skids, and whooshes on-the-fly using the browser's native `AudioContext`.

---

## 💰 Monetization Guide: Publishing Web Games

Because the entire game is self-contained in a single `index.html` file, creators can publish it directly to casual web gaming portals:

| Platform | Monthly Audience | Monetization |
| :--- | :--- | :--- |
| **CrazyGames** | 30M+ Players | Developer ad revenue share |
| **Poki** | 50M+ Players | Developer revenue share |
| **GamePix** | Global HTML5 network | Syndication ad payouts |
| **itch.io** | Indie Game Community | Direct purchases and community tips |

---

## 💻 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/jalagamkalyan/kancha-street-ustad.git
   ```
2. Double-click `index.html` in Chrome, Safari, Edge, or Firefox.
3. No build step, no npm install, no server required.

---

## 🔔 Weekly AI Game Drops at Kalyan's Lab

Every week in **Kalyan's Lab**, I use AI to research, build, and publish a brand new playable game with full open-source code.

👉 **[Subscribe to Kalyan's Lab on YouTube](https://www.youtube.com/@KalyansLab)** to get every free game release!

---

## 📄 License
This project is open-source under the MIT License.
