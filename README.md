### Benchmarking GNNs for link prediction on heterogeneous graphs: Building a Yelp recommendation system
_______________________________________________________________________________________________________

Recommendation systems try to predict which items a user is likely to be interested in, based on their past behavior and preferences. While traditional recommendation systems rely on collaborative filtering and matrix factorization techniques, these methods have limitations when it comes to handling large-scale, sparse, and heterogeneous data.

Graph neural networks (GNNs) offer a promising solution to these challenges by modeling the user-item interactions as a graph and leveraging the graph structure to learn the user and item embeddings.

Since we were interested in building a recommendation system for restaurants, we have chosen to work with Yelp, which is a website publishing crowd-sourced reviews. Yelp does provide a subset of its businesses, reviews, and user data for use in academic purposes. The dataset is a collection of JSON files  containing information such as business categories, review text, star ratings, user profiles but also social network features such as the number of friends each user has, and which businesses they have reviewed.

**Link to download the Yelp dataset:** https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset
