# Product Recommendation System
This project explores collaborative filtering to build a personalized recommendation engine — just like the ones used by Netflix, Amazon, and Spotify. Using real user-product interaction data from an e-commerce platform, it predicts what products each customer might like next.

The system is trained using the SVD algorithm (matrix factorization) and visualized with simple, clean charts to help communicate how it works and what value it offers.

# Objectives

-Build a recommender system based on past user behavior

-Predict user-item match scores with matrix factorization

-Generate Top-N personalized product recommendations

-Visualize which products get recommended and model confidence

# Techniques Used

-Collaborative Filtering (SVD) using scikit-surprise

-Implicit Feedback (treating transactions as positive ratings)

-Top-N Filtering per user based on predicted preference

-Visualization with seaborn and matplotlib

-Recommendation Evaluation using RMSE

# Dataset Info
Source: RetailRocket E-Commerce Dataset (Kaggle)

Events Used: transaction only (purchases)

Fields Used:

user_id (anonymized)

item_id (product)

rating (set to 1 per transaction)


#Key Insights
-Products recommended most often had strong collaborative signals

-Most predicted scores clustered around moderate to high confidence

-Model performance evaluated using RMSE on a held-out test set

-System is capable of scaling to larger datasets and being integrated into production