# Home-Credit-Default-risk
## Business problem 
Many individuals who lack access to formal banking due to no credit histories are often vulnerable to predatory lenders who impose high-interest rates and unfair loan terms, worsening their financial stability. Home Credit, a non-banking financial institution, addresses this issue by offering safer lending options to those with minimal or no credit histories. By focusing on financial inclusion, Home Credit aims to empower economic improvement for its clients.

This financial inclusion initiative presents significant risks for Home Credit, particularly due to the high likelihood of loan defaults among borrowers with limited credit histories. Nevertheless, the institution is committed to ensuring that clients who are capable of repayment are not unfairly excluded from receiving loans. To address these challenges while minimizing risk, Home Credit focuses on developing methods to accurately predict the loan repayment abilities of applicants, ultimately facilitating more informed and cautious lending decisions.

## Solution 
The solution to this issue involves the use of supervised predictive classification models, capitalizing on historical labeled data to forecast loan repayment behaviors. With the target variable being binary—'0' for on-time repayment and '1' for potential repayment issues—techniques like Logistic Regression, Random Forest, and Light Gradient Boosting Machine (LightGBM) are particularly suited for this analysis.

In terms of evaluating these models, performance metrics such as the Area Under the Curve (AUC) from the receiver operating characteristics (ROC) curves are used. Notably, models like Random Forest and LightGBM have demonstrated strong performance, achieving test AUCs and scores on Kaggle around 0.63. This performance level signifies a robust capability to differentiate between customers likely to repay their loans on time and those who might encounter difficulties, thereby supporting more precise lending decisions.

## Contribution:
My contribution to the project included implementing cross-validation and balancing techniques like upsampling and downsampling to enhance model generalizability and performance. I employed ROC-AUC curves for effectiveness assessment and conducted feature importance analysis to refine model inputs. Additionally, I was responsible for fitting and fine-tuning the Light Gradient Boosting Machine (LightGBM) model, optimizing parameters based on validation insights, and preparing the test set for final model deployment.

## Business Benefits

Enhanced Decision-Making in Lending: By leveraging models such as Logistic Regression, Random Forest, and LGBM, Home Credit can make more precise and confident loan approval decisions. These models provide accurate forecasts of repayment behaviors, greatly aiding the decision-making process.

Mitigation of Financial Risks:  Improved predictive models help in early identification of potential defaulters, significantly reducing the occurrence of Non-Performing Assets and mitigating associated financial risks.

Efficiency in Loan Processing:  The integration of machine learning models into the loan processing workflow automates many steps, accelerating the approval process, lowering operational costs, and enhancing customer satisfaction.

Tailored Financial Offerings:   Outputs from these models facilitate the customization of credit offerings, allowing for adjustments in credit limits and interest rates based on individual risk profiles.

Proactive Default Prevention:   Advanced predictive insights empower Home Credit to implement preemptive measures such as financial counseling to reduce the risk of defaults.

Optimal Use of Resources:    Accurate loan repayment predictions enable more efficient allocation of resources, focusing manual reviews on high-risk cases and streamlining approvals for lower-risk applications.

Increased Repayment Success:   Reliable prediction of repayment behaviors ensures that loans are extended to clients with a higher likelihood of fulfillment, boosting repayment rates and enhancing overall profitability of the loan portfolio


## Challenges faced 

Throughout the project, I faced numerous challenges that affected both the modeling techniques and data management. One major issue was dealing with missing values in data columns that were significantly correlated with the target variable, making data imputation complex without risking bias. Additionally, optimizing the Random Forest and LGBM models was computationally intensive, pushing the limits of our systems. Specifically, the LGBM model required precise tuning of parameters to strike the right balance between accuracy and computational load.

The need for robust computational resources was highlighted by the demands of processing large datasets and running sophisticated models. In my role, I also took on the responsibility of determining feature importance and rigorously testing the models to validate their accuracy and reliability under various conditions. This added an additional layer of complexity to the project, emphasizing the importance of thorough testing and validation to ensure the models' effectiveness in real-world applications.

## My learnings 

This end-to-end project, from pinpointing the business problem to extracting meaningful business value, significantly enhanced my skills across multiple dimensions. I deepened my knowledge in Exploratory Data Analysis and refined my expertise with Logistic Regression and Random Forest models. This project also marked my first encounter with the LGBM model; delving into its complexities and tuning the model proved to be a challenging but immensely rewarding experience. I was also introduced to techniques such as upsampling and downsampling to tackle the issue of imbalanced data, which was a new and enlightening aspect for me. Utilizing ROC-AUC curves and feature importance charts allowed me to effectively translate technical outcomes into clear, actionable business insights. Engaging with large datasets in a real-world setting not only bolstered my analytical acumen but also ignited my passion for overcoming similar challenges in the future, pushing me to further explore and master advanced analytical tools in my upcoming projects.

## Presentation Link
[Home Credit PPT](https://github.com/adxrsh9/Home-Credit-Default-risk/blob/cb50667811d2922edd55c73433d06edd529e16d1/Capstone%20Presentation%20Group%206.pptx)

## Project file link
[Project File]()
