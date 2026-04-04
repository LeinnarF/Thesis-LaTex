# LAKAD: A Personalized Mobile Itinerary Generator with Focus in Bulacan Tourism

**LAKAD** is a mobile itinerary generator designed to promote tourism in Bulacan, Philippines. It addresses the inefficiencies of manual itinerary planning by integrating route optimization tools and personalization features.

## Abstract
Manual itinerary planning is inefficient because of poor personalization and the lack of integration with route optimization tools. This study develops Lakad, a personalized mobile itinerary generator for promoting tourism in Bulacan. Lakad utilized an Adaptive Genetic Algorithm with Dynamic Mutation and Crossover Probabilities (AGAM) for preference-based itinerary generation and integrates Simulated Annealing (SA) for further route optimization. 

The research involved a comparative evaluation of seven different algorithms for the Traveling Salesman Problem (TSP), with Simulated Annealing (SA) being identified as having the best balance of accuracy and execution speed for real-time mobile applications using Simple Additive Weighting (SAW). The system was evaluated using the Technology Acceptance Model (TAM) and ISO/IEC 25010:2023 standard, receiving favorable scores from both end-users and experts.

## Key Features
- **AGAM (Adaptive Genetic Algorithm with Dynamic Mutation and Crossover Probabilities)**: For generating itineraries based on user preferences.
- **Simulated Annealing (SA)**: For route optimization to ensure the most efficient travel path.
- **Bulacan Tourism Focus**: Integrated local tourism information for the province of Bulacan.
- **Evaluation Framework**: Assessed via TAM (Mean: 4.67) and ISO/IEC 25010:2023 (Mean: 4.76).

## Repository Structure
The repository is organized into several key directories:

- **`Manuscript/`**: Contains the full LaTeX source files for the thesis document.
  - `Thesis-main.tex`: The main LaTeX entry point for the thesis.
  - `main-chapter-*.tex`: The five main chapters of the thesis.
  - `agamcode.tex` & `sacode.tex`: Source code for the AGAM and SA algorithm implementations.
  - `pseudocode.tex`: Detailed algorithms described in pseudocode.
  - `syseval.tex`: System evaluation results and analysis.
  - `Thesis-main.pdf`: The final compiled version of the full thesis.
- **`IMRAD/`**: Contains a condensed version of the research in IMRAD format (Introduction, Methods, Results, and Discussion), suitable for journal submission.
  - `imrad-main.tex`: The main entry point for the IMRAD document.
  - `section-*.tex`: Individual sections (Introduction, Methods, Results, and Conclusion).
  - `imrad-main.pdf`: The compiled version of the IMRAD document.
- **`Figures/`**: Contains all visual assets used in both documents.
  - `dev-system/`: Screenshots from the mobile application.
  - `evaluation/`: Data visualizations, TAM scores, and ISO standard results.
  - `flowchart/`: Algorithmic and system flowcharts.
  - `SysArch.png`: System architecture diagram.
  - `GanttChart.png`: Project timeline.
- **`CV/`**: Curriculum Vitae of the research proponents.
- **`Instrument/`**: Research instruments, such as surveys and questionnaires.
- **`Letters/`**: Official transmittal and permission letters.
- **`Misc/`**: Miscellaneous documents and resources.
- **Root Directory**:
  - `abstract.tex`: The research abstract.
  - `reference.bib`: Bibliography containing all references in BibLaTeX format.

## How to Build
To compile the LaTeX source into a PDF:
1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2. Use `pdflatex` or `latexmk`. For references, use `biber`.

### Build Full Thesis
```bash
cd Manuscript
latexmk -pdf Thesis-main.tex
```

### Build IMRAD Version
```bash
cd IMRAD
latexmk -pdf imrad-main.tex
```

## Authors
- **Bryan C. Declaro**
- **Franniel Luigi C. Hilario**
- **Brian Gabriel G. Magbanua**
- **Richard M. Manansala**

---
*Developed for the College of Science, Bulacan State University.*
