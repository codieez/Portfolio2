# Portfolio2

Personal portfolio for Kavya Animi, built as a lightweight static site with vanilla HTML, CSS, and JavaScript.

## Setup

Requirements:

- Python 3
- A modern browser with WebGL support for the Three.js intro loader

Start the local server from the project root:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000/index.html](http://localhost:8000/index.html).

Three.js is stored locally at `vendor/three.module.js`, so the intro does not depend on a CDN. A 2D fallback keeps the loader functional when WebGL is unavailable.

## Project Files

- `index.html` - portfolio layout, styles, interactions, and loader.
- `images/` - profile and project imagery.
- `fonts/` - locally hosted font files.
- `vendor/three.module.js` - local Three.js runtime for the 3D loader.

## Development

Edit `index.html` directly, then refresh the local server. The site has no build step or package installation requirement.