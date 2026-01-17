# 📊 Scientific Visualization in Astronomy

## Project Description
This project focuses on studying the relationship between electromagnetic emissions in the visible and X-ray spectra of celestial bodies, using scientific visualization techniques applied to astronomical data. Specifically, the analysis investigates the link between visible luminosity and X-ray luminosity, two fundamental quantities for understanding the physical processes governing astronomical source emissions.

Observational data in astronomy are often characterized by high complexity, with values distributed over wide ranges and involving numerous variables. For this reason, scientific visualization is a key tool for exploring datasets and highlighting correlations, density structures, patterns, and potential anomalies that do not emerge immediately from numerical analysis.

Throughout the project, various visualization techniques were adopted, including log-log scatter plots, density maps, and univariate distribution analysis, with the goal of evaluating the effectiveness of each approach in interpreting the data. Additionally, a density-based clustering method (DBSCAN) was tested to verify the presence of significant groupings among the observations.

Developed as part of the Scientific Visualization course (A.Y. 2025/2026), this project aims to demonstrate how a conscious use of visualization techniques can support the analysis and interpretation of complex astronomical phenomena.
[Link to the slides (n italian)](https://www.canva.com/design/DAG6fLkFpy0/INrlAEsH5qZ0NVXHWp1zSA/view?utm_content=DAG6fLkFpy0&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h1f700ca13d)


---

# 🎯 Objectives
The main objectives of the project are:

- Explore relationships between astronomical variables through effective visualizations.

- Identify patterns, densities, and anomalies in the data.

- Evaluate the effectiveness of different visualization techniques.

- Analyze the applicability of clustering methods to astronomical data.

---

# 📁 Dataset
Public astronomical datasets from official sources were utilized:

- [SIMBAD Astronomical Database](https://simbad.cds.unistra.fr/simbad/)   
- [EXTraS Public Archive](https://extras.inaf.it)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/93/low+resolution+spectrometer)
- [HTRU2](https://archive.ics.uci.edu/dataset/372/htru2)


The data contain observational measurements related to the luminosity and physical properties of celestial objects.

---

# 🧹 Data Preparation
Prior to the visualization phase, the data underwent:

- Cleaning and removal of missing or invalid values.

- Selection of the most relevant variables.

- Application of logarithmic scales to handle wide ranges of values.

These steps were fundamental for obtaining readable and meaningful visualizations.

---
# 📈 Visualization Techniques
Several techniques were employed in this project:

- Log-log scatter plots for correlation analysis.

- Heatmaps and density plots to highlight data concentrations.

- 2D Histograms for distribution studies.

- Univariate distributions (histograms and cumulative distribution functions).

- Logarithmic Boxplots to analyze luminosity distribution across different ID Types.

Each visualization was chosen based on specific analytical goals.

---

# 🧑‍💻 Technologies Used
Python for data analysis and visualization.

- NumPy and Pandas for dataset manipulation and organization.

- Matplotlib and Seaborn for creating scientific plots.

- scikit-learn for clustering analysis (DBSCAN).

- SciPy for Kernel Density Estimation (KDE).

Canva for the final presentation.

---

# 👥 Authors
Daniele del Pozzo

Andrea Rossi

Mohamed El Jaouhari
