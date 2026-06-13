# Asutosha Nanda — Portfolio

Personal portfolio of **Asutosha Nanda**, a Software Engineer building multi-agent LLM
applications (OpenAI, Claude, Gemini) and RAG pipelines, with a strong foundation in
big-data engineering (Apache Spark, PySpark, Databricks, Azure) and full-stack development
(Spring Boot, React, REST).

A single-page site built with **vanilla HTML, CSS and JavaScript** — no frameworks, no build
step. It wears a neo-brutalist, Hollow-Knight-flavoured "scrapbook" theme: thick borders,
flat offset shadows, torn-paper section dividers, taped photo frame, and small character
cutouts scattered behind the content.

**[Live Site](https://asutoshananda.github.io/)**

## Highlights

- **Hero** — animated tech-stack marquee and a taped, hand-cut photo frame.
- **Skills** — categorised skill boxes with in-box pagination for long tag lists.
- **Creator of** — paginated grid of 28+ open-source projects (FastAPI, LLM, data tools).
- **Certifications** — paginated grid of competitions and course certificates.
- **Journey map** — an interactive Leaflet map tied to the timeline.
- **Dark mode** — light/dark theming via CSS custom properties.

## Tech Stack

- **HTML / CSS / JS** — no frameworks, no build step
- **Leaflet.js** — interactive journey map
- **Font Awesome 6.4** — icons
- **Google Fonts** — Cinzel, IM Fell English SC, Space Grotesk, Space Mono

## Project Structure

```
.
├── index.html        # The portfolio (markup + inline JS)
├── neo-styles.css    # All styles
├── image/            # Avatar, character cutouts, decorations
├── favicon.svg       # Site favicon
├── robots.txt        # Crawler directives
├── sitemap.xml       # Sitemap for SEO
└── LICENSE           # License
```

## Run Locally

Any static server works:

```bash
python3 -m http.server 3000
# then open http://localhost:3000
```

## Credits & License

The neo-brutalist template this site is built on was originally created by
**Marjo Ballabani** ([marjoballabani.me](https://marjoballabani.me)). The portfolio content
(text, projects, images) is Asutosha Nanda's. See [LICENSE](LICENSE) for code terms.
