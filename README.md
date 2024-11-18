# Breast Cancer Prediction
### Problem statement:
Breast cancer stands as the prevailing form of cancer among women on a global scale. It constitutes a quarter of all cancer instances and impacted more than a million individuals in the single year of 2015. Its onset occurs as cells within the breast commence an unregulated proliferation (Breast Cancer Dataset, n.d.). Breast tumor diagnosis and categorization are critical for effective medical treatment and results for patients. The goal of this project is to create a machine-learning model that can help physicians diagnose breast cancer by analyzing medical imaging data.
### Dataset
##### Source:   
Breast cancer classification dataset from Kaggle.
##### Size:     
18208 records
##### Features: 
id,	diagnosis, radius_mean,	texture_mean,	perimeter_mean,	area_mean,	smoothness_mean,	compactness_mean,	concavity_mean,	concave points_mean,	symmetry_mean	fractal_dimension_mean,	radius_se	texture_se,	perimeter_se,	area_se,	smoothness_se,	compactness_se,	concavity_se,	concave points_se,	symmetry_se,	fractal_dimension_se,	radius_worst,	texture_worst,	perimeter_worst,	area_worst,	smoothness_worst,	compactness_worst,	concavity_worst,	concave points_worst,	symmetry_worst,	fractal_dimension_worst
### Key Features
##### Data Collection and Processing: 
The project involves collecting a dataset containing features extracted from breast cancer cell images, such as cell size, shape, and texture. Using Pandas, the collected data is cleaned, preprocessed, and transformed to ensure it is suitable for analysis. The dataset is included in the repository for easy access.
##### Data Visualization: 
The project utilizes data visualization techniques to gain insights into the dataset. Matplotlib is employed to create visualizations such as histograms, bar plots, and scatter plots. These visualizations provide a deeper understanding of the distribution of features and help identify differences between malignant and benign samples.
##### Train-Test Split: 
To evaluate the performance of the neural network model, the project employs the train-test split technique. The dataset is divided into training and testing subsets, ensuring that the model is trained on a portion of the data and evaluated on unseen data. This allows for an accurate assessment of the model's ability to generalize to new samples.

##### Decision Tree Model: 
#### Model Evaluation: 
In this project, three different models were evaluated for classification. 

##### Logistic Regression Model:
The Logistic Regression model achieved an accuracy of 73.42%, with a precision of 0.83 and recall of 0.75. Its F1 score of 0.79 indicates a reasonable balance between precision and recall, but its overall performance lags behind that of the Decision Tree and Random Forest models. While Logistic Regression is often chosen for its simplicity and interpretability, in this case, it has slightly lower performance metrics across all evaluation measures. Nevertheless, it remains a viable option for classification tasks where model simplicity and faster computation are prioritized over higher accuracy.

##### Randome Forest Model:
##### Decision Tree Model: 
The Decision Tree model achieved an accuracy of 79.75%, with a precision of 0.86 and a recall of 0.83, indicating solid performance. The F1 score of 0.84 suggests a balanced trade-off between precision and recall, showing that the model is fairly effective at both minimizing false positives and capturing true positives. While the Decision Tree performs well, it is outperformed by the Random Forest model in terms of both accuracy and recall. However, it still represents a reliable model for classification tasks where interpretability and simplicity are key considerations.

##### Model Evaluation: 
##### Ranfom Forest Model:
The Random Forest model demonstrated exceptional performance in this classification task, achieving an accuracy of 92.41%. With a precision of 0.93, the model correctly identified a high proportion of positive instances, while its recall score of 0.96 indicates its ability to capture most of the true positives. The F1 score of 0.94 reflects a strong balance between precision and recall, highlighting the model's overall robustness. Compared to other models, Random Forest outperformed in terms of accuracy, precision, recall, and F1 score, making it the most effective model for this particular dataset.

### Conclusion:
After analyzing the accuracy of the three models employing training, testing, and validation datasets, it is evident that the Random Forest model is more accurate than the Decision Tree and Logistic Regression models. Accuracy, Precision, Recall, and F1-score are calculated in this research and compared between the three models. Statistics testing verified that the Random forest model performed well on untested data, indicating good generalization capabilities. Therefore, the Random forest model is the best approach for the selected project.
### References:
Dataset: https://www.kaggle.com/datasets
