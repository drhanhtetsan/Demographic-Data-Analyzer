# Demographic Data Analyzer

This project analyzes demographic and income data from the Adult Census dataset using pandas. It answers structured questions about race representation, education, income, working hours, country-level income distribution, and occupation patterns.

## Portfolio Review

This is a useful statistical analysis project for showing practical data wrangling rather than only chart styling. The implementation turns a raw census-style dataset into interpretable metrics that can support socioeconomic discussion and business or policy reporting.

The project is now completed with reproducible calculations for the expected freeCodeCamp test cases.

## Analysis Questions

- How many people are represented in each race category?
- What is the average age of men?
- What percentage of people hold a Bachelor's degree?
- How does income over `50K` differ between higher and lower education groups?
- What is the minimum reported work week, and how many of those workers earn over `50K`?
- Which country has the highest percentage of high earners?
- What is the most common high-income occupation in India?

## Result Summary

| Metric | Result |
| --- | --- |
| Average age of men | 39.4 |
| Bachelor's degree percentage | 16.4% |
| Higher education earning >50K | 46.5% |
| Lower education earning >50K | 17.4% |
| Minimum work hours per week | 1 |
| High earners among minimum-hour workers | 10.0% |
| Highest earning country by percentage | Iran |
| Highest earning country percentage | 41.9% |
| Top high-income occupation in India | Prof-specialty |

## Visualization View

```text
Income >50K by education level

Higher education    | ############################## 46.5%
Lower education     | ###########                    17.4%
```

This simple portfolio visualization highlights the clearest signal in the dataset: people with Bachelor's, Master's, or Doctorate education have a much higher high-income rate than people without those credentials.

## Skills Demonstrated

- pandas filtering and aggregation
- categorical grouping
- percentage calculation
- socioeconomic data interpretation
- test-driven project completion

## Files

- `demographic_data_analyzer.py`: completed analysis function
- `adult.data.csv`: source dataset
- `test_module.py`: expected-result tests
