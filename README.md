# Student Alcohol Consumption: Statistical Analysis

Project for the **Descriptive Statistics** course of the MBA in Data Science.

## Objective

Analyze alcohol consumption among high school students in Portugal, identifying patterns related to social habits, academic performance, and demographic variables.

## Data

| File | Source | Description |
|---|---|---|
| `Student_Alcohol.csv` | UCI / Kaggle | Main dataset: 395 students with grades, habits, and alcohol consumption |
| `colunas_pt.json` | Own authorship | Column name mapping to Portuguese |
| `valores_pt.json` | Own authorship | Categorical value mapping to Portuguese |

External source: [Kaggle — Student Alcohol Consumption](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption)

## Notebook Structure

1. **Imports**
2. **Dataset Preparation:** CSV loading, column and value translation, overview
3. **Exploratory Analysis**
   - 3.1 Distribution by Address
   - 3.2 Alcohol Consumption on Weekdays
   - 3.3 Consumption by Address
   - 3.4 Consumption by Parental Status
   - 3.5 Final Grade × Study Time by Alcohol Level
4. **Summary and Conclusions**
   - 4.1 General Descriptive Measures
   - 4.2 Summary: Consumption × Performance
   - 4.3 Conclusions

## Key Findings

**Sample profile:** 395 students, 77.7% urban. 88.9% have very low or low alcohol consumption on weekdays.

**Consumption and address:** rural students show higher average consumption (12.5%) than urban students (4.9%), but the sample disproportion (307 vs 88) limits absolute comparisons.

**Consumption and family structure:** students with separated parents have a higher proportion of medium and high consumption (14.7% vs 8.2%), but the group represents only 41 students (10.4% of the sample).

**Consumption and performance:** the data shows no association between alcohol consumption and academic approval. The very high consumption group has 77.8% approval, above low (58.7%) and medium (65.4%). There is no linear pattern. The high and very high groups total only 18 students, which limits any conclusions about those levels.

**Observed mechanism:** what the data clearly shows is the association between consumption and study time. Those who drink more on weekdays study less. The average study time in the very low consumption group is 2.14, compared to values below 1.88 in the other groups.

## Requirements

```
pandas
matplotlib
scipy
numpy
```
