# BCG-Virtual-Internship
<b>Problem Statement:</b> 

• A client in the electricity sector is losing customers. 



<b>Objective:</b>

• Understand the reasons why customers are churning and what could be done to prevent customer churn



<b>Data Provided:</b>

• Customer data should include characteristics of each client such as industry, size, historical electricity consumption, and date joined as a customer.

• Churn data should indicate if the customer has churned.

• Historical price data should show the prices the client charges each customer for electricity and gas at granular time intervals.



<b>Approach:</b> 

• Cleaning the dataset and performing feature engineering, the goal was to test the hypothesis of whether churn is driven by customers' price sensitivity, and to derive the effect of prices on churn rate. .  

• The data will then be ready to build a binary classification model (such as Logistic Regression, Random Forest, or Gradient Boosted Machines), picking the most appropriate model based on the tradeoff between complexity, expandability, and accuracy



<b>Results:</b>

 • The top drivers of client churn are the age of the client, their tenure, and the difference between off-peak and peak energy prices.

 • If a client has been with the company for a short time, they are more likely to churn. New clients are more likely to churn than older, more loyal clients.

 • The larger the difference between off-peak and peak energy prices, the more likely it is that clients will churn. When off-peak prices are significantly higher than peak prices, it increases the likelihood of churn.

 • Price sensitivity is also a significant predictor of churn. Higher prices tend to drive clients to churn.

 • In general, price sensitivity is a key driver of client churn, and both off-peak and peak energy prices contribute to this.



<b>Recommendations:</b> 

 • A discount strategy of 20% is effective but only if targeted appropriately

 • Offer discount only to high-value customers with high churn probability
