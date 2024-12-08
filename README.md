# Wine Quality Prediction

## Objective
This project focuses on predicting wine quality using machine learning and deep learning techniques. The goal is to classify wine quality based on its chemical properties, such as pH, alcohol content, and residual sugar.

## Dataset Description
The dataset contains detailed information about the chemical composition of wines and their respective quality ratings. It includes features like pH, alcohol content, residual sugar, and more, with the target variable being wine quality.

## Methodology
1. **Approach for Machine Learning and Deep Learning**:
   - The machine learning approach utilizes a Support Vector Machine (SVM) model, which efficiently handles high-dimensional data and separates classes using a hyperplane.
   - A neural network is implemented to capture complex relationships in the data, leveraging its ability to model non-linear patterns.
   - Hyperparameter tuning is performed to optimize learning rates and batch sizes, enhancing the models' performance.
   - TensorBoard is used to visualize training metrics, providing insights into model optimization.

2. **Models Used in the Project**:
   - **Model 1**: Support Vector Machine (SVM) for classification tasks.
   - **Model 2**: Neural Network for classification tasks.
   - **Additional Techniques**:
       - Hyperparameter tuning to refine learning rates and batch sizes.
       - TensorBoard integration to track training metrics and monitor progress.

## Results Summary
Both models achieved high accuracy for the majority class but struggled with class imbalance, leading to lower recall for the minority class. Hyperparameter tuning revealed stability across tested values, and TensorBoard provided valuable visualizations to monitor performance.

## Key Takeaways
- The chemical properties of wine are effective predictors of quality, particularly for the majority class.
- Addressing class imbalance is critical to improving predictions for underrepresented categories.
- TensorBoard and hyperparameter tuning proved useful for optimizing and monitoring the models.
