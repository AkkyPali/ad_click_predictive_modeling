# Ad Click Predictive Modeling
**Objective:**

- Predict which users might click a particular advertisement. 
- Explain the findings effectively to technical and non-technical audiences using comments and visualizations. 
- Build an optimized model that effectively solves the business problem. Evaluate the model on the basis of accuracy.

<img width="800" alt="Screen Shot 2021-10-27 at 1 01 54 PM" src="https://user-images.githubusercontent.com/21275064/139138450-79233653-5b44-4ead-a91b-909abaf32378.png">

**Approach:**
-	Visualise and deepdive in the data
-	Feature Engineering: Extract more meaningful features (eg: Hour and month from Timestamp and length of Topic from Ad Topic Line)
-	Check for missing data, Impute missing data in Area Income with median values, since it is (roughly) normally distributed
-	Now that we're all prepared to start modeling, apply logistic regression because it is a binary classification problem (Clicked 0, Not Clicked 1)
-	Optimise th model by applying regularization techniques and CV to get the best C(penalty coeficient) value.
-	Interpret coefs

**Results**
Achieved accuracy of 96.6% using Logistic Regression Model with Tuned Hyperparameters 
