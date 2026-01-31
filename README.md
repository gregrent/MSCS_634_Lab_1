# Lab 1: Data Visualization, Processing, and Statistical Analysis Using Python

## Purpose
The purpose of this lab was to explore and analyze a weather dataset for Seattle using Python and Pandas. The objectives included performing data preprocessing, creating meaningful visualizations, and applying statistical analysis techniques to understand trends, distributions, and relationships within the dataset. This exercise aimed to demonstrate practical skills in data cleaning, exploratory data analysis, and basic statistical computations.

## Key Insights

### Visualizations
- **Line Plot (Maximum Temperature Over Time):** Showed clear seasonal variation in maximum temperatures. Winter days had low maximum temperatures (~6–7°C), summer days were much hotter (~28–31°C), and transitional fall dates had moderate temperatures (~13°C).
- **Scatter Plot (Max Temperature vs Precipitation):** Indicated that colder days were associated with higher precipitation, while warmer summer days had little to no precipitation. This suggests a seasonal relationship between temperature and precipitation.
- **Bar Chart (Weather Conditions):** Highlighted that sunny conditions were most frequent in the sample, while snow, rain, and fog occurred less often.

### Statistical Measures
- **Central Tendency:** Mean and median values provided an understanding of typical temperature and precipitation levels, while mode highlighted the most common values (e.g., zero precipitation on several summer days).
- **Dispersion:** Range, quartiles, IQR, variance, and standard deviation quantified variability in numeric columns, revealing that temperatures had wider variability compared to wind speed or precipitation in this small sample.
- **Correlation:** Analysis showed strong positive correlation between maximum and minimum temperatures, while other numeric variables such as precipitation and wind speed had weaker correlations with temperature.

## Challenges and Decisions
- The dataset had missing values in the precipitation column, which were handled using mean imputation to maintain dataset integrity.
- Outlier detection was applied using the IQR method for maximum temperature to identify extreme values that could skew analysis.
- Data reduction techniques, including sampling and dropping less relevant columns, were applied to simplify the dataset for demonstration purposes.
- Scaling and discretization were implemented to standardize numeric columns and categorize continuous variables into meaningful bins for easier interpretation.
- A key decision was to perform all analyses on a small subset of the dataset to clearly demonstrate preprocessing, visualization, and statistical techniques in a compact, reproducible manner.

---
