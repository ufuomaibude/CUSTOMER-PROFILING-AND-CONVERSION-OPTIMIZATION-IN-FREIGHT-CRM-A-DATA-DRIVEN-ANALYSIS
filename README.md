# CUSTOMER-PROFILING-AND-CONVERSION-OPTIMIZATION-IN-FREIGHT-CRM-A-DATA-DRIVEN-ANALYSIS
A machine learning analysis of Customer Profiling and Conversion Optimization in Freight CRM using a company as a case study in the research. The research aims to enhance customer segmentation and improve conversion rates, providing actionable insights for optimizing freight customer relationship management (CRM) strategies.

# Abstract
This study uses data analytics and machine learning to improve customer profiling and conversion optimization in freight CRM, with Tudor Freight International as a case study. Descriptive analytics explored key metrics such as quote volumes, transport modes, destinations, and conversion rates—revealing that 87.2% of quotes convert into clients and identifying significant seasonal and operator-based patterns. Air transport was the most quoted mode. Using K-means clustering, three customer segments were uncovered based on cost and timing, linked to specific operators. The findings offer actionable insights to enhance segmentation, improve service personalization, and optimize freight operations.

# Supply chain and Logistics sector
Logistics companies increasingly rely on Customer Relationship Management (CRM) systems to centralize and streamline the collection, organization, and analysis of critical customer data. CRM systems capture valuable information such as customer inquiries, quote requests, shipment preferences, and feedback, all of which are essential for understanding customer behavior and demand patterns. By leveraging this data, logistics companies gain deep insights into customer needs and preferences, enabling them to tailor their services more effectively. The strategic application of CRM data supports refined customer segmentation, optimized sales strategies, and enhanced service offerings. This approach, in turn, improves operational decision-making, enables more accurate demand forecasting, and drives business growth while fostering long-term, sustainable customer relationships.


 # Introducing the Dataset 

<img width="341" alt="Percentage quotes out" src="https://github.com/user-attachments/assets/768679b3-97d8-4c0e-8127-d38219547dd6" />

 # The Dataset Dictionary

<img width="367" alt="Tudor data dictionary" src="https://github.com/user-attachments/assets/563481e5-fc46-44dc-ad42-264c324128db" />
 
<img width="322" alt="Distribution Analysis of Tudor data" src="https://github.com/user-attachments/assets/827ba55c-e0f0-435a-acdf-e6e6c7c499f8" />


 # Unique variables showing significant missing entries in the dataset

<img width="343" alt="unique variables" src="https://github.com/user-attachments/assets/88768de3-69b7-44c0-b860-6085e2273a6f" />

 # Data Preprocessing steps (1)

<img width="490" alt="image" src="https://github.com/user-attachments/assets/fb13d71c-c96c-49fc-b6c7-e6b383c7e75a" />

 # Data Preprocessing steps (2)
<img width="490" alt="Datapreprocessing2" src="https://github.com/user-attachments/assets/f8ce47c3-c395-4ded-bdd1-6ccd15c394ba" />

 # Descriptive Analytics

![image](https://github.com/user-attachments/assets/027a74e7-68b4-474d-8afc-094a0304850d)

![image](https://github.com/user-attachments/assets/099eeeee-c431-45ba-bf31-6c403df745d3)

![image](https://github.com/user-attachments/assets/dd743d5b-679b-4a05-800b-3532110388ff)

![image](https://github.com/user-attachments/assets/f873bfd1-21d2-43c3-a080-08d4a5e86b13)


 # Unsupervised Machine Learning(K-Means Clustering)
This reveals hidden patterns within a dataset. ​
Unlike a supervised machine learning that uses pre-defined
output labels for prediction, unsupervised machine
learning  deals with dataset that do not contain pre-defined
labels. ​The objective is to reveal hidden patterns within the dataset. ​
The two unsupervised machine learning methods were used
for this project:​
Clustering (Grouping similar data points together) using K-
Means algorithm to assign the data into K clusters based on
similarity.​
Dimensionality Reduction using PCA (Reducing the number
of features while preserving the information).​

 # Cluster determination using elbow method
<img width="377" alt="elbowmethod" src="https://github.com/user-attachments/assets/46d51da8-8b9b-44b1-8395-d203d55f8d99" />

​ <img width="415" alt="clustering_numerical" src="https://github.com/user-attachments/assets/45b7475d-739d-4110-99e6-321db0dc0b9c" />

 # K-MEANS Clustering Visualization
 
<img width="454" alt="clustering" src="https://github.com/user-attachments/assets/fec32e9f-c8ce-4780-bf0c-6d2d384bf0d5" />

PCA ANALYSIS (3D CLUSTER VISUALIZATION)
Principal Component Analysis (PCA) was conducted to reduce the dimensionality of the dataset, to visualize the clustering results in a three-dimensional space. By transforming the original high-dimensional data into 3 principal components. PCA captures the most significant patterns and variance within the dataset. This technique simplifies the complexity of the data while preserving the most important information, making it easier to interpret and analyze the underlying structure and relationships between clusters. Through this approach, the visualization becomes more effective, allowing clearer insights into how data points are grouped and how distinct each cluster is in the reduced feature space.

<img width="293" alt="3D Cluster visualization tudor" src="https://github.com/user-attachments/assets/2ff5c2db-4b74-4570-beb8-10fb5218287d" />


# Predictive Analytics​

Target Encoding

Machine learning models require numerical inputs.​
Categorical variables need to be converted into numerical values for effective model training.​
Common encoding techniques: ​

One-Hot Encoding (expands dimensions)​
Label Encoding (arbitrary numerical assignments)​
Target Encoding (leverages statistical relationships)​​

<img width="497" alt="image" src="https://github.com/user-attachments/assets/cd93293d-9f72-4fbe-9e88-2b551a872a61" />


<img width="448" alt="Premodeling techniques3" src="https://github.com/user-attachments/assets/03d88ac8-d23a-49ea-8e31-f2cb462dab57" />

<img width="490" alt="Premodelling techniques2" src="https://github.com/user-attachments/assets/69bac1e5-4ddc-491e-a866-341f6548d4bb" />


<img width="497" alt="image" src="https://github.com/user-attachments/assets/bb6bbda3-c2a6-4e1c-bf3a-9821ebfa946d" />




<img width="492" alt="image" src="https://github.com/user-attachments/assets/11073ab8-a88a-479d-af40-c926eb98277c" />



<img width="497" alt="Model evaluation" src="https://github.com/user-attachments/assets/696b1c4b-aaa5-4def-9643-d2ab092eb969" />



# Conclusion on Descriptive analysis, Predictive analysis and clustering analysis 

This study effectively combined descriptive analytics and machine learning techniques to enhance Freight Customer Relationship Management (CRM) strategies. Descriptive analysis uncovered vital insights, including AJ's lead in quote volume and JH's superior conversion rate, seasonal quoting peaks, and the UK’s dominance in global logistics. Despite the high conversion rate (87.2%) and substantial data variability, clustering methods revealed limited segmentation success due to overlapping patterns and low silhouette scores.

Machine learning model evaluation further deepened these insights. Among the models tested—XGBoost, AutoML, and Random Forest. XGBoost consistently outperformed others, achieving a maximum accuracy of 96% on synthetic data and maintaining strong F1-scores across both converted and non-converted quotes. AutoML also performed well, especially using all features, with an accuracy of 90%. In contrast, Random Forest showed weaker results, particularly for converted quotes, with a low F1-score of 18% using all features.

These findings demonstrate that data-driven models—particularly ensemble methods like XGBoost—can provide high predictive performance for quote conversions, offering logistics companies an opportunity to proactively identify valuable leads and improve customer engagement strategies.

