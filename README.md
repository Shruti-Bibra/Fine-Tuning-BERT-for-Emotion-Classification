# Fine-Tuning-BERT-for-Emotion-Classification

 ## ABSTRACT
 In this project, we implemented analyzed 3 different machine learning methods for classifying the EmotionsGo
 dataset. The models that we tested were XGBoost, random forest, softmax regression, naive Bayes and Bert
 for sequence classification. Additionally, we did two extensions: one with masked token prediction and
 using word2Vec embeddings instead of TD-IDF. The results show that BERT after fine-tuning and hyper
parameter tuning produced the best results with the highest testing accuracy of 0.56 compared to the lowest
 performance of baseline RF at 0.35. This shows that this dataset has highly non-linear features and needs
 a high expressive model like BERT. However increasing model complexity does also result in overfitting
 which various regularization methods could fix. Despite some of those overfitting issues we see in the
 attention matrix of our fine-tuned layers, lots of new semantic relationships in sentences were discovered which
 demonstrates the model’s potential. Overall, the project show-cases the importance of feature engineering,
 fine-tuning, and other design choices (like hyper-parameters and architecture) to balance the bias-variance
 trade-off in tasks like emotion classification.
