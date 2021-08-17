# Spectral-Data-Prediction-TMLC
Solution to the problem statement provided by The Machine Learning Company

## Problem Statement
Build a deep learning model on given tabular data(File is attached along with this email)

Details about the dataset :          
Feature names – 1110 to 1800
Target Variable – ContentUniformity

Research Papers to follow  -    
- https://www.sciencedirect.com/science/article/pii/S1350449521002358
- https://www.nature.com/articles/s41598-020-80486-9

 
Submission Criteria – 
- Email us your jupyter notebook solution
- Evaluation metric is mean absolute percentage error
- Use visualizations and explain your model performance
- Email before 11:59 PM  15-08-2021




## Solution Methodology
On the given dataset, following operations were performed to get an ideal MAPE of ~1.69.

- The dataset was loaded and EDA was performed.
- Using Pearson Correlation highly correlated features were eliminated.
- A Baseline Model was looked upon from the Research Work that I have previously worked on this Domain - https://ieeexplore.ieee.org/document/9415633
- The dataset was normalized and trained on a baseline model scoring a MAPE of 5.9318.
- Using Keras Tuner, a hyper-parameter optimized model was trained, and using that, the final predictions provided a MAPE of 1.685780.
