# Space Impact

A fast-paced, retro-inspired side-scrolling space shooter built entirely in a single HTML file using the Canvas API. Experience classic arcade gameplay with modern visual effects, multiple difficulty settings, and a unique "Nokia 3310" nostalgia mode.

## ✨ Features

* **Retro Gameplay**: Classic side-scrolling action with progressive difficulty across multiple waves (First Contact, Sine Swarm, Hunter Pack, etc.).
* **Diverse Enemies**: Battle against Drones, Fast interceptors, Sine-wave flyers, Shooters, Bombers, Tanks, Seekers, and Spinners.
* **Epic Boss Fights**: Engage massive bosses at the end of each level with unique attack patterns and phases.
* **Power-ups & Weapons**: Collect upgrades for weapon levels, shields, extra lives, and devastating bombs.
* **Multiple Themes**: 
    * **HIGH GFX**: Full particle effects, glows, nebulae, and high-fidelity visuals.
    * **MINIMUM**: Clean, performance-focused visuals.
    * **NOKIA 3310**: A dedicated monochrome mode inspired by the legendary mobile game.
* **Dynamic Audio**: Procedural music and sound effects generated using the Web Audio API.

## 🕹️ Controls

| Action | Key |
| :--- | :--- |
| **Move** | Arrow Keys or `W`, `A`, `S`, `D` |
| **Shoot** | Automatic (while alive) |
| **Use Bomb** | `Space` |
| **Pause** | `Esc` or `P` |
| **Menu Navigation** | Arrow Keys / `Enter` / `Space` |

## 🚀 Getting Started

1.  Clone this repository or download the `v6.html` file.
2.  Open `v6.html` in any modern web browser.
3.  Adjust your settings (Difficulty, Theme, Sharpness) in the main menu and press **START GAME**.

## 🛠️ Technical Details

* **Engine**: Custom 2D engine built on the HTML5 Canvas API.
* **Performance**: Fully responsive canvas that scales to your window size while maintaining an internal resolution of 480x300.
* **Rendering**: Supports different sharpness modes (Soft, Normal, Sharp) using CSS image-rendering and canvas smoothing.
* **Storage**: Saves your high score locally using `localStorage`.

## 📜 License

This project is open-source. Feel free to modify and distribute.
