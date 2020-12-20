# Book_Rating_Prediction_Project
This is the whole resources for our final project (2020/12) of BDC lecture
  
## Group Members
HKPOLYU MScITF
HUANGZHEMING 20085189G  
LIUJINGDI 20090712G  
  
## Introduction
Given a set of data (10,000) including serveral numerical/text features as well as the book_rating label in training data set, we are going to build a model to predict the book rating for our unlabel test data set. In this part we can only use the training data set to do training and validation jobs.

## Project Structure
doc/
- The final report and presentation

source_code/
- The Source code

dataset_book/
- training data and data set from a early kaggle competition
  
##  Source Code Sketch
1. **Data Preprocessing**  
	- Go through the data set  
	- Text Feature
		- Normalize the outliers in some categories features  
		- One hot encoding  
		- Embedding word2vec
		- Extracting keywords by TF-IDF
	- Numerical Feature
		- Standardize the numerical features  
		- Log transformation
2. **Model Training and Optimization**  
	- Confirm the input dataset  
	- SVM model training  and evaluation 
	- MLP model training  and evaluation 
	- Radom forest training and evaluation
	- Stacking
3. **Predict the Test Data**  
	- Decide the final model
	- Predict the test.csv and output the file in csv format
