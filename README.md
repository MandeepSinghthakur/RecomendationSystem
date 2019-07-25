# Recomendation SystemS
Recommendation System using Simple Approaces   
    1) Based on the count of reviews.
    2) Based on Co-relation b/w two items

Recomendation based on 
    1) Naive Bayes Classification
    2) Logistic Regression

A simple machine learning method you can use to predict he value of the numerical categorical variable
based on its relation with predictor variables.

CLASSIFICATION BASED COLLABRATIVE FILTERING
 a) user and item attribute data  
 b) purchase history data         
 c) other contextual data
 Answer ML Algorithm will  predict -> Will user purchase particular item ?


SINGULAR VALUE DECOMPOSITION(SVD)
a) A linear algebra method that can decompose a utility matrix into 3 compresses matrices
b) Model Based Recommender - use these compressed matrics to make recommendations without being refer back to the            complete data set.
c) Latent Variables: inferred, nonObservable variables that are present within and affect he behavior of the data set.
        A = u * S * v 
        A : original matrix
        u : Left orthogonal matrix - holds important , non reduntant information about the users
        v : Right orthogonal matrix - holds important, non reduntant information about the items
        S : Diagonal matrix - contains all the information about the decomposition processes performed during the compression.

CONTENT-BASED RECOMMENDER SYSTEM 
a) Nearest Neighbour Algorithm
    Unsupervised Classifier. Also known as memory based System.Memorize the instance and then recommends an item (a single instance ) based on how quantatively similar it is to the new, incoming instance.
