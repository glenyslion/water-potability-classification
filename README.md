# Water Potability Classification

Access to clean and potable water is essential for human health and well-being. However, ensuring water safety remains a significant challenge in many regions of the world, where contamination from natural and man-made sources can make water unsafe for consumption. Given the critical importance of water to public health, it is necessary to accurately assess its potability to prevent waterborne diseases and related health issues.

**Project Overview**

This project explores the water potability problem as a classification task, leveraging data analytics to enhance water quality monitoring. By utilizing classification models, we aim to determine whether water samples are potable or non-potable based on various chemical and physical properties. This scalable approach can support ongoing efforts to ensure water safety.

**Dataset**

The project utilizes the Water Potability Dataset, which is publicly available on Kaggle. The dataset contains information on several factors affecting water quality, including:

	•	pH levels
	•	Hardness
	•	Solids
 	•	Chloramines
	•	Sulfate
	•	Conductivity
 	•	Organic Carbon
	•	Trihalomethanes
	•	Turbidity
 
**Methodology**

We apply a several classification models, such as KNN, Logistic Regression, Naive Bayes, Linear Discriminant Analysis, Quadratic Discriminant Analysis, Tree, Support Vector Machine, and Random Forest to predict the potability of water samples. The model helps in identifying patterns and classifying the water samples as either potable or non-potable. The following steps are undertaken:

	1.	Data Preprocessing: Handling missing values and normalizing the dataset.
	2.	Model Training: Training a Random Forest classifier on the dataset.
	3.	Model Tuning: Testing the performance of the model under different tree depths and tuning parameters to improve accuracy.

**Results**

	•	Best Model: Random Forest
	•	Accuracy: 79.12%

**Why Random Forest?**

Random Forest was chosen as the primary model due to its ability to handle uncorrelated variables efficiently. The model also excels at reducing overfitting by averaging results across multiple decision trees, improving both performance and reliability.

**Key Takeaways**

	•	Performance: Random Forest performed the best due to the low correlation between variables, making it an ideal choice for this classification problem.
	•	Overfitting Mitigation: Random Forest mitigates overfitting by building multiple trees and averaging the predictions, contributing to its stable performance.

**Conclusion**

This project demonstrates the power of machine learning in water quality monitoring. The Random Forest model, with its robust performance and overfitting resistance, is highly effective in predicting the potability of water samples. With an accuracy of 79.12%, this model provides a reliable tool for assessing water safety and supports efforts to prevent waterborne diseases.
