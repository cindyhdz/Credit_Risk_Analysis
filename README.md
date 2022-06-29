# Credit_Risk_Analysis

# Overview
This project analyzes loan statistics to help predict low/high credit risks.  This was done by creating a model that applies the resampling method to examine and predict credit risks. Data was oversampled using the randomoversample technique and smote algorithms. Additionally, it compares six machine learning models such as balancedrandomforestclassifier and easyensembleclassifier.

# Results
Naive Random Oversampling Results: Balanced accuracy test it 50%, the precision for the high-risk has a low positivity at 0% and the recall is 0%.
![image](https://user-images.githubusercontent.com/99698846/176514923-dec4334b-f6ff-4a1b-825d-245453f8726b.png)

SMOTE oversampling results: Balanced accuracy test it 50%, the precision for the high-risk has a low positivity at 0% and the recall is 0%.
 ![image](https://user-images.githubusercontent.com/99698846/176514945-1282e104-06f7-4356-a813-0c04cd8ef5fb.png)

Undersampling results: Balanced accuracy test it 50%, the precision for the high-risk has a low positivity at 0% and the recall is 0%.
 ![image](https://user-images.githubusercontent.com/99698846/176514969-1e95f827-0936-44e7-b261-8b7d5f2a3827.png)

Combination(over and undersampling) results: Balanced accuracy test it 50%, the precision for the high-risk has a low positivity at 0% and the recall is 0%.
 ![image](https://user-images.githubusercontent.com/99698846/176514983-c8ad1da8-4579-4997-b203-f5e31b552438.png)

# Summary 
Using EasyEnsembleClassifier is the most effective, as it provides a highest score for all models.  
