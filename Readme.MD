# Sampling Package

## Introduction
The Sampling Package provides tools for applying various sampling techniques and evaluating their impact on machine learning model performance. With features like data balancing, multiple sampling strategies, and model evaluation, it enables users to analyze and compare sampling methods effectively.

## Features
1. **Data Loading and Preprocessing**
   - Load datasets using pandas for easy manipulation.
   - Split data into features (`X_features`) and the target variable (`y_target`).

2. **Balancing Data**
   - Address data imbalance using SMOTE (Synthetic Minority Oversampling Technique).

3. **Sampling Techniques**
   - Implement the following techniques:
     - Random Sampling (with different proportions).
     - Stratified Sampling (to maintain class distribution).

4. **Machine Learning Models**
   - Evaluate the performance of the following models:
     - Logistic Regression (LogReg)
     - Random Forest Classifier (RandForest)
     - Decision Tree Classifier (DecTree)
     - Naive Bayes (NaiveBayes)
     - Support Vector Machine (SVM)

5. **Evaluation**
   - Measure model performance using accuracy.
   - Save results to a CSV file for further analysis.

## Results
The package outputs a `model_results.csv` file containing the accuracy of each model for every sampling method, allowing users to compare and identify the most effective strategy.

## Example Result Table
| Sample    | Model       | Accuracy |
|-----------|-------------|----------|
| Sample_A  | LogReg      | 0.89     |
| Sample_B  | RandForest  | 0.92     |
| Sample_C  | DecTree     | 0.88     |
| Sample_D  | NaiveBayes  | 0.85     |
| Sample_E  | SVM         | 0.91     |

## Dependencies
- pandas
- scikit-learn
- imbalanced-learn

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Fork the repository and submit a pull request for review.

## Contact
For questions or feedback, contact:
**Pranav Dev Khindria**
**Roll No:** 102203279
