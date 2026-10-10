# Exploratory Data Analysis (EDA)

## 1. Project Introduction
This project performs Exploratory Data Analysis (EDA) on the Palmer Penguins dataset.
The purpose is to understand the dataset, handle missing values,
identify possible outliers, and explore relationships between features.

## 2. Dataset Information
- Dataset: Palmer Penguins
- Data type: Biological measurements of penguins
- Main features: Species, island, bill length, bill depth,
  flipper length, body mass, and sex
- Source: https://github.com/allisonhorst/palmerpenguins

## 3. Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 4. Data Cleaning
The dataset was checked for:
- Missing values
- Duplicate records
- Incorrect data types
- Potential outliers

Missing numerical values were handled using the median,
and categorical missing values were handled using the mode,
where appropriate. Outliers were identified using the IQR method
and reviewed rather than automatically deleted.

## 5. Visualizations
The notebook includes:
- Feature distribution plots
- Boxplots for outlier analysis
- Correlation heatmap
- Pairwise scatter plots

Each visualization is used to explore patterns and relationships
in the data.

## 6. Key Findings
Update this section after running the notebook:
- Total rows and columns: Add the actual dataset shape.
- Missing values: Add the missing-value findings.
- Outliers: Describe the features where potential outliers were found.
- Correlations: Mention the strongest relationships shown by the heatmap.
- Feature patterns: Summarize the patterns observed in the plots.

## 7. Conclusion
EDA helps identify data quality issues and understand patterns
before further statistical analysis or machine learning.

## 8. Project Files
- Task1_Exploratory_Data_Analysis.ipynb: Analysis notebook
- eda_outputs/: Generated visualizations and reports
- README.md: Project documentation

## 9. Author
Hamna Zahoor
