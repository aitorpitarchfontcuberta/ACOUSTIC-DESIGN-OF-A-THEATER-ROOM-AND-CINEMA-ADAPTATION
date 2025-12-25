# Acoustic Design of a Theater Room and Cinema Adaptation

This repository contains the project files and documentation for the acoustic design, modelling, simulations, and evaluation carried out during the design of a theatre room and its adaptation to a cinema configuration.

The full project report (PDF) included in the repository documents the problem statement, modelling process, design decisions, simulation setup, results, and acoustic evaluations. Consult that document for detailed background, assumptions, parameter values, and complete results.

## Contents

- ease project/  
  - [Theatre].(Ease Project/Theatre)
  - files/ — ancillary files used by the EASE projects (measurement files, impulse responses, exported results, images, etc.)
- Project report pdf " — full written report describing objectives, methods, simulations and conclusions

## Project overview

The objective of this work is to design and evaluate the acoustics of a performing theatre room and explore its adaptation to a cinema layout. The workflow includes:

- Creating room geometry and seating layouts in EASE (or equivalent acoustic modelling software).
- Defining sound sources, loudspeaker configurations (for the cinema adaptation), and receiver positions.
- Assigning material acoustic properties and modelling room acoustic treatments.
- Running simulations to obtain objective acoustic metrics (e.g., RT60, clarity (C80/C50), speech transmission index (STI)/STIPA, early decay time, etc.).
- Comparing configurations and proposing design recommendations based on simulation results and acoustic criteria.

For full methodological details, parameter values, graphs and discussion, see the Project_Report.pdf included in the repository.

## Opening and using the EASE projects

1. Install EASE (AFMG EASE) or the acoustic modelling tool used to create the projects:
   - EASE website: [AFMG EASE](https://www.afmg.eu)
2. Open the project files located in `ease project/ease projects/`. Typical file extensions for EASE projects are `.apr` or other EASE-specific project files — open the file with EASE.
3. Inspect the model: geometry, source definitions, receiver grids, and assigned materials.
4. Run the simulations inside EASE to reproduce the results. Exported results and images (if present) are inside `ease project/files/`.
5. If you do not have access to EASE, review exported data inside `ease project/files/` (csv/txt or images) to examine results.

If the repository includes exported impulse responses or measurement data, those files can be used in audio analysis software (e.g., MATLAB, Python with scipy/numpy, Room EQ Wizard) to reproduce derived metrics and plots.

## Repository structure (example)

- ease project/
  - ease projects/          — EASE project files
  - files/                  — exported results, measurement files, images
- Project_Report.pdf        — final report with methods, results and conclusions
- README.md                 — this file

(Actual filenames and structure may vary; use `ls`/your file browser to inspect the exact filenames.)

## Reproducing results

To reproduce simulations and figures you will typically need:
- EASE (same or compatible version used to build the projects),
- The project files in `ease project/ease projects/`,
- Any exported measurement or configuration files in `ease project/files/`.

Recommended steps:
1. Open the EASE project(s).
2. Verify material and source settings match those documented in the Project_Report.pdf.
3. Run the same simulation scenarios (seating layouts, loudspeaker/sound source configurations).
4. Export objective acoustical metrics and compare with values reported in the PDF.

If you need scripts to parse exported data (CSV/TXT) into plots or compute acoustic metrics, consider using Python (numpy/scipy/matplotlib) or MATLAB. These scripts are not included by default unless present in the `files/` folder.

## Key findings (summary)

A short, high-level summary of conclusions is provided here for convenience. For complete discussion and numeric results, refer to the Project_Report.pdf.

- The proposed room geometry and surface treatments achieve target reverberation characteristics for theatre use.
- Adapting the space to a cinema layout requires specific adjustments to loudspeaker placement and additional acoustic treatments to satisfy cinema clarity and intelligibility targets.
- Simulation results guided placement of absorptive/reflective treatments and suggested modifications to seating and speaker arrays to balance reverberation and clarity.

(See the PDF for detailed tables, plots, and recommended treatment specifications.)

## Contributing

Contributions are welcome. If you propose changes:
- Open an issue describing the change or enhancement.
- Provide updated EASE project files and, where applicable, exported result files and scripts.
- Include a brief description of the test/reproduction steps for any modifications.

## License

No license file is included in this repository. If you wish to reuse or redistribute materials, please contact the repository owner or add an explicit LICENSE file to clarify terms.

## Author / Contact

Project author: aitorpitarchfontcuberta  
GitHub: [https://github.com/aitorpitarchfontcuberta](https://github.com/aitorpitarchfontcuberta)

For questions about the project, simulation details, or to request raw data/scripts, open an issue in this repository or contact the author via their GitHub profile.

## Acknowledgements

This work uses EASE for acoustic modelling. See the Project_Report.pdf for references, standards used, and acknowledgements.
