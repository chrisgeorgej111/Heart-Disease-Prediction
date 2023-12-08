# Heart-Disease-Prediction
Predicting the Heart Disease from the imbalanced dataset..

The data set has 3 lac plus observations.. The preprocessing steps for the dataset are to mapping the catagorical values to numbers by mapping, label encoding, and one Hot encoding..Theese are decided to the number of unique values, order of values,in a particular column of the dataset.

This dataset is very imbalanced..90+% of data is towards to the Class No of the target variable and only 8% of data is towards to the class Yes of the target variable..

Many Classifier models are used to train the model and They are evaluated based on Recall Score because the False negatives need to be reduced in the dataset..

Here the focus was that the features that lead to heart disease shouldn't be missed out.. This will give us an idea on what leads to Heart disease...This was decided based on the severity of the disease

	
Models	Recall_Score
0	Gradient Boost	0.797443
1	XGB	0.797078
2	Support Vector Machine	0.795068
3	Random Forest	0.773699
4	Ada Boost	0.772420
5	Logistic Regreesion	0.763470
6	ExtraTrees	0.742648
7	Decision Tree	0.656256
8	Multinomial NB	0.399269
9	Gaussian NB	0.399269

