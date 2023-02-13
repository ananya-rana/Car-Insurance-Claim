# Car-Insurance-Claim
applying SMOTE, Variance Inflation Factor etc.

* Performed EDA, found the dataset to be extremely imbalanced. Since such datasets may occur in the real world I wanted to work on such a problem. </br>
* I applied Variance Inflation Factor and found the independent variables to be highly correlated, therefore I took steps to eliminate multicollinearity as well. </br>
* Used imblearn library's SMOTE technique to artificially create data to balance the dataset, and then applied ML algorithms. I also applied SMOTE's relatives to the problem. However even after Hyperparameter tuning I did not achieve satisfactory results. I have provided the reasons why this could have happened.
