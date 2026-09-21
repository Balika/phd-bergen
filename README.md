# PhD research repository — Ghana geographic health inequalities

Article-based PhD project on geospatial inequality in health in Ghana and a framework for priority setting toward geographically equitable UHC.

**Candidate:** Edmond Mwinbamon Balika  
**Host:** Bergen Centre for Ethics and Priority Setting (BCEPS), University of Bergen

## Repository structure


| Path               | Purpose                                                                         |
| ------------------ | ------------------------------------------------------------------------------- |
| `literature/`      | Papers, notes, and evidence tables                                              |
| `data/`            | Raw, processed, and metadata-controlled datasets                                |
| `gis/`             | Boundaries, rasters, roads, facilities, and spatial workflows                   |
| `gbd/`             | Burden inputs, transformations, and validation                                  |
| `paper1/`          | Analysis, figures, manuscript, and supplementary material                       |
| `costing/`         | Ingredients lists, costing model inputs, and related work for Paper 2           |
| `paper2/`          | Paper 2 analysis, figures, manuscript *(create when work starts)*               |
| `cea/` / `dcea/`   | Equity analysis and distributional CEA work leading into Paper 3                |
| `paper3/`          | Paper 3 decision-rule analysis, figures, manuscript *(create when work starts)* |
| `fairchoices/`     | FairChoices integration work and implementation documentation                   |
| `R/`               | Reusable functions and packages                                                 |
| `reports/`         | Outputs, reproducibility notes, and project documentation                       |
| `reports/figures/` | Shared or final figures for reports and manuscripts                             |
| `lib/`             | Protocol, roadmap, and other reference documents                                |
| `local/`           | Local-only working files (**gitignored**; not tracked)                          |




## Three-paper layout

1. **Paper 1** (`paper1/`, `gbd/`, `gis/`, `data/`) — Disaggregate GBD burden to show geographic health inequalities.
2. **Paper 2** (`costing/`, `paper2/`) — Ingredients-based costing of interventions that reduce geographic disadvantage.
3. **Paper 3** (`cea/` / `dcea/`, `paper3/`, `fairchoices/`) — Ethically grounded priority-setting framework integrated with FairChoices.



## Living notebooks

Five living notebooks (under `literature/` or alongside analysis folders) are kept here. Each answers: *What did I learn? How does it apply to my PhD? What do I still not understand?*

1. Epidemiology & Disease Burden
2. GIS & Spatial Analysis
3. Health Economics & Costing
4. CEA & Equity
5. FairChoices



## Working principles

- Prefer scripted, version-controlled, rerunnable analysis.
- Validate on a small geography before scaling nationally.
- Keep a clear **core analysis** per paper; label extensions separately.

