# AI_ML_Internship-Task-16
# Hyperparameter Tuning using GridSearchCV

## Objective
To improve model performance using GridSearchCV.

## Dataset
Breast Cancer Dataset from sklearn.

## Steps Performed
- Data preprocessing
- Train-test split
- Feature scaling
- Model training (SVM)
- Hyperparameter tuning using GridSearchCV
- Performance evaluation

## Results
| Model        | Accuracy |
|--------------|---------|
| Default SVM  | 98%     |
| Tuned SVM    | 98%     |

## Best Parameters
C = 10  
Kernel = rbf  
Gamma = scale  

## Conclusion
The tuned model achieved the same accuracy as the default model because the default hyperparameters of SVM were already optimal for this dataset. This indicates that GridSearchCV successfully validated the best parameter combination rather than improving performance significantly.
