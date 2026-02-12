# Alcohol Consumption and National Happiness

## Project Overview
This project explores the relationship between national happiness scores and alcohol consumption using cross-country data. Through exploratory data analysis (EDA), correlation analysis, and region-specific visualizations, the project examines how total alcohol consumption and different types of alcohol (beer, wine, spirits) relate to reported happiness levels. The analysis emphasizes careful interpretation of observational data and explicitly avoids causal claims.

## Research Questions
- Is there a relationship between national happiness scores and alcohol consumption?
- Does this relationship differ by type of alcohol (beer, wine, spirits)?
- How does the relationship change when countries are analyzed within geographic regions?
- To what extent might economic development and regional clustering confound observed correlations?

## Data
The dataset combines:
- National happiness scores
- Per-capita alcohol consumption (total and by beverage type)
- Regional classifications and development indicators

The data represent country-level aggregates and are treated as observational rather than experimental.

## Methods
- Exploratory data analysis using pandas and matplotlib
- Descriptive statistics and correlation analysis
- Disaggregation by alcohol type
- Region-specific scatterplots to assess within-region relationships
- Comparative interpretation of global vs. regional patterns

The analysis prioritizes transparency and interpretive caution, particularly with respect to confounding variables such as wealth, development, and cultural norms.

## Key Findings
- Total alcohol consumption shows a positive bivariate association with national happiness at the global level.
- Wine and beer consumption exhibit moderate correlations with happiness, while spirits consumption shows a weaker relationship.
- Within-region analyses (e.g., Western Europe) reveal weaker and more clustered relationships, suggesting that global correlations are partially driven by cross-regional differences.
- Economic development and regional context appear to mediate much of the observed association.

## Limitations
- The analysis is correlational and does not establish causation.
- Economic and cultural variables are highly interrelated, raising the risk of confounding and multicollinearity.
- Country-level aggregates may mask within-country variation.
- Data sources may not be perfectly aligned temporally.

## Tools and Technologies
- Python
- pandas
- matplotlib
- Jupyter Notebook

## Future Work
Potential extensions of this project include:
- Multivariate regression or partial correlation analysis
- Log transformations to address skewed distributions
- Region-fixed-effects models
- Longitudinal analysis using time-series happiness and consumption data

## Repository Structure
```
.
├── alcohol-happiness.ipynb
├── data/
│   └── (raw and cleaned datasets)
└── README.md
```

## Notes
This project is intended as an exploratory data analysis and portfolio demonstration. The findings should be interpreted as descriptive patterns rather than policy or behavioral conclusions.
