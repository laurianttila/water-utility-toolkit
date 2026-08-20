[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

# Hybrid Threat Modeling Toolkit for Small Water Utilities

Practical, workshop-oriented resources for identifying and responding to sociotechnical threats at small water utilities.

This repository is a work in progress connected to ongoing doctoral dissertation research. The materials combine printable workshop canvases with small browser-based tools. Some components are early research prototypes. Review and adapt them to your context before use.

## Toolkit contents

### 1. Sociotechnical diagnosis canvases

Printable A2 workshop templates for mapping a utility as a combination of people, technology, regulation, and day-to-day processes. The canvases support environment mapping, risk identification, and a deeper examination of the most critical risk.

- [Read the canvas guidance](https://github.com/laurianttila/water-utility-toolkit/tree/main/canvases)
- [English: Sociotechnical mapping canvas](https://laurianttila.github.io/water-utility-toolkit/canvases/EN%20IAR%20Diagnosis%20-%20Sociotechnical%20mapping.pdf)
- [Finnish: Toimintaympäristö](https://laurianttila.github.io/water-utility-toolkit/canvases/FI%20IAR%20Diagnosis%20-%20Toimintaymp%C3%A4rist%C3%B6.pdf)
- [Finnish: Riskien tunnistaminen](https://laurianttila.github.io/water-utility-toolkit/canvases/FI%20IAR%20Diagnosis%20-%20Riskien%20tunnistaminen.pdf)
- [Finnish: Kriittisin riski](https://laurianttila.github.io/water-utility-toolkit/canvases/FI%20IAR%20Diagnosis%20-%20Kriittisin%20riski.pdf)
- [Finnish: Bonus canvas](https://laurianttila.github.io/water-utility-toolkit/canvases/FI%20IAR%20Diagnosis%20-%20Bonus%20canvas.pdf)

English versions are being added gradually; most canvases are currently available only in Finnish.

### 2. Software risk and vendor evaluation assistant

A bilingual, browser-based intake assistant for considering software and vendor risks before procurement. Its guided assessment covers operational need, vendor and support considerations, software security and technical quality, and contractual commitments. It produces a printable summary that can be saved as a PDF.

- [Open the assessment](https://laurianttila.github.io/water-utility-toolkit/procurement-tool/)
- [English version](https://laurianttila.github.io/water-utility-toolkit/procurement-tool/en.html)
- [Finnish version](https://laurianttila.github.io/water-utility-toolkit/procurement-tool/fi.html)
- [Read the tool documentation](https://github.com/laurianttila/water-utility-toolkit/tree/main/procurement-tool)

The assessment runs in the browser without a server or build step. Progress is stored temporarily in the browser's `localStorage`; the tool's documentation states that assessment data is not transmitted externally. This is an educational research tool, not a replacement for a formal cybersecurity audit or legal review. The application and its documentation were produced with assistance from a large language model and should be independently reviewed.

### 3. Water Tower Defense materials

Early tabletop-game resources include English and Finnish research-template boards, an initial CSV set of cyber, physical, and information threat scenarios, and two printable card-generator layouts.

- [English board template](https://laurianttila.github.io/water-utility-toolkit/water-tower-defense/WTD%20Board%20%28research%20template%29.pdf)
- [Finnish board template](https://laurianttila.github.io/water-utility-toolkit/water-tower-defense/WTD%20Board%20Finnish%20%28research%20template%29.pdf)
- [Initial scenario-card data](https://github.com/laurianttila/water-utility-toolkit/blob/main/water-tower-defense/small_utility_playing_cards_initial.csv)
- [Open card generator A](https://laurianttila.github.io/water-utility-toolkit/water-tower-defense/card-generator-att.html)
- [Open card generator B](https://laurianttila.github.io/water-utility-toolkit/water-tower-defense/card-generator-def.html)
- [Browse the Water Tower Defense folder](https://github.com/laurianttila/water-utility-toolkit/tree/main/water-tower-defense)

To generate cards, upload a CSV containing `Type`, `Title`, and `Description` columns, then print the generated pages from the browser. The included sample CSV is semicolon-delimited. The generators load the Papa Parse library from a public CDN, so they require an internet connection unless that dependency is made available locally. Detailed game rules are not yet included in the repository.

### 4. Zine / handbook editor

An experimental in-browser editor for composing and printing a 16-page folded handbook layout. Content can be exported to JSON and imported again later.

- [Open the 16-page handbook editor](https://laurianttila.github.io/water-utility-toolkit/zine-editor/zine-facelift.html)
- [Open the earlier 8-page editor](https://laurianttila.github.io/water-utility-toolkit/zine-editor/handbook-zine.html)
- [View the example JSON](https://github.com/laurianttila/water-utility-toolkit/blob/main/zine-editor/example.json)
- [Browse the zine editor folder](https://github.com/laurianttila/water-utility-toolkit/tree/main/zine-editor)

Enter content directly into the page panels, adjust alignment and text size, export a JSON backup, and use the browser's print function when ready. This component is marked as work in progress.

## Quick start

### Use the hosted tools

Open any of the tool or document links above. No installation is required.

### Use a local copy

1. Clone or download this repository.
2. Open the relevant `.html` file in a modern browser, or open and print the PDF canvases directly.
3. Keep exported JSON or PDF files with your project records as appropriate.

There is no package manager, compilation step, or application server in the repository. The browser tools are plain HTML, CSS, and JavaScript.

## Project status and responsible use

These resources are research prototypes intended to support discussion and risk-aware decision-making. They are not complete security controls, incident-response plans, procurement approvals, or professional advice. Validate results against your utility's operational, regulatory, cybersecurity, accessibility, and legal requirements.

Questions, corrections, and contributions can be submitted through [GitHub Issues](https://github.com/laurianttila/water-utility-toolkit/issues).

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). You may share and adapt the material with appropriate attribution, a link to the license, and an indication of changes.
