# Portfolio

Source for my personal site: [markhanna10.github.io/github-portfolio](https://markhanna10.github.io/github-portfolio/)

A static site with no build step, served by GitHub Pages. Everything lives in `index.html`, styled by `assets/site.css`.

- **Look:** one navy field with pink ink, set in Epilogue. The name runs across the first screen over a screen from Hem, and returns as the footer.
- **Hiring for:** buttons above the work dim the projects and roles that don't match a role (back end, web, mobile, embedded, games). Without JavaScript the buttons stay hidden and everything shows.
- **Project panels:** clicking a project opens a panel over the page with its screenshots, diagrams and data tables. Each panel has its own link, such as `#project-hem`. Diagrams are inline SVG.
- **Motion:** sections rise in once as they scroll into view, and the name shrinks slightly as the first screen leaves. All of it is switched off under `prefers-reduced-motion`.
- **Photo credits:** in the footer, and in `assets/credits.json`.

To preview locally:

```bash
python3 -m http.server 8000
```
