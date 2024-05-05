# Home-Credit-Default-risk
## Business problem 
Home Credit aims to identify which unbanked clients are eligible for a loan and can afford to repay it. Many individuals with no credit history often rely on predatory lenders charging excessive interest rates and imposing unfavorable terms. Home Credit's objective is to provide safer lending options for such individuals, focusing on accurately assessing applicants' repayment abilities to ensure those capable of repayment receive fair access to loans. The challenge lies in identifying eligible clients without credit histories who can repay loans, ultimately preventing them from falling into the cycle of predatory lending.

## Solution 
### Accurate Client Assessment:
Utilizes supervised predictive classification models to analyze client repayment behaviors.
Differentiates between clients likely to repay on time and those prone to repayment challenges.
### Confident Lending:
Minimizes the risk of non-repayment by confidently extending loans.
Offers safer lending options to clients with limited or no credit history.
### Predictive Model Selection:
Applies models like Logistic Regression, Random Forest, and Light Gradient Boosting Machine (LightGBM) for historical trend analysis.
Focuses on a binary target variable ('0' for on-time repayment, '1' for potential repayment issues).
### Model Performance Metrics:
Evaluates models using Area Under the Curve (AUC) from receiver operating characteristics (ROC) curves.
Random Forest and LightGBM models demonstrated strong predictive power, achieving test AUC scores of around 0.63 on Kaggle.
These high AUC scores reflect these models' accuracy in distinguishing between reliable clients and those at risk of default.
### Strategic Benefits:
Leads to secure borrowing experiences for first-time borrowers.
Establishes trust through fair and inclusive lending practices.
Grows Home Credit's customer base via positive client recommendations.

## Contribution:

- **Cross-Validation:** Implemented cross-validation techniques to enhance model robustness and generalizability.
- **Sampling Techniques:** Applied upsampling and downsampling methods to balance the data for better performance.
- **ROC-AUC Curves:** Used ROC-AUC curves to assess model effectiveness and refine the predictive process.
- **Feature Importance:** Conducted feature importance analysis to optimize model inputs.
- **LightGBM Model:** Fitted, tuned, and fine-tuned the Light Gradient Boosting Machine (LightGBM) model, optimizing parameters based on validation results.
- **Model Predictions:** Generated accurate predictions using the tuned LightGBM model.
- **Test Set Preparation:** Prepared the test set for final model deployment.
- **Final Edits:** Managed the final model edits to ensure accuracy and reliability.

## Business Benefits

### Business Benefits

1. **Improved Lending Precision:**  
   The optimized models provided more accurate predictions, allowing Home Credit to identify clients with higher repayment probabilities. This precision minimizes the risk of non-repayment, leading to more informed lending decisions.

2. **Increased Financial Inclusion:**  
   By evaluating repayment ability more accurately through advanced predictive techniques, Home Credit can extend fair and safe lending options to clients with limited or no credit history, thereby promoting financial inclusion.

3. **Portfolio Strengthening:**  
   Enhanced prediction models result in a stronger, more reliable portfolio by reducing the number of non-performing loans and increasing overall repayment rates.

4. **Better Resource Allocation:**  
   Improved models streamline the loan approval process, helping Home Credit allocate resources efficiently by focusing efforts on clients who align with the institution's risk tolerance.

5. **Positive Customer Experience:**  
   First-time borrowers benefit from secure borrowing experiences, building trust and fostering brand loyalty. Satisfied clients are more likely to recommend Home Credit, expanding the company's customer base through positive word of mouth.

6. **Data-Driven Insights:**  
   Feature importance analysis and ROC-AUC evaluations offer valuable insights into client behaviors and repayment trends, which can further guide future lending strategies and model development.

## Challenges faced 
During the implementation phase, cross-validation across multiple folds proved challenging, particularly in managing computational resources and processing time without compromising accuracy. Achieving the right balance in sampling techniques was also crucial; while upsampling risked overfitting, under-sampling could result in losing valuable data, necessitating iterative adjustments to ensure optimal balance. Fine-tuning the LightGBM model required extensive grid search for the best parameters, which took significant time due to the model's complexity and the vast array of hyperparameters to consider. Lastly, generating accurate predictions while minimizing false positives and negatives was challenging due to the dataset's diverse characteristics, demanding a comprehensive evaluation.

## My learnings 
In this project, learning about LightGBM and optimizing its parameters through grid search significantly improved my model-tuning skills. Mastering ROC-AUC curves was particularly valuable for understanding predictive accuracy, especially when working with imbalanced datasets. Upsampling and downsampling techniques proved essential for ensuring model robustness and generalizability. These methods collectively enabled me to provide meaningful business value by building models that identified eligible clients more effectively, reduced the risk of non-repayment, and improved lending precision.

## Presentation Link
[Home Credit PPT](https://github.com/adxrsh9/Home-Credit-Default-risk/blob/cb50667811d2922edd55c73433d06edd529e16d1/Capstone%20Presentation%20Group%206.pptx)

## Project file link
[Project File](https://github.com/adxrsh9/Home-Credit-Default-risk/blob/32b3c7cd05a8c1b94ed115741a8bf865d99b987a/Home%20Credit_new_Group_6_modified%20(1).ipynb)
