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

![image](https://github.com/xxchanjotxx/Medical-Analysis/assets/78687582/1678512d-6e00-4160-bc42-e8fa5ef4908a)

---
## Analysis:

- A person consuming alcohol is likely to smoke and vice versa
- A person with high glucose is likely to have high cholesterol and vice versa
- Diastolic pressure is a significant factor in determining the presence of cardiovascular disease
- Age, Weight, and Cholesterol also play a part in determining the presence of cardiovascular disease
- Higher the Cholesterol, being Overweight, more the chances of cardiovascular disease

