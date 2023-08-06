# LiverDisease
 I had the opportunity to work on the Indian Liver Disease dataset, exploring various machine learning models and implementing three different Voting classifiers with distinct estimators.

📈 Initially, I experimented with several individual models, including Logistic Regression, Decision Trees, Bagging, Random Forest, KNN, and SVM with different kernels. It was fascinating to observe how each model performed differently on the dataset, providing valuable insights into their effectiveness.

💡 Taking it a step further, I decided to dive into ensemble learning with Voting classifiers. The idea was to combine the predictive power of multiple models and create robust classifiers for accurate predictions.

🏆 Here's a glimpse of the results from the three different Voting classifiers I implemented:

🧱Estimator_all: This ensemble was constructed using all the individual models, aiming to leverage the collective intelligence of each model. It achieved a compelling training accuracy of 75% and a test accuracy of 73%, showcasing its potential to make accurate predictions.

🧱Estimator_good: For this Voting classifier, I selected only the individual models with training and test accuracy above 70%. It maintained a consistent performance, with both training and test accuracy at 73%.

🧱Estimator_bad: In contrast, this ensemble included models with accuracy below 70%, with the goal of identifying areas for improvement. It showed promise with a training accuracy of 72% and a test accuracy of 70%.

🔍 The project provided valuable insights into the strengths and weaknesses of different models and showcased the power of ensemble learning in improving predictive capabilities.
