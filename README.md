# Hurricane Intensity Analysis

This project explores how atmospheric pressure correlates with hurricane intensity using historical storm data. We apply both statistical and probabilistic modeling to test the hypothesis that lower pressure leads to stronger storms, measured by wind speed and storm category.

---

## Project Highlights

- Performed exploratory data analysis on NOAA hurricane dataset (19,000+ rows)
- Found a strong inverse relationship between pressure and wind speed
- Applied both:
  - Simple Linear Regression
  - Bayesian Linear Regression
- Evaluated model fit and predictive uncertainty
- Supported emergency preparedness and forecasting efforts with visual and statistical insights

---

## Files

| File | Description |
|------|-------------|
| `hurricane_intensity_analysis.ipynb` | Main notebook containing EDA, modeling, and visualizations |
| `hurricane_storm_data.csv` | Dataset with storm pressure, wind speed, coordinates, and category |
| `project_presentation_slides.pdf` | Slide deck summarizing the analysis and conclusions |

---

## Key Insights

- Pressure and wind speed show an inverse correlation of approximately -0.72 after filtering outliers
- Linear regression yielded strong R² scores, validating the hypothesis
- Bayesian model provided uncertainty estimates and credible intervals around predictions

---

## Tools and Libraries

- pandas, numpy
- matplotlib, seaborn
- scikit-learn (Linear Regression)
- pymc (Bayesian Regression)

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/trivedif/hurricane-intensity-analysis.git
   cd hurricane-intensity-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn pymc
   ```

3. Open the notebook:
   - Launch `hurricane_intensity_analysis.ipynb` in Jupyter or Colab
   - Execute cells in sequence to run the analysis

---

## Presentation

For a summary of the project including methodology, key results, and visuals, refer to:

[project_presentation_slides.pdf](./project_presentation_slides.pdf)

---

## Author

**Foram Trivedi**  
Data Science · Regression Analysis · Weather Analytics  
[GitHub Profile](https://github.com/trivedif)

---

## Acknowledgements

- [NOAA Hurricane Dataset](https://www.nhc.noaa.gov/)
- [PyMC Documentation](https://www.pymc.io/)
- [Scikit-learn](https://scikit-learn.org/)
