# Biggest-Predictor-Of-Academic-Success-In-Students
A data analysis project, including 10 different visualisations each with descriptive markdown cells..
## Dataset
[Student Dataset - Kaggle(https://www.kaggle.com/code/robiulhasanjisan/predicting-student-success-eda-ml)

## Analysis
- After checking the data for errors like missing values, redundancies, or type errors I analysed the dataset using Python Libraries (Matplotlib + Seaborn)
- Before starting visualising I stored my string data types as integers for accurate diaplay in visualisation : I did this using a dictionary
  
***Before***


| Parental_Involvement | Access_to_Resources | Motivation_Level | Internet_Access |
|---|---|---|---|
| Low | Low | Yes | Yes |
| High | Medium | No | No |
| Medium | High | Yes | No |

***After***

| Parental_Involvement | Access_to_Resources | Motivation_Level | Internet_Access |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 1 | 2 | 1 | 1 |
| 2 | 1 | 0 | 1 |


- This helped me make 10 visualisations prodcued which made the relationship between factors affecting students' performance clear

### Major Key Findings
1. Parental Involvement is not a major factor in determining students' academic performance : results formed from chart # 10, a pivot heatmap

2. The most important factor remains students motivation this factor alone got the most positve academic result regardless of other factors like Parental Involvement, Tutoring Sessions being absent.

## Files

| File | Description |
|---|---|
| final-modification.ipynb | Visualisation + story telling markdowns + Analysis |
| student data.zip | orignal data from kaggle |
| requirement.txt | requirements to use data and to analyse it |






