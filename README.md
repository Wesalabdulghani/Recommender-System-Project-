
# Movie Recommendation System

Movie Recommendation System combines Matrix Factorization (MF) and Multi-Layer Perceptron (MLP) approaches to provide personalized movie recommendations. The system is built using Python with Keras and TensorFlow as the primary deep learning libraries.

## Dataset
[The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) is used to train.

## Model Architecture
- MF Component: User and movie embeddings with a dot product layer to simulate traditional matrix factorization.
- MLP Component: User and movie embeddings followed by multiple dense layers to capture non-linear interactions.
- Combination Layer: Concatenation of the outputs from MF and MLP, followed by additional dense layers for integration.
- Output Layer: Generates final predicted ratings.
  
## Model Evaluation
The performance of the recommendation model is evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
  
## Example Use Case
The model can predict individual user ratings for movies and recommend movies with the highest predicted ratings to users.
