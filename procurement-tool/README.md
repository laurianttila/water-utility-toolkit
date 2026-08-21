# Software Risk & Vendor Evaluation Assistant

A lightweight, browser-based intake assistant designed for small, resource-constrained municipal utilities and cooperatives to evaluate software tools and vendor risks before procurement.

The tool and questions have been developed in cooperation by Taneli Kukonlehto (UTU) and Lauri Anttila (JYU).

---

## Overview

Small utilities often lack dedicated IT or cybersecurity personnel. While comprehensive frameworks (such as NIST SP 800-161, NIST SP 800-82, and national critical infrastructure guidelines like VESKY 2025) provide robust risk models, they can introduce significant administrative friction when applied directly to small teams.

This tool operationalizes these complex standards into an accessible, wizard-driven assessment. It replaces technical jargon with plain operational concepts (e.g., translating *MFA*, *CVE*, *SLA*, and *lateral movement* into concepts like *two-step login*, *software flaw patch timelines*, *guaranteed response commitments*, and *stepping-stone infection risks*).

---

## AI Generation Notice

Both the codebase for this application and this documentation were generated with the assistance of a Large Language Model (LLM) as part of an exploratory research workflow. Users should review and validate the outputs according to their organizational and legal requirements.

---

## Key Features

* **Gated Criticality Assessment:** Differentiates between core operational tools and non-critical administrative tools to avoid unnecessary administrative overhead.
* **Decoupled Evaluation:** Assesses vendor organizational stability separately from software technical security.
* **Network Exposure Checks:** Identifies the differing risk profiles between vendor-hosted web applications (SaaS) and tools installed directly on utility endpoints or connected to internal networks.
* **Vendor Lock-in Prevention:** Checks for explicit data export rights and standard file formats.
* **Actionable Risk Summaries:** Generates printable, archival evaluation reports with clear advisory safeguards for decision-makers and municipal boards.
* **Zero Dependencies:** Built as a single-file application (HTML, CSS, vanilla JavaScript). Runs locally in any standard web browser without server infrastructure, build tools, or data transmission.

---

## Getting Started

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser.
3. Follow the guided steps to complete an evaluation.
4. Export or print the final summary page to PDF for archival records.

All data remains local to your browser session (stored temporarily via `localStorage`) and is not transmitted to any external server.

---

## Research Context

This tool was created as part of academic research examining supply chain risk management, shadow IT mitigation, and cybersecurity adoption in under-resourced critical infrastructure organizations. 

It is designed as an educational intake tool to promote risk-aware decision-making, not as a replacement for a formal, comprehensive cybersecurity audit.

---

## Disclaimer

**This software is provided "as is", for research and educational purposes only, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.** 

In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

---

## License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:
* **Share** — copy and redistribute the material in any medium or format.
* **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
* **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

For details, visit: [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
