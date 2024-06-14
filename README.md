![Header Image](https://github.com/andmercado/Capstone-Project-Group-6/assets/159932014/7409f5bc-d706-4524-a64a-4eab1d0351f0)

## LoyalLock: Predictive Modeling for Customer Segmentation and Churn Reduction

Significant revenue losses due to customer churn are a critical issue in the credit card industry. This proposal offers a solution that enables companies to use data analysis to predict potential customer churn in advance. The predictive approach encourages companies to incentivize customers who are likely to churn, thereby reducing the probability of their departure and securing revenue. 

## Business Understanding and Data Understanding

### Business Understanding

In the competitive realm of credit card companies, each firm offers a wide range of incentives to attract and retain customers. These incentives include reward systems that allow customers to redeem rewards for travel, card statements, or gift cards, and offering low interest rates on balances. Customer retention is crucial for sustaining revenue growth and fostering long-term profitability.

The key stakeholders include the credit card companies who seek to decrease customer churn, the customer service and marketing teams who may need to adjust their operations and strategies based on our insights, and the customers who will benefit from improved services and retention incentives.

This proposal aims to recognize the importance of retaining clientele by implementing and developing a predictive analytics tool to forecast customer churn by enabling proactive measures to mitigate churning rates effectively. Our primary goal is to identify potential churning among credit card company's customers and harness the retention. We would investigate the identifying factors within the data set that we feel contribute to the customer churn. We would then perform evaluations with models to increase customer retention. By carefully analyzing these predictions and creating an analysis, credit card companies can then tailor their retention rates by implementing strategies to incentivize their current customers that are at risk of churning.

To enable our predictive analytic models, we would require specific customer data. Using this data, we will be able to strategically plan and allocate resources to overcome potential challenges. The predictive modeling insights will guide changes to increase customer retention. This process may involve modifying current marketing strategies or enhancing customer service operations. However, with the correct approach and by leveraging the insights obtained from our predictive analytics, we are confident that any arising challenges can be effectively addressed, leading to improved customer retention and business growth.

### Data Understanding

The dataset from Kaggle is designed to help predict when customers might stop using their credit cards. This dataset includes information on how customers spend, who they are, how they interact with the company, and details about their accounts. This data is great for spotting customers who might leave and helping us figure out how to keep them. We have data on thousands of customers, which gives us a lot of information to work with. We look at average spending, types of customers, and how often they engage with services. The dataset includes a mix of numerical and categorical data, which are handled differently to ensure optimal processing by predictive models. See below:

**Transactional Data**: Shows how customers are spending their money.

**Demographic Data:** Information like age, gender, income, and job status.

**Account Information:** Details like how long they’ve had their account and what type of card they use.

**Spending and Engagement**: These tell us a lot about how happy customers are and if they might leave.

**Account Details:** These help us understand how deep and strong the relationship with the customer is.

**Handling Categorical Data (Strings)**:

One-hot Encoding: For categorical variables stored as strings, one-hot encoding is implemented. This method converts categorical values into a binary vector format. Each category is represented by a vector where only the relevant category is marked with a '1', and all others are '0'. This transformation allows the model to process categorical data as numerical inputs.

**Handling Numerical Data (Integers and Floats)**:

Standardization: Numerical data such as integers and floats are directly usable in models but come with the challenge of varying scales. To address this, all numerical features are standardized. Standardization adjusts the data to have a mean of zero and a standard deviation of one, ensuring that no single feature disproportionately influences the model due to its scale.

**Use of SMOTE for Imbalanced Data:** The Synthetic Minority Over-sampling Technique (SMOTE) is used to address the imbalance in the dataset, particularly when the number of customers who churn is significantly lower compared to those who do not. SMOTE generates synthetic samples from the minority class (churned customers) to equalize the influence of both classes during model training. This approach helps in improving the model's sensitivity to churn by providing a balanced perspective, which is crucial for accurate prediction and classification.

Data Set from Kaggle: 

https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m

Original Owner of Data Set:

https://zenodo.org/records/4322342#.Y8OsBdJBwUE

## References

Dey, S. (2022, May 7). [Building Comprehensible Customer Churn Prediction Models](https://medium.com/swlh/building-comprehensible-customer-churn-prediction-models-ca61ecce529d). Medium.

Zenodo. (2020). [Prediction of Churning Credit Card Customers]. Retrieved from https://zenodo.org/records/4322342#.Y8OsBdJBwUE

## Modeling and Evaluation

The team started with Logistic Regression to establish a baseline accuracy score for this binary classification task.

During the feature selection process, we incorporated Principal Component Analysis (PCA) for dimensionality reduction, which simplified the high-dimensional data into fewer principal components, enhancing model performance by minimizing overfitting.

Then, was explored K-Nearest Neighbor model, utilizing its ability to classify outcomes based on feature proximity.

The Random Forest algorithm was employed for its capability to handle many variables, reduce overfitting, and identify the most critical features contributing to customer churn.

After evaluating the above models, we decided to proceed with the Decision Tree model due to its excellent interpretability in rule-based classification.

## Conclusion

The team recommends using the model to mitigate customer churn by implementing a sophisticated predictive modeling approach that leverages customer data to identify individuals at risk and tailor retention strategies accordingly. By collecting and analyzing data, the model can pinpoint the key factors contributing to churn. Continuous monitoring and refinement of the model ensures it adapts to evolving customer behaviors, ultimately leading to improved retention rates, customer loyalty, and sustained business growth.


## Repository Navigation
Final Notebook Link: https://github.com/andmercado/Capstone-Project-Group-6/blob/main/final_notebook.ipynb

Final Presentation Link: https://github.com/andmercado/Capstone-Project-Group-6/blob/main/CAPSTONE%20PPT.pptx
