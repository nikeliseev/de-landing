# Personal landing page

Static one-page website for positioning Nikita Eliseev as an independent data engineering and analytics consulting specialist. The site is GitHub Pages-ready and uses plain HTML, CSS, and JavaScript.

## Project structure

- `index.html` - page content, SEO metadata, and consultant-facing copy
- `styles/main.css` - layout, typography, responsive behavior, and visual design
- `scripts/main.js` - mobile navigation toggle and footer year
- `assets/favicon.svg` - favicon placeholder
- `.github/workflows/deploy.yml` - automatic GitHub Pages deployment on push to `main`

## Run locally

No dependencies are required.

```bash
cd /Users/nikita_eliseev/DataspellProjects/DE_landing
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

## Before publishing

Current contact details in `index.html`:

- `nik970110@gmail.com`
- `https://github.com/nikeliseev`

Optional:

- add a custom domain and then update canonical / social preview metadata if needed
- replace the placeholder favicon if you want a branded icon

## GitHub Pages deployment

If this directory is not already a git repository:

```bash
cd /Users/nikita_eliseev/DataspellProjects/DE_landing
git init -b main
git add .
git commit -m "Initial personal landing page"
```

Create a GitHub repository, then connect and push:

```bash
git remote add origin git@github.com:<your-username>/<repo-name>.git
git push -u origin main
```

The included workflow deploys the static site on every push to `main`.

If GitHub Pages is not auto-configured after the first push:

1. Open the repository on GitHub.
2. Go to `Settings` -> `Pages`.
3. Set the source to `GitHub Actions`.
4. Push again or re-run the workflow.

## LinkedIn adaptation summary

Used from the LinkedIn profile:

- headline and current positioning as a data engineer
- experience across EWA Learn Languages, OTUS, and OZON
- sectors: edtech, e-commerce, and engineering
- technology references: Python, SQL, dbt, Airflow, ClickHouse, AWS Glue, AWS S3, Kafka, Docker, MongoDB, Apache Iceberg, Grafana, Tableau, Superset, Power BI
- education at Bauman Moscow State Technical University
- public location and language information

Adapted for the website:

- resume-style job descriptions were rewritten into client-relevant capability statements
- experience bullets were reframed around systems, reliability, reporting, and stakeholder outcomes
- instructor work was used as a credibility signal
- engineering background was compressed into a short trust-building note instead of a detailed CV section

Omitted on purpose:

- LinkedIn UI noise, profile metrics, followers, connections, and "open to work" elements
- overly detailed employment formatting such as "full-time" and recruiter-facing phrasing
- unsupported claims, fake case studies, testimonials, or invented client results
