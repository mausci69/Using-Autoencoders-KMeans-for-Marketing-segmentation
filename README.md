# Using-Autoencoders-KMeans-for-Marketing-segmentation

Marketing is crucial for the growth and sustainability of any business. What really matters to customers is to know their customers. This kind of knowledge means the possibility to perform what is called market segmentation.

Our use case is a New York City Bank that had the opportunity to study their customers for the past 6 months and now want to lanunch a targeted marketing campaign by dividing them into at least 3 groups.

After taking a look at the data, with a really minimum preprocessing, they are actually clean, we will follow two approaches to perform a segmentation.

First, we'll use Kmeans Clustering, an algorithm that assign data to K different clusters. It is an unsupervised algorithm, 'cause we don't need labels to train our model. We just need a number K, meaning how many clusters we will be splitting our data in, and in order to find a good value for it, we are gonna use a method called Elbow Method. We will eventually show how data behave in different clusters and finally reduce dimensions of data to 2 using Principal Component Analysis to visually see where different clusters are located.

Second and last, we'll repeat this approach, but this time we'll reduce the dimension of our data from 17 features to 10 using Autoencoders, a particular Neural Network model specialized in what is called representation learning. After this, everything will proceed the same as before, but now, with this extra reduction, the number of clusters is gonna be 4 and our data will be segmented by this number.
