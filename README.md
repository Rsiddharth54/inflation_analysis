# Inflation Predictions Project

This project analyzes inflation data and builds predictive models for inflation rates using various economic indicators, from the Yuan Dynasty (1271–1368).
Certified by the London School of Economics (LSE)

## 📁 Project Structure

```
inflation-predictions/
├── data/                    # Data files
│   ├── yuan_inflation_data.dta
│   ├── BoE_interest_rates.csv
│   ├── economic_indicators_interest_rate_setting.csv
│   ├── rate_change_probabilities.csv
│   ├── rates_with_quarterly_indicators.csv
│   ├── boe_with_quarterly_indicators.csv
│   └── README_yuan_inflation_data.txt
├── scripts/                 # Analysis scripts
│   ├── inflation_analysis.qmd      # Main analysis document
│   ├── inflation_analysis.ipynb    # Jupyter notebook version
│   └── interactive_analysis.ipynb  # Interactive analysis
├── outputs/                 # Generated outputs
│   └── figures/            # Generated plots and visualizations
│       ├── confusion_matrix.png
│       ├── roc_curve.png
│       ├── precision_recall_curve.png
│       ├── feature_importance.png
│       ├── probability_distribution.png
│       ├── advanced_confusion_matrix.png
│       ├── advanced_roc_curve.png
│       └── yuan_dynasty_variables.png
├── book/                   # Quarto book project
│   ├── _quarto.yml
│   ├── index.qmd
│   ├── intro.qmd
│   ├── summary.qmd
│   ├── references.qmd
│   ├── references.bib
│   └── cover.png
└── README.md              # This file
```

## 🎯 Project Overview

This project focuses on:
- **Data Analysis**: Exploring inflation data and economic indicators
- **Model Building**: Developing predictive models for inflation rates
- **Model Evaluation**: Assessing model performance using various metrics
- **Visualization**: Creating informative plots and charts

## 📊 Data Sources

- **Yuan Inflation Data**: Historical inflation data from the Yuan dynasty
- **Bank of England Data**: Interest rates and economic indicators
- **Economic Indicators**: Various macroeconomic variables

## 🔧 Key Scripts

### Main Analysis (`scripts/inflation_analysis.qmd`)
- Primary analysis document in Quarto format
- Contains the complete analysis workflow
- Includes model fitting, evaluation, and interpretation

### Interactive Analysis (`scripts/interactive_analysis.ipynb`)
- Interactive Jupyter notebook for exploratory analysis
- Useful for data exploration and quick prototyping

## 📈 Outputs

All generated figures and visualizations are stored in `outputs/figures/`:
- **Confusion Matrices**: Model classification performance
- **ROC Curves**: Model discrimination ability
- **Feature Importance**: Key variables in the model
- **Probability Distributions**: Model prediction distributions

## 🚀 Getting Started

1. **Install Dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. **Run Analysis**:
   ```bash
   quarto render scripts/inflation_analysis.qmd
   ```

3. **Interactive Analysis**:
   ```bash
   jupyter notebook scripts/interactive_analysis.ipynb
   ```

## 📝 Notes

- The main analysis document (`inflation_analysis.qmd`) contains the complete workflow
- All data files are organized in the `data/` directory
- Generated outputs are stored in `outputs/figures/`
- The project includes a Quarto book setup in the `book/` directory

## 🔍 Model Performance

The project includes various model evaluation metrics:
- Classification accuracy
- ROC curves and AUC scores
- Precision-recall curves
- Feature importance analysis

For detailed results, see the analysis documents in the `scripts/` directory.
