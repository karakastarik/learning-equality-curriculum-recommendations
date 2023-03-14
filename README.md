# Learning Equality - Curriculum Recommendations

Competition Link: https://www.kaggle.com/competitions/learning-equality-curriculum-recommendations

Competition Goal: Recommend content items to curators for potential inclusion in a topic, to reduce the time they spend searching for and discovering relevant content to consider including in each topic.

Solution:

Three steps of the competition:

1. Stage 1: Use sentence transformers to extract embeddings for topics and contents. Fine-tuning with MultipleNegativesRanking loss boosted the score.
2. Train a K-Nearest Neighbors (KNN) or Approximate Nearest Neighbors (ANN) algorithm to recommend related contents to topic.
3. Stage 2: Re-rank (Binary Classification) using fine-tuned model from Stage 1. The metric is F2 so it is important to select proper threshold. 


