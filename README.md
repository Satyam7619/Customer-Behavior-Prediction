# Customer-Behavior-Prediction
Introduction:
Understanding customer purchasing behavior is crucial for businesses aiming to tailor marketing strategies, improve customer engagement, and boost sales. In this project, we aim to classify customers as either "Bargain Hunters" or "Premium Buyers" using their purchase history. These labels reflect different shopping behaviors:

Bargain Hunters typically look for discounts, offers, and make smaller, more frequent purchases.

Premium Buyers prefer quality over cost, usually making larger purchases less frequently.




By analyzing features such as total amount spent, average purchase value, and visits per month, we can build a predictive model that helps companies categorize their customers efficiently. This classification can enhance targeted promotions, product recommendations, and personalized experiences.



Methodology:
To solve the problem of classifying customer behavior, we followed these steps:
Data Collection:


We used a dataset containing customer purchase history including:


total_spent


avg_purchase_value


visits_per_month


buyer_type (target: Bargain Hunter or Premium Buyer)


Data Preprocessing:


Encoded the categorical target variable using LabelEncoder.


Standardized the numerical features using StandardScaler for optimal model performance.


Model Selection and Training:


Chose Logistic Regression as the baseline model for binary classification.


Trained the model on 80% of the data and tested it on the remaining 20%.


Evaluation:


Evaluated the model using a Confusion Matrix, and calculated:


Accuracy


Precision


Recall


Displayed a heatmap of the confusion matrix for visual assessment of predictions.


Tools Used:


Python (Pandas, Scikit-learn, Seaborn, Matplotlib)


Google Colab for coding


GitHub for version control and file submission


