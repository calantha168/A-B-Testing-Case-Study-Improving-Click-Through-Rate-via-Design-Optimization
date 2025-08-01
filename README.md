A/B Testing Case Study: Improving Click-Through Rate via Design Optimization
This project showcases a full A/B testing workflow using Python to evaluate the impact of a UI design change on click-through rates (CTR). It includes statistical testing, power analysis, simulation of user behavior, and business interpretation of the results.

Project Overview
The goal was to determine whether a new interface design (Group B) leads to a significantly higher CTR compared to the current version (Group A). The process involved:

- Simulating binary click data
- Conducting a power analysis to find the required sample size
- Running a two-proportion Z-test
- Visualizing the test results
- Drawing business conclusions and recommendations

 Files Included
- `ab_testing_notebook.ipynb` — Main notebook with code, results, and visualizations
- `ab_test_data.csv` — Simulated user click data
- `ab_testing_case_study.pdf` — Final PDF report summarizing methodology and findings

 Key Methods Used
- Power Analysis (`statsmodels.stats.power`)
- Proportion Effect Size Calculation
- Two-Proportion Z-Test
- Data Visualization with Matplotlib
- Aggregation and Summary Statistics using Pandas

Technologies
- Python 3.x
- Jupyter Notebook
- pandas, numpy
- matplotlib
- statsmodels

Results
- Group A (Control) CTR: 11.92%
- Group B (Treatmeant) CTR: 14.18%
- Z-statistic: -2.143  
- P-value: 0.0321  
- Conclusion: Statistically significant — Group B performs better.

Business Recommendation
Implement the Group B design for all users to improve CTR. Continue A/B testing additional UI changes to drive further gains.

Feel free to clone or fork this project for your own experimentation with A/B testing workflows.
