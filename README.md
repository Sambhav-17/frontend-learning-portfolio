# Frontend Learning Portfolio

Thirteen small projects that turn a frontend learning path into hands-on practice: terminal and Git workflows first, followed by semantic HTML, visual foundations, and CSS layout.

## Projects

| Project | Focus | Files |
| --- | --- | --- |
| [P1 · Project folder and terminal navigation](projects/01-terminal-explorer/README.md) | Create a portfolio folder and navigate its files | Guide |
| [P2 · Portfolio repo with an initial commit](projects/02-git-checkpoints/README.md) | Initialize Git and record the portfolio's first commit | Guide |
| [P3 · Feature-branch Git workflow](projects/03-github-remote/README.md) | Create a branch, commit a change, and merge it | Guide |
| [P4 · GitHub README and version tags](projects/04-publish-the-portfolio/README.md) | Write repository documentation and tag a release | Guide |
| [P5 · Semantic bio page](projects/05-semantic-profile/index.html) | Build a bio page with meaningful HTML landmarks | HTML + CSS |
| [P6 · Full portfolio page structure in semantic HTML](projects/06-one-page-portfolio/index.html) | Structure a portfolio page with semantic sections | HTML + CSS |
| [P7 · Design tokens and typography system in CSS](projects/07-design-tokens/index.html) | Define reusable visual tokens and a type scale | HTML + CSS |
| [P8 · Sticky navbar and card overlay using CSS positioning](projects/08-sticky-navbar-card-overlay/index.html) | Combine sticky navigation and positioned card details | HTML + CSS |
| [P9 · Responsive navbar and card grid using Flexbox](projects/09-responsive-navbar-card-grid/index.html) | Build a flexible nav and wrapping card collection | HTML + CSS |
| [P10 · Portfolio header and footer with advanced Flexbox](projects/10-flexbox-header-footer/index.html) | Use flexible alignment, growth, and wrapping in page chrome | HTML + CSS |
| [P11 · Newspaper-style three-column layout with CSS Grid](projects/11-newspaper-grid-layout/index.html) | Compose an editorial page on a three-column grid | HTML + CSS |
| [P12 · Portfolio projects grid with advanced CSS Grid](projects/12-portfolio-projects-grid/index.html) | Create a responsive portfolio gallery with spanning cards | HTML + CSS |
| [P13 · Choosing between Flexbox and Grid for a shared layout](projects/13-flexbox-vs-grid/index.html) | Compare both layout systems on the same component | HTML + CSS |

## Run a project

P1–P4 are step-by-step workflow guides. For P5–P13, open that project's `index.html` directly in a browser. No build step or package installation is required. A few projects use Google Fonts when online; the system font fallback keeps each page usable offline.

For a local server, run this command from the repository root:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000/projects/05-semantic-profile/` (change the project folder to preview another exercise).

## Learning path

Follow the projects in order. The first four guides establish a local Git workflow and a useful GitHub repository. The remaining projects move from semantic document structure to visual foundations, then from CSS positioning and Flexbox to two-dimensional Grid layouts. P13 compares Flexbox and Grid to help choose the right tool for a shared layout. Each page is intentionally small enough to inspect and modify.
