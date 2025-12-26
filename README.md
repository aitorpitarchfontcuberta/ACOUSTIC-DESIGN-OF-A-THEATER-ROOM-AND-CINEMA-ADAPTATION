# Acoustic Design of a Theater Room and Cinema Adaptation

This repository contains the project files and documentation for the acoustic design, modelling, simulations, and evaluation carried out during the design of a theatre room and its adaptation to a cinema configuration.

The full project report (PDF) included in the repository documents the problem statement, modelling process, design decisions, simulation setup, results, and acoustic evaluations. Consult that document for detailed background, assumptions, parameter values, and complete results.

## Contents

- ease project/  
  - [Theatre](<Ease Project/Theatre>) : EASE project files of the theatre design.
  - [CInema](<Ease Project/Cinema>) : EASE project files of the cinema adaptation.
- [Project report pdf](<DESIGN OF A THEATER ROOM AND CINEMA ADAPTATION.pdf>)  — full written report describing objectives, methods, simulations and conclusions.

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


## Authors / Contact

Project authors: Aitor Pitarch  and Bernat García

Aitor Pitarch: [GitHub](https://github.com/aitorpitarchfontcuberta)    [Linkedin](https://linkedin.com/in/aitor-pitarch-fontcuberta-a9970a367).
Bernat García: [Linkedin](https://www.linkedin.com/in/bernat-garcia-bahi-6b1097367/?locale=en_US)

For questions about the project, simulation details, or to request raw data/scripts, open an issue in this repository or contact the authors via their GitHub profile.

## Acknowledgements

This work uses EASE for acoustic modelling. See the Project_Report.pdf for references, standards used, and acknowledgements.
