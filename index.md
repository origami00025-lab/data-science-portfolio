# Mengjie Lu — Data Science Portfolio

I study data science and data visualization, using Python, pandas, NumPy and Matplotlib to develop reproducible exploratory analyses.

## Featured project: Iris measurements
**Question:** How do petal measurements and median flower measurements differ between three Iris species in this historical sample?

**Status:** Completed descriptive analysis.

![Petal measurements by species](assets/petal_scatter.svg)

Setosa petal lengths span 1.0–1.9 cm, while the other species start at 3.0 cm in this sample. The other two species overlap, so visual separation must not be interpreted as measured classification accuracy.

![Median measurements by species](assets/species_medians.svg)

Median petal lengths are 1.50, 4.35 and 5.55 cm for setosa, versicolor and virginica. Medians summarize groups but hide their spread.

**Limitation:** This small historical sample does not establish performance on new flowers. UCI documents historical data discrepancies; this project retains the downloaded data variant and reports descriptive results only.

[Project repository and reproduction instructions](https://github.com/origami00025-lab/data-science-project)

Source: Fisher, R. (1936). *Iris*. UCI Machine Learning Repository. https://doi.org/10.24432/C56C76. Data: CC BY 4.0; source measurements retained, column headers added.

The styled website entry is the adjacent index.html. This index.md provides the Markdown entry requested in the course instructions and a readable content alternative.
