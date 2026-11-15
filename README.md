# BoilerAlert

- **Live simulator** — [BoilerAlert on Vercel](https://simulator-boiler-alert.vercel.app/)
- **Presentation slides** — [View the slides on Google Drive](https://drive.google.com/file/d/1sF5QpFbz28ZVaXdzVTMN1XfzOzmRm2ay/view?usp=sharing)
- **Challenge** — [Be An Earth System Trend Detective!](https://www.spaceappschallenge.org/2026/challenges/earth-system-trend-detective/)
- **Local event** — NASA Space Apps Challenge 2026, Besançon (14–15 November 2026) - participated virtually

## Team members / Membres

| Name / Nom | GitHub |
| --- | --- |
| Fatmata Babou Condé | [@Fatmata1](https://github.com/Fatmata1) |

## The problem / Le problème

The challenge asks us to visualize changes in Earth science data, quantify them, and test their statistical significance. In buildings, weather-driven changes in electricity use can make sustained overconsumption hard to spot.

## Our solution / Notre solution

BoilerAlert is a software-only web prototype. It compares climate trends in Besançon, Marseille, and London and reports slopes per decade, 95% confidence intervals, and Mann–Kendall results. Mean air temperature rose significantly in all three cities from 1996 to 2024.

The simulator pairs daily NASA temperatures with real meter readings from a London university building. A model fitted on 2016 estimates expected electricity use in 2017. A simulated 25% increase triggers an alert on day three, and the user can plan a maintenance check from that alert.

## NASA data & resources used / Données NASA utilisées

- [NASA POWER (MERRA-2)](https://power.larc.nasa.gov/) — Temperature data for six climate indicators (1996–2024) and the building’s weather-adjusted baseline.
- [NASA Giovanni](https://giovanni.gsfc.nasa.gov/) — Aqua AIRS daytime surface temperature (`AIRS3STM` v7.0) near London (2003–2024).

## Use of AI tools / Utilisation d’outils d’IA

Fatmata designed the project. SI assisted the project with coding and documentation.

## How to run it / Comment le lancer

Open the live simulator in a browser. Choose a climate indicator or try the **Persistent drift** scenario.

## Sources & credits

- [Building Data Genome Project 2](https://github.com/buds-lab/building-data-genome-project-2) — 2016–2017 hourly electricity readings for `Robin_education_Margarito`.
- [SciPy](https://scipy.org/) — Cross-check of the trend statistics.
- [BoilerAlert](https://boileralert.fr/) — Prior work that inspired the standalone Trend Detective prototype.

---

### Submission checklist / Vérifications

- [x] README written in English.
- [ ] Slides open without signing in.
- [x] Use of SI is disclosed.
- [ ] Confirm that the submitted Space Apps **Project** links to this repository.
