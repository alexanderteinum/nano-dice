# nano-dice

A blazing fast and fully keyboard-driven Yacht clone. Built to scratch an itch for a snappy dice game without the bloat, ads, or slow 3D animations. 

**Play it live:** [nano-dice.netlify.app](https://nano-dice.netlify.app)

## Features

* **100% Keyboard Support:** Navigate with `Arrows`, keep/release dice with `Space`, and roll/confirm with `Enter`.
* **Zero-delay Touch:** Optimized with `touch-action: manipulation` and disabled text-selection. (Tip: Add it to your home screen as a PWA for an immersive fullscreen experience!)
* **Zero-lag SVG Sprites:** Dice are embedded as SVG `<symbol>`s using `<use>` tags. Zero network requests during gameplay means instant dice switching.
* **Catppuccin Theming:** Uses the beautiful Catppuccin Macchiato (dark) and Latte (light) palettes. Respects your OS preferences, or hit `T` to toggle manually.
* **Snappy Animations:** Powered by a tiny sprinkle of GSAP for 0.2s staggers that give the game a physical feel without slowing you down.
* **Local High Score:** Saves your best score directly to `localStorage`. No backend, no accounts, just you against yourself.

## How to Play

The rules are based on the modern, strategically balanced version of Yacht:

* **4 of a Kind** counts the sum of all 5 dice.
* **Small Straight** is 15 points.
* **Large Straight** is 30 points.

## License

This project is licensed under the [MIT License](LICENSE).
