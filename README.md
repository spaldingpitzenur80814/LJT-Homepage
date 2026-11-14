# LJT-Homepage

Personal homepage of **Junteng Liu**, first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology (HKUST).

The site is built with [Jekyll](https://jekyllrb.com/) using the [Academic Pages template](https://github.com/academicpages/academicpages.github.io); this repository is a fork of it.

## Site contents

- **About** (front page): personal details, research interests, education, research experience, publications, skills, honors and awards, and contact information.
- **Publications**: the full publication list (one Markdown file per paper in `_publications/`).

## Where to edit

| Content | File |
| --- | --- |
| Site-wide settings and sidebar profile | `_config.yml` |
| Front page (About) | `_pages/about.md` |
| Publications | `_publications/*.md` |
| Header navigation | `_data/navigation.yml` |
| Author profiles | `_data/authors.yml` |

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000/LJT-Homepage/`.

## Deployment

The site is built and deployed to GitHub Pages by the workflow in `.github/workflows/jekyll.yml` on pushes to `master`.
