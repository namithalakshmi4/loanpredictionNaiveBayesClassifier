Loan approval is a critical process for financial institutions. By using predictive models, we can automate and improve the speed and fairness of loan decisions. In this project, we explored different machine learning algorithms and finalized the Naive Bayes Classifier due to its better performance compared to other methods like Decision Tree.

✅ Technologies & Tools Used
--------------------------------
Component	                                     | Description
Language	                                     |  Python
Libraries                                      |	pandas, numpy, matplotlib, seaborn
ML Algorithms Tested                           |  Decision Tree, Naive Bayes
Final Model                                    |	Gaussian Naive Bayes (best accuracy)
Evaluation Metric                            	 | Accuracy Score

🔍 Data Preprocessing Steps
------------------------------------------
Loaded the training dataset using Pandas

Checked for null values using .isnull().sum()

Filled missing values appropriately (mean / mode)

Label encoded categorical variables like Gender, Married, Education, Property_Area, etc.

Split dataset into x_train, x_test, y_train, y_test

Applied StandardScaler after encoding

Trained models and compared accuracy

📊 Model Evaluation
--------------------------------
We compared two models:

Model	|Accuracy
Decision Tree	|~70%
Naive Bayes	Better |82% (highest) ✅

Therefore, the Naive Bayes Classifier was chosen as the final model.
It also performed well on separate unseen test data supplied manually.

🧪 Single Prediction Example
---------------------------------------------

We created a sample input tuple with encoded values and used the Naive Bayes model to predict if a loan would be approved or not. The model successfully returned predictions (approved / not approved) based on the given input.

✅ Final Outcome
-----------------------------

✔ The model can now predict loan approval status with good accuracy.
✔ The project can be extended with GUI or Flask web app for deployment.
