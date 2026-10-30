# Marasigan_Tupas_Engineering-Students-Burnout-Dataset 

## 👥 GROUP INTRODUCTION

| Name | Student Number | Section |
|---|---|---|
| Marasigan, Alden | 23-07009 | MEXE-4101 |
| Tupas, Lodian | 23-05226 | MEXE-4101 |
  
### Assigned Theme:
*Engineering*

### Topic:
*Relationship Between Backlogs and Stress Levels of Engineering Students*

---

## 🛠️ PROJECT OVERVIEW

| Dataset Title | Source | License |
|---|---|---|
| Engineering Academic Pressure Dataset | *https://www.kaggle.com/datasets/prince7489/engineering-academic-pressure-dataset* | CC0: Public Domain |

### Objective: 
```markdown
This project focuses on identifying the underlying relationships between different academic efforts and lapses
that engineering students undergo or experience throughout their journey.
```
---

## 📈 FLOWCHART
| Finalized Flowchart | 
|---|
  |<img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/6888e30d-f959-4ebe-ab90-dd8f38cffa2a" />|

- **Decisions in our flowchart:** list each decision diamond and what you chose on each branch.
- **Changes we made:** if the code ended up different from your first flowchart, say what changed and why.

## 🖋️ PREPROCESSING SUMMARY
| Preprocessing method | Description | 
|---|---|
| Imputation and Scaling: numerical_transformer = Pipeline(steps=[('imputer', SimpleImputer(strategy='median')), ('scaler', StandardScaler())| These preprocessing methods basically focuses on preprocessing numerical columns, eliminating missing data as well as organizing magnitudes.| 
| Imputation and Oneshot encoding: categorical_transformer = Pipeline(steps=[('imputer', SimpleImputer(strategy='constant', fill_value='missing')),('onehot', OneHotEncoder(handle_unknown='ignore'))| These preprocessing methods focuses on preprocessing categorical columns, eliminating missing data as well as converting categorical data into binary values (1 and 0).| 

## 5. Visualizations
<img width="1522" height="563" alt="IMAGE1" src="https://github.com/user-attachments/assets/e31b6144-0fbf-41de-919b-351cd5cd45f0" />
<p align="center"> The missingness plot shows no red markers that symbolize missing values. It means the data is complete </p>


<img width="1412" height="477" alt="IMAGE2" src="https://github.com/user-attachments/assets/0ba2d866-27bc-40dc-8c72-f5d2d8e08b30" />
<p align="center"> The backlog histogram and stress histogram show that almost all the values are within a 20 or so range of each other. This means that the values are more or less evenly spread. 

<img width="1082" height="752" alt="IMAGE3" src="https://github.com/user-attachments/assets/b7b29c4d-bff0-4223-92e2-5e8ed72c0d4d" />
<p align="center"> The KDE Plot above shows that the students that have 0 backlogs tend to be populous at the 2 and 6 stress levels. Those with 1 backlog

## 6. Key Insights
- 3 to 5 main findings from your data.

## 7. How to Run
- Open the notebook in Google Colab.
- Install dependencies from `requirements.txt`.
