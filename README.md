# 🏎️ Asphalt Racer — HTML5 React Racing Game

Welcome to **Asphalt Racer**, a slick and responsive HTML5 racing game inspired by arcade classics and powered by modern front-end tools like **React**, **TailwindCSS**, and **Canvas 2D**.

This game features multiple tracks, gear-based transmission modes, smooth HUDs, dynamic environments, and juicy game physics — all packed in a single HTML file. 😎

---

## 🚀 Features

- **Track Selection Menu** with unlockable progression system
- **Realistic car physics**: acceleration, deceleration, RPM, gears, drift turns
- **Canvas-rendered 2D environments**: city, mountain, highway
- **Manual & Automatic Transmission** (switch anytime!)
- **Boost Mode** (⚡️ SPACEBAR)
- **In-game HUD**: Speedometer, RPM gauge, current lap, lap timer
- **Responsive design** with pixel-art aesthetic
- **No dependencies needed** — runs entirely in the browser!

---

## 🛠️ Tech Stack

| Tech            | Usage                                     |
|-----------------|-------------------------------------------|
| React 18 (UMD)  | UI components & state management          |
| Babel (UMD)     | JSX transformation inside browser         |
| Tailwind CSS    | Styling, layout, and utility classes      |
| Lucide-React    | Iconography for menus and HUD             |
| Canvas API      | Rendering game visuals                    |

---

## 🎮 Controls

| Action              | Keys                      |
|---------------------|---------------------------|
| Accelerate          | ↑ / `W`                   |
| Brake/Reverse       | ↓ / `S`                   |
| Steer Left / Right  | ← / → / `A` / `D`         |
| Boost               | `SPACE`                   |
| Toggle Transmission | `A` = Auto / `M` = Manual |
| Manual Gear Shift   | `1` - `6`                 |
| Pause / Resume      | `ESC`                     |

---

## 🧪 How to Run

1. Download or clone this repo.
2. Open `GoKartGame.html` in any modern browser (Chrome, Firefox, Edge, etc).
3. 🚘 Race on the **City Circuit** and unlock harder tracks as you improve.

✅ **No server or build step required. Just double-click the HTML file.**

---

## 🗺️ Tracks

| Name           | Environment | Difficulty | Length | Unlocked |
|----------------|-------------|------------|--------|----------|
| City Circuit   | City        | Easy       | 2.1 km | ✅        |
| Highway Rush   | Highway     | Medium     | 3.5 km | 🔒        |
| Mountain Pass  | Mountain    | Hard       | 4.8 km | 🔒        |

Progression is based on best lap times. Finish one track to unlock the next!

---

## 🧠 Behind the Scenes

- **Physics Engine**: Handles car movement, speed, rotation, RPM, and gear logic.
- **Track Component**: Renders environment, road, decorations, and car visuals on canvas.
- **HUD**: Displays speed, RPM, current lap, and transmission mode.
- **Menu**: Interactive UI to select tracks, view stats, and control the game mode.
- **Single-Page Game App**: Built entirely in a single HTML file using React and JSX with in-browser Babel.

---

## 📦 File Structure

Since everything lives in one file, here's what’s inside:

