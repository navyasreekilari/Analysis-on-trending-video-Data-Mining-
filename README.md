# Analysis-on-trending-video-Data-Mining-
Deep analysis on trending youtube videos
   



Introduction
This project is a deep analysis on Trending Youtube Videos. I am going to explain more about some data exploration and data analysis on Youtube trending videos in between countries like the United States, UK, Canada, France, Germany, India, Korea, Russia.

Background Information

Platforms for streaming videos online are widely utilized today. Content producers have a great platform to communicate their knowledge, thoughts, and intriguing material with their viewers thanks to websites like YouTube. YouTube has a trending page on its website that displays videos that are popular at that given moment for a video to be seen by as many people as possible. Other than a few popular videos with a large view count that are expected to appear in the trending area, the remaining videos are unpredictable. Corporate organizations use social media to grow their operations; today, data mining and analysis are crucial. The examination of YouTube Data on Trending Videos is the subject of this essay. Utilizing user features like Views, Comments, Likes, and other interactions. The dataset chose includes data collected from several months on daily trending videos in Youtube. Combined data from each region into a single dataset.

Summary  
With the ever-expanding world of social media and its data, its appropriate utilization to get insightful knowledge has become the deciding factor in the platform's success. Here I used  the Real-World Dataset of Trending YouTube Videos for several countries. Analyzed YouTube Videos, Titles, and Stats to get valuable insights. We developed a Clustering algorithm that will segregate videos into several groups, and we will run tests to verify how many videos of the same category are clustered together. We further evaluated the model with improved parameters to get more accuracy.
Implemented a clustering algorithm in Python and Visualized its results on Tableau, along with other visual data analysis. Tableau Prep is utilized in data cleaning and preparation in initial stages.


Methods Used

I used Clustering, K-means and TF-IDF data mining technologies in the project.

Clustering
Clustering Analysis is a way to find a group of objects which are similar to each other in the group but are different from objects in the other groups. Clustering in data analysis divides the sets of data into groups or classes based upon the data similarity. Clustering method is helpful in understanding the analysis more extensively. Clustering method is also used to detect and remove outliers. Data points that fall outside of the clusters are considered as outliers. We can either change the value of the outliers to a value within the nearest cluster or remove the outliers.


Used this clustering feature in Tableau to easily group similar dimension members. This helped me to create statistically-based segments that provide insight on how different groups are similar to each other and how they are performing compared to each other.

K-means
K-means is one of the simplest and most popular unsupervised machine learning algorithms. It is a centroid-based clustering method, where we calculate distance between each data point and a centroid to assign it to a cluster. The main goal is to identify the K number of groups in the dataset. The main objective of this method is to minimize the sum of distances between the data points and the cluster centroid, to identify the correct group each data point belongs to.


The K-means clustering technique in Tableau is the clustering method used to produce clusters on a Tableau worksheet. Because this technique separates a data set into K clusters or segments based on similarity measures, it is known as the "K-means" algorithm. The mean (i.e., the average value across all clusters) is then calculated for each cluster, giving the centroid (cluster center) of a cluster.After determining the centroid value for each cluster that is present, it arranges the clusters so that the total sum of distances between the centroid and any relevant members is as little as possible. The K-means algorithm provides us with densely packed clusters that are each composed of variables that are comparable or connected to one another.

TF – IDF
TF-IDF(term frequency-inverse document frequency) is better used by search engines to understand the content that is undervalued. It is mainly helpful in document search and information retrieval. 
Term Frequency: TF of a term is the number of times the term appears in a document compared to the total number of words in the document.
TF=number of times the term appears in the documenttotal number of terms in the document
Inverse Document Frequency: IDF of a term reflects the proportion of documents that contain the term. 
IDF=log⁡(number of the documents in the corpusnumber of documents in the corpus contain the term)
The TF-IDF of a term is calculated by multiplying TF and IDF scores:
                         TF-IDF = TF*IDF



