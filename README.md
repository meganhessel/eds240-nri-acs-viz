# Visualizing FEMA NRI Data

EDS240 Data Viz

Author: Megan Hessel

Date: Feb 12, 2026

## Purpose

This repository uses data visualization to understand:

1.  How FEMA National Risk Index scores for counties in California compare to those in other states.

2.  How does climate hazard risk exposure vary across racial / ethnic groups in California.

## File Structure

Final data visualizations are accomplished within the `HW2.qmd` and `HW3.qmd` (and there html and pdf form) which are located in the root. The finalized visualizations are also saved as pngs in the `fig` folder. Also in the root is the README and the unpolished, preliminary data exploration and visualization quarto documents called `HW#_draft.qmd`. There is **no** data within this repository.

```         
eds240-nri-acs-viz
├─ figs
│  ├─ nri_lollipop_plot.png
│  ├─ nri_stackedPropBar_plot.png
│  └─ CA_NRI_racial_prop_plot.png
├─ HW2_draft.qmd
├─ HW2.qmd
├─ HW3_draft.qmd
├─ HW3.qmd
└─ README.md
```

## Data

The data used in this repository is the [National Risk Index for Natural Hazards](https://www.fema.gov/flood-maps/products-tools/national-risk-index) which is used in the [FEMA Resilience Analysis and Planning Tool (RAPT)](https://www.fema.gov/emergency-managers/practitioners/resilience-analysis-and-planning-tool).

The HW3 also used the [US Census Bureau’s American Community Survey (ACS)](https://www.census.gov/programs-surveys/acs/about.html) for California's racial and ethnic group data. 

## Reference

Federal Emergency Management Agency (FEMA). (2026). *National Risk Index for Natural Hazards* (dataset). <https://www.fema.gov/flood-maps/products-tools/national-risk-index>.

Federal Emergency Management Agency (FEMA). (2025). *Resilience Analysis and Planning Tool* (RAPT). <https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/>.

Federal Emergency Management Agency (FEMA). (2025). *National Risk Index Data Technical Documentation*. <https://www.fema.gov/sites/default/files/documents/fema_national-risk-index_technical-documentation.pdf>

US Census Bureau. (2025).*About the American Community Survey*. <https://www.census.gov/programs-surveys/acs/about.html>

