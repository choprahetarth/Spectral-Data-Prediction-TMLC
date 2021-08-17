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

## Tech Stack Used
<img src="https://cdn.worldvectorlogo.com/logos/python-5.svg" alt="Python Logo" width="100" height="100"/> <img src="https://camo.githubusercontent.com/c04e16c05de80dadbdc990884672fc941fdcbbfbb02b31dd48c248d010861426/68747470733a2f2f7777772e74656e736f72666c6f772e6f72672f696d616765732f74665f6c6f676f5f736f6369616c2e706e67" alt="TF Logo" width="100" height="100"/> <img src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas_white.svg" alt="Pandas Logo" width="100" height="100"/>  <img src="https://raw.githubusercontent.com/scikit-learn/scikit-learn/main/doc/logos/scikit-learn-logo.svg" alt="Scikit-Learn Logo" width="100" height="100"/>  <img src="http://cms.ipressroom.com.s3.amazonaws.com/219/files/20149/NVIDIA_CUDA_V_2C_r.jpg" alt="CUDA Logo" width="100" height="100"/>  <img src="https://raw.githubusercontent.com/valohai/ml-logos/master/matplotlib.svg" alt="MatPlotLib" width="100" height="100"/>  <img src="https://raw.githubusercontent.com/valohai/ml-logos/master/numpy-simple.svg" alt="Numpy" width="100" height="100"/> 
