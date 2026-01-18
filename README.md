All project codes are in `notebook_general.ipynb` and task description in `task_description_2024.html`.

## Project goal
The goal of this project is to enhance the targeting efficiency of the marketing campaign aimed at persuading customers to subscribe to the term deposit product. We can improve the campaign performance by leveraging Uplift modeling with appropriete machine learning classifiers. We are presented with a dataset consisting of predictors, outcome variable and treatment variable (single - only one way of contact). To properly measure the expected uplift in each model we have to standardize the metrics used for each model as well as introduce a proper validation framework 

## Results
1. Uplift at 30% - The expected subscription rate for the deposit product within the top 30% of the population, when considering each treatment group separately, is higher by 0.118 compared to the control group. The treatment group performs 0.118 better compared to the control group within the top 30%
2. Uplift at 30% overall - The expected subscription rate for the deposit product within the top 30% of the entire population, considering both treatment and control groups toghether, is higher by 0.423 compared to the control group. This value indicates a substantial difference in conversion rates between the treatment and control groups. It suggests that the treatment is highly effective in this segment, and it identifies the most responsive customers well, leading to a higher conversion rate in the treatment group
3. AUUC score - The value of 0.29 indicates that the cumulative uplift across the entire population is moderate. It suggests that the treatment is effective in improving the conversion rate, but its overall impact is not very high.
4. QINI score - qini coefficient of 0.423 indicates a strong cumulative uplift, particularly in the top segments of the population. This suggests that the treatment is effective in persuading the most responsive customers to subscribe the term deposit product. The uplidt model is effectively identifying and targeting the most responsvie customers, leading to a significant improvement in subscription rates.
cross validated Uplift and QINI curves (SVM radial kernel) can be seen on the graph below

