# Bank Customer Churn Analytics
## Business Understanding

### Company Background
Autumn bank is a Malaysian universal bank based in Kuala Lumpur, Malaysia. This bank was founded in 1988 by Ong T’nsam (20WMR08883), Lai Pei Xuan (20WMR08869) and Leong Yit Wee (20WMR08876). Autumn bank is the largest public listed company in Bursa Malaysia, the Malaysian Stock Exchange in 1990. Autumn bank issued the ATM and debit card for accessing the balance of savings account in 1992 so that it is more convenient for their customers to withdraw money and check account balance. Indirectly, customer satisfaction will be increased and customer loyalty and retention will be improved. Autumn bank provides financial products and services to the public namely personal banking, commercial banking, investment banking, management of unit trust funds, general insurance products and so on.

### Objectives
Due to the increasing competitiveness, Autumn bank has adopted a system to analyse the customer churn, predict the customer churn rate and the group of customers that are churn. So, by having this system, Autumn bank’s management is able to carry out the strategic plan to retain the existing customers based on the customer churn analytics. In addition, customer loyalty and retention will be improved as the management is able to develop customer retention strategies such as improve customer service, offer a discount or credit to return based on the results from churn analytics.

### Current Situation
Inventory of Resources
Students from Bachelor of Computer Science (Honours) in Data Science which include Ong T’nsam (20WMR08883), Lai Pei Xuan (20WMR08869) and Leong Yit Wee (20WMR08876) are helping Autumn Bank to perform the churn analytics in order to identify the customers who are going to churn so that the management is able to plan some strategies to retain the customers. The source of the dataset used is from Kaggle (https://www.kaggle.com/kmalit/bank-customer-churn-prediction). The software used in developing this system is Google Colab.

### Project Plan
The dataset will be splitted into train set and test set. Also, the null values will be removed from the datasets if there are any null values. Not only that, the columns ‘Geography’ and ‘Gender’ will be transformed to numeric data as it is easier to perform churn analytics by using numeric data as compared to categorical data. In additon, due to the imbalance of the dataset, Synthetic Minority Over-sampling Technique (SMOTE) is being used to handle the imbalance data before modelling so that results generated will be more accurate. The evaluation for modelling used is based on the accuracy, precision, recall and F1 score, the model with high accuracy, precision, recall and F1 score will be deployed for the churn analytics system.

### Initial assessment of tools and techniques
Scikit-learn is used for the modelling part as scikit-learn is a machine learning library which features various algorithms which are required for the churn analytics system implementation. The tool used for this project is Google Colab as it does not have a limit for the memory space and it will save everything in Google Drive, so users do not need to worry about the problem of lack of memory space on their laptop. Also, Google Colab includes a user-friendly interface which is easier for the users to learn, use and understand in order to do the coding.
