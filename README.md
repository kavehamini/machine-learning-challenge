# machine-learning-challenge

Tools and Technologies used in this project: Python for programming, SVM and Random forest as Machine Learning Models 
 
# Summary

The Random Forest model performs better than the SVM model.

## SVM

|              |   With CV      | Without CV    |
| :---         |     :---:      |          ---: |
| Training Score |  0.88777       |0.85025 | 
| Testing Score  | 0.88106    |0.83897      |


|              | precision | recall | f1-score | support |
| :---         |     :---:      |          ---: |     :---:      |          ---: |
| CANDIDATE   | 0.85      | 0.65    | 0.73     | 523    |
| CONFIRMED   | 0.75       | 0.87       | 0.81       | 594      |
| FALSE POS   | 0.98     | 1.00    | 0.99     | 1069    |
| accuracy    |      |     | 0.88     | 2186|
| macro avg   | 0.86           | 0.84    | 0.84     | 2186    |
| weighted avg| 0.88       | 0.88      | 0.88       | 2186      |
 

## Random Forest

|              |   With CV      | Without CV    |
| :---         |     :---:      |          ---: |
| Training Score |  1.0    | 0.99435   | 
| Testing Score  |   0.89478  | 0.83897    | 


|              | precision | recall | f1-score | support |
| :---         |     :---:      |          ---: |     :---:      |          ---: |
| CANDIDATE   | 0.85      | 0.65    | 0.73     | 523    |
| CONFIRMED   | 0.75       | 0.87       | 0.81       | 594      |
| FALSE POS   | 0.98     | 1.00    | 0.99     | 1069    |
| accuracy    |      |     | 0.88     | 2186|
| macro avg   | 0.86           | 0.84    | 0.84     | 2186    |
| weighted avg| 0.88       | 0.88      | 0.88       | 2186      |



