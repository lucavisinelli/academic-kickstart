# Homepage v2: information architecture and copy map

Version: 2.0.0  
Prepared: 31 August 2026

## Editorial objective

The homepage should establish Luca Visinelli as a principal investigator with a coherent research programme—not as a chronological archive. Its first screen answers identity and relevance; the next two sections explain the programme and current leadership; evidence, recruitment, teaching, and news follow in decreasing strategic importance.

The long-form media and talks archives remain available, but they no longer interrupt the main narrative.

## Definitive homepage order

| Order | Navigation label | Section title | Visitor question | Source of exact copy |
|---:|---|---|---|---|
| 10 | — | Research profile | Who is Luca, and why does his work matter? | `content/authors/admin/_index.md` |
| 20 | Research | Research programme | What connected scientific questions drive the work? | `content/home/research.md` |
| 30 | Projects | Research leadership and experiments | Where does theory meet instruments and observations? | `content/home/projects.md` |
| 40 | Publications | Selected publications | What evidence establishes the programme? | `content/home/publications.md` |
| 50 | Group | Group and opportunities | How are researchers trained, and how can I enquire? | `content/home/group.md` |
| 60 | Teaching | Teaching | What learning resources are public? | `content/home/teaching.md` |
| 70 | News | News and media | What is happening now? | `content/home/news.md` |
| 100 | Contact | Contact | How can I reach Luca? | `content/home/contact.md` and `config/_default/params.toml` |

The persistent navigation mirrors this sequence and adds a direct CV link before Contact. It deliberately omits a redundant Home link and removes Media and Talks from the primary navigation.

## Copy principles

1. Lead with the present position and a one-sentence account of the research programme.
2. Organize research by connected questions, not by generic definitions of particles or cosmological components.
3. Give experimental leadership its own section so it is not buried inside biography or publication lists.
4. Curate eight publications spanning foundational contributions and the newest directions; link to complete external records instead of duplicating a stale local bibliography.
5. Make recruitment useful without publishing unconfirmed group membership or promising funded positions.
6. Keep news to three consequential items and send archival browsing to the existing post collection.
7. Use first person for the research narrative and direct, concrete calls to action.

## Supporting changes

- Research-theme pages now describe Luca's actual programme and no longer redirect to Wikipedia.
- The Cosmology & Astroparticles course now lives only under Teaching; its former project URL redirects through a Hugo alias.
- Demo alerts, example slide links, and placeholder supplementary text were removed from local publication pages.
- Metadata now uses a specific search description, a valid sharing-image filename, the canonical non-`www` base URL, and Academicons for scholarly profiles.
- Education and current affiliation were aligned with the current CV.
- `assets/scss/custom.scss` supplies the responsive card, publication, CTA, light-mode, dark-mode, focus, and reduced-motion treatments used by v2.

## Maintenance rhythm

- **Quarterly:** refresh the three News and media items and check every homepage link.
- **After a major paper or award:** reconsider the selected-publication set; keep it to roughly eight items.
- **At each academic-year transition:** verify title, affiliation, teaching links, recruitment wording, and CV.
- **Before adding people:** confirm names, roles, preferred profile links, and consent; then create a dedicated group page rather than expanding the homepage into a directory.
- **Annually:** test mobile and desktop layouts in both color modes, review accessibility labels and keyboard focus, and run a broken-link scan.

## Content intentionally retained off the homepage

The existing talk and media source files are inactive rather than deleted. They preserve archival material for later migration, but their dates and destinations should be reviewed before they are promoted again.
