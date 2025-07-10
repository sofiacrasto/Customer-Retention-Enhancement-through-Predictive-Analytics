# Customer-Retention-Enhancement-through-Predictive-Analytics
Forage - LLOYDS Banking Group - Internship Project 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This project simulates a real-world data science engagement focused on reducing customer churn through predictive modeling. Using structured data from a fictional financial institution, the analysis integrates behavioral, transactional, and digital engagement signals to identify customers at risk of attrition. The deliverable includes a machine learning pipeline, feature importance insights, and strategic recommendations to support customer retention initiatives.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📌 Executive Summary
Customer churn poses a significant threat to long-term profitability, especially in competitive digital banking environments. This project addresses that challenge by building a predictive model that classifies customers based on their likelihood to churn. The analysis draws from multiple data sources—including transaction history, service interactions, and online activity—to engineer features that reflect customer engagement and satisfaction. After preprocessing and balancing the dataset, several machine learning models were evaluated, with the Random Forest classifier achieving the best performance at 82% accuracy.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧩 Business Context
The dataset reflects a scenario where churn is influenced by:
- Unresolved service complaints
- Low digital engagement (e.g., infrequent logins)
- Demographic and behavioral patterns (e.g., income level, product diversity)
The goal is to proactively identify customers likely to churn and enable targeted retention strategies.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧪 Analytical Approach
📥 Data Sources
- Transaction_History: Purchase behavior and spending patterns
- Customer_Service: Support interactions and resolution outcomes
- Online_Activity: Login frequency and platform usage
- Churn_Status: Binary churn labels (0 = retained, 1 = churned)
  
🧹 Preprocessing & Feature Engineering
- Aggregated transactional and interaction data to one row per customer
- Engineered features such as:
- TotalAmountSpent
- ProductCategoryDiversity
- DaysSinceLastLogin
- UnresolvedInteractions
- Encoded categorical variables (e.g., PreferredPlatform)
- Scaled numerical features using MinMaxScaler
- Balanced the dataset using SMOTE to address class imbalance

🤖 Model Development
- Trained and evaluated multiple classifiers:
- Logistic Regression
- Decision Tree
- Random Forest ✅ (Best performer)
- K-Nearest Neighbors
- SVM
- Extra Trees
- Naive Bayes
- Evaluated using precision, recall, F1-score, and accuracy

📈 Results
- Best Model: Random Forest Classifier
- Accuracy: 82%
- Key Predictors:
- Number of unresolved interactions
- Days since last login
- Preferred digital platform
- Product category diversity

💡 Strategic Insights
- Customers with unresolved complaints are significantly more likely to churn.
- Infrequent login activity is a strong early signal of disengagement.
- Platform preference (e.g., mobile app vs. website) can inform targeted outreach.
- Customers with low product diversity may be less embedded in the ecosystem and more prone to churn.

📌 Business Recommendations
- Proactive Service Recovery: Prioritize follow-ups for unresolved complaints.
- Digital Re-engagement: Target customers with low login frequency using personalized nudges.
- Platform Optimization: Enhance user experience across all digital channels.
- Product Cross-Selling: Encourage broader product adoption to deepen customer relationships.
- Segmented Campaigns: Tailor retention strategies based on income level, platform usage, and interaction history.

📁 Repository Structure
├── data/                         # Raw and processed datasets
├── notebooks/                   # Jupyter notebooks for EDA and modeling
├── models/                      # Trained models (optional)
├── assets/                      # Visualizations and plots
├── churn_prediction.py          # Main script (if applicable)
└── README.md                    # Project overview

📊 Visualizations
<img width="507" height="432" alt="image" src="https://github.com/user-attachments/assets/f41e7b44-6f19-4e7d-b0e2-9366adc9a39f" />
<img width="448" height="434" alt="image" src="https://github.com/user-attachments/assets/218243e3-5560-4fd0-9305-cf7ac08961f4" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/a1726f49-dc8b-475d-bffe-fd0e25bae002" />


🙋‍♀️ Author
Sofia
📍 Abu Dhabi, UAE
🔗 (https://www.linkedin.com/in/sofia-crasto-137768228/)




