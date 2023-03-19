# NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING
![image](https://user-images.githubusercontent.com/48796009/226182526-1856d9f6-24a9-4647-858e-0864a7131d57.png)

# Problem statement:
1.Netflix is the world's largest online streaming service provider, with over 220 million subscribers as of 2022-Q2. It is crucial that they effectively cluster the shows that are hosted on their platform in order to enhance the user experience, thereby preventing subscriber churn.

2.We will be able to understand the shows that are similar to and different from one another by creating clusters, which may be leveraged to offer the consumers personalized show suggestions depending on their preferences.

3.The goal of this project is to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.


# Introduction:

Netflix’s combats its main threat, subscriber churn, by creating a personalized experience that customers are willing to pay for. 
This strategy has allowed the company to become the largest streaming company in the world with 137 million subscribers throughout 190 countries providing them with
a library of 14,835 worldwide[1] (5,579 in the US)[2] original and licensed titles. But how can Netflix provide a personalized streaming experience to its millions of 
subscribers with its vast library?   The answer lies on the introduction of machine learning to the company’s innovation and improvement processes.

Machine learning has been instrumental at creating a competitive edge for Netflix on two main avenues: (1) content suggestion and (2) content acquisition and creation.

# (1) Content Suggestion

Two years ago, Netflix started experimenting with sophisticated supervised (e.g. classification and regression) and unsupervised (e.g. clustering and compression) machine learning algorithms.
that aimed at aggregating large sets of data and identifying patterns in consumer behavior to improve user experience while decreasing monthly churn rate (lowest in the streaming industry at 9%/year in 2016).
![image](https://user-images.githubusercontent.com/48796009/226182888-f9c3671f-35b9-4c6f-a595-dec12914d694.png)

Netflix has estimated that users spend 60 to 90 seconds browsing on its interface for new shows to watch before they lose interest. These machine learning algorithms help
users navigate through Netflix’s vast library, translating into 80% of watched content coming from algorithmic recommendations and annual savings of well over US$1 billion 
from decreasing churn rates.

Historically, Netflix relied on customer reviews (ranking from 1 to 5 stars) to predict consumer preferences. After the introduction of machine learning algorithms on their streaming content, Netflix started collecting and analyzing a wide arrange of data on many metrics considered to be better predictors of subscriber behavior including:
*How many users watched an episode and an entire series
*Episode and series rating
*In-title behavior (pause, rewind or fast-forward)
*Churn rate per episode or series
*User browsing and scrolling habits.
Netflix is investing heavily on providing customers with the largest and most relevant content library in the market. Therefore, it is instrumental to provide subscribers with an effective medium to facilitate the navigation and selection process of this library which is considered by Netflix to be the “moment of truth”


# (2) content acquisition and creation

In 2013, the company started producing original content which supports the company’s long term strategy of relying less on outside studios.The data they gather using
machine learning has been widely used internally to acquire and create relevant content that users will find exciting. As traditional studios shift towards their own 
online streaming models (e.g. Disney+), content supply will likely see a dramatic decline, which drives Netflix’s need to strengthen its internal creation efforts and
acquire the right material to provide its subscribers with a relevant and exciting library.

In the short-term, Netflix is expected to increase investing in original content (US$ 8 billion in 2018)[11] and continue developing machine learning to guide subscribers to relevant
content. In the medium term, Netflix is experimenting with a groundbreaking interactive “Choose-Your-Own Ending” format to provide customers with a tailor-made title experience 
while learning new insights from their users.


# Kmeans clustering

k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster.
![image](https://user-images.githubusercontent.com/48796009/226184164-8d2c85fa-b19d-4693-a340-315865e38bdd.png)








# Agglomerative — Hierarchical Clustering
*Clustering based nearest neighbor approach to obtain genre for every movie from external sources. We create a vector representing each genre as one cell and we count
the number of moviews that users has rated in that particular genre. This has collective opinion of the users.

*When given with the query instance q(MovieID,userID), we find all the genre for that movie. For each genre we calcualte the distance of the movie from cluster centres
for the genre and combine the two clusters with smallest centroid distance. We average per genre predicted rating and get the predicted ratings for q.

![image](https://user-images.githubusercontent.com/48796009/226183871-163e9e46-63ac-464c-8eea-ae04155635c8.png)















