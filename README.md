# Data Science and Business Analytics Projects
  

These projects were completed during my Data Sciense & Business Analytics Post Graduate Certificate at UT Austin. They showcase my ability and experience in solving a variety of data science tasks utilzing technical tools. 

**Project List**
 - [Jump to Business Statistics Project](#business-statistics-project)
 - [Jump to Supervised Machine Learning: Regression Project](#supervised-machine-learning-regression-project)
 - [Jump to Supervised Machine Learning: Classification Project](#supervised-machine-learning-classification-project)
 - [Jump to Unsupervised Machine Learning Project](#unsupervised-machine-learning-project)
 - [Jump to Model Tuning Project](#model-tuning-project)

**Skills & Tools Covered Across All Projects**

- Python (NumPy, Pandas, Seaborn)
- Multivariate and Bivariate Data Analysis
- Data Vizualization
- Data Investigation and Preprocessing (handling outliers, missing values, duplicates, etc)
- Data Manipulation (creating new variables, normalizing values)
- Data Engineering (Creating new columns, One Hot Encoding, Test Train Split)
- Communicating Data-Driven Business Insights

  
  ____________________________________________________________________________________________________________________________


## Business Statistics Project

### **Summary:**

In this project I used statistical analysis, a/b testing, and data visualization to determine whether the new landing page of an online news portal is more effective at converting viewers to subscribers than the current landing page. I answered the following questions regarding user data:

1. Do the users spend more time on the new landing page than the existing landing page?
2. Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
3. Is the conversion and preferred language independent or related?
4. Is the time spent on the new page the same for the different language users?

Initial visual analysis shown below seemed to suggest that the new landing page is more effective at converting viewers to subscribers than the old landing page, but further statistical analysis was required to determine the statistical significance of the new page's performance.

<img src="assets/ENews_Express_Conversion_Rate.png" alt="E-News Express Conversion Rate">

### **Project Result & Conclusion:**

I applied hypothesis testing to assess webpage performance, providing statistical evidence (p = 0.008) that the new design improved conversion rates with 95% confidence. I visually analyzed the data and tested four statistical hypothesis to provide strong insight into the data and answer important questions. 

### **Unique Skills & Tools Covered:**

- Hypothesis Testing
- A/B testing
- Statistical Inference

[Business Statistics Project Link](https://github.com/MarkNoble-1/portfolio/blob/main/ENews_Business_Statistics_Project.ipynb)





____________________________________________________________________________________________________________________________


## Supervised Machine Learning: Regression Project
[Full Project Link](https://github.com/MarkNoble-1/portfolio/blob/main/Recell_Supervised_Machine_Learning_Project.ipynb)

**Summary:**

In this project I built a linear regression model to help develop a dynamic pricing strategy for used electronic devices for a reseller. I analyzed the variables and handled multicollinearity in the data to improve the model and identify the most important factors that significantly influence the price of used electronic devices.

This heatmap below showing the correlation between variables helped visualize multicollinearity in the original model, which resulted in non-optimal performance. Handling multicollinearity allowed me to further refine the model until I had only significant and independent variables left in the final model. 

<img src="assets/Recell_Heatmap_Screenshot.png" alt="Recell Heatmap Screenshot">

**Project Result:**

I applied regression model to estimate used device prices, predicting within 4.5% of actual values and demonstrating strong training and testing performance.

**Unique Skills & Tools Covered:**

- Linear Regression Model Building
- Linear Regression Analysis



____________________________________________________________________________________________________________________________

## Supervised Machine Learning: Classification Project
[Full Project Link](https://github.com/MarkNoble-1/portfolio/blob/main/INN_Hotels_Supervised_Machine_Learning_Project.ipynb)

**Summary:**

In this project I analyzed customer data for a hotel to find which factors have a high influence on booking cancellations, and built a decision tree model to predict bookings which are likely canceled in advance resulting in revenue loss. I used this data to help formulate profitable policies for cancellations and refunds for the hotel. Additionally, I investigated a variable in the dataset that presented logical inconsistencies, and I presented possible explanations for the data shown by that variable to highlight the importance of clean data. 

I used pruning techniques to refine the decision tree, allowing for a more rubust model.

The first decision tree was highly complex and performed with 99% accuracy and a 99% F1 score on the training data, but poorly performed on the testing data set as it was overfitting:

<img src="assets/INN_prepruned_tree.png" alt="Prepruned Decision Tree">

The pruned tree was more computationally effecient and had approximately equal performance on training and testing data:

<img src="assets/INN_Decision_Tree.png" alt="Pruned Decision Tree">

**Project Result:**

I developed a decision tree model with a high F1 score of 0.81, allowing the hotel to take action on 78% of at-risk cancellations (recall) while ensuring 84% of flagged cancellations were truly at risk (precision)

**Unique Skills & Tools Covered:**

- Logistic Regression Model Building
- Handling Multicollinearity
- Utilizing and Analyzing an AUC-ROC Curve
- Decision Tree Building and Pruning
____________________________________________________________________________________________________________________________


## Unsupervised Machine Learning Project
[Full Project Link](https://github.com/MarkNoble-1/portfolio/blob/main/Trade%26Ahead_Unsupervised_Machine_Learning_Project.ipynb)

**Summary:**

In this project I analyzed data for certain stocks, comparing a K-Means clustering model and a Heirarchical clustering model that identified groups of stocks based on the attributes provided. I compared both models and optimized their performance to select the model creating the most appropriately sized and distinct clusters. I shared insights about the characteristics of each group, and how the model can be used to drive decision making for investment on these stocks. 

I created the below dendogram to vizualize the clusters of the hierarchicchal clustering model, and the quanitites in each:

<img src="assets/TradeAhead_Cluster_Dendogram.png" alt="Cluster Dendogram">

In order to compare variables, I created the below plot to show the differences in how variables from each cluster vary from the dataset mean:

<img src="assets/TradeAhead_cluster_characteristics.png" alt="Cluster Characteristics">


**Project Result:**

I created a clustering model splitting the stocks into 3 distinct groups, allowing users to select stocks from certain clusters based on their trading profile and risk tolerance.

**Unique Skills & Tools Covered:**

- K-Means Clustring
- Hierarchical Clustring
- Cluter Profiling


____________________________________________________________________________________________________________________________


## Model Tuning Project

**Summary:**

In this project I analyzed encoded sensor data to help improve the cost and efficiency of wind energy production by building a model to predict windmill failures. I built and tuned several classification models to find the most effective model at predicting failures, which would allow the company to avoid steep repair costs and downtime.

I optmized the accuracy and recall score on the models created because False Negatives (real failures where there is no detection by the model) cost significantly more than False Positives (failture predicted when there is no failure), and actual failures predicted by the model still result in hefty repair costs.

I discovered and vizualized the most important features in the dataset according to my final model, providing powerful insights that could be used to reduce windmill failure. 

<img src="assets/Renewind_Feature_Importances.png" alt="Feature Importances">

**Unique Skills & Tools Covered:**

- Upsampling and Downsampling
- Data Regularization
- Hyperparameter Tuning

**Project Result:**

I developed and tested several models, selecting a under-sampled random forest model that performed well with 95% accuracy and an a recall score of 85%. Using this model would allow for reduced costs on expensive unexpected repairs.

[Model Tuning Project Link](https://github.com/MarkNoble-1/portfolio/blob/main/Renewind_Model_Tuning_Project.ipynb)








       
