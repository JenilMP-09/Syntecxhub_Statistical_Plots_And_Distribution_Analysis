# Statistical Plots & Distribution Analysis

## Introduction
This project focuses on statistical visualization, distribution analysis, and data preprocessing using Python.  
The notebook demonstrates how to clean a real-world cafe sales dataset, handle missing values, detect outliers, and visualize distributions using statistical plots.

The analysis is performed on the dataset:

- `dirty_cafe_sales.csv`

and implemented inside:

- `Syntecxhub_Statistical_Plots_And_Distribution_Analysis.ipynb`

---

## Project Objectives

- Perform data cleaning and preprocessing
- Handle missing and inconsistent values
- Analyze feature distributions
- Generate histograms, KDE plots, and boxplots
- Detect outliers and skewness
- Compare distributions across categories
- Export insights and interpretations

---

## Dataset Information

### Dataset Name
`dirty_cafe_sales.csv`

### Dataset Shape
- Rows: 10000
- Columns: 8

### Columns
Transaction ID, Item, Quantity, Price Per Unit, Total Spent, Payment Method, Location, Transaction Date

---

## Features Covered

### Data Cleaning
- Missing value analysis
- Null value handling
- Data type corrections
- Replacing invalid/unknown entries
- Numeric conversion

### Statistical Analysis
- Distribution analysis
- Skewness detection
- Spread analysis
- Outlier identification

### Visualization
The notebook includes:

- Histograms
- KDE (Kernel Density Estimation) plots
- Boxplots
- Comparative distribution plots

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Installation

### Clone the repository
```bash
git clone <repository-url>
cd <repository-folder>
```

### Install dependencies
```bash
pip install pandas numpy matplotlib seaborn notebook
```

---

## Usage

### Run Jupyter Notebook
```bash
jupyter notebook
```

Open:

```text
Syntecxhub_Statistical_Plots_And_Distribution_Analysis.ipynb
```

Run all cells sequentially to reproduce the analysis.

---

## Data Preprocessing Workflow

The notebook performs the following preprocessing tasks:

1. Inspect missing values
2. Analyze missing value percentages
3. Fill categorical null values using mode
4. Fill numeric null values using mean/median
5. Convert object columns to numeric types
6. Handle unknown or invalid entries
7. Validate cleaned dataset

---

## Statistical Visualization Workflow

The notebook demonstrates:

- Distribution inspection using histograms
- Density estimation using KDE plots
- Outlier analysis using boxplots
- Spread and skewness analysis
- Comparative statistical analysis

---

## Example Insights

- Certain columns contain significant missing values but remain recoverable.
- Numeric columns originally stored as object types are converted correctly.
- Boxplots help identify potential outliers in sales-related metrics.
- KDE plots reveal distribution patterns and skewness.

---

## File Structure

```text
.
├── dirty_cafe_sales.csv
├── Syntecxhub_Statistical_Plots_And_Distribution_Analysis.ipynb
└── README.md
```

---

## Troubleshooting

### Common Issues

#### ModuleNotFoundError
Install missing packages:

```bash
pip install <package-name>
```

#### Notebook Not Opening
Ensure Jupyter Notebook is installed correctly:

```bash
pip install notebook
```

---

## Future Improvements

- Add automated preprocessing pipeline
- Add advanced statistical testing
- Include correlation heatmaps
- Build interactive dashboards
- Export reports automatically

---

## Contributors

Developed for statistical distribution analysis and visualization practice.

---

## License

This project is intended for educational and analytical purposes.

You may modify and use it for learning and research.

---
