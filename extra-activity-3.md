# Extra Activity 3

The dataset contains various financial ratios and ratings for corporate bonds. Here are the columns in the dataset:

1. `CurrentRatio`
2. `QuickRatio`
3. `CashRatio`
4. `P/E`
5. `Earnings Yield`
6. `ROCE`
7. `CASA`
8. `Sector P/E`
9. `Status`
10. `Level`
11. `Rating`
12. `Unnamed: 11` (likely an empty or unused column)

Now let’s perform the following tasks:
1. Select three numerical variables and create scatterplots.
2. Calculate the covariance for the selected pairs.
3. Calculate the mean and standard deviation for the selected variables.
4. Apply Chebyshev's inequality to find upper and lower bounds.

### Scatterplots and Covariance Calculation

I'll create scatterplots for the pairs (`CurrentRatio` vs. `QuickRatio`, `QuickRatio` vs. `CashRatio`, and `CurrentRatio` vs. `CashRatio`) and calculate the covariances for these pairs.

### Scatterplot Insights

1. **CurrentRatio vs QuickRatio**:
   - The scatterplot shows a spread of data points with a slight downward trend, indicating a weak negative relationship between CurrentRatio and QuickRatio.
   
2. **QuickRatio vs CashRatio**:
   - This scatterplot displays a more distinct upward trend, suggesting a positive relationship between QuickRatio and CashRatio.
   
3. **CurrentRatio vs CashRatio**:
   - The scatterplot for this pair shows a spread of points with no clear trend, indicating a very weak or no relationship between CurrentRatio and CashRatio.

### Covariance Analysis

1. **Cov(CurrentRatio, QuickRatio) = -0.618**:
   - The negative covariance indicates an inverse relationship between CurrentRatio and QuickRatio, meaning as one increases, the other tends to decrease.
   
2. **Cov(QuickRatio, CashRatio) = 1.406**:
   - The positive covariance indicates a direct relationship between QuickRatio and CashRatio, meaning as one increases, the other tends to increase as well.
   
3. **Cov(CurrentRatio, CashRatio) = 0.018**:
   - This near-zero covariance suggests a very weak or no linear relationship between CurrentRatio and CashRatio.

### Mean and Standard Deviation

Now, let's calculate the mean and standard deviation for the three selected variables.

### Mean and Standard Deviation Interpretation

1. **CurrentRatio**:
   - Mean: -0.002
   - Standard Deviation: 0.962
   - Interpretation: The average CurrentRatio is close to zero, with a moderate spread around the mean.

2. **QuickRatio**:
   - Mean: -0.013
   - Standard Deviation: 1.446
   - Interpretation: The average QuickRatio is slightly negative, with a larger spread around the mean compared to CurrentRatio.

3. **CashRatio**:
   - Mean: -0.021
   - Standard Deviation: 1.227
   - Interpretation: The average CashRatio is also close to zero, with a moderate spread around the mean.

### Chebyshev's Inequality

To apply Chebyshev's inequality, we'll calculate the upper and lower bounds for each variable. Chebyshev's inequality states that for any k > 1, at least \( \frac{1}{k^2} \) of the data lies within k standard deviations of the mean.

Let's choose \( k = 2 \), which gives us an interval that covers at least \( \frac{3}{4} \) or 75% of the data.

### Chebyshev's Inequality Interpretation

1. **CurrentRatio**:
   - Lower Bound: -1.926
   - Upper Bound: 1.922
   - Interpretation: At least 75% of the data for CurrentRatio lies between -1.926 and 1.922.

2. **QuickRatio**:
   - Lower Bound: -2.905
   - Upper Bound: 2.879
   - Interpretation: At least 75% of the data for QuickRatio lies between -2.905 and 2.879.

3. **CashRatio**:
   - Lower Bound: -2.476
   - Upper Bound: 2.434
   - Interpretation: At least 75% of the data for CashRatio lies between -2.476 and 2.434.

### Summary of Results

- **Scatterplots**: Show relationships between selected numerical variables.
- **Covariances**: Indicate the strength and direction of the linear relationships.
- **Mean and Standard Deviation**: Provide insights into the central tendency and variability.
- **Chebyshev's Inequality**: Offers bounds within which a significant portion of the data lies.

### Links

- [Google Docs with Analysis](https://docs.google.com/document/d/1Co-Jo3yOngoufi7GG09-Jgbr49T5p1tKNBhuX9XCxts/edit?usp=sharing)
- [Google Sheets with Dataset](https://docs.google.com/spreadsheets/d/1L91qzGLJHvWst1VeHjCkBvTGScxfSAlMw1nLl624L84/edit?usp=sharing)
