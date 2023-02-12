# Compare-Classifers
In this project, I will compare the performance of the classifiers including K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines.  I will utilize a dataset related to marketing bank products over the telephone. The dataset comes from the UCI Machine Learning repository [link](https://archive.ics.uci.edu/ml/datasets/bank+marketing).  The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. The dataset collected is related to 17 campaigns that occurred between May 2008 and November 2010, corresponding to a total of 79354 contacts. The goal is to increase efficiency of directed campaigns for long-term deposit subscriptions by reducing the number of contacts to do. I will determine if a client will subscribe a deposit by his or her characteristics and contact information. We will make an analysis on what attribute influence the the successs rate.

Due to the hardware limit, I did not include svm result because it took so long to run.Here is the result for the performance of the different classifers



<img width="545" alt="Screenshot 2023-02-11 at 8 04 25 PM" src="https://user-images.githubusercontent.com/103546558/218292439-883ce684-417d-4082-bac7-5393ff88307a.png">

Overall, the logistic regression have the best performance. It has the auc score. It's traing time is also short and comparable to that of knn. Even though knn has shorter traning time, it takes much more time to predict the new dataset. So the overall performance of logsitic regression is better than knn. Decision tree has the highest accuracy score and a medium auc score. However, its traing time is much longer than that of logistic regression

For the feature importance, duration time is the most interpretable and correlated features. It means increasing the phone call duration time will increase the successful rate. I would recommend bank staff to increase the contact duration such as talking more benefits. 



<img width="421" alt="Screenshot 2023-02-11 at 8 19 32 PM" src="https://user-images.githubusercontent.com/103546558/218292884-234f916a-cd90-4c0f-be0d-b894cdb9f09c.png">
