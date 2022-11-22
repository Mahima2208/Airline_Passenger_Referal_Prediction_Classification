# Airline Passenger Referal Prediction Classification
![start slide](https://user-images.githubusercontent.com/48561668/179386169-8fa35a85-2b75-471d-9b01-19a20acb1674.jpg)
# 📖PROBLEM STATEMENT
Any child who sees a plane in the sky fantasises about riding in it. Traveling by plane has become a craze, and as an adult, one will consider taking care of the experience. As a result, the opinions of those who have travelled have become increasingly important. This improved people's positive travel experiences, as well as the airlines' ability to understand what their customers are feeling and this increased the amount of room for improvement that airlines can do.

The main objective of this project is to predict whether passengers will refer the airline to their friends. In this project we deployed multiple machine learning models to see the performance.

Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scraped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends.
The main objective of this project is to predict whether passengers will refer the airline to their friends. In this project we deployed multiple machine learning models to see the performance.

# 📖ALGORITHMS USED:

## i.     LOGISTIC REGRESSION

## ii.   RANDOM FOREST

## iii.  SVM


# 📖Conclusion: 

•	In the EDA part we observed that

o	It is apparent that people gave a high recommendation to the economic class in the cabin. This tells us that people like to travel in economy class due to the low price, but we can also see that they give the economy class the highest negative ratings because they receive less infrastructure or service. Likewise, the business class has received the highest rating due to the quality service offered there, while the economy class has received the lowest rating due to its price or low attendance.

o	'British airways' has the maximum number of trips and this can be attributed to its ultra-low-cost fare compared to other airlines.

o	Clearly, 'No' responses are more than 'Yes' responses in recommended, which means airlines have to focus on some aspects to make their fliers happy.

•	According to our business needs, we will give first priority to recall and then to accuracy from a metrics point of view because we need to find how many people will recommend it.

•	We can see that our models have performed very well all of the models have given recall greater than 90% which means our models are performing very well.

•	Logistic Regression has the highest recall value It gave a recall of 95.12% followed by SVM which gave 94.91%.

•	Support Vector Machine has the highest accuracy of the models but others also performed very well SVM gave 95.40% accuracy.

•	Even after using Grid Search CV our models are giving similar accuracy.

•	Naive Bayes Classifier and Random forest has the lowest recall of 93.95%.

•	In Shap JS summary we can see positive features overall, value for money, numeric review combined red color block pushes the prediction toward right over base value and causing positive model prediction for random forest model.

•	In Shap summary scatter plot we can see in scatter plot high overall, value for money, numeric review, cabin service, ground_service positive features, and low airline_British_airways is increasing positive prediction and it is common for all models. Also, we can see that overall, value for money, numeric review, cabin service, and ground_service has high shap feature value.

•	From Eli5 we can see overall and value for money contributed more to giving the positive recommendation and ground service and family leisure contributed to giving a negative recommendation for XGBoost.

•	From Eli5 we can see overall and value for money contributed more to giving the positive recommendation and Gradient Boosting model.

# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
Mahima Phalkey | Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/mahima-phalkey/) [![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/Mahima2208) [![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@mahimaphalkey) [![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)](https://drive.google.com/file/d/1Xi9oBrCjMc3QPGAhFdfO5rnMUssLa7Hw/view?usp=sharing)


# 📚 References

1. GeekforGeeks

2. Kaggle

3. Analytics Vidya
