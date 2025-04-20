
# SVM Parameter Optimization
**Chahat Verma**  
**102203637**  
**3C35**

## Overview
This program performs **Support Vector Machine (SVM) Parameter Optimization** using the **Dry Bean dataset** from the UCI Machine Learning Repository. The aim is to identify the optimal SVM parameters through extensive experimentation.

## Methodology
1. **Data Preprocessing**: The dataset was preprocessed to ensure suitability for SVM training.
2. **Random Sampling**: 10 random samples of the dataset were generated to assess model performance.
3. **Iteration & Optimization**: Each sample underwent **100 iterations** to optimize the SVM parameters.
4. **Data Split**: A **70-30 train-test split** was applied for model validation.
5. **Parameter Tuning**: Key parameters such as kernel, C, and gamma were optimized during the process.

## Results
The table below summarizes the results obtained after running the optimization procedure on each sample:

![Results Table](https://github.com/user-attachments/assets/26fc2292-f8b7-479f-b885-f04eea49f00e)

### Best Performing Sample: Convergence Graph
The convergence graph for the sample with the highest accuracy (Sample 3) is shown below, illustrating the change in accuracy across 100 iterations.

![Convergence Graph](https://github.com/user-attachments/assets/12b6fdf0-9d38-42a0-9280-12fe9b821f8e)

#### Note: 
The results may vary across different runs as the optimization process involves random sampling and parameter selection.
