# julianterstegge.com

Personal academic website of Julian Terstegge — Assistant Professor of Finance,
Stephen M. Ross School of Business, University of Michigan.

Static HTML/CSS, no build step. Hosted on GitHub Pages.

## Structure
- `index.html` — Home (bio, links, papers)
- `discussions.html` — conference & seminar discussions, with slides
- `css/style.css` — single stylesheet
- `assets/` — `img/` headshot, `cv/`, `papers/`, `discussions/` (PDFs)

## Preview locally
```
python -m http.server 8131
```
then open <http://localhost:8131>.

## Adding a discussion
Drop the slide PDF in `assets/discussions/` and add a `<li>` block to
`discussions.html` (copy an existing one).
