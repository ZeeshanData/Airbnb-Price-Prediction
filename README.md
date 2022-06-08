Our Goal
Constructing a set of predictions for Airbnb rentals in the scoring dataset and
evaluating RMSE (root mean squared error).

EFFORTS IN PREPARAING THE DATA.


80% of your success is all dependent on the wrangling phase. If this phase is achieved
successfully the life becomes easy.


RELEVANT FEATURES.
For any Regression model it is important that the input data is numeric. The exclusion of
characters features was relevant as either you could use them by making them as ‘dummy
variable’ or just garbage them.

IMPUTING THE MISSING VALUES.
Before we dump our data into the model building phase we need to remember about complete
data especially for certain models like Linear Regression. Before we could further the imputation
of missing data was important which was done by replacing all missing value by mean using the
‘ImputeTS’ which helps in imputing the missing values in one go.


FEATURE SELECTION.
It was always important to select appropriate input features for the model building.
The concept of Garbage In Garbage Out. Certain Feature Selection techniques
were used to get the best features.

TECHNIQUES EXPLORED
• Forward Selection (Success)
• Backward Elimination (Success)
• Hybrid Stepwise (Success)
• Decision Tree (For Feature Selection) - Success
• Function (rmse,mean) (Failed & Success)
• VIF selection (Failed)
• Linear Regression (Success)
• Random Forest (Failed)
• XGBOOST (Successful)
• Tuning XGBOOST (Success)

TAKEAWAYS FROM THIS COURSE & PAC
• Usage of feature selection techniques was very helpful and clearly understood
(Forward, Backward, Hybrid Stepwise, Subset, VIF)
• Gained knowledge on algorithms such as Logistic Regression, Decision Tree,
Random Forest, XGBOOST
• Biggest takeaway is the concept of Hyperparameter tuning. Concepts such as CP, BIC
and cross-validation was understood on the surface level.
• One of the learnings from PAC is take your time with ‘DATA WRANGLING’ you
can s get the right RMSE Value if you have 100% cleaned data and right predictors.
• ‘GARBAGE IN GARBAGE OUT’
• Power of certain R packages.



