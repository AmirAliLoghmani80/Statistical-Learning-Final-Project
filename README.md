
# Statistical Learning Final Project

This project was completed as part of the Statistical Learning course at Sharif University of Technology, Electrical Engineering Department. The main objective of the project was to apply various machine learning techniques to analyze and predict the correctness of answers provided by students in an online educational platform.

## Project Overview

This project includes several tasks aimed at understanding and improving predictive models used to assess students' knowledge based on their responses to diagnostic questions. The data used in this project was sourced from platforms like Khan Academy and Coursera, which provide large-scale educational datasets.

### Key Tasks

1. **Data Loading and Preprocessing**
   - The project involved handling and cleaning sparse matrix data representing student responses to questions.
   - The dataset includes various metadata related to both the students and the questions, which was used to build the models.

2. **K-Nearest Neighbor (KNN)**
   - The KNN model was implemented to predict whether a student would correctly answer a question based on their previous responses.
   - Both user-based and item-based collaborative filtering approaches were explored.

3. **Item Response Theory (IRT)**
   - The IRT model was used to estimate the latent abilities of students and the difficulty levels of questions.
   - A gradient descent optimization technique was applied to maximize the log-likelihood function for parameter estimation.

4. **Matrix Factorization**
   - Singular Value Decomposition (SVD) and Alternating Least Squares (ALS) methods were used for matrix factorization to predict student responses.
   - The accuracy of the model was measured using the validation dataset, and the best hyperparameters were selected.

5. **Ensemble Learning**
   - An ensemble of models, including bagging, was used to improve prediction stability and accuracy.

### Results

- The accuracy of each model was evaluated, and the results were plotted to compare the performance across different algorithms.
- The project identified key limitations of each model, such as overfitting and underfitting, and proposed methods for improvement.

### Files

- **Code:** The Python scripts implementing KNN, IRT, matrix factorization, and ensemble methods can be found in the `codes` directory.
- **Data:** The data used for the project is stored in the `data` directory.
- **Plots:** Visualizations of the results are saved in the `plots` folder.

### Conclusion

This project provided a deep understanding of various machine learning algorithms applied to educational data. The results demonstrated the potential and limitations of models like KNN, IRT, and matrix factorization in predicting student performance.
