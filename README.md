# Operation - Card Dealer & Scorekeeper

Small browser game that deals specialist cards and a doctor deck. This repo contains a single-page app: `index.html`.

**Quick Start (recommended)**

- **Serve locally with Python 3:**

```bash
cd OperationGame
python3 -m http.server 8001
# Open http://localhost:8001/ in your browser
```

- **Open directly:** double-click [index.html](index.html) or open it from your browser (some browsers restrict module/CORS behavior when opened as file).

- **VS Code:** install the Live Server extension, open [index.html](index.html) and click "Go Live".

**Notes**
- If you change player counts after typing names, the inputs now preserve typed names.
- Failed cards are returned to the bottom of the doctor deck; there is no discard pile.
- The cards-remaining counter reflects physical pieces left on the board.

If you want, I can add a `.gitignore` and a short demo GIF or set up GitHub Pages hosting.
