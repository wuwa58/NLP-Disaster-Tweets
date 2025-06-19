# NLP-Disaster-Tweets
In this notebook, we developed a compact BiLSTM model to classify disaster-related tweets. By incorporating dropout and L2 regularization, we successfully mitigated overfitting and achieved a validation accuracy of **80.30%**, comparable to a traditional logistic regression model with TF-IDF features.

The training logs indicate that the model achieves peak performance early (epoch 1), and overfitting starts quickly afterwards, which confirms the necessity of early stopping.

### Future improvements:
- Load pre-trained GloVe embeddings for better word representations.
- Experiment with CNN-based text models or attention mechanisms.
- Apply text data augmentation to expand limited training data.
- Try ensembling multiple models for potentially higher Kaggle leaderboard scores.
