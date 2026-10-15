# Thesis Project State
Last updated: 2026-10-15

---

## Thesis details
- **Title:** Interactive Web-Based 3D Geoheritage Visualization: Platform Selection and Usability Evaluation
- **Student:** Yasmine Garsaa
- **Period:** October 2026 – May 2027
- **Supervisor workflow doc:** Thesis_workflow_Yasmine_Garsaa.docx
- **GitHub:** https://github.com/YasmineGarsaa/geosite_viewer (branch: main)

## What the thesis is
A user-friendly browser-based web app for exploring 3D geosite/geoheritage models, targeting non-specialists (geoscience students, geotourists, general public). Existing tools like V3Geo are built for researchers — that is the gap this thesis fills. Includes a formal usability study (think-aloud sessions + SUS questionnaire).

---

## Files in this folder
```
thesis/
  Thesis_workflow_Yasmine_Garsaa.docx       original supervisor workflow
  Thesis_Summary_Yasmine_Garsaa.docx        submitted Phase 0 summary
  Thesis_Plan_Phase1_Phase2_Yasmine_Garsaa.docx  action plan Phase 1 & 2
  literature/
    Reading_Notes_Yasmine_Garsaa.docx       notes on all 10 papers
  comparison/
    Platform_Comparison_Matrix.docx         filled comparison of 5 platforms
  writing/
    Literature_Review_Draft.docx            full lit review draft
  platforms/                                empty — for hands-on platform notes
  project/                                  web app code (on GitHub)
    README.md
    src/ (components, viewer, map, catalogue)
    public/models/
    docs/
```

---

## Zotero library — 10 papers (all verified)
1. Brilha, J. (2016). Geoheritage, 8(2), 119–134. DOI: 10.1007/s12371-014-0139-3
2. Buckley et al. (2022). Geoscience Communication, 5, 67–82. DOI: 10.5194/gc-5-67-2022
3. Cocal-Smith et al. (2023). Geosciences, 13(8), 253. DOI: 10.3390/geosciences13080253
4. Hajdú, E. & Pál, M. (2024). EGU General Assembly 2024. DOI: 10.5194/egusphere-egu24-1370
5. Martin et al. (2014). Geoheritage, 6, 141–148. DOI: 10.1007/s12371-014-0102-3
6. Nesbit et al. (2020). GSA Today, 30(6), 4–10. DOI: 10.1130/GSATG425A.1
7. Pasquaré Mariotto et al. (2021). Applied Sciences, 11(12), 5466. DOI: 10.3390/app11125466
8. Pasquaré Mariotto & Bonali (2021). Geosciences, 11(4), 149. DOI: 10.3390/geosciences11040149
9. Pasquaré Mariotto et al. (2023). Applied Sciences, 13(9), 5598. DOI: 10.3390/app13095598
10. Unrau, R. & Kray, C. (2020). LIPIcs GIScience 2021, 177. DOI: 10.4230/LIPICS.GISCIENCE.2021.I.15

---

## Phase progress
**Phase 0 — DONE** (submitted in Neptun by 15 Oct 2026)
  - Title and summary submitted

**Phase 1 — IN PROGRESS** (mid-Oct to end of Nov 2026)
  - [x] Zotero set up with 10 papers
  - [x] Reading notes written for all 10 papers
  - [x] Platform comparison matrix filled
  - [x] Literature review first draft written
  - [x] GitHub repo created and pushed
  - [x] Folder structure created
  - [ ] Read the actual PDFs (not just notes)
  - [ ] Ask supervisor for a 3D model file to test platforms
  - [ ] Test all 5 platforms hands-on with real model
  - [ ] Fill starred (*) cells in comparison matrix after hands-on testing
  - [ ] Send literature review draft to supervisor by end of November

**Phase 2 — NOT STARTED** (Nov to mid-Dec 2026)
  - Define users and requirements
  - Finalise platform/tech stack choice
  - Design wireframes
  - Plan usability study protocol

---

## Platform comparison decisions
- **Primary recommendation:** three.js (MIT licence, most flexible, best long-term)
- **Fallback:** model-viewer (simple, good mobile support)
- **Avoid for final app:** Sketchfab (proprietary, acquired by KitBash 2023, pricing risk)
- **Potree:** only relevant if models include LiDAR/point cloud data — ask supervisor
- **V3Geo:** researcher-oriented — not user-friendly, cannot self-host

---

## Literature review rules
- No references published before 2010
- SUS and think-aloud described as established practice — no citation for original authors
- Hajdú & Pál (2024) is the key reference for usability evaluation in the same domain

## Literature review structure
1. Geoheritage and Geotourism (Brilha 2016, Martin 2014, Pasquaré Mariotto 2021 x2, Cocal-Smith 2023, Pasquaré Mariotto 2023 review)
2. Web-Based 3D Visualization Technologies (Nesbit 2020, Buckley 2022)
3. Usability Evaluation Methods (Unrau & Kray 2021 for WebGIS usability, Hajdú & Pál 2024 as domain example)
4. Summary and Research Gap

---

## Preferences (for Claude)
- Always save documents as .docx, never .md
- Do not add author name to every file — only on formal submissions
- No references before 2010
