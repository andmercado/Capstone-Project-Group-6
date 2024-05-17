![Header Image](https://github.com/andmercado/Capstone-Project-Group-6/assets/159932014/7409f5bc-d706-4524-a64a-4eab1d0351f0)

## LoyalLock: Predictive Modeling for Customer Segmentation and Churn Reduction

Significant revenue loss, as a result of customer churn, is an issue in the credit card industry. We offer a solution enabling these companies to leverage data analysis to predict potential customer churn in advance. Our predictive approach motivates companies incentivize customers likely to churn, thereby reducing the probability of customer departure and locking in revenue. 

## Business Understanding and Data Understanding

In the competitive realm of credit card companies, each company offers a wide range of incentives to obtain a customer and keep them loyal to their services. From offering a reward system that allows customers to use their rewards towards travel, card statements, or gift cards to offering a low percentage of interest rates on monthly statements. Customer retention is a crucial factor for sustaining revenue growth and fostering long-term clientele and profitability.

The key stakeholders include the credit card companies who seek to decrease customer churn, the customer service and marketing teams who may need to adjust their operations and strategies based on our insights, and the customers who will benefit from improved services and retention incentives.

This proposal aims to recognize the importance of retaining clientele by implementing and developing a predictive analytics tool to forecast customer churn by enabling proactive measures to mitigate churning rates effectively. Our primary goal is to identify potential churning among credit card company's customers and harness the retention. We would investigate the identifying factors within the data set that we feel contribute to the customer churn. We would then perform evaluations with models to increase customer retention. By carefully analyzing these predictions and creating an analysis, credit card companies can then tailor their retention rates by implementing strategies to incentivize their current customers that are at risk of churning.

To enable our predictive analytic models, we would require specific customer data. Using this data, we will be able to strategically plan and allocate resources to overcome potential challenges. The predictive modeling insights will guide changes to increase customer retention. This process may involve modifying current marketing strategies or enhancing customer service operations. However, with the correct approach and by leveraging the insights obtained from our predictive analytics, we are confident that any arising challenges can be effectively addressed, leading to improved customer retention and business growth.

References

Dey, S. (2022, May 7). [Building Comprehensible Customer Churn Prediction Models](https://medium.com/swlh/building-comprehensible-customer-churn-prediction-models-ca61ecce529d). Medium.


## Modeling and Evaluation
What kind of model(s) did you use?
How well did your final model perform, compared to the baseline?

Our team started with the simplest model, Logistic Regression, to establish a base accuracy score. This binary classification model was necessary given the objective. 

During the feature selection process, our team incorporated Principal Component Analysis (PCA) for dimensionality reduction. This technique simplified our high-dimensional data into fewer 'principal components', enhancing model performance by minimizing overfitting.  

We then explored the K-Nearest Neighbor model, capitalizing on its ability to classify outcomes based on proximity to selected features.  

The Random Forest algorithm was useful in handling many variables, reducing overfitting, and identifying the most important features contributing to customer churn.

After trying the models above we decided move forward with the Decision Tree model as it has excellent interpretability in rule-based classification.  

Our Team then used the K-Means algorithm, an unsupervised learning method, to segment customers into different groups based on their behavior or characteristics, thereby identifying patterns indicative of churn.


## Conclusion
How would you recommend that your model be used?

## Repository Navigation
An explanation of the repository organization
Links to the final notebook and presentation
Reproduction instructions (or a link to them)
