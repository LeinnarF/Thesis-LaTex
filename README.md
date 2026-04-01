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
The repository is organized as follows:
- `Thesis-main.tex`: The main LaTeX file for the thesis document.
- `main-chapter-*.tex`: Individual chapters (1 to 5) of the thesis.
- `Figures/`: Contains all graphical assets:
  - `dev-system/`: Screenshots of the developed mobile application.
  - `evaluation/`: Graphs and charts from the system evaluation (TAM, ISO).
  - `flowchart/`: Detailed flowcharts of the algorithms and system processes.
  - `SysArch.png`: System architecture diagram.
  - `GanttChart.png`: Project timeline and Gantt chart.
  - `TSP.jpeg`: Visualization of the Traveling Salesman Problem.
- `reference.bib`: Bibliography file in BibLaTeX format.
- `agamcode.tex` & `sacode.tex`: Implementation details for the AGAM and SA algorithms.
- `Thesis-main.pdf`: The compiled version of the thesis document.

## How to Build
To compile the LaTeX source into a PDF:
1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2. Use `pdflatex` (or `latexmk` with `biber` for references).
3. The main file is `Thesis-main.tex`.

Example command:
```bash
latexmk -pdf Thesis-main.tex
```

## Authors
- **Bryan C. Declaro**
- **Franniel Luigi C. Hilario**
- **Brian Gabriel G. Magbanua**
- **Richard M. Manansala**

---
*Developed for Bulacan State University.*
