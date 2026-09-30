# How Incident Reviews for Datix (now RLDatix) Actually Work: A Frontline & Systems Perspective

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23071323.svg)](https://doi.org/10.5281/zenodo.23071323)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

**Author:** Ashwin Yadhav Kumar  
**Affiliation:** Independent Healthcare Systems & Operational Analytics Researcher  
**ORCID:** [0009-0007-2825-4474](https://orcid.org/0009-0007-2825-4474)  
**Contact:** [LinkedIn Profile](https://www.linkedin.com/in/ashwin-yadhav-kumar) | ykashwin@gmail.com  
**Persistent DOI:** [10.5281/zenodo.23071323](https://doi.org/10.5281/zenodo.23071323)

---

## Executive Overview
When clinical omissions or safety events occur across NHS acute trusts, incident reports are logged through Datix (now RLDatix). Historically viewed with apprehension as an instrument of individual blame or mandatory re-education, incident reviews have been structurally transformed under the **NHS Patient Safety Incident Response Framework (PSIRF)**. 

This technical working paper presents an operational examination of how an incident report actually progresses through an acute healthcare setting—moving from initial frontline logging to root-cause deconstruction, executive committee oversight, and a 90-day closed-loop audit.

---

## The 5-Stage Datix Resolution Pathway

![Incident Response Flow](incident-response-flow.png)

1. **Incident Logging (Frontline Entry):** Clinicians log an objective factual timeline, immediate containment actions, and staff notified, omitting speculative blame.
2. **Triage & Risk Assessment (Governance Review):** Within 24–48 hours, triage evaluates both the factual harm level and forward-looking $5 \times 5$ Risk Score ($1 \text{ to } 25$). Events graded Moderate Harm or higher initiate statutory **Duty of Candour** (Regulation 20) and **Just Culture** review.
3. **Systems-Based Investigation (Root Causes):** Conducted blamelessly using frameworks like the Yorkshire Contributory Factors Framework (YCFF), employing proportionate learning responses (Swarm Huddles, After Action Reviews, or Patient Safety Incident Investigations).
4. **Formulating Practical Fixes (Action Plans):** Prioritizes the **Hierarchy of Controls**—engineering forcing functions and physical protections over passive re-education—assigned to operational leads with clear delivery timelines.
5. **Checking Results & Closing the Loop (Audit):** Approved by the Trust Risk and Quality Governance Committee, validated via a 90-day ward audit, feedback provided to the reporter, and national synchronization via **Learn from Patient Safety Events (LFPSE)**.

---

## Comparative Operational Study: Traditional vs. Modern Model

![Traditional vs Modern Model](traditional-vs-modern.png)

| Operational Dimension | Traditional Punitive Reaction | Systems-Based Datix Review |
| :--- | :--- | :--- |
| **Initial Assumption** | The individual made an isolated, careless error. | Latent operational conditions failed the clinician. |
| **Core Finding** | "Nurse failed to check the electronic medicine record on time." | Multiple system breakdowns aligned to cause the delivery delay. |
| **Prescribed Action** | Mandatory refresher training and formal note on record. | Workflow re-engineering, digital alert fixes, and rota adjustments. |
| **Frontline Outcome** | Staff fear reporting; ward conditions remain unsafe. | Staff report hazards willingly; operational reliability improves. |

---

## Key Results from 90-Day Operational Audit

![90-Day Audit Results](90-day-audit-results.png)

* **Timely Administration of IV Antibiotics:** Improved by **34%** across the acute ward.
* **Incident Reporting Rate:** Increased by **22%**, reflecting enhanced psychological safety and trust in systemic reporting.

---

## Repository Contents
* `How Incident Reviews for Datix (now RLDatix) Works.pdf` — Full published technical working paper.
* Workflow diagrams, process maps, and audit frameworks.

## Citation
If you use or reference this framework, please cite it as:

```bibtex
@techreport{kumar2026datix,
  author      = {Kumar, Ashwin Yadhav},
  title       = {How Incident Reviews for Datix (now RLDatix) Works: A Frontline \& Systems Perspective},
  institution = {Zenodo},
  year        = {2026},
  doi         = {10.5281/zenodo.23071323},
  url         = {[https://doi.org/10.5281/zenodo.23071323](https://doi.org/10.5281/zenodo.23071323)}
}
