<div align="center">

# 💗 Word Love Code

**A canvas-powered love letter: a heart drawn from particles, "LOVE" raining in Matrix style, and your name in lights.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-word--love--code.vercel.app-00AEFF?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117)](https://word-love-code.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-00AEFF?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=0D1117)](LICENSE)
[![Stars](https://img.shields.io/github/stars/FIQTOR/Word-Love-Code?style=for-the-badge&color=00AEFF&labelColor=0D1117&logo=github)](https://github.com/FIQTOR/Word-Love-Code/stargazers)

<br />

<img src="docs/preview.png" alt="Word Love Code — Matrix love rain and particle heart" width="100%" />

</div>

---

## ✨ What is this?

**Word Love Code** is a single-page, animated love letter built on HTML5 `<canvas>`. Open it and the screen fills with pink **"LOVE"** characters raining down like the Matrix, with tiny hearts scattered through the streams. Behind it, a particle engine assembles a glowing heart — and your name fades in at the centre.

No frameworks, no build step — just open `index.html`.

## 🎬 The three effects

| Layer | File | What it does |
| :--- | :--- | :--- |
| 💗 **Particle heart** | `js/index.js` | A particle engine (Shape Shifter) morphs thousands of dots into a heart shape. |
| 🌧️ **Matrix love rain** | `js/matrix.js` | Vertical streams of `LOVE` / `I LOVE U ❤` characters fall down the canvas. |
| ✍️ **Name box** | `index.html` | Your name fades in over the animation (`.namebox`). |

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Canvas_API-00AEFF?style=for-the-badge&logo=html5&logoColor=white" alt="Canvas API" />
</p>

## 🚀 Run locally

```bash
git clone https://github.com/FIQTOR/Word-Love-Code.git
cd Word-Love-Code

# serve it (recommended — canvas scripts load from js/)
npx serve .
# or: python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## 🎨 Make it yours

| What | Where |
| :--- | :--- |
| The name shown | `index.html` → `.namebox` |
| The rain characters | `js/matrix.js` → `var letters = '...'` |
| Heart color / size | `js/index.js` (particle config) |

## 🙏 Credits & Attribution

This project is built on top of open-source work — huge thanks to the original authors:

- **[Awesome-Love-Code](https://github.com/sun0225SUN/Awesome-Love-Code)** by [@sun0225SUN](https://github.com/sun0225SUN) — MIT licensed. This repo is derived from it.
- **[Shape Shifter](https://github.com/kennethcachia/Shape-Shifter)** by [Kenneth Cachia](http://www.kennethcachia.com) — the particle engine behind the heart (`js/index.js`).

## ☕ Support this project

If this little page helped you say something you couldn't put into words, you can buy me a coffee 💗

<div align="center">

<a href="https://www.buymeacoffee.com/fiqtor" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="200" /></a>

</div>

## 📄 License

Released under the [MIT License](LICENSE), preserving the original upstream MIT license from Awesome-Love-Code.

<div align="center">

Made with ❤️ by [FIQTOR](https://github.com/FIQTOR)

</div>
