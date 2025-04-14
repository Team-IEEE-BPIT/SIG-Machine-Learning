# ML SIG 2025 Final Assignments
---
### Guidelines : 
1. **No more than 10% of total code can be AI generated.**
2. **Write from scratch without using sklearn unless you are explicitly asked to do so.**
3. **Justify your answers as much as you can, there are no word or LOC limit for any of the assignments. But most optimized solutions will get 5 points extra (in terms of loss or LOC, the exact criteria will not be revealed).**
4. **Any format for submission is allowed but markdowns are appreciated, also handwritten solutions(for math questions) as well as a single Python script for all the code is also allowed and appreciated.**
5. **You are free to Google any terms you might have not heard of.**
6. **This set of assignments is competitive and a leaderboard will be maintained to check your progress against your peers.**
7. **The deadline to submit this assignment is 1st May 2025.**

### Guidelines for submission:
- **A Google drive folder [link](https://drive.google.com/drive/folders/1-h-zI9YmGG7ioIeMkrdJEuj-QFYq7xIf?usp=sharing) has been created in which you will have to create a folder of your name and submit the files in the created folder.**
---
# Assignment 1: Introduction to Machine Learning (Very Easy)
**Total Marks: 30**  
---

### **Theoretical Questions**  
1. **What is Overfitting? (3 marks)**  
   - Explain overfitting in simple terms. Provide one method to prevent it.  

2. **Types of Machine Learning (3 marks)**  
   - Compare supervised, unsupervised, and reinforcement learning. Give one example for each.  

3. **Bias-Variance Tradeoff (3 marks)**  
   - Define bias and variance. How does increasing model complexity affect them?  

4. **Linear Algebra Basics (3 marks)**  
   - Multiply the matrices:  
   $$
      A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \quad 
      B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}
   $$
  

5. **Probability Basics (3 marks)**  
   - If the probability of rain on any given day is 0.3, what is the probability it rains exactly 2 days in a week?  

---

### **Practical Questions**  
6. **Data Preprocessing (4 marks)**  
   - Write Python code to normalize a dataset using Min-Max scaling.  

7. **k-NN Implementation (4 marks)**  
   - Implement the k-Nearest Neighbors algorithm **from scratch** for a binary classification task.  

8. **Model Evaluation (4 marks)**  
   - Given actual labels `y_true = [1, 0, 1, 1, 0]` and predicted labels `y_pred = [1, 1, 1, 0, 0]`, compute precision and recall.  

9. **Linear Regression Coding (4 marks)**  
   - Fit a linear regression model using `scikit-learn` on the Boston Housing dataset. Print the RMSE.  

10. **Decision Tree (4 marks)**  
    - Explain how a decision tree splits data. Write code to train a decision tree classifier on the Iris dataset.  

---

# Assignment 2: Supervised Learning and Model Tuning  (Easy)
**Total Marks: 30**  

---

### **Theoretical Questions**  
1. **Loss Functions (3 marks)**  
   - Compare MSE (Mean Squared Error) and MAE (Mean Absolute Error). When would you use MSE?  

2. **Logistic Regression (3 marks)**  
   - Why is logistic regression used for classification? Write its sigmoid function.  

3. **Hyperparameter Tuning (3 marks)**  
   - What is grid search? How does it differ from random search?  

4. **Support Vector Machines (3 marks)**  
   - Explain the role of the kernel trick in SVM. Name two kernels.  

5. **Ensemble Learning (3 marks)**  
   - What is bagging? How does Random Forest use it?  

---

### **Practical Questions**  
6. **Cross-Validation (4 marks)**  
   - Perform 5-fold cross-validation on a logistic regression model using `scikit-learn`. Report average accuracy.  

7. **Confusion Matrix (4 marks)**  
   - Generate a confusion matrix for `y_true = [0, 1, 0, 1, 1]` and `y_pred = [0, 0, 1, 1, 1]`.  

8. **Feature Importance (4 marks)**  
   - Train a Random Forest classifier and plot feature importances for the Breast Cancer dataset.  

9. **Gradient Descent Coding (4 marks)**  
   - Implement gradient descent for linear regression with learning rate 0.01 and 1000 iterations.  

10. **Regularization (4 marks)**  
    - Add L1 regularization to a logistic regression model. Compare model weights before and after.  

---

# Assignment 3: Advanced Techniques and Applications  (Easy to Medium)
**Total Marks: 30**  

---

### **Theoretical Questions**  
1. **Clustering (3 marks)**  
   - What is the elbow method? How does it help in choosing K for K-means?  

2. **Neural Networks (3 marks)**  
   - Explain forward propagation in a neural network. What is an activation function?  

3. **Dimensionality Reduction (3 marks)**  
   - Why is PCA used? How much variance is retained if you select the top 2 principal components?  

4. **Evaluation Metrics (3 marks)**  
   - What is ROC-AUC? Draw a sample ROC curve.  

5. **Ethics in ML (3 marks)**  
   - What is algorithmic bias? Provide one example.  

---

### **Practical Questions**  
6. **PCA Implementation (4 marks)**  
   - Apply PCA to the Wine dataset and visualize the first two components.  

7. **K-Means Clustering (4 marks)**  
   - Cluster the MNIST dataset into 10 groups using K-means. Calculate silhouette score.  

8. **Neural Network Coding (4 marks)**  
   - Build a 2-layer neural network with PyTorch to classify handwritten digits (MNIST).  

9. **Hyperparameter Optimization (4 marks)**  
   - Use `GridSearchCV` to find the best `max_depth` for a decision tree (range 1–10).  

10. **Deployment (4 marks)**  
    - Save a trained SVM model to a file using `pickle` and write code to load it for predictions.  

---
