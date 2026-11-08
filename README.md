# 🏠 Real Estate Price Drivers

**EDA · Feature engineering · Pricing analytics**

## Overview
Exploration of residential property listings to identify characteristics associated with apartment prices. The focus is on interpretable analysis of location, floor, size, and price-per-square-meter relationships.

**[View the Jupyter notebook](project/real_estate_patterns.ipynb)**

## Questions investigated
- How strongly is apartment size related to listing price?
- How do floor level and location influence pricing?
- What can price per square meter reveal about regional differences?
- Which variables should be considered in a future price estimation model?

## Methods
1. Validate records and handle missing or inconsistent values.
2. Engineer useful variables, including price per square meter.
3. Analyze the effects of area, floor, distance to the center, and listing date.
4. Explore correlations and visualize segment-level distributions.
5. Summarize possible pricing drivers and the limits of observational data.

## Tools
`Python` · `pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `SciPy`

## Selected observations
The original analysis highlighted total floor area and location as important correlates of listed prices, along with differences between ground-floor and other apartments. These are dataset-specific associations; they should not be treated as established causal effects.

## Run
```bash
pip install jupyter pandas numpy matplotlib seaborn scipy
```

Open `project/real_estate_patterns.ipynb` and provide any referenced datasets where required.

## Project provenance
Notebook copied from [the original project](https://github.com/HendlessWizzard/real_estate_patterns); README rewritten in English.