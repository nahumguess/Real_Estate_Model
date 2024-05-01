### Overview
This repository contains the implementation and comparison of two machine learning models trained to predict real estate prices from the "new-realtor-dataset.csv". The models compared are a Ridge Regression model enhanced with Polynomial Features and a Feed-Forward Neural Network. This project aims to evaluate the effectiveness of traditional machine learning versus neural networks in regression tasks on the same dataset.

### Models

#### Model 1: Ridge Regression with Polynomial Features
- **Preprocessing**: Standard scaling, polynomial feature expansion.
- **Algorithm**: Ridge regression to mitigate overfitting through regularization.
- **Evaluation**: Performance evaluated using Mean Squared Error (MSE) and R2 Score.

#### Model 2: Feed-Forward Neural Network
- **Architecture**: Two hidden layers with 32 and 16 neurons respectively.
- **Optimization**: Adam optimizer with early stopping based on validation loss.
- **Evaluation**: Tracked using MSE during training for both training and validation sets.

### Results
- **Ridge Regression**: Demonstrated strong performance with a polynomial feature approach, achieving a final test R2 Score of 0.8568.
- **Neural Network**: While slightly underperforming compared to Ridge Regression with a final test R2 Score of 0.8463, it showcased the capability of neural networks to handle complex nonlinear patterns.

This repository is intended for educational purposes and serves as a demonstration of applying different machine learning methodologies to a common regression problem.
