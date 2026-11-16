# Water Tower Defense (WTD)

**Water Tower Defense** is a printable tabletop card and mapping game designed to help small water utilities spot hidden technical dependencies, practice handling compound disruptions, and test their ability to run operations manually when digital systems fail.

> **Research Prototype Notice:** This toolkit is an early-stage research prototype. While it has been field-tested in workshops with Finnish water utilities, it is provided as an experimental learning and discussion aid rather than a certified compliance or risk-management standard.

---

## What's in the Toolkit?

1. **Sociotechnical Mapping Canvas:** A large printable sheet for mapping your team, external contractors, physical equipment (pumps, booster stations), and digital tools (cloud platforms, SCADA, remote access). [See another repository folder for the canvas](https://github.com/laurianttila/water-utility-toolkit/tree/main/canvases)
2. **Game Canvas:** A shared tabletop board where players build incident scenarios and plan responses.
3. **Attack Deck (60 Cards):** Divided evenly across three domains:
   * **Cyber (20 cards):** e.g., ransomware, cloud outages, compromised remote access.
   * **Physical (20 cards):** e.g., perimeter tampering, chemical delivery delays, drone sightings.
   * **Information (20 cards):** e.g., local social media contamination rumors, spoofed boil-water notices.
4. **Response Deck (20 Cards):** Practical operational countermeasures, including manual overrides, preventive barriers, and out-of-band communication steps.
5. **CSV Threat Catalog & HTML Card Compiler:** A simple spreadsheet file and a single-file web tool that turns your card list into printable A4 sheets.

---

## How to Play

* **Players:** 2–8 participants (operators, managers, board members, or local health inspectors)
* **Time:** ~90–120 minutes (30 minutes for mapping + 15–20 minutes per gameplay round)
* **Materials:** Printed canvases, printed card decks, pens, and sticky notes

### Phase 1: Map Your System (30 Minutes)
Before playing any cards, gather around the **Sociotechnical Mapping Canvas**. Use sticky notes to map out:
* **Who** runs and supports the utility (internal staff, maintenance contractors, IT/OT vendors, bulk-water suppliers).
* **What** physical and digital assets keep water flowing (intake wells, booster pumps, PLCs, cloud services).

### Phase 2: Build a Hybrid Attack (Attacker Turn)
Pick one player to start as the **Attacker**. 
1. The Attacker draws or selects **3 Attack Cards** from the deck.
2. **Rule:** The 3 cards must come from **at least 2 different domains** (for example, combining a *Cyber* outage with *Physical* tampering and an *Information* rumor).
3. The Attacker places the cards on the Game Canvas and explains to the group how these three events happen together as one realistic hybrid incident.

### Phase 3: Defend the Utility (Defender Turn)
Everyone else works together as the **Defenders**.
1. Discuss how the incident unfolds across your mapped assets.
2. Choose **up to 3 Response Cards** (or write custom actions on sticky notes) to contain the crisis and keep water flowing.
3. **Rule:** You are strictly capped at **3 actions**. This forces you to prioritize what matters most when time and staff are limited.

### Phase 4: Debrief & Rotate
As a group, talk through how your response holds up:
* Could you actually run the pumps manually if digital systems went down?
* Do your vendor contracts or emergency contacts cover this scenario?
* How would you communicate with the public if normal channels were disrupted?

Write down any concrete follow-up tasks (like testing a manual valve override or updating an emergency phone list). Pass the Attacker role clockwise to the next player and start a new round.

---

## Customizing the Cards

You don't need special software to adapt the game to your utility:
1. Open the `threat-catalog.csv` file in Excel, LibreOffice, or any text editor.
2. Add or edit rows to include your own local equipment, legacy systems, or contractor roles.
3. Open the included single-file HTML compiler in your web browser, load your CSV, and print fresh A4 card sheets.
4. During gameplay, players can also write ad-hoc threats or responses directly onto blank sticky notes.

---

## Citation & License

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share, print, translate, and adapt the materials for your own workshops.

If you use or adapt this toolkit in research or training, please cite:
> Anttila, L. (2026). *Water Tower Defense: A Serious Game for Supporting Frontline Autonomy Against Hybrid Threats in Small Water Utilities*. In Proceedings of the 3rd International Conference on Digital Sovereignty (ICDS 2026) (to be updated).
