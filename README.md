# BCW-Dataset-NN
Artificial Neural Network Estimator (tensorflow) that uses the Breast Cancer Dataset from the UCI Machine Learning Repository

Author: Will Ryan

Uses the Breast Cancer Wisconsin (original) Dataset:
Format of data:
1. Sample code number: id number 
2. Clump Thickness: 1 - 10 
3. Uniformity of Cell Size: 1 - 10 
4. Uniformity of Cell Shape: 1 - 10 
5. Marginal Adhesion: 1 - 10 
6. Single Epithelial Cell Size: 1 - 10 
7. Bare Nuclei: 1 - 10 
8. Bland Chromatin: 1 - 10 
9. Normal Nucleoli: 1 - 10 
10. Mitoses: 1 - 10 

Format of Output:

1. Class: (0 for benign, 1 for malignant)

Uses 40000 iterations at a learning rate of 0.05

Uses sigmoid activation function and the gradient descent optimizer for learning (Backpropigation)

683 data points

Accuracy ~ 98.2%

Notes: output2 is irrelevant
My variable naming and commenting is horrible I will fix that later
After it runs it allows you to enter a datapoint to check its estimated value (still has some bugs)
Stores the summaries of each run in the summary_log folder
