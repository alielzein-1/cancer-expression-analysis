# TP53 Gene Expression Analysis in Tumor vs Normal Tissue

## About This Project
This project analyzes the expression of the **TP53 gene**, a key tumor suppressor, in **tumor versus normal tissue samples**.  
It demonstrates:

- Data handling and cleaning in R  
- Statistical analysis using a **t-test**  
- Visualization with **ggplot2**  
- Reproducible research practices

The goal is to showcase the ability to process biological data, perform statistical comparisons, and communicate results clearly — skills relevant for bioinformatics research.

---

## Folder Structure
cancer-expression-analysis/
  - README.md ← this file
  - data/ ← contains tp53_data.csv
  - scripts/ ← contains analysis.R
  - figures/ ← contains tp53_boxplot.png

---

## Dataset

- **tp53_data.csv**:  
  - `SampleID` — unique identifier for each sample  
  - `Condition` — `Normal` or `Tumor`  
  - `TP53_expression` — normalized gene expression value  

---

## Analysis Workflow

1. Load the dataset in R  
2. Calculate summary statistics (mean, standard deviation)  
3. Conduct a **t-test** comparing tumor vs normal expression  
4. Generate a **boxplot** with jitter points and p-value annotation  
5. Save the figure to `figures/tp53_boxplot.png`  

---

## Results

- TP53 expression is **higher in tumor samples** compared to normal tissue  
- The difference is statistically significant (p-value from t-test shown in the plot)  
- This highlights potential dysregulation of TP53 in cancer samples  

---

## How to Run

1. Open **RStudio**  
2. Open `scripts/analysis.R`  
3. Run the script — the boxplot will appear and save automatically in `figures/`  

---

## Extensions

- Additional genes (e.g., BRCA1, MYC) can be analyzed similarly  
- Multiple genes can be visualized in a **heatmap**  
- Dataset can be expanded to other cancer types or tissues  

---

## Skills Demonstrated

- R programming and data manipulation  
- Statistical testing and interpretation  
- Data visualization and figure generation  
- Project organization and reproducibility  
- Bioinformatics awareness and application
