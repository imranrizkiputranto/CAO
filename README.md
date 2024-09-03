# New York Collision Risk Insurance Pricing

## Executive Summary
Leveraging Python, Pandas, and machine learning techniques, I developed a predictive model to assess car collision risks for a New York-based car rental company, utilising weather data as a key factor. 
By analysing historical traffic collision data and correlating it with weather patterns, I built a model that accurately predicts daily collision risks. 

The project involved data preprocessing, exploratory data analysis (EDA), and feature engineering to ensure the robustness of the predictions. 
The model's output was used to propose a dynamic pricing strategy for the company’s insurance policies, aligning policy costs with the predicted risk level. 
This approach aims to enhance profitability while providing fair pricing to customers. 

I recommend implementing this model into the company's pricing algorithm to optimize insurance rates based on real-time weather data and collision risk assessments.

## Business Problem
For a New York-based car rental company, offering competitively priced daily insurance policies is crucial for both customer satisfaction and profitability. 
However, the current flat-rate pricing model does not account for fluctuating collision risks, particularly those influenced by varying weather conditions. 
Stakeholders have observed that this approach may lead to either overpricing, discouraging potential customers, or underpricing, resulting in financial losses due to high claim rates on days with adverse weather.

![NUMCOLLISIONS](https://github.com/user-attachments/assets/ff22d746-c327-4c43-adaf-58ddecff928c)


Because of this, only 30% of customers have been willing to pay the insurance policy when renting out a car. 
However, a recent survey conducted by the company found out that 80% of customers would be willing to pay for the insurance policy if prices were more competitive.

The challenge is to develop a data-driven model that accurately predicts the daily risk of car collisions based on weather data, allowing the company to adjust its insurance pricing dynamically. 
By aligning the insurance premiums with actual risk, the company can improve customer satisfaction, remain competitive, and optimize revenue. 
The goal is to understand how weather patterns correlate with collision risks and to integrate these insights into the pricing strategy for insurance policies.

## Methodology
1. Data Collection and Preprocessing: Imported and cleaned traffic collision data and corresponding weather data for New York City using Python's Pandas library.

2. Exploratory Data Analysis (EDA): Identified patterns and correlations between weather conditions and traffic collisions. 

3. Feature Engineering: Created new features based on the weather data, such as categorizing days into different weather conditions (e.g., rainy, snowy, clear), and identified key predictors of collision risks.

4. Model Development: Developed and trained predictive models using machine learning techniques to estimate the daily risk of collisions based on the engineered features.

5. Insurance Pricing Strategy: Used the model’s predictions to propose a dynamic pricing strategy for the car rental company’s insurance policies. 
The model’s output informed the adjustment of insurance premiums based on the predicted collision risk for each day.

## Skills
Python: Pandas, Matplotlib, Seaborn, Writing functtions.

Machine Learning: Scikit-Learn, Tensorflow.

Statistics: Employed statistical methods to analyze the distribution of collision data, identify patterns, and validate assumptions. Used quantiles and interquartile ranges (IQR) to detect and handle outliers in the data.

Business Intelligence: Proposed a dynamic insurance pricing strategy based on predictive model outputs, demonstrating how data-driven insights can inform and optimize business decisions.

## Results and Business Recommendations

The analysis of collision data combined with weather patterns led to the development of multiple predictive models that more accurately estimate daily collision risks. Key results and insights from this project include:

- Collision Prediction Accuracy: The developed models significantly outperformed the initial assumptions of 1,200 daily collisions when compared to the actual number of collisions that occur, thereby providing a more realistic basis for pricing insurance policies.

- Dynamic Pricing and Revenue Impact: By adjusting the insurance policy prices based on the model's predictions, the car rental company could reduce the average daily policy price from the flat rate of $30 to a more competitive and accurate price of approximately $16.

- Customer Uptake: The reduced and more accurate pricing strategy is projected to increase customer willingness to purchase insurance policies from 30% to 80%, further boosting revenue and customer satisfaction.
  This uptake, when applied across an average of 20,000 daily customers, would potentially increase the average daily revenue from $180,000 to $256,000, with daily profits rising from $100,000 to $176,000.
  This marks an 76% increase in profitability due to more accurate pricing that aligns with actual risk.
  

![SecondMultiLinear](https://github.com/user-attachments/assets/6a7d1492-2b68-48da-813d-f8c913952bd6)

  
  
#### Business Recommendations:

- Implement Model-Driven Pricing: Transition from a flat-rate insurance policy to a dynamic pricing model that leverages the predictions from the Second Multi-Input Model. This will align policy prices with actual collision risks, optimizing both profitability and customer satisfaction.

- Enhance Customer Communication: Inform customers about the rationale behind dynamic pricing, emphasizing fairness and alignment with actual risk. This transparency will help in gaining customer trust and improving uptake rates.

- Continuous Model Optimization: Invest in ongoing model refinement and training, particularly exploring more advanced deep learning techniques to capture any potential non-linear relationships that could further enhance prediction accuracy.

- Address Data Quality Issues: Improve the data collection process to minimize missing values and ensure that the input data for the models remains accurate and complete. This will enhance the reliability of the predictions and the associated pricing strategy.

By adopting these recommendations, the car rental company can enhance its profitability while offering fair, data-driven insurance prices, leading to increased customer satisfaction and market competitiveness.

## Next Steps

1. Address assumptions: Optimise relationship of price with collisions to increase profits while maximising the number of customers taking the policy.
2. Address missing data: Fix and replace any missing values with actual values if possible.
3. Optimise model training procedures: Model training procedures must be optimised further to ensure the most accurate and reliable results (especially for the DNN model).
4. Refine Cost-Benefit Analysis: Improve the profit calculation method to ensure more reliable numbers.
