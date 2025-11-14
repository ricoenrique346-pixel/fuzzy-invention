# ✨ Fuzzy Invention  
*A collaborative playground for half‑formed prototypes, creative prompts, and experimental ideas.*

---

## 🌐 Preview  
Open `index.html` in your browser to view the site locally.  
Optional screenshots can be stored in `assets/screenshot.png`.

---

## 🚀 Features  
- Clean, semantic HTML structure  
- Responsive layout powered by a single CSS file (`style.css`)  
- Gallery of featured prototypes + community challenges  
- Contributor highlight cards (avatars + GitHub links)  
- Roadmap and lightweight call‑to‑action sections  

---

## 📂 Project Structure  
- `index.html` — main markup  
- `style.css` — primary stylesheet  
- `assets/` — media and images  
  - `logo.png`  
  - `rico.jpeg`  
  - `stevie.jpg`  
  - `jaz.svg`  
  - *(optional)* `screenshot.png`  

---

## 🛠 Getting Started  
**Option 1 — Quick view:**  
- Double‑click `index.html` or open it in your browser.  

**Option 2 — Local server (recommended):**  
- **Python 3:**  
  ```bash
  python -m http.server 8000


---

## 🏅 Contributor Badges  

Celebrate contributions with fun badges! Add them to your profile card in `index.html` by including the badge icons from `assets/badges/`.

| Badge Name            | Icon (placeholder)           | Awarded For |
|-----------------------|------------------------------|-------------|
| **Prototype Builder** | `assets/badges/builder.svg`  | Added a new prototype card to the gallery |
| **Design Tweaker**    | `assets/badges/designer.svg` | Improved CSS, layout, or visual identity |
| **Challenge Solver**  | `assets/badges/solver.svg`   | Completed or contributed to a community challenge |
| **Accessibility Ally**| `assets/badges/access.svg`   | Enhanced alt text, focus states, or contrast |
| **Roadmapper**        | `assets/badges/roadmap.svg`  | Suggested or documented future project ideas |
| **Connector**         | `assets/badges/link.svg`     | Added meaningful external links or resources |
| **Showcase Star**     | `assets/badges/star.svg`     | Shared a preview screenshot or demo |
| **Collab Champion**   | `assets/badges/collab.svg`   | Helped another contributor or reviewed PRs |

### Example Usage in a Contributor Card
```html
<div class="profile">
  <img src="assets/rico.jpeg" alt="Rico Enrique avatar">
  <h3>Rico Enrique</h3>
  <p>Creative technologist, playful builder.</p>
  <div class="badges">
    <img src="assets/badges/builder.svg" alt="Prototype Builder badge">
    <img src="assets/badges/designer.svg" alt="Design Tweaker badge">
  </div>
</div>

.badges img {
  width: 24px;
  height: 24px;
  margin-right: 4px;
  vertical-align: middle;
}
.badges img:hover {
  transform: scale(1.1);
}
