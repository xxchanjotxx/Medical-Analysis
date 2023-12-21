# Medical-Analysis

Exploring the relationship between cardiac disease, body measurements, blood markers, and lifestyle choices.

## Data: 


---


| Feature                                   | Variable Type        | Variable            | Value Type                                             |
|-------------------------------------------|----------------------|---------------------|--------------------------------------------------------|
| Age                                       | Objective Feature    | age                 | int (days)                                             |
| Height                                    | Objective Feature    | height              | int (cm)                                               |
| Weight                                    | Objective Feature    | weight              | float (kg)                                             |
| Gender                                    | Objective Feature    | gender              | categorical code                                      |
| Systolic blood pressure                   | Examination Feature  | ap_hi               | int                                                    |
| Diastolic blood pressure                  | Examination Feature  | ap_lo               | int                                                    |
| Cholesterol                               | Examination Feature  | cholesterol         | 1: normal, 2: above normal, 3: well above normal       |
| Glucose                                   | Examination Feature  | gluc                | 1: normal, 2: above normal, 3: well above normal       |
| Smoking                                   | Subjective Feature   | smoke               | binary                                                 |
| Alcohol intake                            | Subjective Feature   | alco                | binary                                                 |
| Physical activity                         | Subjective Feature   | active              | binary                                                 |
| Presence or absence of cardiovascular disease | Target Variable   | cardio              | binary                                                 |



---
## Result:

After removing the outliers, normalizing the data, and calculating whether an individual is overweight; The data can be visualized as follows:

<img width="1048" alt="image" src="https://github.com/xxchanjotxx/Medical-Analysis/assets/78687582/9a10f9ec-93ca-4726-baa5-be42129e2f6c">

