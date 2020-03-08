+-------------+-----------+----------------+-----------+
|  Vectorizer |   Model   | Hyperparameter | AUC_Score |
+-------------+-----------+----------------+-----------+
|     BOW     | Brute KNN |       95       |   0.667   |
|    TF-IDF   | Brute KNN |       65       |   0.629   |
|   AVG-W2V   | Brute KNN |       85       |   0.658   |
|  TFIDF-W2v  | Brute KNN |      115       |   0.665   |
| TFIDF KBest | Brute KNN |       5        |   0.513   |
+-------------+-----------+----------------+-----------+
By comparing the AUC Scores, we can say that for the given dataset, the model employing BOW Vectorization and the model employing TFIDF-W2V are the best models as they have nearly same highest AUC_Score of 0.667 and 0.665 respectively.
