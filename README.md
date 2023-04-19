# Parameter-Optimization
## Objective
This project aimed to evaluate the efficacy of Support Vector Machines (SVM) in classification problems through parameter optimization. Utilizing the Scikit-learn library in Python, we implemented SVM models on the room occupancy Data Set, randomly dividing it into 10 samples for training and testing. By testing various SVM parameter combinations, we determined the optimal settings for each sample. The results, presented in a tabular format, showcase the accuracy achieved for each sample and the corresponding SVM parameters that yielded the highest accuracy. This table can serve as a valuable reference for future classification tasks requiring SVM parameter optimization.
## About-DataSet
The "Room Occupancy Estimation Data Set" available on the UCI Machine Learning Repository comprises 20,560 instances with 7 features, including temperature, relative humidity, light intensity, CO2 level, humidity ratio, and binary occupancy labels. This dataset is commonly used for binary classification tasks aimed at predicting room occupancy based on sensor measurements, making it relevant for research in areas such as energy management in buildings and smart homes. It serves as a valuable resource for evaluating and comparing the performance of various machine learning algorithms, including Support Vector Machines (SVM), for the estimation of room occupancy.
## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.88 | Poly | 5.82 | 4.35 |
| 2 | 0.95 | Linear | 5.13 | 0.30 |
| 3 | 0.96 | Linear | 3.13 | 6.32 |
| 4 | 0.96 | Poly | 1.49 | 3.26 |
| 5 | 0.91 | Linear | 3.52 | 7.34 |
| 6 | 0.83 | RBF | 5.60 | 3.14 |
| 7 | 0.95 | Poly | 0.29 | 7.71 |
| 8 | 0.95 | Poly | 4.87 | 5.57 |
| 9 | 0.97 | Poly | 1.27 | 6.87 |
| 10 | 0.92 | Poly | 0.34 | 5.50 |

## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.
![image](https://user-images.githubusercontent.com/100682731/233170932-325b3d56-8844-465b-93dd-2f6a902adecc.png)
