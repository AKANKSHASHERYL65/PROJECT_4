Product-Recommendation-System

The objective of this task is to recommend the products based on the similar reviews.
The model recommends two more products based on the similar reviews.



Dataset

Link : https://drive.google.com/file/d/11bRaDVvK0BbEHbo5zocM0Z3eBIMZhHtz/view?usp=drivesdk

The dataset initially had 8 columns i.e, id,username,productname,profilename,rating,summary,text,time when reviewed.
Data is preprocssed first and all the irrelevant details such as username,time,profilename are removed, only the productname and summary(review) is kept in dataset.

Algorithm
K Nearest Neighbor which is a Supervised Machine Learning algorithm is used to find similar products and to predict the result with k=3.
It is item-based collaborative filtering model.
