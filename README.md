# Your website

A static site: About, Projects, Publications, Blog, and CV, plus an interactive
geospatial dashboard project page. No build tools needed — just plain HTML/CSS/JS.

## Pages
- `index.html`, `projects.html`, `publications.html`, `blog.html`, `cv.html` — the main site
- `projects/geo-dashboard.html` — a MapLibre GL JS geospatial dashboard (map + filter
  bar + indicator cards), linked from the Projects page. Sample data lives at the top
  of the `<script>` block in that file, in the `siteData` array — replace it with your
  real sites, or load it via `fetch()` from a JSON/CSV file instead. It uses MapLibre's
  free demo tiles; swap the `style:` URL for a MapTiler/Stadia Maps key (or your own
  tile server) for production use.
- `projects/dashboard.css` — styles specific to the dashboard (filter bar, indicator
  cards, map legend). Base colors/fonts still come from the main `style.css`.

## To customize
- Everything is placeholder content for "Jordan Ellis" — search-and-replace the name, university, and bio text in each `.html` file.
- Colors, fonts, and spacing live in `style.css` under `:root` at the top if you want to adjust the palette.
- Add your real photo: replace the `.portrait` div in `index.html` with an `<img>` tag.
- Add a real CV: drop a `cv.pdf` file next to `cv.html` (the download button already points to it).
- To add a new blog post or publication, copy one `.entry` block and edit the text.
- To add a new indicator card to the dashboard, copy one `.indicator` block in
  `geo-dashboard.html` and wire it up in the `updateIndicators()` function.

## To host it for free
1. Create a GitHub repo named `yourusername.github.io`.
2. Push these files to it.
3. Turn on GitHub Pages in the repo settings (Settings → Pages → deploy from main branch).
4. Your site will be live at `https://yourusername.github.io`.

Alternatively, drag the folder into Netlify Drop (netlify.com/drop) for an instant live link.
