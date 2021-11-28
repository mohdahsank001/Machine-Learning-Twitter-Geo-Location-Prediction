A Comprehensive Comparison and Analysis of Machine Learning Algorithms for Twitter Geographic Location Prediction  - PUBLICATION IN PROGRESS

Project Abstract 
--------------------

Given a tweet, a machine learning model when after undertaking the training, development and testing phase is able to predict where the author of the tweet is situated. Our notion is that a user’s tweet may consist of some location specific content which can indicatively consist of certain names or phrases related to the geographic location of the user.
In today’s world, can find that increasing amounts of data would result in more precise location estimation, giving us belief in the soundness and continued refinement of location prediction using the user tweets data. By increasing enormous human powered sensing capabilities of Twitter and associated microblogging services with content derived location data, the algorithms can overcome the dispersion of geo-enabled features in these services and bring augmented scope and breadth to surfacing location-based personalized information services. With these objectives in mind, I propose and evaluate various different machine learning algorithms and models for predicting a tweeter’s geographical location. In addition to this, this paper would primarily critically analyze the efficacy of many different algorithms on the problem of determining a tweeter’s location by undergoing a comparative analysis of the machine learning algorithms based on different performance and evaluation metrics.



Through this Project I have implemeted many different Classifiers for Geolocation prediction on Twitter Tweets dataset. 

Primarily a comparative analysis was done on multiple models of different classifier including : 
 
1. k Nearest-Neighbor Algorithm 
2. Random Forest Classifier 
3. The LR Classifier 


Datasets
----------

The dataset that is obtained from dataset of tweets gathered from Twitter’s streaming API can be used as part of this work Initial filtering can be done to remove the retweets and repetition   of the previously posted messages. To eliminate spam and automated accounts tweets containing the URLs can be removed.

One of the featured engineered datasets that I have implemented in my project is glove300, where each word is mapped to a 300-dimensional Glove “embedding vector”. These vectors were used to capture the meaning of each word. We then average the vectors of each word in a tweet to obtain a single 300-dimensional representation of the tweet. Example would include User_ID, 2.05549970e-02 where the vector 2.05549970e-02 would represent a 300-dimensional list of number.1,7

Lexical blending is a highly productive and frequent process by which new words enter a language. A blend    is formed when two or more source words are combined, with at least one of them shortened, as in brunch (breakfast+lunch). Datasets consisting of blend words can also be used for the geolocation prediction of tweets. We would use the existing Twitter geolocation dataset which is GEOTEXT and the blend datasets.   They are all pre-partitioned into training, development and test sets.  To aid in initial experiments many different feature engineering methods were applied   to the raw tweets. Within the datasets, each tweet is labelled with one of the four possible regions which can be MIDWEST, NORTHEAST, SOUTH OR WEST.

In addition to it many additional techniques like Upsampling, Downsampling, Hyper parameter optimisation were done on the data set that was provided.In machine learning hyper parameter optimization or tuning is the process of choosing an optimal set of hyperparameters for a learning algorithm.


K fold cross validation was used to approximate the skill of a model. The objective of k fold cross validation through this project was to test how good the model is trained upon a given data and test it on unseen data.

Results 
------------
Random Forest classifier would outperform the other classifiers with the best accuracy and also best macro averaged f1 score in the first phase over LR and kNN models. Hence it can be chosen as the model to do predictions. Moreover, the results also show that all of the classifiers would give good accuracy, however when doing a comparative analysis random forest classifier can be preferred for performing geolocation predictions based on twitter tweets. 


