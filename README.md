# ML-assignment-5
Collaborative Filtering Recommender Systems

Collaborative filtering is a technique used by recommender systems to make predictions or recommendations about items (such as movies, books, products) based on the preferences or behavior of other users. Here is a practice lab of collaborative filtering recommerder system in machine learning. In this exercise, collaborative filtering was implemented to build a recommender system for movies.

The first step is to detail the data set and data structures that will be used in the lab. This dataset consists of ratings on a scale of 0.5 to 5 in 0.5 step increments. We loaded 𝑌 and 𝑅 with the movie dataset and also load X, W, and b with pre-computed values. The matrix Y restores the data of ratings. The matrix 𝑅 is an binary-valued indicator matrix, where 𝑅(𝑖,𝑗)=1 if user 𝑗 gave a rating to movie 𝑖, and 𝑅(𝑖,𝑗)=0 otherwise.

Then, we begin implementing the collaborative filtering learning algorithm start by implementing the objective function where the model predicts the rating for movie 𝑖 by user 𝑗 as 𝑦(𝑖,𝑗)=w(𝑗)⋅x(𝑖)+𝑏(𝑗). After that, consider developing the cost function in two steps. First, develop the cost function without regularization. Second, create a vectorized implementation to compute 𝐽.

After we have finished implementing the collaborative filtering cost function, we can start training our algorithm to make movie recommendations.
