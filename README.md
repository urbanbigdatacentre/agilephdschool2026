# AGILE PhD School 2026 — Glasgow

Website for the 8th AGILE PhD School, **"Urban Analytics in the AI Era: From Smart Data to Participatory Action"**, hosted by the Urban Big Data Centre, University of Glasgow, 8–10 September 2026 (arrival 7 September).

Design closely follows the [AGILE PhD School 2024 site](https://begin-standrews.github.io/agilephdschool2024/) (R distill look: white fixed navbar with AGILE logo, `#1277A7` links, floating table of contents, `#0F2E3D` dark footer) — but as a plain static site with no build tools. Edit [index.html](index.html) for content and [style.css](style.css) for styling, then push.

## Structure

Single page with anchor sections (linkable, e.g. `…/#how-to-apply`):

| Anchor | Content |
|---|---|
| `#why-to-participate` | What the school is and why to join |
| `#venue` | "Where will it take place?" — venue + travel info |
| `#programme` | Provisional 4-day programme |
| `#how-to-apply` | **Key section** — eligibility, materials, deadline, criteria; incl. `#funding` (Financial support) and Visas |
| `#organising-committee` | Organising committee |
| `#sponsors` | Sponsor logos |
| `#contact` | Contact details |

## Remote assets (consider self-hosting before/after launch)

- **AGILE logo** in navbar + sponsors: hotlinked from `agile-gi.eu` (the 2024 site does the same).
- **Hero photo**: Gilbert Scott Building by Diliff, [Wikimedia Commons, CC BY 3.0](https://commons.wikimedia.org/wiki/File:University_of_Glasgow_Gilbert_Scott_Building_-_Feb_2008.jpg), hotlinked via Special:FilePath. Attribution is in the figure caption — keep it if you replace the URL with a local copy in `images/`.
- UofG / UBDC appear as text links in Sponsors — replace with official logo files when available (drop into `images/` and swap the `.sponsor-text` links for `<img>`).

## Things to confirm before publishing

- **Application deadline** (currently *Fri 14 Aug 2026, 23:59 BST*) and **notification date** (*by Fri 21 Aug 2026*) — appear in the callout box and in `#how-to-apply`.
- **Application e-mail** — currently `qunshan.zhao@glasgow.ac.uk` (in `#how-to-apply` and `#contact`).
- Exact meeting room (page currently says "confirmed to accepted participants").
- Staff titles (e.g. Dr vs Prof Mingshu Wang) in `#organising-committee`.

## Deployment

Live at **<https://urbanbigdatacentre.github.io/agilephdschool2026/>**, served by GitHub Pages from the `main` branch of [urbanbigdatacentre/agilephdschool2026](https://github.com/urbanbigdatacentre/agilephdschool2026) (root path). To update the site:

```bash
cd /Users/qzhao/Desktop/AGILEPhDSchool2026
git add -A
git commit -m "update"
git push
```

Pages redeploys automatically within a minute or two of each push.

## License

Text and figures: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The hero photo remains under its own CC BY 3.0 license (see caption).
