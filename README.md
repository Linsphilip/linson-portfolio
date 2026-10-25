# Linson Philip — bilingual portfolio sample

## Preview
Extract the ZIP completely. Open `index.html`: it defaults to German.
All pages also work as local files. No installation, external fonts, CDN, build
step or API is required. Alternatively run `python -m http.server 8000` in
this folder and open http://localhost:8000.

## Structure
- `de/`: complete German pages.
- `en/`: equivalent English pages.
- `assets/style.css`: shared responsive design.
- `assets/main.js`: mobile menu and back-to-top behaviour.
- `assets/portrait.png`: AI-edited professional portrait approved in the conversation.
- `assets/CV_DE.pdf`, `assets/CV_EN.pdf`: CV snapshots from the uploaded portfolio ZIP.

The language switch opens the matching page. Experience and project links open
dedicated pages in the same tab. Technical diagrams are embedded SVG and HTML,
editable in each page; no diagram library is needed. SVG drawings are conceptual
illustrations, not photographs of the user's actual equipment or measured data.

## Before publishing
1. Review all content, dates and translations. This is a sample, not a deployed site.
2. Replace both CV PDFs with your final approved language-specific files. The ZIP's
   existing CV snapshots are preserved; they were NOT newly edited for this sample.
3. Confirm the micro-PV end date (currently 09/2024, following the uploaded CV).
4. Review the portrait for faithful likeness. Substitute an authentic photo if preferred.
5. The publication-based workflow cites the paper and its three authors. Original
   figure downloads were unavailable; no original figure or publisher PDF is redistributed.
6. Use only approved, non-confidential lab photographs or results if you replace
   the schematics. Do not upload raw partner data, internal network details or credentials.
7. Check any legal/privacy information required for your final public site. No analytics,
   cookies, external embeds or contact-form data collection are included in this sample.

## Upload to GitHub Pages
Back up the existing repository first. Upload the CONTENTS of this extracted folder
to the repository's published folder: index.html, de/, en/, assets/, and .nojekyll.
Do not upload the ZIP or create an extra nested portfolio_sample directory.
Keep files unrelated to this sample unless you intentionally retire them.
Relative URLs support a repository subpath such as /linson-portfolio/.

## Editing
Edit the corresponding HTML in de/ and en/. Search for the visible heading.
Examples: de/ines.html and en/ines.html; de/prueflabor.html and en/test-lab.html.
Keep equivalent language links when renaming pages. No GitHub contact link is included.
This sample is intentionally independent from the live website and does not change it.

## Realistic images — updated edition
Latest equipment-specific images: `assets/meter-lab-branded.png` (Chroma,
Cinergia, Janitza and Binder), `assets/filter-bode100.png` (generic filter with
illustrative Bode 100), and `assets/meter-data-analysis.png` (Project 1).
These replace the displayed generic lab/filter illustrations; earlier assets
remain available as alternatives. Equipment geometry, wiring, labels and screen
plots are illustrative, not verified exact product representations or test results.
See IMAGE_PROMPTS_EQUIPMENT_UPDATE.md for the generation/edit prompts.

Four AI-generated representative PNGs are included in assets/: substation-representative,
balcony-pv-representative, meter-lab-representative, and inductive-component-representative.
All images are clearly identified in both languages. These are not photographs of actual
KSEB/INES/Livarsa installations or evidence of work performed. The operator is generic,
not Linson. The inductor illustration is NOT a Livarsa product recreation and does not
depict the paper's exact coupled-winding topology. Instrument screens are illustrative,
not results. Authentic approved project photographs would be preferable when available.

The Livarsa/thesis and digital-twin pages include a newly drawn, simplified workflow
based on Fig. 6 of the publication, with author attribution, DOI and licence link.
It is not a reproduced paper figure or a wiring diagram. The publication is linked so
visitors can inspect the actual schematic and impedance-measurement photograph.

## KSEB: scope and items to confirm before adding
Six responsibility sections expand the duties already supplied in your CV; they do
not turn a generic job description into personal experience. No new management authority,
certification, voltage level, relay-setting work or quantified result has been added.
If personally applicable, confirm the following before adding them to the website:
- Shift handover, operator diary/log sheets, and precise shift-in-charge responsibility.
- Formal permit-to-work issue/cancellation or isolation-certificate authority.
- Fault/alarm response and liaison with load dispatch or neighbouring stations.
- Specific transformer inspections, battery checks, tests or maintenance you performed.
- Protection-relay testing/commissioning versus observation or coordination only.
Do not publish safety-critical switching sequences or confidential station diagrams.

Context reference consulted (not evidence of your employment duties): CSEZA,
2021 O&M procurement document, Annexure J, page 63, 110/11-kV shift/station-engineer
responsibilities: https://csezauthority.in/tenders/files/103-1.pdf . This describes a
Kerala installation coordinated with KSEB, not a KSEB-wide employment specification.

Publication source for the conceptual workflow:
Linson Philip, Uchenna Johnpaul Aniekwensi and Jörg Bausch (2026),
A Waveform-Driven Framework for Pre-Installation Assessment of Series-Connected
Passive Inductive Filter Performance in Industrial Power Systems.
https://doi.org/10.1109/OAJPE.2026.3743650
Author-posted text/figure descriptions: https://www.researchgate.net/publication/415926034
Licence listed by the publication: https://creativecommons.org/licenses/by/4.0/
