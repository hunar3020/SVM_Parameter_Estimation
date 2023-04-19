# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 10129

Number of Attributes: 16

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.88 | Poly | 5.85 | 4.34 |
| 2 | 0.95 | Linear | 5.16 | 0.33 |
| 3 | 0.96 | Linear | 3.16 | 6.35 |
| 4 | 0.96 | Poly | 1.47 | 3.28 |
| 5 | 0.91 | Linear | 3.56 | 7.38 |
| 6 | 0.83 | RBF | 5.62 | 3.18 |
| 7 | 0.95 | Poly | 0.27 | 7.74 |
| 8 | 0.95 | Poly | 4.86 | 5.58 |
| 9 | 0.97 | Poly | 1.29 | 6.85 |
| 10 | 0.92 | Poly | 0.37 | 5.52 |

## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.

## Written By
Name : Hunar
  
Roll No. : 102003161

Sub-Group: 3CO6
