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

## Images (`images/`)

- `agile_logo.svg` — from [agile-gi.eu](https://agile-gi.eu/) (navbar + sponsors).
- `ubdc_logo.svg` — from [ubdc.ac.uk](https://www.ubdc.ac.uk/) (sponsors).
- `glasgow-gilbert-scott.jpg` — Gilbert Scott Building by Diliff, [Wikimedia Commons, CC BY 3.0](https://commons.wikimedia.org/wiki/File:University_of_Glasgow_Gilbert_Scott_Building_-_Feb_2008.jpg), resized to 1600 px. Attribution lives in the figure caption — keep it. Swap for a cohort photo after the school.

Urban Studies & Social Policy has no standalone logo, so it appears as a styled text link in Sponsors.

## Key facts on the page

- Applications close **Fri 14 Aug 2026, 17:00 BST**; decisions by **Fri 21 Aug 2026**; applications by email to `qunshan.zhao@glasgow.ac.uk` (single PDF: max-300-word abstract + 150-word motivation + 2-page CV).
- Cohort size 20–25. No registration fee; social dinner (Òran Mór) subsidised; partial travel grants (Europe) + UK budget — no amounts stated publicly.
- Still to fill in later: exact meeting room; staff titles worth re-checking (e.g. Dr vs Prof Mingshu Wang).

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
