# Student-Performance-model : 95% Accurate
### Must Insatll The Libarary befor use 😊
```
pip install scikit-learn
pip install matplotlib
```
### Import's
```
import pandas as pd
import matplotlib.pyplot as plt  
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
```
- Also use [random_state](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) in train_test_split for not Shuffle
- Model on me

  ```
  # X = GENDER_M,AGE,SMOKING,YELLOW_FINGERS,ANXIETY,PEER_PRESSURE,CHRONIC DISEASE,FATIGUE,ALLERGY,WHEEZING,ALCOHOL CONSUMING,COUGHING,SHORTNESS OF BREATH,SWALLOWING DIFFICULTY,CHEST PAIN
  model.predict([[1,21,1,1,1,1,1,1,1,1,1,1,1,1,1]])
  ```
  ### Output
  ```
  array([0])
  ```
  ```
  Yes=Male=1
  No=Female=0
  ```
 
