# Economic-Development-Analysis
This project analyzes long-term economic growth across individual countries and globally, involving extensive data wrangling, merging, and statistical modeling. The goal of the project is to uncover key economic factors driving development by examining trade, labor force, population trends, and GDP growth over several decades.

## Data Sources
The project relies on multiple datasets:
- GDP and Population Data: University of Groningen Maddison Project
- Trade Data: United Nations Department of Economic and Social Affairs
- Economic and Health Data: World Bank World Development Indicators Dataset

## Methodology
1. Data Cleaning and Processing  
Merging datasets from different sources with varying formats and conventions. (All work done with pandas dataframes)  
Handling missing values, ensuring consistent country name mappings.  
Standardizing economic indicators for analysis across different timeframes.  
2. Feature Selection  
Read 'Emerging From Poverty' by Gerald Meier to inform understanding of widely accepted development indicators and predictors.  
Chose final growth predictors and indicators based on data availability.  
In the end analyzed 8 influential factors and 14 economic indicators.  
4. Statistical Analysis  
Calculated R² correlations between indicators and predictors for individual countries over data-available time span.  
Compiled results in boxplots to visualize which predictors are most often highly correlated with growth indicators.  
Visualized relationships in ≈180 countries over 70+ year time-frame.  

## Key Findings
