BoilerAlert
Live demo — BoilerAlert on Vercel.
- Challenge — Be An Earth System Trend Detective!
- Local event — NASA Space Apps Challenge 2026, Besançon (14–15 November 2026)
Team members / Membres
Name / Nom	GitHub
Fatmata Babou Condé	@Fatmata1


The problem / Le problème
The challenge asks us to visualize changes in Earth science data, quantify them, and test their statistical significance. In buildings, weather-driven changes in electricity use can make sustained overconsumption hard to spot.
Our solution / Notre solution
BoilerAlert is a software-only web prototype. It compares climate trends in Besançon, Marseille, and London and reports slopes per decade, 95% confidence intervals, and Mann–Kendall results. Mean air temperature rose significantly in all three cities from 1996 to 2024.

The simulator pairs daily NASA temperatures with real meter readings from a London university building. A model fitted on 2016 estimates expected electricity use in 2017. A simulated 25% increase triggers an alert on day three, and the user can plan a maintenance check from that alert.
NASA data & resources used / Données NASA utilisées
- NASA POWER (MERRA-2) — Temperature data for six climate indicators (1996–2024) and the building’s weather-adjusted baseline.
- NASA Giovanni — Aqua AIRS daytime surface temperature (AIRS3STM v7.0) near London (2003–2024).
Use of AI tools / Utilisation d’outils d’IA
Fatmata designed the project. SI assisted with coding and documentation.
Deliverables / Livrables
- Source code — [Standalone HTML and JavaScript](./BoilerAlert-Space-Apps-Simulator.html).
How to run it / Comment le lancer
Open the live demo or open BoilerAlert-Space-Apps-Simulator.html in a browser. Choose a climate indicator or try the Persistent drift scenario.
Sources & credits
- Building Data Genome Project 2 — 2016–2017 hourly electricity readings for Robin_education_Margarito.
- SciPy — Cross-check of the trend statistics.
- BoilerAlert — Prior work that inspired the standalone Trend Detective prototype.
