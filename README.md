# customer_churn_predication
This model loads, analyze ,predict ,evaluate and visualize the dataset from the kaggle .It is most useful for finding which customer will leave the service.

#libraries used:-
1.Pandas
2.Numpy
3.Matplotlib
4.Seaborn
5.Sciktlearn

#loading the data
I used Kaggle dataset for this model of 50000 rows

#cleaning and converting the categorical data into numeric data
Firstly converted categorica data into numeric data ,Then removed all rows tha contains NaN values.

#Splitting the data and Handle imbalanced data using SMOTE
splitting the whole data in four parts X_train,X_test,y_train,y_test and then used SMOTE to handle imbalance data so that my model can not be biased 

#LogisticRegression 
-Make Prediction
-Evaluate them using accuracy,precision,recall,f1_score
-Visualize them by bar chart,heatmap,line chart

#decisionTree
-Make Prediction
-Evaluate them using accuracy,precision,recall,f1_score
-Visualize them by bar chart,heatmap,line chart

#XGBoost
-Make Prediction
-Evaluate them using accuracy,precision,recall,f1_score
-Visualize them by bar chart,heatmap,line chart
