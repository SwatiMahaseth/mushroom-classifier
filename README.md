# mushroom-classifier
## Problem Statement: 
The Audubon Society Field Guide to North American Mushrooms contains descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the  Agaricus and Lepiota Family Mushroom (1981). Each species is labelled as either  definitely edible, definitely poisonous, or maybe edible but not recommended. This last  category was merged with the toxic category. The Guide asserts unequivocally that  there is no simple rule for judging a mushroom's edibility, such as "leaflets three, leave it  be" for Poisonous Oak and Ivy. 
The main goal is to predict which mushroom is poisonous & which is edible. 

### Approach:
The classical machine learning tasks like Data Exploration, Data Cleaning,  Feature Engineering, Model Building and Model Testing. Try out different machine  learning algorithms that’s best fit for the above case.

### Resources Used
- Packages: pandas, numpy, sklearn, matplotlib, seaborn, nltk.
- Dataset by UCI Machine Learing on Kaggle: https://www.kaggle.com/uciml/mushroom-classification

### Feature Engineering
- Removing irrelevant feature from dataset
- converting categorical variables into numeric form using label encoder

### Feature Selection¶
- using mutual information to select top 10 features for model building

#### Model Building and Evaluation
- Logistic Regression: 0.95
- Decision Tree: 1.0 
- Random Forest: 1.0 
Note: Evaluation scores are obtained using accuracy score.

