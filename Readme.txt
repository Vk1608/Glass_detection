Structure of Code:
The attached colab file constists of 8 parts:
	1) Dependencies all the dependencies are imported in this part.
	2) Importing Data:capturing data from google drive where is uploaded.
		For uploading data on drive:
		Download data from https://www.kaggle.com/jeffheaton/glasses-or-no-glasses/
		extract it and upload train.csv and test.csv to your google drive.
		
	3) Data Analysis: Analysis of raw data its shape,  max, min, distribution nad trends
	4) Data Splitting: Splitting  Data into dependent and independent part. its trends, correlation etc.
	5) Models fitted with original data set: 4 separate classifiers Decision tree, Random Forest, SVM and MLP with optimal parameters are applied on data and their scores.
	6) After scaling: Accuracies of the 4 models after scaling the data.
	7) PCA: Accuracies of the 4 models after reducing dimensionality of dataset.
	8)  Cross validation: Cross validation is applied over all 4 models with original data and Dimensionally reduced data.



To run the code:
	Upload the notebook on google Colab.   https://colab.research.google.com/
	Upload data on google drive.
	Give access of Drive to Colab.
	Run all Cells One after thhe another and observe the result
	     