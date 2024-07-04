Problem Statement
Develop a model to predict the likelihood of a customer returning to the departmental store, and the likelihood of them buying the same product/service, also recommend the products that will increase the store revenue.

Abstract
According to the assingment, I developed a machine learning model to predict the likelihood of a customer returning to a departmental store and the likelihood of them buying the same product or service. Additionally, we aimed to recommend products that could increase the store's revenue. The dataset used, "online_shoppers_intention.csv," comprised various features, including visitor behavior, page interactions, and transaction details.

The data underwent several preprocessing steps, including handling missing values, encoding categorical variables, and scaling numerical features. Two primary models were trained: one to predict customer return likelihood and another to predict repeat purchases of the same product or service. These models were evaluated using metrics such as accuracy, ROC-AUC, and classification reports.

To enhance the recommendations and identify products that could boost revenue, implemented a collaborative filtering recommendation system using the Surprise library. This system provided personalized product recommendations based on user-item interaction matrices.We also performed extensive data visualization to gain deeper insights into the dataset. Key visualizations included:

Distribution of Target Variable: A bar chart showing the count of sessions with and without revenue generation. Correlation Heatmap: A heatmap illustrating the relationships between numerical features. Pair Plot for Numerical Features: Scatter plots showcasing the distribution of numerical features across the revenue classes. Revenue by Month: A bar chart displaying revenue generation across different months. Revenue by Visitor Type: A bar chart depicting revenue generation by different visitor types. Visitor Type Proportion: A pie chart highlighting the proportion of returning versus new visitors.
