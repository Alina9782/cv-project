# Front-End CV + Portfolio

Personal website project with two static pages:

- CV page (`index.html`)
- Portfolio page (`portfolio.html`)

Built with plain HTML and CSS for fast loading, simple maintenance, and easy deployment to Vercel.

## Project Structure

```text
cv_project/
├─ index.html
├─ portfolio.html
├─ vercel.json
├─ assets/
│  ├─ css/
│  │  └─ portfolio.css
│  ├─ img/
│  │  ├─ favicon.ico (or favicon.svg)
│  │  └─ ...images
│  └─ js/
└─ projects/
```

## Local Preview

Open `index.html` directly in browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then open: `http://localhost:8000`

## Customize Content

### CV page (`index.html`)

- Update summary, skills, and experience text.
- Verify contact links (`mailto:`, `tel:`, LinkedIn, GitHub).
- Check asset paths for `CV-img.png`, `bg-img.png`, and favicon.

### Portfolio page (`portfolio.html`)

- Replace placeholder projects with real ones.
- For each card, update:
  - title
  - stack (`meta` line)
  - description
  - bullet points
  - `Live Demo` and `Source Code` links

## Deployment (Vercel)
