# Web Development Learning Track

This repository contains hands-on practical projects covering Git/GitHub, HTML5 Foundations, CSS Foundations, and Modern CSS Layout Systems (Flexbox & CSS Grid).

---

## 📚 Curriculum Breakdown

### Module 1: Git & GitHub Foundations
- **P1**: Local Git setup and initial repository initialization.
- **P2**: Git staging, branching, and commit history exploration.
- **P3**: Merge conflicts resolution and git branch workflows.
- **P4**: Remote repository management, pushing, and tagging releases.

---

### Module 2: HTML & CSS Foundations (P5–P9)

| Project | Title | Key Concepts & Techniques | Directory |
| :--- | :--- | :--- | :--- |
| **P5** | **Semantic Bio Page** | Semantic HTML elements (`<header>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<aside>`, `<footer>`, `<address>`, `<time>`, `<details>`), accessible box model, beginner pastel palette. | [`P5/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P5/index.html) |
| **P6** | **Full Portfolio Structure** | Complete semantic portfolio document structure: Hero, About, Projects (`<article>`), Skills, Semantic Contact `<form>` with fieldsets, `<aside>`, and `<nav>`. | [`P6/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P6/index.html) |
| **P7** | **Design Tokens & Typography** | CSS Custom Properties (`:root`), color system, modular font scale (`--font-size-xs` to `--font-size-3xl`), 8pt spacing intervals, token-driven component architecture. | [`P7/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P7/index.html) |
| **P8** | **Sticky Navbar & Card Overlays** | CSS Positioning: `position: sticky; top: 0;`, `position: relative` coordinate parent, `position: absolute` badge and sliding hover overlays, `position: fixed` floating action button. | [`P8/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P8/index.html) |
| **P9** | **Responsive Navbar & Card Grid** | 1D Flexbox layout, `flex-wrap: wrap`, `flex: 1 1 260px`, internal card flex anchoring, media queries for mobile stacked navigation. | [`P9/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P9/index.html) |

---

### Module 3: CSS Layout Systems (P10–P13)

| Project | Title | Key Concepts & Techniques | Directory |
| :--- | :--- | :--- | :--- |
| **P10** | **Advanced Flexbox Header & Footer** | Multi-item navbar with `flex-grow: 1` search bar, `order` manipulation for responsive rearrangement, asymmetric multi-column footer (`flex: 2 1 ...`), nested flex forms. | [`P10/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P10/index.html) |
| **P11** | **Newspaper 3-Column Layout** | 2D CSS Grid editorial layout: `grid-template-columns: minmax(200px, 1fr) 2.5fr minmax(200px, 1fr);`, `grid-column: 1 / -1` masthead/breaking news, drop-caps, pull quotes. | [`P11/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P11/index.html) |
| **P12** | **Portfolio Projects Bento Grid** | Advanced CSS Grid: Asymmetric bento-box spans (`grid-column: span 2; grid-row: span 2;`), `grid-auto-flow: dense;` automatic gap-packing, metrics cards, responsive collapse. | [`P12/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P12/index.html) |
| **P13** | **Choosing Between Flexbox & Grid** | Comparative architectural guide: 1D content-driven vs 2D layout-driven, live 5-card wrapping experiment, production hybrid pattern (Grid macro shell + Flexbox micro items), decision matrix. | [`P13/`](file:///Users/deeprajsharma/Documents/web-dev-git-project/P13/index.html) |

---

## 🚀 How to View Any Project

Each project is fully self-contained with its own semantic `index.html` and stylesheet `style.css`.

You can view any project by opening the respective `index.html` directly in your browser:
- Open in Chrome / Safari / Edge: Double-click `index.html` inside any project folder (e.g., `P5/index.html`).
- Or run a lightweight local static server:
  ```bash
  # Using Python built-in server
  python3 -m http.server 8080
  # Then open http://localhost:8080 in your browser
  ```
