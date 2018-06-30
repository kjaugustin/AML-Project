# AML-Project
The dataset used for this Machine Learning project is obained from Kaggle. A detailed description about the data set could be found at https://www.kaggle.com/agpickersgill/credit-card-fraud-detection/data .
The  differentiator  in our solution is the use of transforming the features of the  data set as distance to clusters. This was an experimental appraoch and could be found from the heading .
# Feature Engineering (Experimental)
in the note book https://github.com/kjaugustin/AML-Project/blob/master/Phase%204_AGS.ipynb.
Our motivation was the infrences from the pair plot analysis. We found in most of the pair plots , the class 0 and class 1 data were forming  set of cluster many many of them where liniarly sperable in a 2 dimentional plane.
By the use of K Means clustering we took 6 and 4 Clusters of Class 0 and Class 1 data respectively. Hence we optained a set of 10 centroids.
Then we computed the distance of each data , to each of the centroid using the precictor variable.
The hence transformed data was used as for further analysis.

# Outcome
To detect maximum number of fraud transacations, we need to have model that maximizes the recall and minimizes the false negative rate. As you can see from the results, the best model reduced the false negative rate from 10% to 2%, while improving the recall from 0.89 to 0.97. The feature transformation is key factor in this achievement. The best model's performance is much better than the base model as indicated by the statistical significance test.
