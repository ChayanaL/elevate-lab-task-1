# elevate-lab-task-1 
New dataset shape: (638, 12)

--- Final Dataset Info ---
<class 'pandas.core.frame.DataFrame'>
Index: 638 entries, 0 to 890
Data columns (total 12 columns):
 #   Column       Non-Null Count  Dtype  
---  ------       --------------  -----  
 0   PassengerId  638 non-null    int64  
 1   Survived     638 non-null    int64  
 2   Pclass       638 non-null    int64  
 3   Name         638 non-null    object 
 4   Sex          638 non-null    int64  
 5   Age          638 non-null    float64
 6   SibSp        638 non-null    float64
 7   Parch        638 non-null    float64
 8   Ticket       638 non-null    object 
 9   Fare         638 non-null    float64
 10  Embarked_Q   638 non-null    bool   
 11  Embarked_S   638 non-null    bool   
dtypes: bool(2), float64(4), int64(4), object(2)
memory usage: 56.1+ KB
...
Fare           0
Handled missing values using mean/median/imputation.
Converted categorical features into numerical using encoding.
Normalized/standardized the numerical features.
Visualized outliers using boxplots and remove them
Embarked_Q     0
Embarked_S     0
