# 🏰 Sapna — The Cinematic Archive & Portfolio

A cinematic, image-rich portfolio website with a refined Dark Academia / Enchanted Archive aesthetic.

> **Zero JavaScript • Zero Libraries • Zero Build Tools • Pure Semantic HTML5 & CSS3**

---

## 📸 Generated Cinematic Asset Collection (Phase 1)

All 6 custom landscape backgrounds were generated in 16:9 aspect ratio, inspected for zero text/logos/faces, and compressed to under 600 KB:

1. **`images/hero-castle.jpg`** (376 KB): Wide cinematic shot of a gothic castle on rocky cliffs above a misty lake at golden hour sunset with volumetric light rays.
2. **`images/train-window.jpg`** (422 KB): View looking out through an empty vintage wooden steam-train carriage window toward the distant valley castle.
3. **`images/great-hall.jpg`** (516 KB): Vaulted stone hall with long timber tables, stained glass, and dozens of candles floating in mid-air.
4. **`images/library.jpg`** (484 KB): Ancient dark-academia library with rolling ladders, glowing floating books, and green banker's lamps.
5. **`images/ballroom.jpg`** (517 KB): Grand gothic ballroom with polished marble flooring, candelabras, and a vertical spotlight beam.
6. **`images/atelier.jpg`** (562 KB): High-fashion couture atelier inside a gothic stone chamber with dress forms in velvet and gold embroidery.

---

## 🏛️ Scene & Chamber Architecture (Phase 2)

- **00. The Gate (Hero):**
  - Full-screen `hero-castle.jpg` with a slow 25-second camera push-in.
  - 35 rising golden embers (`@keyframes riseEmber`) with randomized paths, sizes, and delays.
  - Multi-speed drifting mist layers and gliding bird silhouettes.
  - Staggered letter-by-letter blur-to-sharp reveal for **"SAPNA"** followed by a golden shimmer sweep.
  - Faint pulsing glow over the castle windows and torn-parchment bottom edge transition.
- **Scene 2. The Journey:**
  - Pinned vintage train compartment with wooden window frame. On hover/scroll, the scenery pans and zooms while role cards introduce Sapna as Developer, Marketer, Dancer, and Fashion Designer.
- **Scene 3. The Great Hall:**
  - `great-hall.jpg` backdrop with 30 floating bobbing CSS candles and 4 illuminated 3D tilt portal cards linking to each chamber.
- **Chamber I. The Spellbook (Code):**
  - `library.jpg` backdrop, huge editorial headline *"Code is just spellwork."*, terminal manuscript with CSS `steps()` typing animation, and 3D leather book spines that slide forward on hover.
- **Chamber II. The Daily Prophet (Marketing at Vedonyx):**
  - High-fashion broadsheet on bone paper with CSS multi-columns, animated `@property` counters (`350%`, `45+`, `2.5M`, `98%`), and continuous skills marquee ticker.
- **Chamber III. The Midnight Ball (Dance):**
  - `ballroom.jpg` backdrop with animated conical spotlight beam, cinematic letterbox bands, horizontal scroll-snap reel strip, and glowing node timeline.
- **Chamber IV. The Atelier (Fashion):**
  - `atelier.jpg` backdrop with slow ambient zoom, 6 editorial look cards with interactive **Sketch-to-Final Reveal** via `clip-path` wipe, fabric swatches strip, and research journal.
- **The Cabinet of Curiosities (About):**
  - Frosted glass specimen display cells (`backdrop-filter`) with aged gold borders that lift and glow with amber embers on hover.
- **The Last Letter (Contact):**
  - CSS wax-sealed envelope that cracks open on click to reveal a styled HTML form, social links, and the closing vow: *"MISCHIEF MANAGED."*

---

## 🚀 How to View Locally

Simply double-click **`index.html`** in Finder or File Explorer. It opens instantly in Safari, Chrome, Firefox, or Edge.

Or launch a local server:
```bash
python3 -m http.server 3000
# Open http://localhost:3000
```

---

## ✍️ Customization Guide

Every section features clear comments formatted as `<!-- EDIT ME -->`:
- **Bio & Titles:** Update text directly in `index.html`.
- **Your Own Outfits:** Add your images to `images/` as `fashion-01.jpg` (final photo) and `fashion-01-sketch.jpg` (sketch) to enable the automatic hover wipe.
- **Video & Audio:** Replace `videos/dance-01.mp4` or `audio/ambient.mp3`.
- **Contact Form:** Replace `https://formspree.io/f/placeholder` in Chamber VI with your free Formspree ID.

---

## 🌐 Free Deployment

### GitHub Pages
```bash
git init
git add .
git commit -m "Cinematic Portfolio"
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```
Enable Pages in repository **Settings > Pages** from the `main` branch.

### Netlify Drop
Drag and drop the `Portfolio` folder directly onto [app.netlify.com/drop](https://app.netlify.com/drop).
