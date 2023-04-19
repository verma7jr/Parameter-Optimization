# Parameter-Optimization
## Objective
This project aimed to evaluate the efficacy of Support Vector Machines (SVM) in classification problems through parameter optimization. Utilizing the Scikit-learn library in Python, we implemented SVM models on the room occupancy Data Set, randomly dividing it into 10 samples for training and testing. By testing various SVM parameter combinations, we determined the optimal settings for each sample. The results, presented in a tabular format, showcase the accuracy achieved for each sample and the corresponding SVM parameters that yielded the highest accuracy. This table can serve as a valuable reference for future classification tasks requiring SVM parameter optimization.
## About-DataSet
The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)
The "Room Occupancy Estimation Data Set" available on the UCI Machine Learning Repository comprises 10129 instances with 16 features.This dataset is commonly used for binary classification tasks aimed at predicting room occupancy based on sensor measurements, making it relevant for research in areas such as energy management in buildings and smart homes. It serves as a valuable resource for evaluating and comparing the performance of various machine learning algorithms, including Support Vector Machines (SVM), for the estimation of room occupancy.
## Final Result Table

![table1](https://user-images.githubusercontent.com/100682731/233174860-1c08287e-10ca-4d13-b62b-f222977c7a42.jpg)



## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 3 and 4 has the best accuracy of 0.97 having kernel = rbf, Nu = 4.01 and Epsilon = 0.11 and kernel = linear, Nu = 0.47 and Epsilon = 1.31.
