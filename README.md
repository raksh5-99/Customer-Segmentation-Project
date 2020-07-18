# CUSTOMER SEGMENTATION USING MACHINE LEARNING 

##Project:Customer Segmentation in R
####In this project,we will implement customer segmentation in R. Whenever you need to find your best customer, customer segmentation is the ideal methodology. It is one of the most important applications of unsupervised learning.


# CUSTOMER SEGMENTATION
![imagename](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/07/R-project-customer-segmentation.png)

###Customer Segmentation is the process of division of customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.

###Therefore, their aim has to be specific and should be tailored to address the requirements of each and every individual customer.

###Furthermore, through the data collected, companies can gain a deeper understanding of customer preferences as well as the requirements for discovering valuable segments that would reap them maximum profit. 

###This way, they can strategize their marketing techniques more efficiently and minimize the possibility of risk to their investment.


##K-means Algorithm

###The algorithm starts by selecting k objects from dataset randomly that will serve as the initial centers for our clusters. These selected objects are the cluster means, also known as centroids. 
###Then, the remaining objects have an assignment of the closest centroid. This centroid is defined by the Euclidean Distance present between the object and the cluster mean. We refer to this step as “cluster assignment”. 
###When the assignment is complete, the algorithm proceeds to calculate new mean value of each cluster present in the data. After the recalculation of the centers, the observations are checked if they are closer to a different cluster.
###Using the updated cluster mean, the objects undergo reassignment. This goes on repeatedly through several iterations until the cluster assignments stop altering.
###The clusters that are present in the current iteration are the same as the ones obtained in the previous iteration.

##Summing up the K-means clustering –

###We specify the number of clusters that we need to create.
###The algorithm selects k objects at random from the dataset. This object is the initial cluster or mean.
###The closest centroid obtains the assignment of a new observation. We base this assignment on the Euclidean Distance between object and the centroid.
###k clusters in the data points update the centroid through calculation of the new mean values present in all the data points of the cluster. The kth cluster’s centroid has a length of p that contains means of all variables for observations in the k-th cluster. We denote the number of variables with p.
###Iterative minimization of the total within the sum of squares. Then through the iterative minimization of the total sum of the square, the assignment stop wavering when we achieve maximum iteration. The default value is 10 that the R software uses for the maximum iterations.

##Vizualizing Clustering Results using Two Components- Spendig Score and Annual Income

![imagename](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/07/PCA-Cluster-Graph-in-ML.png)

###From the above visualization, we observe that there is a distribution of 6 clusters as follows –

###Cluster 6 and 4 – These clusters represent the customer_data with the medium income salary as well as the medium annual spend of salary.

###Cluster 1 – This cluster represents the customer_data having a high annual income as well as a high annual spend.

###Cluster 3 – This cluster denotes the customer_data with low annual income as well as low yearly spend of income.

###Cluster 2 – This cluster denotes a high annual income and low yearly spend.

Cluster 5 – This cluster represents a low annual income but its high yearly expenditure.
##Reference statement :"Assignment during Online Internship with DLithe(www.dlithe.com)"
