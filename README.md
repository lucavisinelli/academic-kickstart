# Luca Visinelli — academic website

Source for [lucavisinelli.com](https://lucavisinelli.com/), built with Hugo and the Academic theme.

## Homepage v2

Version 2 reorganizes the homepage around the visitor's main questions: who Luca is, what the research programme addresses, which experiments and collaborations he leads, which publications best establish the work, and how students or collaborators can engage.

The definitive information architecture, copy map, and maintenance notes are in [`HOMEPAGE_V2.md`](HOMEPAGE_V2.md). Homepage sections live in `content/home/`; profile copy lives in `content/authors/admin/_index.md`; visual refinements live in `assets/scss/custom.scss`.

## Local development

The Academic theme is a Git submodule, so clone recursively:

```bash
git clone --recursive https://github.com/lucavisinelli/academic-kickstart.git
cd academic-kickstart
hugo server
```

If the repository has already been cloned:

```bash
git submodule update --init --recursive
hugo server
```

GitHub-style source archives do not include submodule contents. From an extracted archive with an empty `themes/academic/` directory, restore the exact theme revision used for validation:

```bash
git clone https://github.com/gcushen/hugo-academic.git themes/academic
git -C themes/academic checkout 7108eefac11bda75a0859bd428fd147476f390a4
hugo server
```

Netlify currently pins Hugo Extended `0.74.3`; use the same version when reproducing the production build.

## Deployment

Netlify builds the `master` branch with `hugo --gc --minify`. Before merging homepage changes, check desktop and mobile layouts, both color modes, internal links, and downloadable files.

## Structure

- `content/home/` — homepage sections and their order
- `content/authors/admin/` — profile, biography, affiliations, and social links
- `content/project/` — research-theme landing pages
- `content/teaching/` — course pages
- `assets/scss/custom.scss` — site-specific presentation
- `static/` — images, PDFs, and downloads
- `config/` — Hugo and navigation configuration

## Contact

- Email: [lvisinelli@unisa.it](mailto:lvisinelli@unisa.it)
- GitHub: [lucavisinelli](https://github.com/lucavisinelli)
- INSPIRE: [author profile](https://inspirehep.net/authors/1269953)
- Google Scholar: [author profile](https://scholar.google.com/citations?user=9w4cYvoAAAAJ)
