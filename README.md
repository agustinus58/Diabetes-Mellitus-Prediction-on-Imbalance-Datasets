<br>
<br>

# APENDIX

***

## 1. Dataset BRFSS Diabetes 2015

***
### Dataset Descriptions
*Table 1. BRFSS2015 Dataset Atribut Descriptions*
| No. | Variable Name         | Role    | Type    | Demographic | Description                                                                                                                                       | Missing Values |
|-----|-----------------------|---------|---------|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| 0   | Diabetes_binary        | Target  | Binary  |             | 0 = no diabetes, 1 = prediabetes or diabetes                                                                                                      | no             |
| 1   | HighBP                 | Feature | Binary  |             | 0 = no high BP, 1 = high BP                                                                                                                        | no             |
| 2   | HighChol               | Feature | Binary  |             | 0 = no high cholesterol, 1 = high cholesterol                                                                                                      | no             |
| 3   | CholCheck              | Feature | Binary  |             | 0 = no cholesterol check in 5 years, 1 = yes cholesterol check in 5 years                                                                          | no             |
| 4   | BMI                    | Feature | Integer |             | Body Mass Index                                                                                                                                   | no             |
| 5   | Smoker                 | Feature | Binary  |             | Have you smoked at least 100 cigarettes in your entire life? (5 packs = 100 cigarettes) 0 = no, 1 = yes                                            | no             |
| 6   | Stroke                 | Feature | Binary  |             | (Ever told) you had a stroke. 0 = no, 1 = yes                                                                                                      | no             |
| 7   | HeartDiseaseorAttack   | Feature | Binary  |             | Coronary heart disease (CHD) or myocardial infarction (MI). 0 = no, 1 = yes                                                                        | no             |
| 8   | PhysActivity           | Feature | Binary  |             | Physical activity in past 30 days - not including job. 0 = no, 1 = yes                                                                             | no             |
| 9   | Fruits                 | Feature | Binary  |             | Consume fruit 1 or more times per day. 0 = no, 1 = yes                                                                                            | no             |
| 10  | Veggies                | Feature | Binary  |             | Consume vegetables 1 or more times per day. 0 = no, 1 = yes                                                                                       | no             |
| 11  | HvyAlcoholConsump      | Feature | Binary  |             | Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week). 0 = no, 1 = yes                 | no             |
| 12  | AnyHealthcare          | Feature | Binary  |             | Have any kind of healthcare coverage, including health insurance, prepaid plans such as HMO, etc. 0 = no, 1 = yes                                  | no             |
| 13  | NoDocbcCost            | Feature | Binary  |             | Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? 0 = no, 1 = yes                              | no             |
| 14  | GenHlth                | Feature | Integer |             | Would you say that in general your health is: 1 = excellent, 2 = very good, 3 = good, 4 = fair, 5 = poor                                           | no             |
| 15  | MentHlth               | Feature | Integer |             | Mental health in the past 30 days (stress, depression, emotions): number of days not good. Scale: 1-30 days                                        | no             |
| 16  | PhysHlth               | Feature | Integer |             | Physical health in the past 30 days (physical illness and injury): number of days not good. Scale: 1-30 days                                       | no             |
| 17  | DiffWalk               | Feature | Binary  |             | Serious difficulty walking or climbing stairs. 0 = no, 1 = yes                                                                                     | no             |
| 18  | Sex                    | Feature | Binary  | Sex         | 0 = female, 1 = male                                                                                                                               | no             |
| 19  | Age                    | Feature | Integer | Age         | 13-level age category (_AGEG5YR code): 1 = 18-24, 9 = 60-64, 13 = 80 or older                                                                      | no             |
| 20  | Education              | Feature | Integer | Education   | Education level (EDUCA code): 1 = Never attended school or only kindergarten, 2 = Grades 1-8, 3 = Grades 9-11, 4 = High school graduate, 5-6 = College | no             |
| 21  | Income                 | Feature | Integer | Income      | Income scale (INCOME2 code): 1 = less than $10,000, 5 = less than $35,000, 8 = $75,000 or more                                                     | no             |

*Table 2. BRFSS2015 Dataset Descriptive Feature*
| Feature               | Count   | Mean      | Std Dev   | Min  | 25%   | 50%   | 75%   | Max  |
|-----------------------|---------|-----------|-----------|------|-------|-------|-------|------|
| Diabetes_binary        | 14268.0 | 0.162812  | 0.369207  | 0.0  | 0.0   | 0.0   | 0.0   | 1.0  |
| HighBP                | 14268.0 | 0.471334  | 0.499195  | 0.0  | 0.0   | 0.0   | 1.0   | 1.0  |
| HighChol              | 14268.0 | 0.451990  | 0.497707  | 0.0  | 0.0   | 0.0   | 1.0   | 1.0  |
| CholCheck             | 14268.0 | 0.962293  | 0.190493  | 0.0  | 1.0   | 1.0   | 1.0   | 1.0  |
| BMI                   | 14268.0 | 28.627979 | 6.419328  | 14.0 | 24.0  | 27.0  | 32.0  | 85.0 |
| Smoker                | 14268.0 | 0.453532  | 0.497854  | 0.0  | 0.0   | 0.0   | 1.0   | 1.0  |
| Stroke                | 14268.0 | 0.050042  | 0.218039  | 0.0  | 0.0   | 0.0   | 0.0   | 1.0  |
| HeartDiseaseorAttack  | 14268.0 | 0.107443  | 0.309687  | 0.0  | 0.0   | 0.0   | 0.0   | 1.0  |
| PhysActivity          | 14268.0 | 0.730025  | 0.443962  | 0.0  | 0.0   | 1.0   | 1.0   | 1.0  |
| Fruits                | 14267.0 | 0.598023  | 0.490314  | 0.0  | 0.0   | 1.0   | 1.0   | 1.0  |
| Veggies               | 14267.0 | 0.799537  | 0.400361  | 0.0  | 1.0   | 1.0   | 1.0   | 1.0  |
| HvyAlcoholConsump     | 14267.0 | 0.052569  | 0.223179  | 0.0  | 0.0   | 0.0   | 0.0   | 1.0  |
| AnyHealthcare         | 14267.0 | 0.943646  | 0.230612  | 0.0  | 1.0   | 1.0   | 1.0   | 1.0  |
| NoDocbcCost           | 14267.0 | 0.102614  | 0.303465  | 0.0  | 0.0   | 0.0   | 0.0   | 1.0  |
| GenHlth               | 14267.0 | 2.627252  | 1.114367  | 1.0  | 2.0   | 3.0   | 3.0   | 5.0  |
| MentHlth              | 14267.0 | 3.526249  | 7.853331  | 0.0  | 0.0   | 0.0   | 2.0   | 30.0 |
| PhysHlth              | 14267.0 | 4.866195  | 9.255579  | 0.0  | 0.0   | 0.0   | 4.0   | 30.0 |
| DiffWalk              | 14267.0 | 0.205649  | 0.404190  | 0.0  | 0.0   | 0.0   | 0.0   | 1.0  |
| Sex                   | 14267.0 | 0.416065  | 0.492922  | 0.0  | 0.0   | 0.0   | 1.0   | 1.0  |
| Age                   | 14267.0 | 8.205019  | 3.006551  | 1.0  | 6.0   | 9.0   | 10.0  | 13.0 |
| Education             | 14267.0 | 4.991659  | 0.997192  | 1.0  | 4.0   | 5.0   | 6.0   | 6.0  |
| Income                | 14267.0 | 5.849232  | 2.138429  | 1.0  | 4.0   | 6.0   | 8.0   | 8.0  |

#### Best Parameter for Hyperparameter Tuning
*Table 3. Best Parameters from Hyperparameter Tuning for the BRFSS2015 Dataset*
| DATASET          | MODEL               | PARAMETER NAME      | BEST VALUE                           |
|------------------|---------------------|---------------------|--------------------------------------|
|                  |                     |                     | Imbalance Data | SMOTE | SMOTE-ENN | SMOTE-Tomeks |
| BRFSS2015        | KNN                  | n_neighbors         | 9           | 3           | 3           | 3           |
|                  |                      | Weights             | Uniform     | Distance    | Distance    | Distance    |
|                  |                      | Algorithm           | Ball_tree   | Ball_tree   | kd_tree     | Auto        |
|                  |                      | leaf_size           | 20          | 10          | 20          | 10          |
|                  |                      | p                   | 2           | 1           | 1           | 1           |
|                  | Random Forest        | n_estimators        | 50          | 100         | 200         | 100         |
|                  |                      | max_depth           | 10          | None        | 30          | None        |
|                  |                      | min_samples_split    | 2           | 5           | 2           | 5           |
|                  |                      | min_samples_leaf     | 1           | 1           | 1           | 2           |
|                  |                      | max_features        | sqrt        | sqrt        | sqrt        | sqrt        |
|                  |                      | Bootstrap           | False       | True        | False       | False       |
|                  | SVM                  | C                   | 100         | 100         | 100         | 10          |
|                  |                      | Kernel              | rbf         | rbf         | rbf         | rbf         |
|                  |                      | Gamma               | Scale       | Auto        | Auto        | Auto        |
|                  |                      | class_weight        | None        | None        | None        | None        |
|                  | Gradient Boosting    | n_estimators        | 100         | 200         | 200         | 100         |
|                  |                      | learning_rate       | 0.1         | 0.1         | 0.1         | 0.1         |
|                  |                      | max_depth           | 3           | 5           | 6           | 6           |
|                  |                      | min_samples_split    | 10          | 2           | 5           | 2           |
|                  |                      | min_samples_leaf     | 2           | 4           | 1           | 1           |
|                  |                      | Subsample           | 1           | 1           | 1           | 0.8         |
|                  |                      | max_features        | sqrt        | sqrt        | sqrt        | sqrt        |
|                  | XG Boosting          | n_estimators        | 100         | 300         | 300         | 300         |
|                  |                      | learning_rate       | 0.05        | 0.1         | 0.1         | 0.05        |
|                  |                      | max_depth           | 4           | 3           | 5           | 5           |
|                  |                      | Subsample           | 0.8         | 0.8         | 0.8         | 0.9         |
|                  |                      | colsample_bytree    | 1           | 0.9         | 0.9         | 1.0         |



## 2. Dataset Pima

***
### Dataset Descriptions
*Table 1. Pima Indians Dataset Atribut Descriptions*
| No. | Attribute                  | Description                                       | Measurement | Value Range  |
|-----|----------------------------|---------------------------------------------------|-------------|--------------|
| 1   | Pregnancies                 | How many times a person became pregnant           | Years       | 0 to 17      |
| 2   | Glucose                     | Plasma glucose level after 2 h                    | mg/dL       | 0 to 199     |
| 3   | Blood Pressure              | Pressure of an individual's blood pressure        | mmHg        | 0 to 122     |
| 4   | Skin Thickness              | The triceps fold thickness                        | mm          | 0 to 99      |
| 5   | Insulin                     | Patient's blood insulin levels                    | μU/mL       | 0 to 846     |
| 6   | BMI                         | Body mass index                                   | kg/m²       | 0 to 67      |
| 7   | Diabetes Pedigree Function  | Indicates the hereditary risk of diabetes         | -           | 0 to 2.45    |
| 8   | Age                         | Age of the individual                             | Years       | 21 to 81     |
| 9   | Outcome                     | Class attribute (1 = diabetic, 0 = non-diabetic)  | -           | 0 or 1       |


*Table 2. Pima Indians Dataset Descriptive Feature*
| Feature                  | Count | Mean      | Std Dev   | Min   | 25%     | 50%     | 75%     | Max    |
|--------------------------|-------|-----------|-----------|-------|---------|---------|---------|--------|
| Pregnancies               | 768.0 | 3.845052  | 3.369578  | 0.000 | 1.00000 | 3.0000  | 6.00000 | 17.00  |
| Glucose                   | 768.0 | 120.894531| 31.972618 | 0.000 | 99.00000| 117.0000| 140.25000| 199.00 |
| BloodPressure             | 768.0 | 69.105469 | 19.355807 | 0.000 | 62.00000| 72.0000 | 80.00000| 122.00 |
| SkinThickness             | 768.0 | 20.536458 | 15.952218 | 0.000 | 0.00000| 23.0000 | 32.00000| 99.00  |
| Insulin                   | 768.0 | 79.799479 | 115.244002| 0.000 | 0.00000| 30.5000 | 127.25000| 846.00 |
| BMI                       | 768.0 | 31.992578 | 7.884160  | 0.000 | 27.30000| 32.0000 | 36.60000| 67.10  |
| DiabetesPedigreeFunction   | 768.0 | 0.471876  | 0.331329  | 0.078 | 0.24375| 0.3725  | 0.62625 | 2.42   |
| Age                       | 768.0 | 33.240885 | 11.760232 | 21.000| 24.00000| 29.0000 | 41.00000| 81.00  |
| Outcome                   | 768.0 | 0.348958  | 0.476951  | 0.000 | 0.00000|         |         |        |

#### Best Parameter for Hyperparameter Tuning
*Table 3. Best Parameters from Hyperparameter Tuning for the Pima Indian Dataset*
| DATASET          | MODEL               | PARAMETER NAME      | BEST VALUE                           |
|------------------|---------------------|---------------------|--------------------------------------|
|                  |                     |                     | Imbalance Data | SMOTE | SMOTE-ENN | SMOTE-Tomeks |
|PIMA Indian       | KNN                  | n_neighbors         | 3           | 7           | 3           | 3           |
|                  |                      | Weights             | Distance    | Distance    | Distance    | Distance    |
|                  |                      | Algorithm           | Auto        | Auto        | Auto        | Auto        |
|                  |                      | leaf_size           | 10          | 10          | 10          | 10          |
|                  |                      | p                   | 2           | 2           | 1           | 1           |
|                  | Random Forest        | n_estimators        | 100         | 100         | 50          | 20          |
|                  |                      | max_depth           | None        | None        | None        | None        |
|                  |                      | min_samples_split   | 5           | 2           | 5           | 2           |
|                  |                      | min_samples_leaf    | 2           | 1           | 1           | 1           |
|                  |                      | max_features        | sqrt        | log2        | sqrt        | log2        |
|                  |                      | Bootstrap           | False       | False       | True        | False       |
|                  | SVM                  | C                   | 0.01        | 100         | 10          | 100         |
|                  |                      | Kernel              | Linear      | rbf         | Linear      | rbf         |
|                  |                      | Gamma               | Scale       | Scale       | Scale       | Scale       |
|                  |                      | class_weight        | Balanced    | None        | None        | None        |
|                  | Gradient Boosting    | n_estimators        | 50          | 100         | 50          | 50          |
|                  |                      | learning_rate       | 0.2         | 0.2         | 0.2         | 0.2         |
|                  |                      | max_depth           | 6           | 6           | 5           | 5           |
|                  |                      | min_samples_split   | 5           | 10          | 2           | 2           |
|                  |                      | min_samples_leaf    | 1           | 1           | 2           | 1           |
|                  |                      | Subsample           | 0.8         | 1           | 0.6         | 1           |
|                  |                      | max_features        | log2        | sqrt        | sqrt        | log2        |
|                  | XG Boosting          | n_estimators        | 100         | 200         | 200         | 300         |
|                  |                      | learning_rate       | 0.1         | 0.1         | 0.05        | 0.05        |
|                  |                      | max_depth           | 3           | 5           | 4           | 3           |
|                  |                      | Subsample           | 0.8         | 1           | 1           | 1           |
|                  |                      | colsample_bytree    | 0.8         | 1           | 0.8         | 1           |
